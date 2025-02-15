# 为什么服务的秘钥验证失败？

服务验证失败通常有以下几种类型，遇到问题麻烦先自查一下

01. 申请服务的时候**跳过了**我写的申请文档里面的某一步或者多个步骤。
    01. 有的文档的截图可能已经和申请时在服务商官网看到的不一样，因为服务商可能改 UI 了
    02. 不过整体步骤应该变化不会太大
    03. 只要是我写出来的步骤，如果没有明确说明可以跳过那就是不能跳过的，请按步骤申请
    04. **麻烦好好检查一下，很多用户都是因跳过了某个步骤** 🙏
02. 将秘钥粘贴到 Bob 秘钥输入框的时候**多粘贴的一些东西**，比如空格换行符之类的，也有的人是将秘钥粘贴进去了多次。
    01. 选中 Bob 秘钥输入框之后，command + a 选中所有的文本，然后按一下 delete 键全部删掉，然后重新把你的秘钥粘贴进去。
    02. Bob 秘钥输入框只能显示一行，可能显示不全你的秘钥，这个不用管。你只需要保证你从服务商那儿复制的秘钥是全的就行。
    03. **这个问题也是重灾区，好好检查下**
03. 网络问题。
    01. 有的服务在科学上网（或者肉身在国外）的情况下无法访问
    02. 检查下自己是否开启了全局的科学上网，如果是建议改成 PAC 模式
    03. 另外，谷歌系列的服务在国内访问不了确实有可能概率性无法验证成功
    04. 如果想为某个服务开启代理，[点此查看各个服务域名](faq/service-proxy.md)
04. 服务商的问题。例如百度翻译，偶尔会概率性封禁用户的秘钥一天，第二天又好了，原因不是太明确。
05. Bob 网络请求的权限可能出问题了，这种情况**重启电脑**试试。

如果感觉不属于以上情况，请加入 QQ 群联系我们。

👉 [点此查看如何加群？](general/contact.md)





