# linter-flow package

linter-flow implements a [linter](https://github.com/AtomLinter/Linter) plugin
for Facebook's [Flow JS typechecker](http://flowtype.org/).

![](http://cl.ly/image/1x013a2V1m0b/content#png)

### How to use it

1. [Install Flow](http://flowtype.org/docs/getting-started.html#installing-flow)
1. Install the package
1. Create an empty `.flowconfig` file at the root of your repo
1. Open a JS file

You should start seeing lint errors related to types - try opening the Flow
example projects in Atom

### Troubleshooting

##### OS X: No lint errors are shown?
* **Possible cause:** The PATH to your Flow executable cannot be found.
* **Solution:** Try launching Atom from the terminal. Alternative workarounds here: [atom/atom-shell#550](https://github.com/atom/atom-shell/issues/550)
