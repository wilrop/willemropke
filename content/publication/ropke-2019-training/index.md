---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Training a Speech-to-Text Model for Dutch on the Corpus Gesproken Nederlands
subtitle: ''
summary: ''
authors:
- Willem Röpke
- Roxana Radulescu
- Kyriakos Efthymiadis
- Ann Nowé
tags: []
categories: []
date: '2019-01-01'
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
publishDate: '2022-08-02T10:24:17.351147Z'
publication_types:
- '1'
abstract: Speech-to-text, also known as Speech Recognition, is a technology that is
  able to recognize and transcribe spoken language into text. In subsequent steps,
  this transcription can be used to complete a multitude of tasks, such as providing
  automatic subtitles or parsing voice commands. In recent years, Speech-to-Text models
  have dramatically improved thanks partially to advances in Deep Learning methods.
  Starting from the open-source project DeepSpeech, we train speech-to-text models
  for Dutch, using the Corpus Gesproken Nederlands (CGN). First, we contribute a pre-processing
  pipeline for this dataset, to make it suitable for the task at hand, obtaining a
  ready-to-use speech-to-text dataset for Dutch. Second, we investigate the performance
  of Dutch and Flemish models trained from scratch, establishing a baseline for the
  CGN dataset for this task. Finally, we investigate the issue of transferring speech-to-text
  models between related languages. In this case, we analyse how a pre-trained English
  model can be transferred and fine-tuned for Dutch.
publication: '*Proceedings of the 31st Benelux Conference on Artificial Intelligence
  (BNAIC 2019)*'
---
