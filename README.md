sqlitep
-------

1. download SQLite: http://www.java2s.com/Code/Jar/s/Downloadsqlitejar.htm

2. 当前最新3.8.0.1，推荐下载，sqlite.org

$ git push git@github.com:icersummer/sqlitep.git master

=======

Java &amp; SQLite

SQLite简介：
===========
SQLite 是一款轻量级的、基于文件的嵌入式数据库，2000年就已经诞生，经过7年多的发展，直到今天已经成为最流行的嵌入式数据库，包括google在内的公司 在其桌面软件中亦使用 SQLite 存储用户数据。由此可以看出，已经没有任何理由去怀疑SQLite的稳定性了。

SQLite的优势:

- 免配置，和access一样，只要把数据库文件通过ftp上传到服务器上就可以使用，不需要服务器的额外支持

- 备份方便，因为只是一个文件，只要复制一份该文件，就能备份整个数据库

- 虽然是轻量级数据库，但他支持最大 2tb 的单个库文件。

- 快，无与伦比的快。经过实际测试，在几百万记录的情况下，SQLite的插入和查询速度和 mysql 不分上下，快于 sql server，10倍于 access （但这并不意味着它可以替代 sql server） 。
