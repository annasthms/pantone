# Modified ntc.js for Pantone Colors
This is a modified version of [Chirag Mehta's ntc js (Name that Color JavaScript)](http://chir.ag/projects/ntc/). This modified version finds the closest Pantone swatch for a given HEX color. The Pantone colors were taken from [this Github repository](https://github.com/Margaret2/pantone-colors).

Play with it [here](https://annasthms.github.io/pantone/index.html).

## Sample HTML Code
```html
<script type="text/javascript" src="pantone ntc.js"></script>

<script type="text/javascript">

  var n_match  = ntc.name("#6195ED");
  n_hex        = n_match[0]; // HEX value of closest match
  n_name       = n_match[1]; // Text string: Color name
  n_number     = n_match[2]; // Text string: Color number
  n_exactmatch = n_match[3]; // True if exact color match

  alert(n_match);

</script>
```
