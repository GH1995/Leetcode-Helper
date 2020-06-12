# Leetcode-Helper

![](https://badgen.net/badge/Coder/Mr Liu/red?icon=github)![](https://badgen.net/badge/Python/ 3.7.6/yellow?)![](https://badgen.net/badge/pandas/ 1.0.1/green?) ![](https://badgen.net/badge/requests/ 2.22.0/blue?)

哪个~~男孩~~程序员不想一键下载写过的代码，并且生成一份好看的README呢？

真的有人会不点:star:吗?  不会吧，不会吧，不会吧。



<hr>

**:heart:主要功能:heart:**

:cat: 模拟登陆力扣中国站(leetcode-cn)

:cat: 顺序爬取每题最新的提交代码，保存至本地。

:cat: 自动生成优美的github的README文件至本地。

:cat: 支持指定id区间的源码下载保存。​

<hr>
**少啰嗦，先看东西 :      [具体生成效果。点击这里](https://github.com/Liuyang0001/LeetCode_By_Python)**

生成的README效果图：

![](https://gitee.com/liuyang0001/blogimage/raw/master/img/20200612225140.png)

生成的源码效果图：

![](https://gitee.com/liuyang0001/blogimage/raw/master/img/20200612225252.png)

<hr>

## 使用说明

1. clone 该项目到你的本地。

```python
git clone https://github.com/Liuyang0001/Leetcode-Helper.git
```

2. 配置你的cofig.json文件。

```json
{
    "email": "xx账号xxxx",
    "password": "xxx密码xxx",
    "outdir": "xxxxxx",
    "git_url": "https://github.com/xxxxx/xxx仓库名xx/tree/master/codes_auto/",
    "download_start_id": 1, 
    "download_end_id": 10000,
    "refresh": false
}
```

3. 运行`main.py`文件

```
python main,py
```

<hr>
> 其他说明：
>
> 1. 第一次运行比较慢，主要是爬取速度太快太频繁，会偶尔无回应。
> 2. 题库后续会增加局部更新，就不用每次都全局更新，请持续关注。
> 3. 如果发生异常，请尝试重新运行
> 4. 为了运行速度，已生成代码不会覆盖，相同题的代码仅保留一份ac的。
> 5. 如果大家有需求的话，可能还会写个GUI界面，会更直观一点，没人的话就算了。



本人是一个准研一的小菜🐔，在家无事的练手项目，求轻喷。

万水千山总是情，给个:star: 行不行，感谢大家。

Enjoy coding！