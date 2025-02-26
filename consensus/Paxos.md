# 6.3 Paxos 算法

Paxos 算法由 Leslie Lamport[^1] 于 1990 年提出，是一种基于消息传递、具备高度容错特性的共识算法。该算法是当今分布式系统最重要的理论基础，几乎就是“共识系统”的代名词。

Paxos 算法因复杂广为人知，围绕它发生过许多有趣的故事，这些已成为人们津津乐道的一段轶事。直接切入 Paxos 算法未免望文生畏，我们不妨从这段轶事开始学习 Paxos 算法之旅。

[^1]: Lamport 在分布式系统理论方面有非常多的成就，比如 Lamport 时钟、拜占庭将军问题、Paxos 算法等等。除了计算机领域之外，其他领域的无数科研工作者也要成天和 Lamport 开发的一套软件打交道，目前科研行业应用最广泛的论文排版系统 —— LaTeX (名字中的 La 就是指 Lamport)