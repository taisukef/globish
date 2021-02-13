# globish

## CSV
https://taisukef.github.io/globish/globishwords.csv
 
## How to use in JavaScript
```
<script type="module">
import { CSV } from "https://code4sabae.github.io/js/CSV.js";
 
window.onload = async () => {
  const csv = await CSV.fetch("https://taisukef.github.io/globish/globishwords.csv");
  console.log(csv);
 	const words = CSV.toJSON(csv);
  console.log(words);
};
</script>
```

## How to use on Deno
```
import { CSV } from "https://code4sabae.github.io/js/CSV.js";
 
const csv = await CSV.fetch("https://taisukef.github.io/globish/globishwords.csv");
console.log(csv);
const words = CSV.toJSON(csv);
console.log(words);
```
