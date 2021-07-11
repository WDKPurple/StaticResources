# 图床使用指南

当你需要在文章中插入静态资源 *（包括但不限于图像、css等）* 时，你就需要使用图床。

目前，我们的图床托管在GitHub，并使用著名的jsDelivr项目进行分发。速度与稳定性有保障。

## 网页直接上传

以下是使用网页直接上传方式的流程指引：

1. 请确保你拥有一个GitHub账户 *（没有请注册）* ，并已告诉了时远你的用户名，以此获得图床的编辑权限。然后，让我们访问[WDKPurple/StaticResources](https://github.com/WDKPurple/StaticResources)，我们可以看到一个这样的界面：![image-20210708103137821](https://cdn.jsdelivr.net/gh/WDKPurple/StaticResources/images/userguide/image-20210708103137821.png)
2. 点击进入你需要上传的静态资源的对应目录，如图像的对应目录[images](https://github.com/WDKPurple/StaticResources/tree/main/images)，并点击Add file、Upload files，如图所示：![image-20210708103624567](https://cdn.jsdelivr.net/gh/WDKPurple/StaticResources/images/userguide/image-20210708103624567.png)
3. 进入上传界面后，选择你需要上传的文件，并在下方的 *Commit changes* 中简要描述本次上传的文件内容，如简要描述这些图片与哪些文章相关联，建议在描述中使用英文，如图所示：![image-20210708104139904](https://cdn.jsdelivr.net/gh/WDKPurple/StaticResources/images/userguide/image-20210708104139904.png)
4. 点击Commit changes以完成上传，而后你可以就可以通过jsDelivr访问你上传的静态资源，其地址格式为：https://cdn.jsdelivr.net/gh/WDKPurple/StaticResources/目录名/文件名

## 使用Typora配合PicGo使用

*本方式需要一些基础的计算机知识。*

本方式对于使用Typora进行编辑的同学比在网页上手动上传更加方便。

本方式建议直接参考知乎专栏文章[Typora+PicGo+Github+Jsdelivr实现高效图文写作](https://zhuanlan.zhihu.com/p/144053393)。但请注意：

1. 图床设置 > GitHub图床中，仓库名为 *WDKPurple/StaticResources* ，分支名为 *main* ，指定存储路径为 *images/* ，设定自定义域名为 *“https://cdn.jsdelivr.net/gh/WDKPurple/StaticResources/”* 。
2. Typora设置中请勾选“对本地位置的图片应用上述规则“，而不是如上文所描述取消勾选。
3. **注意！请勿使用任何其他图床！**

**如有任何问题，请直接联系时远！**

