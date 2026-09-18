# Savings · $SVNGS

Launch a coin for any X handle. Every trade deposits into their savings account. It grows until they show up.

Static site: `index.html` + `assets/`. No build step.

Settings at the top of the first `<script>` in `index.html`:

```js
window.CONTRACT = "";  // token contract address
window.TWITTER  = "";  // X profile URL
window.BUY_URL  = "";  // buy link (button stays inactive while empty)
```
