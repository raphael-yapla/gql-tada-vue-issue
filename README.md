This repo highlights the false error flagged by gql.tada cli when importing fragments from a Vue SFC file to a TS file.

Repro steps:

1. Clone and install with `npm install`
2. Run `npx gql.tada check`
3. It should output the following error:

```sh
 ⚠ Unexpected Error 
Could not check files
┗ RangeError: Maximum call stack size exceeded
```
