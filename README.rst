关于本书
===============


这个 `源码仓库 <https://github.com/SystemsApproach/SDN_CN>`__ 包含 *软件定义网络：一种系统方法* 一书的中文翻译的源码，
根据Creative Commons（CC BY-NC-ND 4.0）许可条款提供。在相同的条件下，社区被邀请提供更正，改进，更新和提供新材料。

如果您使用了这个项目的相关内容，应包括以下信息: 

| *标题: 软件定义网络: 一种系统方法*  
| *作者: Larry Peterson, Carmelo Cascone, Brian O'Connor, and Thomas Vachuska* 
| *来源:* https://github.com/SystemsApproach/SDN 
| *版权:* \ `CC BY-NC-ND 4.0 <https://creativecommons.org/licenses/by-nc-nd/4.0>`__ 

读这本书
-------------

这本书是 `系统方法系列 <https://www.systemsapproach.org>`__ 的一部分，公开的在线英文版在 `https://sdn.systemsapproach.org
<https://sdn.systemsapproach.org>`__.

为了更好的跟踪和接收本书新版本的信息，你可以关注 `Facebook <https://www.facebook.com/Computer-Networks-A-Systems-Approach-110933578952503/>`__ 以及 `Twitter <https://twitter.com/SystemsAppr>`__.
你还可以关注 `Systems Approach Blog <https://www.systemsapproach.org>`__, 可以及时了解有关Internet演进的最新评论。

构建这本书
--------------

为了构建Web版的书，你首先需要下载源码:

.. code:: shell 

   $ mkdir ~/SDN 
   $ cd ~/SDN 
   $ git clone https://github.com/SystemsApproach/SDN.git 

构建过程存放在Makefile文件中，您需要先安装Python。
Makefile将会创建一个虚拟环境virtialenv (``doc_venv``), 这个虚拟环境用来安装文档生成工具集。

运行命令行 ``make html``， 生成HTML并存放在 ``_build/html``。

运行命令行 ``make lint``，检查书的格式。

运行命令行 ``make``，可以查看其他输出格式。

关于对本书的开源贡献
----------------------

我们特别希望您能使用这些材料，同时也渴望您也愿意为它作出贡献。
如果您是开放源码新手，您可以看看这本指南 `如何做开源贡献 <https://opensource.guide/how-to-contribute/>`__。
除此之外，您还将学习如何发布您希望解决的 *Issues* ，以及发出 *Pull Request* 以将您的改进合并回GitHub。

如果您想做些贡献，并且想寻找一些可以贡献的点，请查看 `wiki <https://github.com/SystemsApproach/SDN/wiki>`__ 上的当前待办事项列表。
