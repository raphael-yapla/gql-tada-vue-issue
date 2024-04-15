This repo highlights the false error flagged by gql.tada cli when importing fragments from a Vue SFC file to a TS file.

Repro steps:

1. Clone and install with `npm install`
2. Run `npx gql.tada check`
3. It should output the following error:
```sh
src/queries.ts
  11:14 error   Unknown fragment "PokemonItem".

✖ 1 problems (1 errors, 0 warnings)
```
