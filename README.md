# 油猴脚本：自动登录校园网

> 可直接前往 [这里](https://greasyfork.org/zh-CN/scripts/373315-dgut-%E6%A0%A1%E5%9B%AD%E7%BD%91%E8%87%AA%E5%8A%A8%E7%99%BB%E5%BD%95) 去安装这个脚本

使用此油猴脚本可以使您免去每次在页面中手动输入校园网账号和密码。（但您仍然需要打开校园网登录页面）

在安装此脚本之后，您需要在登录页面中进行一次手动输入校园网的账号和密码，
以便让此脚本记住您的校园网的账号和密码。下次在浏览器中打开登录页面，此脚本将自动向页面中输入账号信息并提交。

请放心，脚本所记录的账号和密码信息均保存在浏览器的 `localStorage` 中，并且**不会**上传到某处。
一旦浏览器的数据被清除，这些记录的信息也会被清除。
如果您不相信，您可以自行阅读位于 GitHub 中的 [源码](https://github.com/g-plane/dgut-network-login)。
（事实上，在安装此脚本之前，TamperMonkey 也允许您阅读此脚本的源码）

请注意，密码仅仅是经过简单的编码后放在 `localStorage` 中，请注意避免泄露。

如果您觉得脚本对您很有帮助，欢迎前往 [GitHub 仓库](https://github.com/g-plane/dgut-network-login) 给个 star。

## 贡献

欢迎为此脚本做贡献！您可以随时发起 PR。

## 开源许可证

MIT License (c) 2018-present [Pig Fang](https://gplane.win/)
