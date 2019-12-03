## 感谢您

首先，感谢您对Metabase的兴趣和贡献!

在本指南中，我们将讨论Metabase是如何构建的。这将使您对我们的流程有一个很好的了解，并了解您可能希望在哪些方面适合我们。

## 我们要建立的东西

Metabase就是让非技术用户访问他们组织的数据。我们试图最大限度地提高那些了解自己业务的人所能轻松使用的能力，他们在数量上有一定的偏好，但可能只擅长Excel。

务必记住Metabase项目的这些目标。很多次
提案将被标记为“超出范围”，否则将被取消。这并不意味着该建议没有用处，或者我们不希望看到它作为一个附属项目或一个实验性分支完成。然而，这确实意味着我们不会在短期内将核心团队或贡献者指向它。稍微超出范围的问题将保持开放，以备社区支持(最好是贡献)。

为了对最终目标有个概念，一定要读一下 [Zen of Metabase](../zen.md)

## 我们的产品工艺:

核心团队运行定义良好的产品流程。它正在积极调整，但下面是一个相当忠实的描述，在写的时候。在开始公关之前，你应该对我们的工作有一个清晰的概念。

### A) 识别来自社区的产品需求

我们积极地从社区、用户群和我们自己的Metabase内部使用中寻找新的特性。我们专注于潜在的“问题”或“需求”，而不是对特定功能的需求。虽然有时建议的功能是按要求构建的，但是我们经常发现它们涉及到对现有功能的更改，并且可能涉及到对底层问题的完全不同的解决方案。 这些问题通常会在一系列问题中收集并标记 [Proposal](https://github.com/metabase/metabase/labels/Proposal)

### B) 将这些需求综合成一个具体的特征

我们通常会将一组问题或建议收集到一个新的topline功能概念中。通常，我们将创建一个工作文档，收集关于该特性要做什么(更重要的是不要做什么)的所有“开放问题”。我们会和我们的用户聊天，可能会进行深度访谈，并试图严格定义功能。如果某个特性看起来需要时间来讨论和确定范围，那么它将被标记 [Proposal/Being Discussed](https://github.com/metabase/metabase/labels/Proposal%2FBeing%20Discussed) 表示仍在积极讨论中。

### C) Design the feature

一旦一个功能被定义，通常它将由产品设计师来完成。在这里，他们将生产低fi模拟，从我们的用户和社区获得反馈，并进行迭代。

一旦主要的用户体验流程已经被拨通，将会有一个高保真的视觉设计。

准备好设计的特性被标记 [Design Needed](https://github.com/metabase/metabase/labels/Design%2FNeeded). 一旦一个功能有一个合理完整的视觉设计，它应该被标记 [Help Wanted](https://github.com/metabase/metabase/labels/Help%20Wanted).

### D) 构建功能

一旦特性被标记 [Help Wanted](https://github.com/metabase/metabase/labels/Help%20Wanted), 它被认为已经准备好了。一个核心团队成员(或者你，一个非常有帮助的人)可以开始工作了。

如果您正在构建用户将在Metabase中看到的东西，请参考 [Style Guide](https://localhost:3000/_internal) 在运行开发环境时，了解如何以及何时使用各种Metabase UI元素。

一旦一个或多个用户开始使用某个特性，就应该对其进行标记 [In Progress](https://github.com/metabase/metabase/labels/In%20Progress). 一旦有了一个分支+一些代码，就会打开一个拉请求，链接到该特性+任何被拉到一起通知该特性的问题。

### E) 验证和合并

所有涉及到不重要变化的PRs都应该被审查。 看我们的 [Code Review Process](code-reviews.md).

如果一切顺利，该特性将得到编码、验证，然后拉请求将被合并!击掌。

如果拉请求中缺少测试、代码风格问题或特定的体系结构问题，那么应该在合并之前修复它们。我们在代码和产品质量上都有很高的要求，保持这一点很重要，所以请耐心等待我们。

## 帮助方法:

你可以从熟悉Metabase这个产品开始，并了解你的方法。如果你在工作中使用它，那就太好了!如果没有，下载mac应用程序或jar，并尝试使用它。阅读文档，大致了解产品的流程。

如果你想帮忙，有很多方法。为了增加与我们的协调和互动:

### 帮助确定需求和Metabase可以解决的问题

如果您想提供帮助，请尝试Metabase。在你的公司使用它，并报告你喜欢的东西，不喜欢的和任何你遇到的问题。帮助我们尽可能多地了解您的数据模型、所需的度量标准和常见的使用模式。这些信息直接影响产品的质量。你越多地告诉我们你所面临的问题，我们就越能更好地解决它们。

### 帮助我们分类和支持其他用户

花点时间在气馁。metabase.com和新问题上，试着重现报告的错误。对于那些在数据库中遇到问题的人，你有重要的知识，帮助他们。谁知道呢，也许他们将来会在某些事情上帮助你。

如果你能理解我们的要求，那就很有帮助了 [prioritization framework](https://github.com/metabase/metabase/wiki/Bug-Prioritization) 当回应的时候.

### 告诉你的朋友

让你的朋友知道Metabase。在您的区域内启动一个用户组。 [Tweet about us](http://twitter.com/metabase). 在博客上分享你如何使用Metabase，并分享你学到的东西。

### 修正错误

根据我们的定义，“bug”是指程序没有按照设计或规范完成预期的工作。这些问题的范围通常是那些有明确定义的正确行为的问题。获取其中一个，修复它，然后提交一个PR(带有测试!)通常是安全的。除非PR涉及大量的代码，否则这些将被合并而不会有太多的戏剧性。如果我们要求您进行小的修改或添加更多的测试，请不要生气。我们对代码覆盖和编码风格有点强迫症。

### 文档支持

有很多文档。我们经常很难使它们保持最新。如果你正在阅读它们，你注意到不一致，错误或过时的信息，请帮助保持他们的最新!

### 工作特性

有一些功能，如数据库驱动程序，没有任何用户面对像素。这是一个很好的开始贡献的地方，因为它们不需要太多的沟通、关于权衡和过程的讨论。

在已经完成设计的情况下，我们总是可以使用一些帮助。在拉请求或问题上插嘴并提供帮助。

一般来说，任何问题在 [Help Wanted](https://github.com/metabase/metabase/labels/Help%20Wanted) 里面都是一个公平的游戏。

### #你只需要提交一份简历

如果你想出一些很酷,想与我们分享,只是提交公关。如果它没有经历上面的过程中,我们可能不会合并,但如果是引人注目的,我们乐意帮助你通过代码评审,设计评审,一般强迫症找碴儿,让它融入我们的代码库。