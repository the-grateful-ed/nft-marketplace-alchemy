## Here are the instructions on how to use additional plugins of the project

### Solhint
[repo](https://github.com/protofire/solhint)
- Run linter 
```
solhint 'contracts/**/*.sol'
```

### Slither
[repo](https://github.com/crytic/slither)
- Install
```
pip3 install slither-analyzer
```
- Run the security check
```
slither .
```

### Solidity Coverage  
[repo](https://github.com/sc-forks/solidity-coverage)
- Run the coverage check
```
npx hardhat coverage
```
- Open the results in the browser
    - See results in `coverage/index.html` file

### Prettier (+ Solidity Plugin)
[original repo](https://github.com/prettier/prettier)  
[plugin repo](https://github.com/prettier-solidity/prettier-plugin-solidity)
- Run code formatter
```
npx prettier --write .
```

### Hardhat Dodoc
[repo](https://github.com/primitivefinance/primitive-dodoc)
- Run
```
npx hardhat dodoc
```
- It's configured to run on *each* contracts compilation
- See results in `docs/` directory

TODO add other plugins from hardhat config
