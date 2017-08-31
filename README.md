# babel-7-bug-repro

Repro with `npm run babel`

## Error on my machine

TypeError: src\foo.js: Cannot read property 'bindings' of null
    at Scope.moveBindingTo (C:\Users\wilkelly\Downloads\babelBug\node_modules\babel-traverse\lib\scope\index.js:974:12)
    at BlockScoping.updateScopeInfo (C:\Users\wilkelly\Downloads\babelBug\node_modules\babel-plugin-transform-es2015-block-scoping\lib\index.js:364:17)
    at BlockScoping.run (C:\Users\wilkelly\Downloads\babelBug\node_modules\babel-plugin-transform-es2015-block-scoping\lib\index.js:330:12)
    at PluginPass.BlockStatementSwitchStatementProgram (C:\Users\wilkelly\Downloads\babelBug\node_modules\babel-plugin-transform-es2015-block-scoping\lib\index.js:70:24)
    at newFn (C:\Users\wilkelly\Downloads\babelBug\node_modules\babel-traverse\lib\visitors.js:236:21)
    at NodePath._call (C:\Users\wilkelly\Downloads\babelBug\node_modules\babel-traverse\lib\path\context.js:68:19)
    at NodePath.call (C:\Users\wilkelly\Downloads\babelBug\node_modules\babel-traverse\lib\path\context.js:42:17)
    at NodePath.visit (C:\Users\wilkelly\Downloads\babelBug\node_modules\babel-traverse\lib\path\context.js:99:12)
    at TraversalContext.visitQueue (C:\Users\wilkelly\Downloads\babelBug\node_modules\babel-traverse\lib\context.js:137:18)
    at TraversalContext.visitSingle (C:\Users\wilkelly\Downloads\babelBug\node_modules\babel-traverse\lib\context.js:96:19)
