# cmp-nvim-lsp-signature-help

nvim-cmp source for displaying function signatures with the current parameter emphasized:

![Basic Example](https://user-images.githubusercontent.com/12832280/144246351-0604d8cb-40c5-437b-9ca1-f3d420539360.png)  
# Setup

```lua

require'cmp'.setup {
  sources = {
    { name = 'nvim_lsp_signature_help' }
  }
}
```

