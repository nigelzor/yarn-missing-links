steps to reproduce:
```
git clean -fxd
yarn install
```

expected output: (as seen with yarn@1)
```
ls packages/service/node_modules/.bin
> micro
```

observed output: (using yarn@2)
```
ls packages/service/node_modules/.bin
> ls: packages/service/node_modules/.bin: No such file or directory
```
