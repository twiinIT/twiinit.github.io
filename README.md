# twiinIT website

This website uses the static website generator [Hugo](https://gohugo.io/).

To test it, you need to clone it with its submodules.
Either add the option `--recurse-submodules` to the `git clone` command or run manually `git submodule init` and `git submodule update` after cloning.

You can run Hugo's webserver in development mode (supporting automatic rebuilds on changes) with the command `hugo serve` from the root of the repository.
Please note that if you plan to also work on the layouts, you should pass the parameter `--disableFastRender` to Hugo in order to avoid some partial rebuild issues.
