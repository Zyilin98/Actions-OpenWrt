## 一个云编译Openwrt固件的项目
###### 目前项目无法通过Github Action 进行在线编译 *但本地编译可行

*固件主要用于解决校园网的多设备检测 未添加任何UA（User-Agent）修改模块 

*(目前已知大部分学校不会对ipid进行检测 现已经移除rkp-ipid模块 如果我自己的学校会检测的ipid 也许会在某个版本迭代中加入)
### 食用方法：
##### 直接选取Release中最新版本 刷入到设备即可使用
##### 如果需要自行在线编译 用其他CPU架构设备的话请改X86-1.config里的上面三行，改成自己所需要的 config，复制别人的来用也行，下面的不要动哦
##### 目前使用了Immortalwrt源 无Docker支持 暂时只有X86设备固件 （已经计划编译 使用openwrt官方分支22.03和Lean分支的固件）
##### 目前本地编译x86是没有任何问题的
##### 锐捷eportal认证的一个<a href="https://blog.mjjman.com/archives/10">解决方案</a><br>
<br><a href="https://p3terx.com/archives/build-openwrt-with-github-actions.html">参考文献</a><br>
<a href="https://sunbk201public.notion.site/sunbk201public/OpenWrt-f59ae1a76741486092c27bc24dbadc59">详细教程</a><br>
<a href="https://github.com/CHN-beta/rkp-ipid">rkp-ipid</a><br>

#### 目前Release的命名规则
以Immortalwrt-local-22.06.28-beta.2为例<br>
 Immortalwrt代表固件的源码来源于Immortalwrt分支 <br>
 local表示是由本地编译后上传<br>
 22.06.28表示编译于2022.06.28<br>
 beta表示当前的固件仍需要修改<br>
 2表示为这是当日编译的第二个版本<br>

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
- [自动构建Lean源码，天灵的源码，openwrt源码！ ](https://github.com/jingleijack/X86_64-TEST)
