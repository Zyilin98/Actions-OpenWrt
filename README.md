## 一个云编译Openwrt固件的项目
###### 目前项目无法通过Github Action 进行在线编译 将会在不久的将来重构结构 使其能在Github Action编译 *但本地编译可行

*固件主要用于解决校园网的多设备检测 已经在固件内集成rkp-ipid，ttl修改 未添加任何UA（User-Agent）修改模块 

*(目前已知大部分学校不会对ipid进行检测 将会在不久将来移除ipid)
### 食用方法：
##### 用其他设备的话请改X86.config里的上面三行，改成自己所需要的 config，复制别人的来用也行，下面的不要动哦
##### 目前使用了Lean源和天灵源 无Docker支持 暂时只有X86设备固件 （已经计划编译 适用于 Redmi AC2100以及适用于 IPQ6000 CPU 的固件）
##### 目前本地编译x86，已测试成功
##### Releases 中带有Local Tag为本地编译所编译出的包 VMDK格式固件可能会有无法启动的问题
##### 锐捷eportal认证的一个<a href="https://blog.mjjman.com/archives/10">解决方案</a><br>
<br><a href="https://p3terx.com/archives/build-openwrt-with-github-actions.html">参考文献</a><br>
<a href="https://sunbk201public.notion.site/sunbk201public/OpenWrt-f59ae1a76741486092c27bc24dbadc59">详细教程</a><br>
<a href="https://github.com/CHN-beta/rkp-ipid">rkp-ipid</a><br>

## Credits

- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub Actions](https://github.com/features/actions)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [ImmortalWrt](https://github.com/immortalwrt/immortalwrt)
- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)
- [tmate](https://github.com/tmate-io/tmate)
- [mxschmitt/action-tmate](https://github.com/mxschmitt/action-tmate)
- [csexton/debugger-action](https://github.com/csexton/debugger-action)
- [Cowtransfer](https://cowtransfer.com)
- [WeTransfer](https://wetransfer.com/)
- [Mikubill/transfer](https://github.com/Mikubill/transfer)
- [softprops/action-gh-release](https://github.com/softprops/action-gh-release)
- [ActionsRML/delete-workflow-runs](https://github.com/ActionsRML/delete-workflow-runs)
- [dev-drprasad/delete-older-releases](https://github.com/dev-drprasad/delete-older-releases)
- [peter-evans/repository-dispatch](https://github.com/peter-evans/repository-dispatch)
- [锐捷eportal认证破解 - 神域's Blog](https://blog.mjjman.com/archives/10)
- [Openwrt for Nanopi R1S R2S R4S 香橙派 R1 Plus 固件编译 纯净版与大杂烩](https://github.com/klever1988/nanopi-openwrt)
