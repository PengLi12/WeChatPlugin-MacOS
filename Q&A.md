## 常见问题解决方法：

##### 0. 开场:   
由于微信每次更新都会更新一些方法，因此建议可以先备份当前可用的微信.app(~~其实我是不太建议更新的~~)，这样避免微信更新之后，小助手部分功能失效或者闪退。

---

##### 1. 为什么我更新微信之后菜单栏小助手不见了？

因为微信更新之后，整个 app 都被覆盖，所以小助手也被清空，这时候只要重新安装小助手即可。

---

##### 2. 为什么更新了微信之后闪退/崩溃？

因为微信更换了API，导致小助手找不到对应的方法、函数，因此崩溃，解决方法有两种：1. 下载旧版本的微信。2.卸载微信小助手。

---

##### 3. 有没有微信群或者 QQ群讨论？

没有，目前没有这个打算。

---

##### 4. omw 无法安装或者是安装时候不是最新？

omw 的问题可以去 [oh-my-wechat](https://github.com/lmk123/oh-my-wechat) 提 issue，这样作者能够及时解决。
如果使用omw更新小助手不是最新的，可以使用其他安装方法试试。

---

##### 5. 如何卸载小助手？

在终端执行 Other 文件夹中的 Uninstall.sh，如果无效的话，那么再终端执行以下代码:

`cd /Applications/WeChat.app/Contents/MacOS && mv WeChat_backup WeChat`

如果在无效，那么请在Finder中应用程序中，右击微信.app，查看包内容，打开目录`/Contents/MacOS `，将`WeChat_backup`改名为 `WeChat`

---

##### 6. 如何禁止微信更新？

可以下载小助手1.7.5，如果是从官网下载，点击菜单栏的`微信小助手`-`禁止微信启动时检测更新`，如果是从 App Store，那么请在 App Store 中设置去除自动更新下载。

##### 7. 能不能做朋友圈或者微信抢红包？

* 不能，朋友圈工作量大，细节多，没有那么多的时间。
* 抢红包是不可能的，这辈子都不可能的，因为也没有人给我发红包。

---

##### 8. 能不能做群管理或者是自动添加好友？

不能，目前如果是有点微商性质的功能还是尽量避免，避免打扰到别人。

---

##### 9. 能不能做群发消息或者定时发送消息？

不能，目前如果是有点微商性质的功能还是尽量避免，避免打扰到别人。

---

##### 10. 为什么不支持企业微信？

企业微信跟普通的微信是两个app，方法也不一样，另外本人没有使用企业微信，因此不打算。

---

##### 11. 为什么菜单栏的小助手无法点击？

因为目前小助手的功能是分账号设置的，因为如果用户退出登录的话，那么将无法点击，只有重新登录微信才行。

---

##### 12. Safari /共享无法分享到微信？

目前无法解决。

---

##### 13. 休眠无法自动同步微信消息？

目前还无法解决。

---

##### 14. 作者是不是不更新了？

* 作者的目标是一年两更，现在已达标完成了。


