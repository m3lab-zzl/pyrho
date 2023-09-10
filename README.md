相比于前一个仅做简单介绍的项目，这个项目让计算从1D扩展到3D，补充了很多细节，而且算法原理也和第一个项目有所区别，作为正式学习材料比较合适。

Pyrho是一个用Python编写的实空间DFT代码。它强调可读性而不是执行效率。它想帮助对DFT感兴趣但又不敢轻易尝试的人，通过编写一个简单的DFT代码，来理解DFT的基本原理。
> Pyrho is a real-space DFT code written in Python. It is *not* built to be super-fast or scalable-
instead, it is built to be super-readable.*

> In the last few decades, thousands of Ph.D.'s have been given to hard-working theoreticians who solved
complex scientific problems using density functional theory (DFT) codes that they don't really
understand. Pyrho exists to make the "under-the hood" foundation for most DFT codes accessible to
those of us who aren't brave enough to dive into the source code of research grade DFT software packages.

[教程文档入口](./tutorial.ipynb). （原作者Prof. Joerg Neugebauer.）

依赖配置：

```sh
conda install -c conda-forge pyrho
# 或者如果git连接速度不慢
# git clone https://github.com/ashtonmv/pyrho.git
# pip install -r pyrho/requirements.txt
```

处于对精简性的追求，诸如 虚拟环境、Python 项目依赖配置、第三方库版本冲突 这类与pyrho本身无关的问题，请自行搜索解决

备注：

- testing with mybinder
[Run the tutorial notebook on a remote docker instance here](https://mybinder.org/v2/gh/ashtonmv/pyrho/master)
