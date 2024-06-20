# Blockly Components for ErgoScript 

## Usge
```
import * as Blockly from "blockly/core";
import { ergoScriptGenerator, blocks } from "ergoblocks";

Blockly.common.defineBlocks(
  Blockly.common.createBlockDefinitionsFromJsonArray(blocks)
);

// Your Blockly setup code here
```

## Live Demo
Checkout [ErgoScript Playground](https://escript.online/blockly) for a live demo.

## Minimal Integration example

1. Clone this repository `git clone git@github.com:SavonarolaLabs/blockly-ergoscript.git` to your own machine.
2. Run `cd blockly-ergoscript` to navigate inside project folder.
3. Run `npm install` to install the required dependencies.
4. Run `npm run start` to run the development server and see the app in action.
5. If you make any changes to the source code, just refresh the browser while the server is running to see them.


## ErgoScript References
- [ErgoScript Language Description](https://github.com/ScorexFoundation/sigmastate-interpreter/blob/develop/docs/LangSpec.md)  
- [ErgoScript Examples](https://github.com/ergoplatform/ergoscript-by-example)  
