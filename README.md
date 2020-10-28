# nuxt-debug-test

## Steps to reproduce

### Run Nuxt
```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev
```

### Start debugger

1) Launch VSCode and make sure Javascript in-preview debugger is not enabled. 
2) Set breakpoint in `pages/index.vue` on any lines inside the `mounted` method.
3) Run debugger with F5 and hit breakpoint
4) Stop debugging
5) Now enable Javascript in-preview debugger
6) Run debugger and miss breakpoint completely

