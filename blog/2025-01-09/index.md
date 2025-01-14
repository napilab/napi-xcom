---
title: We are up and running in 2025 season !
authors: dmn
---
## Manifest

We want to present the manifest of Napi-X in first post.

## Our Goal

To create a Linux system for single-board computers, routers, and embedded devices that is optimized, user-friendly, and easy to understand, with a lightweight reactive management interface.

## The Backstory of the Napi-X Project

In 2023 and 2024, we worked extensively on our own Linux distribution (NapiOS) for our embedded devices. However, while working with clients and partners, it became clear that a Linux firmware built from source code isn’t very convenient to use and requires a high level of expertise. Moreover, managing a large number of similar embedded devices individually proved inconvenient, as clients wanted a unified interface to control multiple devices.

We created a web interface for basic functions, but we weren’t entirely satisfied with it due to the need to invoke Linux commands directly from the web, which is neither safe nor reactive.

Therefore, in 2025, we decided to transform the project into Napi-X. This combines NapiOS, with all the advantages of Linux for embedded systems, with a modern API-based management approach and a WebApp built on the Vue framework for intuitive visual control of the system and its applications.

Our closest reference point is OpenWRT, but we acknowledge its limitations as a full-fledged Linux system for routers. It lacks support for heavy software, and its web interface, Luci, is outdated and not optimized for mobile devices.

## Why Napi-X?

Napi-X offers several key advantages:

- **NapiOS at its core** remains an open, lightweight Linux system with firmware-like properties for embedded and network devices: dual partitions and a dedicated user data partition.
- A **modern reactive web interface** allows users to manage Linux and its applications both from a desktop workstation and a smartphone. For inexperienced users, we remove the fear of Linux, while for advanced users, we retain the standard SSH access and full openness.
- **Napi-X.Api** enables system management not only via the WebApp but also through third-party integrations.
- The **server-side Napi-X.Api** provides centralized management of multiple authorized devices from a single web application.

## Our Dreams

We hope you will also appreciate our approach, and that Napi-X will win the hearts of developers and open-source community users.
