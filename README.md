# aut0scroll.js

```js
(function autoScroll() {
    let scrollAmount = 1; // Number of pixels to scroll by each step
    let scrollDelay = 15; // Delay in milliseconds (15ms)

    setInterval(() => {
        window.scrollBy(0, scrollAmount);
    }, scrollDelay);
})();
```

# HowTO

* open up DevTools -> Console
* paste the code
