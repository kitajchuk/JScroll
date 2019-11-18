JScroll
=======

> A smooth scroll JS library.



## Attribution
This is a spiritual "fork" of JScroll by [Jesper Landberg](https://github.com/jesperlandberg/JScroll). Here the library is reusable and is actively being enhanced. For instance, I have already added a `JScroll.scrollTo` method to the utility.



## Installation
```shell
npm install properjs-jscroll --save-dev
```


## Usage
You will need to add a `js-smooth` class to your main container and a `js-smooth-section` class to any elements you want to be smooth.

```javascript
import JScroll from "properjs-jscroll";

const jscroll = new JScroll({
    scrollbar: true
});
```
