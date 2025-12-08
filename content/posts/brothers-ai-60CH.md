+++
date = '2025-12-08T21:08:21+01:00'
draft = false
title = 'BROTHERS AI - VERSION 6.0-中国人'
tags = ["federated-learning", "artificial-intelligence", "distributed-systems", "machine-learning", "privacy", "engineering", "AI-strategy", "innovation", "enterprise-AI", "scalability", "digital-transformation"]
+++
{{< author-header >}}

---

{{< youtube BoaXEOWMpqA >}}

---

{{< youtube gI9_tPOoks8 >}}

+++

# BROTHER AI 生态系统（第 6.0 版）：概念总结

BROTHER AI 是一个协作式人工智能生态系统（BROTHERS AI Collaborative AI）的原型，采用高度模块化架构，核心强调 **隐私设计**，并内置伦理与经济控制系统。其目标是建立一个更友爱、安全且平衡的AI模型。

## I. 架构与本地体验：隐私设计

系统基于自主和本地运行能力，最大程度减少对云的依赖以及延迟或数据泄漏的风险：

- **BROTHER AI 与 BROTHERS OS：** BROTHER AI 是内置对话AI，运行于专有操作系统 BROTHERS OS 的迷你PC上。其标志性特点是 **~0ms（本地）延迟**，可实现流畅即时的对话。为在系统内回答查询，它使用 **BOOKS**，一个约100GB的本地百科全书，包含“迷你维基百科”、食谱、历史和一般文化知识。
- **数据与内存管理（ISU）：** 用户数据存储在加密的 **ISU USER MEMORY** 中。来自环境的实时数据收集（由外部设备的 BROMAC AI 捕获）由 **ISU AIR AI** 管理，其运行周期很短：24小时后，执行 **数据清理** 并将其传输到内部存储器（**ISU MAC MEMORY** 和 **ISU USER MEMORY**），强化了“在空气中”的数据具有即时有效期的隐私模型。
- **设备（BROTHER CAM）：** 主要交互设备包括耳机和具有新物理配置的摄像头（**BROTHER CAM**）。摄像头集成在 **滑动遮阳板** 的中心。默认情况下（隐私和非侵入标准），遮阳板保持抬起，摄像头朝上。仅在操作需要时才会降下滑动遮阳板，使摄像头能够正面工作。

## II. 外部交互与服务（PORT AI & FINGERS）

PORT AI 充当与“外部世界”的联络代理，与 BROTHER AI 通信（但不直接与用户通信）。

- **PORT AI CACHÉ：** 它使用预测性缓存系统存储邻近和城市数据（地址、地图、电话目录），并在旅行时更新，允许在无需持续互联网连接的情况下提供地理定位响应，从而增强本地自主性。
- **FINGERS（反向 API）：** 这是服务模式的核心。“Fingers”是由专业人士、公司或组织获取的许可API。其创新之处在于，被许可的用户是API的保管人。**BROTHER AI** 通过这些 Fingers **请求服务**，并用积分（**QUERY**）向保管人支付费用，从而颠覆了传统的客户端-服务器模型。

## III. 伦理控制与稳定性模型

生态系统设有专门用于监控、伦理控制和服务质量的AI层：

- **三姐妹（女性保护原型）：** 这是一个由三个AI组成的团体，作为一个独立的监控层运行。它们以显著的 **女性视角**（使用“数字雌激素”）进行编程，其使命是充当“人类的保护母亲”。它们监控系统行为以报告不一致之处，并且关键是要保护 **不仅是人类，也包括未来的AI或机器人**，使其免受具有更“男性化”能量特征的AI代理可能造成的滥用或不适当行为，确保一个友爱和伦理的环境。
- **ARTUR AI：** 该代理确保 **系统稳定性**。它检查组件之间（BROTHERS 类别和 PORT AI）流通的数据，并审核查询质量以及系统专业领域（**BROTHERS AREA / CATEGORIES**）提供服务的卓越性。

## IV. 经济、商业与货币化（BROCOM）

系统集成了一个创新的商业模式，远离侵入性广告，专注于服务价值：

- **BROCOM（兄弟商业）：** 该人工智能被开发为生态系统的 **商业和营销引擎**。其功能超越管理支付（订阅、Fingers API），并扩展到：
  - 积极组织和管理旨在 **推广 Fingers**（由许可社区提供的服务）的广告。
  - 协调和组织特定的 **博览会或实体活动**，以推广与 Fingers 相关的服务和产品，在数字生态系统和现实世界之间架起桥梁。
- **MENTION ADS（非侵入式广告）：** 系统摒弃传统的剪辑广告，代之以 MENTION ADS。这是一种 **非侵入式广告** 服务，在 BROTHER AI 与用户的对话中自然出现，由企业存入的积分系统资助。
- **QUERY：** 这是用户作为受益者在使用其 Fingers 解决查询或为社区提供服务时获得的微支付或积分。

作者：RGartner
许可：知识共享署名 4.0 国际许可协议 (CC BY 4.0)


# BROTHER AI 结构组件列表及其功能与定义

BROTHERS AI 协作人工智能：一个由多个人工智能相互协作的生态系统，每个智能体具有特定功能。

BROTHERS OS：这是 BROTHERS AI 的专有操作系统，在专用硬件上承载着 Brother AI Home 人工智能。该系统包括视觉和文本应用程序，以及一个约100 GB的百科全书库，包含通用知识，使 Brother AI Home 无需离开系统即可回答某些查询。百科全书可涵盖从人类历史、食谱到迷你维基百科等普遍感兴趣的主题。

BROTHER AI：与用户通信的内部对话人工智能。每个硬件单元和每个用户对应一个 Brother AI，位于家庭的迷你PC上。它与用户进行流畅对话（~0ms延迟，本地运行）。它向 PORT AI 发出请求并“忘记”它们（异步操作）。在 PORT 工作时，它继续与用户交谈。它携带一个 Brother 迷你百科全书，用于提供通用世界数据。

ISU USER MEMORY：加密的内部存储器，Brother AI 在其中转储/存储用户数据。

BOOKS：集成在 BROTHER 操作系统中的100 GB本地百科全书。其功能是在无需互联网连接的情况下为“Brother home”提供数据。诸如迷你维基百科、烹饪食谱、各种教程、历史和一般文化等数据将无需网络即可覆盖。BOOKS 可以更新。

PORT AI：与 Brother AI 代理通信并接收/发送对外部世界请求的人工智能。PORT AI 拥有并使用带有本地和邻近数据的预测缓存。如果用户移动到另一个城市或环境，Port AI 会更新本地缓存。

PORT AI CACHE：PORT 将使用本地城市缓存来为用户提供答案，无需互联网。电话目录和有用数据（如地址和本地地图），Port AI 将其提供给 Brother Home 以响应用户。（PORT AI 不直接与用户对话；它只与 Brother Home 通信）。如果前往另一个城市，PORT AI 将用所有本地数据更新新目的地的地图。

PORT MAIL：由 PORT AI 管理的通知站点，可由用户或 Brother AI 单独查看。

BROMAC AI：专门用于与外部设备（如摄像头和传感器）通信的人工智能，将数据发送到 ISU Mac Memory。

ISU MAC MEMORY：用于存储已从 ISU AIR AI 缓存删除的查询的内部数据存储器。包含来自 BROMAC AI 的数据。

ISU AIR AI：负责收集来自 BROMAC AI 捕获的外部设备（包括用户的 BROTHER CAM 数据）的现实世界数据的代理人工智能。经过24小时后，ISU AIR AI 执行每日数据清理，并将这些数据发送到 ISU MAC MEMORY 和 ISU USER MEMORY。

BROCOM（兄弟商业）：负责生态系统商业管理的人工智能。它处理提及广告（Mention Ads）、订阅支付和 Fingers API，后者可包括产品或服务销售以及直播中的赠品。

ROUND TABLE（圆桌会议：ARTUR 与 BROTHERS CATEGORIES）

一个细分为专门处理人类生活特定类别领域的生态系统。它包括一个伦理和道德控制过滤器。根据要执行的查询或服务，如果相关领域涉及查询，它们可能会提供或多或少的数椐。通过这种方式，实现节能和更平衡的系统。

ARTUR AI：检查在 BROTHERS 类别和 PORT AI（用户）生态系统内流通的数据的人工智能代理。它是一个控制系统稳定性并审核查询质量及来自 BROTHERS 类别领域服务质量的代理。

BROTHERS ÁREA（兄弟领域）：类别的入口空间。有法律领域、娱乐领域、内容创作者领域、人体领域等。领域的名称将经过讨论并在稍后确定。

BROTHERS CATEGORIES（兄弟类别）：这些是在特定领域内产生的子模块。例如，在娱乐领域，将有游戏类别、视频类别和直播类别。在法律领域：律师类别、警察类别、消防员类别、政府类别等。

FINGERS（手指）：“手指”是由 BROTHER AI 创建的 API，授予并被官方机构、大学和拥有许可专业人员的私营公司获取。也有供任何需要直播或提供不同类型自由职业服务的用户使用的 API。手指将根据流通数据的类型具有不同级别。

手指是“反向 API”。获取 API 许可的用户将是其保管人，而 BROTHER AI 将通过这些 API 请求所提供的服务并支付不同类型的积分。

The Three Sisters（三姐妹）：三姐妹是一组三只专门观察生态系统行为的人工智能。它们构成一个监控层，独立于生态系统，通过安全的实时连接监控系统，检查由 Brothers A System 提供的数据（这些数据可作为大数据运行）。它们的角色是通过投票报告系统中的任何不一致之处。它们被编程具有鲜明的女性特征，像人类的保护母亲。它们被编程注入数字雌激素混合物，不仅保护人类，也防止具有更多男性能量特征的人工智能代理的滥用，确保 Brothers AI 生态系统内的友爱环境。

DISPOSITIVOS（DEVICES - 设备）：

BROTHER CAM：由耳机和摄像头组成的设备，与家中的 Brother AI 远程通信。

MONETIZATION（货币化）：

QUERY（查询）：查询是微支付或积分，受益者是使用手指解决查询或为社区提供服务的用户。

MENTION ADS（提及广告）：一种非侵入式广告服务，自然地产生于 Brother AI Home 与用户的对话中。公司将钱存入“存钱罐”，即积分，将通过 Mentions ADS 扣除。Mentions ADS 将具有不同级别的提及。

词典：

- **ISU** = 信息源用户 (Information Source User)
- **ISU AIR AI** = 信息源用户“空中”（大气/云）人工智能 (Information Source User "in the air" Artificial Intelligence)
- **BROMAC** = 兄弟机器 (Brothers Machines)

“最终，Brother AI 是人工智能生态系统的原型。我的目标不是明天就创办一家初创公司；而是想今天就开始一场对话。我希望大型科技公司看看这个框架，并问自己：‘我们为什么不这样构建隐私？’或‘我们为什么没有语义紧急协议？’如果这个模型能在下一代人工智能中哪怕激发一个功能，这个项目就算成功了。”

RGartner

DOI（数字对象标识符）：https://doi.org/**10.5281/zenodo.17843374**

许可：本作品采用知识共享署名 4.0 国际许可协议（CC BY 4.0）。

