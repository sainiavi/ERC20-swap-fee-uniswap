install:
  - yarn install

before_script:
  - yarn lint

script:
  - yarn compile
  - yarn test

please find MockERC20WithFee1.sol in "contracts/mock/MockERC20WithFee1.sol" for token with transfer royality 

please find intermediate.sol in contracts/uniswap/intermediate.sol for uniswap contract which allow user to create a pair and add liqiudity to it and swap token supporting fee.
