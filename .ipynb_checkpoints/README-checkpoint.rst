About The Book
关于本书
===============

This `repository <https://github.com/SystemsApproach/SDN>`__ contains
source for *Software-Defined Networks: A Systems Approach*, available under
terms of the `Creative Commons (CC BY-NC-ND 4.0)
<https://creativecommons.org/licenses/by-nc-nd/4.0>`__ license. The
community is invited to contribute corrections, improvements, updates,
and new material under the same terms.

这个 `源码仓库 <https://github.com/SystemsApproach/SDN_CN>`__包含*软件定义网络：一种系统方法*一书的源码，
根据Creative Commons（CC BY-NC-ND 4.0）许可条款提供。在相同的条件下，社区被邀请提供更正，改进，更新和提供新材料。

If you make use of this work, the attribution should include the following information:

如果您使用了这个项目的相关内容，应包括以下信息:

| *Title: Software-Defined Networks: A Systems Approach* 
| *Authors: Larry Peterson, Carmelo Cascone, Brian O'Connor, and Thomas Vachuska* 
| *Source:* https://github.com/SystemsApproach/SDN 
| *License:* \ `CC BY-NC-ND 4.0 <https://creativecommons.org/licenses/by-nc-nd/4.0>`__

| *标题: 软件定义网络: 一种系统方法* 
| *作者: Larry Peterson, Carmelo Cascone, Brian O'Connor, and Thomas Vachuska* 
| *来源:* https://github.com/SystemsApproach/SDN 
| *版权:* \ `CC BY-NC-ND 4.0 <https://creativecommons.org/licenses/by-nc-nd/4.0>`__

Read the Book
读这本书
-------------

This book is part of the `Systems Approach Series
<https://www.systemsapproach.org>`__, with an online version published
at `https://sdn.systemsapproach.org
<https://sdn.systemsapproach.org>`__.

这本书是`系统方法系列<https://www.systemsapproach.org>`__的一部分，公开的在线英文版在 `https://sdn.systemsapproach.org
<https://sdn.systemsapproach.org>`__.

To track progress and receive notices about new versions, you can follow
the project on
`Facebook <https://www.facebook.com/Computer-Networks-A-Systems-Approach-110933578952503/>`__
and `Twitter <https://twitter.com/SystemsAppr>`__. To read a running
commentary on how the Internet is evolving, follow the `Systems Approach
Blog <https://www.systemsapproach.org>`__.

为了更好的跟踪和接收本书新版本的信息，你可以关注`Facebook <https://www.facebook.com/Computer-Networks-A-Systems-Approach-110933578952503/>`__以及 `Twitter <https://twitter.com/SystemsAppr>`__.
你还可以关注`Systems Approach Blog <https://www.systemsapproach.org>`__, 可以及时了解有关Internet演进的最新评论。

Build the Book
构建这本书
--------------

To build a web-viewable version, you first need to download the source:

为了构建Web版的书，你首先需要下载源码:

.. code:: shell 

   $ mkdir ~/SDN 
   $ cd ~/SDN 
   $ git clone https://github.com/SystemsApproach/SDN.git 

The build process is stored in the Makefile and requires Python be 
installed. The Makefile will create a virtualenv (``doc_venv``) which 
installs the documentation generation toolset. 

构建过程存放在Makefile文件中，您需要先安装Python。
Makefile将会创建一个虚拟环境virtialenv (``doc_venv``), 这个虚拟环境用来安装文档生成工具集。

To generate HTML in ``_build/html``,  run ``make html``.
运行命令行 ``make html``， 生成HTML并存放在``_build/html``。

To check the formatting of the book, run ``make lint``.

运行命令行``make lint``，检查书的格式。

To see the other available output formats, run ``make``.

运行命令行``make``，可以查看其他输出格式。

Contribute to the Book
关于对本书的开源贡献
----------------------

We hope that if you use this material, you are also willing to
contribute back to it. If you are new to open source, you might check
out this `How to Contribute to Open
Source <https://opensource.guide/how-to-contribute/>`__ guide. Among
other things, you’ll learn about posting *Issues* that you’d like to see
addressed, and issuing *Pull Requests* to merge your improvements back
into GitHub.

我们特别希望您能使用这些材料，同时也渴望您也愿意为它作出贡献。
如果您是开放源码新手，您可以看看这本指南<https://opensource.guide/how-to-contribute/>`__。
除此之外，您还将学习如何发布您希望解决的*Issues*，以及发出*Pull Request*以将您的改进合并回GitHub。

If you’d like to contribute and are looking for something that needs
attention, see the `wiki <https://github.com/SystemsApproach/SDN/wiki>`__
for the current TODO list.

如果您想做些贡献，并且想寻找一些可以贡献的点，请查看 `wiki <https://github.com/SystemsApproach/SDN/wiki>`__上的当前待办事项列表。
