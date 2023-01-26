## Testing

Notes on testing Mermaid support in GitHub:
- Supports `.md`, `.mmd` and `.mermaid` files.
- Supports the complete examples.

Notes on testing Mermaid plugins for VSCode:
- [Mermaid Markdown Syntax Highlighting](https://marketplace.visualstudio.com/items?itemName=bpruitt-goddard.mermaid-markdown-syntax-highlighting)
    - Seems to be working fine. Optional, as it just offers syntax highlightning.
    - Seems to be required by other plugins.
- [Markdown Preview Mermaid Support](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid)
    - Works only with `.md` files.
    - Supports the complete example.
- [Mermaid Editor](https://marketplace.visualstudio.com/items?itemName=tomoyukim.vscode-mermaid-editor)
    - Works only with `.mmd` files.
    - Works with simplified example only.
    - Fails generating images with `mermaid-editor: Failed to generate image.` message.
        - Seems to be an issue only in the preview section.
        - Source section generates a solid `.svg`.
- [Mermaid Preview](https://marketplace.visualstudio.com/items?itemName=vstirbu.vscode-mermaid-preview)
    - Works with `.md` and `.mmd` files.
    - Works with simplified examples only.
- [Preview](https://marketplace.visualstudio.com/items?itemName=searKing.preview-vscode)
    - Works with `.md`, `.mmd` and `.mermaid` files.
    - Works with simplified examples only.

## Summary

Using VSCode with [Mermaid Markdown Syntax Highlighting](https://marketplace.visualstudio.com/items?itemName=bpruitt-goddard.mermaid-markdown-syntax-highlighting) and [Markdown Preview Mermaid Support](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid) is a solid option.

The [Markdown Preview Mermaid Support](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid) plugin does limit us to `.md` files, but other plugins do not support `.mmd` and `.mermaid` files completely.