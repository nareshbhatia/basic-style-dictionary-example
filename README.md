# Basic Style Dictionary Example

Based on: https://github.com/amzn/style-dictionary/tree/main/examples/basic

This example code is bare-bones to show you what this framework can do. If you have the style-dictionary module installed globally, you can `cd` into this directory and run:

```bash
npx style-dictionary build
```

Otherwise, install Style Dictionary locally for this project first, `cd` into this directory and run:

```bash
npm init -y && npm install style-dictionary
```

and then run the above command.

## Tokens Exported from Figma

- [1-radix-tokens.json](tokens-from-figma/1-radix-tokens.json)
  - Exported using [Variables Import Export](https://github.com/figma/plugin-samples/tree/main/variables-import-export) plugin
  - Output is in w3c format
  - 1 file per mode per collection

- [2-design-tokens.tokens.json](tokens-from-figma/2-design-tokens.tokens.json)
  - Exported using [Design Tokens](https://www.figma.com/community/plugin/888356646278934516/design-tokens) plugin
  - Output is not in w3c format
  - All output in a single file. It looks like mode is lost.

- [3-radix-tokens.json](tokens-from-figma/3-radix-tokens.json)
  - Exported using [Variables to JSON](https://www.figma.com/community/plugin/1301567053264748331) plugin
  - Output is not in w3c format
  - All output in a single file.
  - Mode is output as a group.

- [4-radix-tokens](tokens-from-figma/4-radix-tokens)
  - Exported using [Design Tokens (W3C) Export](https://www.figma.com/community/plugin/1377982390646186215) plugin
  - Output is not in w3c format
  - 1 file per collection
  - Mode is output as a group.
