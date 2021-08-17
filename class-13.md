# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS

## HTML5 Storage

* web storage , local storage , DOM storage
* store key/value pairs locally within the client web browser
* data persists but is never transmitted to remote web server
* most recent versions of browsers support HTML5 storage

![Local Storage](https://blog.teamtreehouse.com/wp-content/uploads/2013/01/localstorage-feature.png)

## Checking for HTML5 storage

```
function supports_html5_storage() {
  try {
    return 'localStorage' in window && window['localStorage'] !== null;
  } catch (e) {
    return false;
  }
}
```

## Using HTML5 Storage

* stored in named key/value pairs
* data is stored as string
* use functions like parselnt() or parseFloat() to coerce retrieved data

```
interface Storage {

getter any getItem(in DOMString key);

setter creator void setItem(in DOMString key, in any data);

};
```

* calling **setltem()** will overwrite pervious value if it already exists
* calling **getltem()** will return null if doesnt exist
* you can treat localstorage object as an associateive array