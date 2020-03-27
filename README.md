# React parser for Editor.js

React parser for [EditorJS](https://editorjs.io/). 
It reads an object of blocks and returns HTML.

```js
import CleanDataParser from 'react-editor-js-parser'

const HelloWorld = (html) => {

  return (
    <div>
      {html.blocks.map((block, idx) => CleanDataParser(block, idx))}
    </div>
  )
}
```

## TODO

- Add unit tests
- Finish Typescritp typings
- Add support to more block elemenets