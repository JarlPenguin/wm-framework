Blockheads Welcome Message Framework
# [Guide](guide)

## Add to WM
Paste this as your welcome message:
```html
<script type=config>

</script>

<script src="https://jarlpenguin.github.io/wm-framework/bundle.js"></script>
```

## Configuration
### Notes
Statements further to the right take higher priority:
```
key val|key value
```
`key` would be `value`, **not** `val`.

### Key/Value
```
key1 value1|key2 value2
```

### List
```
@List Name|List Item 1|List Item 2||@List Name 2|List Item 1|List Item 2||...
```
Separate list items with a single pipe (`|`). To close a list — whether you are starting a new list or returning to normal settings — you **must** use a double pipe (`||`).

## Custom HTML
Add a `div` with ID `custom-top` or `custom-bottom`.

`custom-top` appears at the top, `custom-middle` is above lists but under title, `custom-bottom` is under lists.