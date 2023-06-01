---
layout: post
title: "Context based classification using a bandit modulated feed forward classifier"
date: 2022-09-22
excerpt: "Lab rotation 2 details"
tags: [lab rotation]

project: true
---

This lab rotation was done at the Sprekeler Lab, TU Berlin under the supervision of Prof. Dr. Henning Sprekeler and Dr. Friedrich Schuessler and Joram Keijser.


Humans are exposed to a lot of sensory information. This sensory information is represented in a brain in different ways based on different contexts. This lab rotation project aims to develop a feed forward neural network which gets the contextual input by a multi-arm bandit to identify the context and then classify the input based on the context. This is done by using a simple feed forward network for binary classification with dynamic targets changing based on context. A k- armed bandit feeds the context from a selection of k-contexts to the network based on the target.

<!-- Please see the [project report](https://drive.google.com/file/d/1O0T1-amTFNOsgI384GHfGw3KUKzad9xs/view?usp=sharing) for more information. -->