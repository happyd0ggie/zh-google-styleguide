3. 来自 Google 的奇技
--------------------------------------

Google 用了很多自己实现的技巧 / 工具使 C++ 代码更加健壮, 我们使用 C++ 的方式可能和你在其它地方见到的有所不同.

3.1. cpplint
~~~~~~~~~~~~~~~~~~~~~~~~

.. tip::

    使用 ``cpplint.py`` 检查风格错误.

``cpplint.py`` 是一个用来分析源文件, 能检查出多种风格错误的工具. 它不并完美, 甚至还会漏报和误报, 但它仍然是一个非常有用的工具. 在行尾加 ``// NOLINT``, 或在上一行加 ``// NOLINTNEXTLINE``, 可以忽略报错。

某些项目会指导你如何使用他们的项目工具运行 ``cpplint.py``. 如果你参与的项目没有提供, 你可以单独下载 `cpplint.py <http://github.com/google/styleguide/blob/gh-pages/cpplint/cpplint.py>`_.


译者笔记
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

#. Arch Linux 用户注意了，AUR 有对 cpplint 打包。
