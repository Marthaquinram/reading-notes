# Local Storage
- Local Storage is one of the areas where native client applications have held an advantage over web applications. For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state. These values may be stored in the registry, INI files, XML files, or some other place according to platform convention. If your native client application needs local storage beyond key/value pairs, you can embed your own database, invent your own file format, or any number of other solutions." 
- HTML5 Storeage is a way for web pages to store named key/value pairs locally, within the client web browser. Data persists even after you navigate away from the web site.
- 
- 
- in more recent times you can just type in local storage as a global variable. 
- local storage lets us keep data per user per browser without knowing anything about them. it changes from device to device. from phone to pc.
- domain name is the www;.google.com within the https. 
-  local storage set items has a key and a value. the key is string and the value is a string
- local storage .age ('age', '28)
- it would read storage ( age: '22', name: 'martha', Length: 2)

- remove item or use clear to get rid of that property (inside the paraethsis)
- in local storage we can store keys and strings, if you want to display a number you can do parseInt(localStorage.getitem)
- use Number instead of parseInt when trying to get an actual number.
- get item and set item need to be the same.



- coffee.drinks = JSON.parse(localStorage.getItem("coffeestand"))??[];
