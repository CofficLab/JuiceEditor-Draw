# JuiceEditor-Draw

![editor](./docs/hero.png)

## Important

This project cannot work independently. It is an extension package for JuiceEditor.

Please read the JuiceEditor documentation first: [JuiceEditor](https://cofficlab.github.io/en/juiceEditor/documents/components/image.html#draw-a-picture)

## Installation

1. Install package:

   ```bash
   npm i @coffic/juice-editor
   npm i @coffic/juice-editor-draw
   ```

2. Copy components to project directory:

   ```bash
   rm -rf ./public/draw
   cp -rf node_modules/@coffic/juice-editor-draw/dist ./public/draw
   ```

3. Configure editor:

   ```typescript
   editor.setDrawLink('http://localhost:5173/drawio/webapp/index.html?');
   ```

## Related Projects

- [JuiceEditor](https://github.com/CofficLab/JuiceEditor)
- [JuiceEditor-Draw](https://github.com/CofficLab/JuiceEditor-Draw)
- [JuiceEditor-SwiftUI](https://github.com/cofficlab/JuiceEditor-SwiftUI)
- [JuiceEditor-Examples](https://github.com/cofficlab/JuiceEditor-Examples)
- [JuiceEditor-Playground](https://github.com/cofficlab/JuiceEditor-Playground)

## NPM Packages

- [juice-editor](https://www.npmjs.com/package/@coffic/juice-editor)
- [juice-editor-draw](https://www.npmjs.com/package/@coffic/juice-editor-draw)

## Maintainers

Work for Joy & Live for Love ➡️ <https://github.com/nookery>

## Contributing

Contributions are welcome! Please submit Pull Requests or report issues.

## License

JuiceEditor is released under a dual license:

1. For non-commercial use: [MIT License](LICENSE)
2. For commercial use or modifications: Please [contact the author](https://github.com/nookery) for a commercial license.

Any use of this software for commercial purposes or any modifications to the source code require explicit permission from the author.
