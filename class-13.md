# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS
>Persistent local storage is one of the areas where native client applications have held an advantage over web applications.

>it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server

* **check for HTML5 Storage**
`function supports_html5_storage() {
  try {
    return 'localStorage' in window && window['localStorage'] !== null;
  } catch (e) {
    return false;
  }
}`

### USING HTML5 STORAGE
HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats.

- `interface Storage {
  getter any getItem(in DOMString key);
  setter creator void setItem(in DOMString key, in any data);
};`

- `var foo = localStorage.getItem("bar");
// ...
localStorage.setItem("bar", foo);`

### TRACKING CHANGES TO THE HTML5 STORAGE AREA
 The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something.
 
 `if (window.addEventListener) {
  window.addEventListener("storage", handle_storage, false);
} else {
  window.attachEvent("onstorage", handle_storage);
};

//The handle_storage callback function will be called with a StorageEvent object, except in Internet Explorer where the event object is stored in window.event.

function handle_storage(e) {
  if (!e) { e = window.event; }
}`

### HTML5 STORAGE IN ACTION
> save the progress locally, within the browser itself.

> Data is stored as strings. If you are storing something other than a string, you’ll need to coerce it yourself when you retrieve it.

### BEYOND NAMED KEY-VALUE PAIRS: COMPETING VISIONS

> Web SQL Database (formerly known as “WebDB”) provides a thin wrapper around a SQL database, allowing you to do things like this from JavaScript:

↶  
`openDatabase('documents', '1.0', 'Local document storage', 5*1024*1024, function (db) {
  db.changeVersion('', '1.0', function (t) {
    t.executeSql('CREATE TABLE docids (id, name)');
  }, error);
});`
* As you can see, most of the action resides in the string you pass to the executeSql method. 

![local storage](https://lh3.googleusercontent.com/proxy/4-j7YTFXGF_FgpibnF5vTxb0X7a4k8bs_Bo-h_V3KbXLa3EN1Ix_5ACzX6NnHsPDaja-e6DdZYWTLRR_zI3rVNjlhRunSjsy-RaMiVk8SRE4KMnn)


------
###### source: The article: [“The Past, Present, and Future of Local Storage for Web Applications”](http://diveinto.html5doctor.com/storage.html)
