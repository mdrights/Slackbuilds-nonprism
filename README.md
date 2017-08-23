# Slackbuilds-nonprism
My Slackbuilds，for my privacy-focused and anti-prism LiveSLAK GNU/Linux (Slackware-based)

这里是本人写的一些 Slackware 软件安装脚本，受 [Parabola GNU/linux-libre](https://parabola.nu/) 中的 [nonprism](https://git.parabola.nu/abslibre.git/tree/nonprism) 社区仓库 启发。更多关于 [nonprism](https://wiki.parabola.nu/Nonprism)。

这些脚本所构建的应用，会成为我的（隐私加强定制的）Live 发行版（基于 Slackware）的一部分。

本 Live发行版 的构建程序在 [LiveSlak repo](), forked 自 Alien Bob 强大的 [脚本](http://www.slackware.com/~alien/liveslak/)！（表示感谢）

更多关于 [LiveSlak / Slackware Live Edition](https://docs.slackware.com/slackware:liveslak)

## 使用方法（目前）

- 下载本repo，或 git clone 之；

- 进入应用的目录，执行（确保有执行权限，可能需要root）：
`./xxxx.slackbuild`

- 得到一个 .tgz 或 .txz 文件，如果你想构建自己的 live 发行版，请
  - 把它（们）放在同一个目录下（并记得这个路径），在执行 LiveSlak 中的 make_slackware_live.sh 时会安装这些软件包。
