# zed-smithy

Syntax highlighting for Smithy in [Zed](https://github.com/zed-industries/zed).

### Test locally

- Clone this repo: `git clone https://github.com/joshrutkowski/zed-smithy`
- Clone the [tree-sitter-smithy](https://github.com/indoorvivants/tree-sitter-smithy) repo: `https://github.com/indoorvivants/tree-sitter-smithy`
- CD into the repo: `cd tree-sitter-smithy`
- Build the WASM: `tree-sitter build-wasm` (might require docker-engine running)
- Rename the WASM file to `smithy.wasm`
- Move the WASM file into `smithy/grammars` (this repository)
- Move the `smithy`repository to `~/Library/Application Support/Zed/extensions/installed`
