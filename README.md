**Reproduction Steps**

*steps for reproducing memory Error* 
1. run `yarn install`
2. run `yarn add @hotglue/widget`

*steps to validate webpack as issue*
1. `rm -rf node_modules`
2.  remove `"webpack": "4.44.2",` from the `package.json`
3.  run `yarn install` again
4.  run `yarn add @hotglue/widget`

