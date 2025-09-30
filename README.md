# repro-snacks-input

* To reproduce issue, start with `nvim -u repro.lua`.
* Afterwards run `:lua vim.ui.input({ prompt = "hey" }, function(input) print("You entered: " .. input) end)`
* Pressing escape does not enter normal mode.
* Pressing escape twice does not close input.
* Pressing escape and a different key like `l` does get into normal mode.

