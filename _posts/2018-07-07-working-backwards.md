---
layout: post
title: 反向工作
description: 亚马逊 CTO 在 2006 年写的文章。他推崇反向工作法，四步：从起草新闻发布稿开始->撰写常见问题解答->定义用户体验->编写用户手册。
author: Tiger
---

我们在亚马逊使用的细粒度服务方法中，服务不仅代表软件结构，还代表组织结构。这些服务有一个强大的所有权模型，它与小团队规模相结合，意在使创新变得非常容易。从某种意义上说，你可以把这些服务看作是一个大公司内部的小型创业公司。每一个服务都需要强烈关注他们的客户是谁，不管这些客户是外部的还是内部的。为了确保服务满足客户的需求（这就够了），我们使用一个称为「反向工作」的流程，在该流程中，从客户开始向后工作，直到找到能够满足预定设想的最低技术要求。我们的目标是通过持续、明确的客户关注来推动简单化。

产品定义流程按如下方式反向进行：我们首先编写发布产品时需要的文档（新闻稿和常见问题解答），然后研究更接近实现的文档。

「反向工作」的产品定义流程就是充实这个概念，并对我们最终要实现和构建的内容进行清晰地思考。它通常有四个步骤：

1.  从起草新闻发布稿开始  
    搞定它。新闻稿用一种简单的方式描述了产品的功能和存在的原因——它的特点和好处是什么，它需要非常清晰并且重点突出。预先起草一份新闻稿澄清了世界将如何看待这个产品，而不仅仅是我们内部如何思考。
2.  撰写常见问题解答  
    这是我们在新闻稿的骨架上添加肉的地方。它包括我们在起草新闻稿时提出的问题，包括你分享新闻稿时其他人会询问的问题，包括产品好在何处的问题。你把自己放在产品使用者的位置上，考虑你将会遇到的所有问题。
3.  定义用户体验  
    详细描述用户对产品可能做的不同操作时的用户体验。对于有用户界面的产品，我们会构建用户使用的每一种屏幕模型。对于 Web 服务，我们编写用例（包括代码片段），它描述了你想象中人们使用该产品的方式。这里的目标是讲述用户如何使用产品解决问题的故事。
4.  编写用户手册  
    用户手册让用户真正了解产品是什么以及他们将如何使用它。用户手册通常有三个部分：概念，操作方法和参考资料，它们告诉用户使用产品时他们需要知道的一切。对于不止一种用户的产品，我们会写多个用户手册。

一旦我们完成了起草新闻发布稿、撰写常见问题解答、构建原型、编写用户手册这个流程之后，令人惊讶的是，你计划创建的产品是如此清晰。现在，我们拥有一套文档，可以用来向亚马逊内部的其他团队解释新产品，并且整个团队对我们正在创建的产品拥有共同愿景。

原文：[Working Backwards](https://www.allthingsdistributed.com/2006/11/working_backwards.html)
