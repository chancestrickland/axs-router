# Running Examples

TODO

Each example uses create-react-app. To develop against the examples you just need to link axs-router.

```
# from the root of the repository
yarn link axs-router
cd examples/crud
yarn && yarn start
```

There's a postinstall hook in each example that consumes the link.

Next you'll want to open a new terminal tab and watch:

```
# from the root of the repository
yarn watch
```
