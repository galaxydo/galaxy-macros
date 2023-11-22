# galaxy-macros

Galaxy Browser supports loading macros added by community in this repository.

You can follow process to register your macro:

1) Create a folder with macro name

2) Add main.ts and test.ts

main.ts should expose function with signature

```
async function macroName(input: Element, output: Element | Element[] | string);
```

3) Make PR
