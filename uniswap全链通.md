<!--
 * @Description: 
 * @version: 
 * @Author: chenchuhua
 * @Date: 2021-06-21 15:02:51
 * @LastEditors: chenchuhua
 * @LastEditTime: 2021-06-21 15:12:46
-->

# 准备物料
# 合约:
    工厂合约
    路由合约
        weth合约
        multiall合的
    知识点:
        快速找到uniswap含均地址
        weth功能,其他链对应的台约
        multial功能


# 前端:
    uniswap前端
    uniswap-edk
    知识点:
        从github找到历史提交


# 其他:
    链的链接方式
            https://cheinlit on/


# 操作顺序
    修改合约获取init_ code
        a. bytes32 public constant INIT. _CODE PAIR_ HASH =keccak256(abi encodePacked(type(UniswapV2Pair).creationCodel);

    部署工厂合约
    获取INIT_ _CODE PAIR. HASH
    修改路由合约
    部署路由合约
    修改sdk
        工厂合约地址
        INIT. CODE PAIR HASH
        weth地址
        链id

    注册npmjs账号
    发布sdk
    修改前端
        路由合约地址
        支持的链id,supportedChainids
        浏览器链接,getEtherscanLink
        sdk包名
        multicall地址
        tokenlist

    部署前端


