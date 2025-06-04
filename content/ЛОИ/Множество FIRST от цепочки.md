---
aliases:
  - FIRST
tags:
  - лои
created: 2025-06-01
modified: 2025-06-04
---
Пусть $G=(\Sigma, \Gamma, P, S)$ - [[Порождающая грамматика|грамматика]], $\gamma \in (\Gamma \cup \Sigma)^*$.
Множеством $FIRST(\gamma) \subseteq \Sigma \cup \{\epsilon\}$ называется множество такое что:
1. $\alpha \in FIRST(\gamma) \Leftrightarrow \gamma \Rightarrow^* \alpha \gamma', \gamma' \in (\Sigma \cup \Gamma)^*, \alpha \in \Sigma$
2. $\epsilon \in FIRST(\gamma) \Leftrightarrow \gamma \Rightarrow^* \epsilon$

>Терминалы выводят сами себя, поэтому считается, что $a \in FIRST(a), a \in \Sigma$

> Пустая строка выводит сами себя, поэтому считается, что $\epsilon \in FIRST(\epsilon)$

<mark style="background: #FF5582A6;">По определению множество FIRST может состоять только из терминалов и пустого слова</mark>