```diff 
+ 注意事项:
- jumkey 仅支持 7.0及以下, pocopico&jun 也仅支持7.0及以下. 
- 只有 DS3615xs 和 DS918+ 支持 6.2.4 版本. DS918+/DS920+/DS1621+/DVA1622 的 7.1.1 版本要用(dev)模式.
- dtb 没有就不要写, 不要再只填个 .zip, 或者复制示例的地址了.更多信息参考 Issues页的置顶Issue.
- 有关map参数：SataPortMap=有几位就表示有几个控制器。DiskIdxMap=按顺序从左到右每两位数(16进制)为一个控制器的盘序数值.
- - 因此 DiskIdxMap 的位数应该是 SataPortMap 的2倍. eg: 1,00  22,0002  222,000204.

```
