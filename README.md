# All ERC20s Subgraph 

This code is inspired by similar projects [1](https://github.com/georgeroman/erc20-subgraph)[2](https://github.com/Abidoyesimze/subgraph). It processes all ERC20 contracts on a chain, only looking at transfers, thus only holding balances. The dependencies have been updated relative to the other projects.


# Build and Deploy
To build and deploy:

```
yarn install
yarn codegen
yarn build
goldsky login
yarn deploy
```

# Docs for Building Subgraphs

See the following links to learn more about how to build the subgraph:

* https://thegraph.com/docs/sv/subgraphs/developing/creating/subgraph-manifest/
* https://docs.goldsky.com/chains/immutable-zkevm