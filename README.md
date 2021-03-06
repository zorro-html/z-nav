# `<z-*nav>`

- extends on [Polymer/core-selector](https://github.com/Polymer/core-selector)
- 3 styles: `<z-tabnav>`, `<z-pillnav>`, `<z-linenav>`
- could add attributes like `[horizontal]` `[layout]` `[flex]` to make `justified` effect

## Import

```
<link rel="import" href="z-nav/z-nav.html">
```

## Examples

### Tabs

```
<z-tabnav layout horizontal>
  <li name="item1" flex active>ITEM 1</li>
  <li name="item2" flex>ITEM 2</li>
  <li name="item3" flex>ITEM 3</li>
</z-tabnav>
```

### Pills

```
<z-pillnav layout horizontal selected="1">
  <li name="item1" flex>ITEM 1</li>
  <li name="item2" flex>ITEM 2</li>
  <li name="item3" flex>ITEM 3</li>
</z-pillnav>
```

### Underlines

```
<z-linenav layout horizontal>
  <li name="item1" flex>ITEM 1</li>
  <li name="item2" flex>ITEM 2</li>
  <li name="item3" flex active>ITEM 3</li>
</z-linenav>
```
