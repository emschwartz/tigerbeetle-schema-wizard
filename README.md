<img src="https://github.com/emschwartz/tigerbeetle-schema-wizard/assets/3262610/046153f4-4657-4109-89b0-cb990b790621" width=200 />

# TigerBeetle Schema Wizard

When using TigerBeetle, you need to model your use case in terms of [ledgers](https://docs.tigerbeetle.com/reference/accounts#ledger), [codes](https://docs.tigerbeetle.com/reference/accounts#code), [accounts](https://docs.tigerbeetle.com/reference/accounts), and [transfers](https://docs.tigerbeetle.com/reference/transfers). That means developers need to first wrap their heads around double-entry bookkeeping in order to take advantage of the power of TigerBeetle.

This project aims to simplify the usage of TigerBeetle by allowing you to define the schema of your business logic in a simple TOML format. It then generates client code in any of the supported languages to make building systems on top of TigerBeetle easy and error-free.

## Contents

- [Schema](./schema.toml)
- [Generated TypeScript client code\*](./src/generated.ts)
- [Example usage script](./src/index.ts)

\* Note: the client code is not currently being generated 😋

## Trying it out

1. [Run TigerBeetle on your local machine](https://docs.tigerbeetle.com/quick-start/single-binary)
2. Clone this repo
3. `npm install`
4. Run `npm run dev` to create two accounts, fund them, and send a transfer between them
