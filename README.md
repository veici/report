# report
umijs与yarn workspace结合使用时bug重现。

```
yarn install

```
报错信息为
```
error D:\hub\report\node_modules\@report\home: Command failed.
Exit code: 1
Command: umi generate tmp
Arguments:
Directory: D:\hub\report\node_modules\@report\home
Output:
node:internal/modules/cjs/loader:903
  throw err;
  ^

Error: Cannot find module 'D:\hub\report\node_modules\node_modules\umi\bin\umi.js'
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:900:15)
    at Function.Module._load (node:internal/modules/cjs/loader:745:27)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:72:12)
    at node:internal/main/run_main_module:17:47 {
 ```
