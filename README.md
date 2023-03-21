# uniswapV2
Deploy IETHPersonal.sol
deploy TOkenERC20.sol
deploy UniswapV2Factory.sol
Read INIT_CODE_HASH -> Copy this hash without prefix 0x
Find UniswapV2Library -> pairFor function => Replace new hex by INIT_CODE_HASH above
Deploy UniswapV2Router02.sol
