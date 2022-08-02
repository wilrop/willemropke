---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Preference Communication in Multi-Objective Normal-Form Games
subtitle: ''
summary: ''
authors:
- Willem Röpke
- Diederik M. Roijers
- Ann Nowé
- Roxana Rădulescu
tags: []
categories: []
date: '2022-07-01'
lastmod: 2022-08-02T12:24:17+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-08-02T10:24:17.461861Z'
publication_types:
- '2'
abstract: We consider preference communication in two-player multi-objective normal-form
  games. In such games, the payoffs resulting from joint actions are vector-valued.
  Taking a utility-based approach, we assume there exists a utility function for each
  player which maps vectors to scalar utilities and consider agents that aim to maximise
  the utility of expected payoff vectors. As agents typically do not know their opponent's
  utility function or strategy, they must learn policies to interact with each other.
  Inspired by Stackelberg games, we introduce four novel preference communication
  protocols to aid agents in arriving at adequate solutions. Each protocol describes
  a specific approach for one agent to communicate preferences over their actions
  and how another agent responds. Additionally, to study when communication emerges,
  we introduce a communication protocol where agents must learn when to communicate.
  These protocols are subsequently evaluated on a set of five benchmark games against
  baseline agents that do not communicate. We find that preference communication can
  alter the learning process and lead to the emergence of cyclic policies which had
  not been previously observed in this setting. We further observe that the resulting
  policies can heavily depend on the characteristics of the game that is played. Lastly,
  we find that communication naturally emerges in both cooperative and self-interested
  settings.
publication: '*Neural Computing and Applications*'
doi: 10.1007/s00521-022-07533-6
---
