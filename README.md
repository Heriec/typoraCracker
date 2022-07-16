# Typora

> 对于现在的新版本，我觉得也没必要破解，作者并没有把以前的版本也收费，已经对他来说仁至义尽了，但是令人琢磨不懂的是，老版本会有过期问题。

放了两个老版本版本的Typora，都是以前的免费版，但是会过期，本项目旨在解决过期问题。

```
链接：https://pan.baidu.com/s/1JBCMcUzs9BH-5nYVCCIiTQ?pwd=5maz 
提取码：5maz
```

## typora Cracker

原项目是[fossabot/typoraCracker: A patch and keygen tools for typora. (github.com)](https://github.com/fossabot/typoraCracker)的，我拿过来使用，防止后面Typora不给用了，我有个备份。

本项目里面的dec_app是已经修改过的了，所以直接放到Typora下改名为`app`就可以用。

下面是解决步骤。

**遇到Typora过期问题**

```
This beta version of Typora is expired, please download and install a newer version.
```
解决方案如下：

1、下载解密typoraCracker教程

https://github.com/fossabot/typoraCracker 

> 现在我们这个项目里面就可以用了，下面操作都不需要。

下载后，win+R打开cmd，进入typoraCracker目录。

2、执行命令
```
pip install -r requirements.txt
python typora.py "C:\Program Files\Typora\resources\app.asar" .  // 你Typora安装在那个文件夹下面就是那个文件夹
```
会在 typoraCracker 文件夹下生成dec_app文件
![在这里插入图片描述](https://img-blog.csdnimg.cn/a1ffe1d6db444e688a4e71d8cae6d67d.png)
3、修改我们反编译的 dec_app 文件夹下的 `License.js`文件

我们省事，直接将文件中`1636297098336`全部替换成`4713176400336`
这就是修改注册时间，如果想研究一下源码也是可以的。
好了，这个时候我们保存这个文件

4、文件替换

把dec_app，把它复制到Typora目录下的resources，并改名为app
![在这里插入图片描述](https://img-blog.csdnimg.cn/f1619a78b9f347bcad1eb62bdcf3ec5f.png)
现在我再打开typora就可以使用了。



## themes

themes文件夹是我存的各种主题直接放到 `偏好设置` 中的 `外观` 里的 `打开主题文件夹`里面的文件夹就可以了

![在这里插入图片描述](https://img-blog.csdnimg.cn/4488ea79f4bd4d10aedc47ba096892ee.png)

