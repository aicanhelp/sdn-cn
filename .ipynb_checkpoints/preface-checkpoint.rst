Preface 
前言
=======

The Internet is the midst of a transformation, one that moves away
from bundled proprietary devices, and instead embraces disaggregating
network hardware (which becomes commodity) from the software that
controls it (which scales in the cloud). The transformation is
generally known as *Software-Defined Networking (SDN)*, but because it
is disrupting the marketplace, it is challenging to untangle business
positioning from technical fundamentals, from short-term engineering
decisions. This book provides such an untangling, where the most
important thing we hope readers take away is an understanding of an
SDN-based network as a scalable distributed system running on
commodity hardware.

互联网正处于一场变革之中，使它从专有设备的捆绑中解放，对网络硬件设备和网络控制软件分离开来，
使网络硬件作为普通商品存在，而控制软件可以部署在云上进行扩展。
这种转变通常被称为软件定义的网络（SDN），但由于它正在冲击着市场，所以也在给业务定位提出了挑战：
如何从技术基础以及短期的工程决策中分离出业务定位。
本书将要给出这个解，更重要的是，我们希望读者能从本书理解一个运行在普通硬件上的基于SDN的可扩展的分布式系统。

Anyone who has taken an introductory networking class recognizes the
protocol stack as the canonical framework for describing the
network. Whether that stack has seven layers or just three, it shapes
and constrains the way we think about computer networks. Textbooks are
organized accordingly. SDN suggests a completely different world-view,
one that comes with a new software stack. This book is organized
around that new stack, with the goal of presenting a top-to-bottom
tour of SDN without leaving any significant gaps that the reader might
suspect can only be filled with magic or proprietary code. *We invite
you do the hands-on programming exercises included at the end of the
book to prove to yourself that the software stack is both real and
complete.*

任何学习过网络入门课程的人都会将协议栈视为描述网络的规范框架。
不管这个栈是七层还是三层，它塑造和约束着我们对计算机网络的思考方式。教科书也是按照这个方式去写的。
而SDN提出了一个完全不同的世界观，一个新的软件栈。这本书是围绕着这个新的栈进行组织，目的是展示一个自上而下的SDN之旅，
而不留下任何可能让读者怀疑只能用魔法或专有代码填补的空白。
*我们邀请您做一下本书末尾包含的实操编程练习，它能证明这个软件栈是真实的和完整的。*

An important aspect of meeting this goal is to use open source. We do
this in large part by taking advantage of two community-based
organizations that are leading the way. One is the *Open Compute
Project (OCP)*, which is actively specifying and certifying commodity
hardware (e.g., bare-metal switches) upon which the SDN software stack
runs. The second is the *Open Networking Foundation (ONF)*, which is
actively implementing a suite of software components that can be
integrated into an end-to-end solution. There are many other players
in this space—from incumbent vendors to network operators, startups,
standards bodies, and other open source projects—each offering varied
interpretations of what SDN *is* and *is not*. We discuss these other
perspectives and explain how they fit into the larger scheme of
things, but we do not let them deter us from describing the full
breadth of SDN. Only time will tell where the SDN journey takes us,
but we believe it is important to understand the scope of the
opportunity.

实现这个目标的一个重要方法是开源。我们主要是通过两个社区组织来实现开源的。
一个是开放计算项目（OCP），它正在积极地指定和认证SDN软件栈运行的商业硬件（例如裸机交换机）。
第二个是开放网络基金会（opennetworkingfoundation，ONF），它正在积极实施一套可以集成到端到端解决方案中的软件组件。
在这一领域还有许多其他参与者，从现有的供应商到网络运营商、初创企业、标准机构和其他开源项目，每个人都对SDN是什么和不是什么提供了不同的解释。
我们将讨论这些其他观点，并解释它们如何适应更大的范围，但它们不会影响我们描述SDN的全部广度。
时间会告诉我们SDN的旅程将带我们去哪里，但我们相信，了解范围是很重要的。

This book assumes a general understanding of the Internet, although a
deeper appreciation for the role switches and routers play forwarding
ethernet frames and IP packets is helpful. Links to related background
information are included to help bridge any gaps. This book is also a
work-in-progress. We are eager to hear your feedback and suggestions.

这本书希望你对因特网已经有了总体的了解，
当然对交换机和路由器在转发以太网帧和IP包的作用有更深入的了解对你读这本书会更有帮助的。
相关背景信息的链接可以帮助弥合知识和理解上的问题。
这本书还在初步的完善过程中。我们渴望听到您的反馈和建议。

Acknowledgements
致谢
----------------

The software described in this book is due to the hard work of the ONF
engineering team and the open source community that works with
them. We acknowledge their contributions. We also thank Charles Chan,
Jennifer Rexford, and Nick McKeown for their feedback on early drafts
of the manuscript.

本书中描述的软件是由于ONF工程团队和与他们一起工作的开源社区的辛勤劳动。在此感谢他们的贡献。
我们也感谢陈冠希、詹妮弗·雷克斯福德和尼克·麦基翁对初稿的反馈。

.. To include in epub and printed versions
.. The cover photo of the Ueno Station (Tokyo) is
.. by `Athena Lam <https://unsplash.com/@thecupandtheroad>`__
.. on `Unsplash <https://unsplash.com>`__.

| Larry Peterson, Carmelo Cascone, Brian O'Connor, and Thomas Vachuska
| Open Networking Foundation 
| 开放网络基金会，ONF
| October 2020 
| 2020年10月

