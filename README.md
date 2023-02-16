## Summary

Add a js file to your interviews with this code:

```js
$(document).on('daPageLoad', function(){
  document.documentElement.setAttribute('data-bs-theme', 'light');
});
```

## Details

For those who don't yet have a good way to support Bootstrap's dark mode (usually because of custom CSS), here's a way to force light mode. This is a temporary stopgap measure while you develop your dark mode styles.

You can make your own js file if you want, containing the same simple code. You then need to import the js file into your interview using a `features` block. See documentation for at [docassemble's docs about the `feature` block](https://docassemble.org/docs/initial.html#javascript).
