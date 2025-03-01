# Table of Contents

- [Table of Contents](#table-of-contents)
  - [Debug](#debug)
    - [Debugger](#debugger)
      - [nvim-dap extension](#nvim-dap-extension)
    - [REPL](#repl)
    - [Refactoring,Debugging](#refactoringdebugging)
      - [print debug](#print-debug)
      - [stack trace analyze](#stack-trace-analyze)

## Debug

### Debugger

- [mfussenegger/nvim-dap](https://github.com/mfussenegger/nvim-dap) ![](https://img.shields.io/github/stars/mfussenegger/nvim-dap) ![](https://img.shields.io/github/last-commit/mfussenegger/nvim-dap) ![](https://img.shields.io/github/commit-activity/y/mfussenegger/nvim-dap)
- [hiberabyss/nvim-dbg](https://github.com/hiberabyss/nvim-dbg) ![](https://img.shields.io/github/stars/hiberabyss/nvim-dbg) ![](https://img.shields.io/github/last-commit/hiberabyss/nvim-dbg) ![](https://img.shields.io/github/commit-activity/y/hiberabyss/nvim-dbg)
- [sakhnik/nvim-gdb](https://github.com/sakhnik/nvim-gdb) ![](https://img.shields.io/github/stars/sakhnik/nvim-gdb) ![](https://img.shields.io/github/last-commit/sakhnik/nvim-gdb) ![](https://img.shields.io/github/commit-activity/y/sakhnik/nvim-gdb)
- [dradtke/debug-console](https://github.com/dradtke/debug-console) ![](https://img.shields.io/github/stars/dradtke/debug-console) ![](https://img.shields.io/github/last-commit/dradtke/debug-console) ![](https://img.shields.io/github/commit-activity/y/dradtke/debug-console)
- [mxsdev/nvim-dap-vscode-js](https://github.com/mxsdev/nvim-dap-vscode-js) ![](https://img.shields.io/github/stars/mxsdev/nvim-dap-vscode-js) ![](https://img.shields.io/github/last-commit/mxsdev/nvim-dap-vscode-js) ![](https://img.shields.io/github/commit-activity/y/mxsdev/nvim-dap-vscode-js)
- [austin5627/acr.nvim](https://github.com/austin5627/acr.nvim) ![](https://img.shields.io/github/stars/austin5627/acr.nvim) ![](https://img.shields.io/github/last-commit/austin5627/acr.nvim) ![](https://img.shields.io/github/commit-activity/y/austin5627/acr.nvim)

#### nvim-dap extension

- [rcarriga/nvim-dap-ui](https://github.com/rcarriga/nvim-dap-ui) ![](https://img.shields.io/github/stars/rcarriga/nvim-dap-ui) ![](https://img.shields.io/github/last-commit/rcarriga/nvim-dap-ui) ![](https://img.shields.io/github/commit-activity/y/rcarriga/nvim-dap-ui)
- [theHamsta/nvim-dap-virtual-text](https://github.com/theHamsta/nvim-dap-virtual-text) ![](https://img.shields.io/github/stars/theHamsta/nvim-dap-virtual-text) ![](https://img.shields.io/github/last-commit/theHamsta/nvim-dap-virtual-text) ![](https://img.shields.io/github/commit-activity/y/theHamsta/nvim-dap-virtual-text)
- [HiPhish/debugpy.nvim](https://github.com/HiPhish/debugpy.nvim) ![](https://img.shields.io/github/stars/HiPhish/debugpy.nvim) ![](https://img.shields.io/github/last-commit/HiPhish/debugpy.nvim) ![](https://img.shields.io/github/commit-activity/y/HiPhish/debugpy.nvim)
- [Weissle/persistent-breakpoints.nvim](https://github.com/Weissle/persistent-breakpoints.nvim) ![](https://img.shields.io/github/stars/Weissle/persistent-breakpoints.nvim) ![](https://img.shields.io/github/last-commit/Weissle/persistent-breakpoints.nvim) ![](https://img.shields.io/github/commit-activity/y/Weissle/persistent-breakpoints.nvim)
- [rcarriga/cmp-dap](https://github.com/rcarriga/cmp-dap) ![](https://img.shields.io/github/stars/rcarriga/cmp-dap) ![](https://img.shields.io/github/last-commit/rcarriga/cmp-dap) ![](https://img.shields.io/github/commit-activity/y/rcarriga/cmp-dap)
- [sidebar-nvim/sections-dap](https://github.com/sidebar-nvim/sections-dap) ![](https://img.shields.io/github/stars/sidebar-nvim/sections-dap) ![](https://img.shields.io/github/last-commit/sidebar-nvim/sections-dap) ![](https://img.shields.io/github/commit-activity/y/sidebar-nvim/sections-dap)
- [nickbanderson/nvim-dap-runner.nvim](https://github.com/nickbanderson/nvim-dap-runner.nvim) ![](https://img.shields.io/github/stars/nickbanderson/nvim-dap-runner.nvim) ![](https://img.shields.io/github/last-commit/nickbanderson/nvim-dap-runner.nvim) ![](https://img.shields.io/github/commit-activity/y/nickbanderson/nvim-dap-runner.nvim)
- [ofirgall/goto-breakpoints.nvim](https://github.com/ofirgall/goto-breakpoints.nvim) ![](https://img.shields.io/github/stars/ofirgall/goto-breakpoints.nvim) ![](https://img.shields.io/github/last-commit/ofirgall/goto-breakpoints.nvim) ![](https://img.shields.io/github/commit-activity/y/ofirgall/goto-breakpoints.nvim)
- [suketa/nvim-dap-ruby](https://github.com/suketa/nvim-dap-ruby) ![](https://img.shields.io/github/stars/suketa/nvim-dap-ruby) ![](https://img.shields.io/github/last-commit/suketa/nvim-dap-ruby) ![](https://img.shields.io/github/commit-activity/y/suketa/nvim-dap-ruby)
- [LiadOz/meta-breakpoints.nvim](https://github.com/LiadOz/meta-breakpoints.nvim) ![](https://img.shields.io/github/stars/LiadOz/meta-breakpoints.nvim) ![](https://img.shields.io/github/last-commit/LiadOz/meta-breakpoints.nvim) ![](https://img.shields.io/github/commit-activity/y/LiadOz/meta-breakpoints.nvim)
- [csterlent/dap-hot-config.nvim](https://github.com/csterlent/dap-hot-config.nvim) ![](https://img.shields.io/github/stars/csterlent/dap-hot-config.nvim) ![](https://img.shields.io/github/last-commit/csterlent/dap-hot-config.nvim) ![](https://img.shields.io/github/commit-activity/y/csterlent/dap-hot-config.nvim)
- [chunleng/nvim-dap-kitty-launcher](https://github.com/chunleng/nvim-dap-kitty-launcher) ![](https://img.shields.io/github/stars/chunleng/nvim-dap-kitty-launcher) ![](https://img.shields.io/github/last-commit/chunleng/nvim-dap-kitty-launcher) ![](https://img.shields.io/github/commit-activity/y/chunleng/nvim-dap-kitty-launcher)
- [przepompownia/nvim-dap-tab](https://github.com/przepompownia/nvim-dap-tab) ![](https://img.shields.io/github/stars/przepompownia/nvim-dap-tab) ![](https://img.shields.io/github/last-commit/przepompownia/nvim-dap-tab) ![](https://img.shields.io/github/commit-activity/y/przepompownia/nvim-dap-tab)
- [GitEdvard/read-settings.nvim](https://github.com/GitEdvard/read-settings.nvim) ![](https://img.shields.io/github/stars/GitEdvard/read-settings.nvim) ![](https://img.shields.io/github/last-commit/GitEdvard/read-settings.nvim) ![](https://img.shields.io/github/commit-activity/y/GitEdvard/read-settings.nvim)

### REPL

- [hkupty/iron.nvim](https://github.com/hkupty/iron.nvim) ![](https://img.shields.io/github/stars/hkupty/iron.nvim) ![](https://img.shields.io/github/last-commit/hkupty/iron.nvim) ![](https://img.shields.io/github/commit-activity/y/hkupty/iron.nvim)
- [jbyuki/dash.nvim](https://github.com/jbyuki/dash.nvim) ![](https://img.shields.io/github/stars/jbyuki/dash.nvim) ![](https://img.shields.io/github/last-commit/jbyuki/dash.nvim) ![](https://img.shields.io/github/commit-activity/y/jbyuki/dash.nvim)
- [fdschmidt93/resin.nvim](https://github.com/fdschmidt93/resin.nvim) ![](https://img.shields.io/github/stars/fdschmidt93/resin.nvim) ![](https://img.shields.io/github/last-commit/fdschmidt93/resin.nvim) ![](https://img.shields.io/github/commit-activity/y/fdschmidt93/resin.nvim)
- [luissimas/eval.nvim](https://github.com/luissimas/eval.nvim) ![](https://img.shields.io/github/stars/luissimas/eval.nvim) ![](https://img.shields.io/github/last-commit/luissimas/eval.nvim) ![](https://img.shields.io/github/commit-activity/y/luissimas/eval.nvim)
- [Olical/conjure](https://github.com/Olical/conjure) ![](https://img.shields.io/github/stars/Olical/conjure) ![](https://img.shields.io/github/last-commit/Olical/conjure) ![](https://img.shields.io/github/commit-activity/y/Olical/conjure)
- [aoi-iter/brepl.nvim](https://github.com/aoi-iter/brepl.nvim) ![](https://img.shields.io/github/stars/aoi-iter/brepl.nvim) ![](https://img.shields.io/github/last-commit/aoi-iter/brepl.nvim) ![](https://img.shields.io/github/commit-activity/y/aoi-iter/brepl.nvim)
- [liborw/equals](https://github.com/liborw/equals) ![](https://img.shields.io/github/stars/liborw/equals) ![](https://img.shields.io/github/last-commit/liborw/equals) ![](https://img.shields.io/github/commit-activity/y/liborw/equals)

### Refactoring,Debugging

- [ThePrimeagen/refactoring.nvim](https://github.com/ThePrimeagen/refactoring.nvim) ![](https://img.shields.io/github/stars/ThePrimeagen/refactoring.nvim) ![](https://img.shields.io/github/last-commit/ThePrimeagen/refactoring.nvim) ![](https://img.shields.io/github/commit-activity/y/ThePrimeagen/refactoring.nvim)
- [nvim-treesitter/nvim-treesitter-refactor](https://github.com/nvim-treesitter/nvim-treesitter-refactor) ![](https://img.shields.io/github/stars/nvim-treesitter/nvim-treesitter-refactor) ![](https://img.shields.io/github/last-commit/nvim-treesitter/nvim-treesitter-refactor) ![](https://img.shields.io/github/commit-activity/y/nvim-treesitter/nvim-treesitter-refactor)

#### print debug

- [andrewferrier/debugprint.nvim](https://github.com/andrewferrier/debugprint.nvim) ![](https://img.shields.io/github/stars/andrewferrier/debugprint.nvim) ![](https://img.shields.io/github/last-commit/andrewferrier/debugprint.nvim) ![](https://img.shields.io/github/commit-activity/y/andrewferrier/debugprint.nvim)
- [rareitems/printer.nvim](https://github.com/rareitems/printer.nvim) ![](https://img.shields.io/github/stars/rareitems/printer.nvim) ![](https://img.shields.io/github/last-commit/rareitems/printer.nvim) ![](https://img.shields.io/github/commit-activity/y/rareitems/printer.nvim)
- [PatschD/zippy.nvim](https://github.com/PatschD/zippy.nvim) ![](https://img.shields.io/github/stars/PatschD/zippy.nvim) ![](https://img.shields.io/github/last-commit/PatschD/zippy.nvim) ![](https://img.shields.io/github/commit-activity/y/PatschD/zippy.nvim)

#### stack trace analyze

- [vigoux/infer.nvim](https://github.com/vigoux/infer.nvim) ![](https://img.shields.io/github/stars/vigoux/infer.nvim) ![](https://img.shields.io/github/last-commit/vigoux/infer.nvim) ![](https://img.shields.io/github/commit-activity/y/vigoux/infer.nvim)
