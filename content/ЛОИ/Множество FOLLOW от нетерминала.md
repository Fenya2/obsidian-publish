---
aliases:
  - FOLLOW
tags:
  - лои
created: 2025-06-01
modified: 2025-06-04
---
Пусть $G=(\Sigma, \Gamma, P, S)$ - [[Контекстно-свободная грамматика|КС-грамматика]], $A \in \Gamma$
Множеством $FOLLOW(A) \subseteq (\Sigma \cup \{\dashv\})$ называется множество такое что:
1) $a \in FOLLOW(A) \Leftrightarrow S \Rightarrow^* \alpha Aa \beta, \alpha,\beta \in (\Sigma \cup \Gamma)^*, a \in \Sigma$
2) $\dashv \in FOLLOW(A) \Leftrightarrow S \Rightarrow^* \alpha A, \alpha \in (\Sigma \cup \Gamma)^*$
3) Полагаем $\dashv \in FOLLOW(S)$, поскольку можно считать, что $S \Rightarrow^* S$