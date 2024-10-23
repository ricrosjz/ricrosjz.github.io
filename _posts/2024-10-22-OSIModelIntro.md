---
title: Tech Fundamentals - OSI Model Intro
date: 2024-10-21 20:45:00
categories: [Fundamentals, OSI 7-Layer Networking Model]
tags: [tech, fundamentals, networking]
---
## OSI 7-Layer Model

![OSI Layer Model](assets/img/OSI7-LayerModel.png)

This is a conceptual framework to understand how networking works. The 7 layers are stacked on top of each other, and are (from bottom to top):

1. Physical
2. Data Link
3. Network
4. Transport
5. Session
6. Presentation
7. Application

These are part of the **Networking Stack**, which can be understood as the software that does each of these functions.

The Physical, Data Link and Network layers are part of the **Media Layers**. -> These refer to how data is moved between point A and point B (on a local or remote network).

The Transport, Session, Presentation, and Application layers are part of the **Host Layers**. -> These refer to how the data is "chopped up", reassembled for transport and formatted so it is understandable by both sides of the network.
