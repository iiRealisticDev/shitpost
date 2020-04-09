# This an MD file incluing "hello world" examples for JS, LUA & HTML!

# Lua
```lua
  local Text = "Hello, world!"
  print(Text) --> Hello, world!
  Text = "Goodbye, world!"
  print(Text) --> Goodbye, world!
```

# JS
```js
  let text = "Hello, world!";
  console.log(text); // --> Hello, world!
  text = "Goodbye, world!"
  console.log(text); // --> Goodbye, world!
```

# HTML
```html
<h id="hello"> Hello, world! </h>
<script>
  setTimeout(function(){
    document.getElementById("hello").innerHTML = "Goodbye, world!"
  }, 3000)
</script>
```
