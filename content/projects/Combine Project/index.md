---
title: Pet Breed Explorer, Swift Combine & REST API
date: 2025-12-26
tags:
  - Swift
  - SwiftUI
  - Combine
---

## Description

Built an iOS application that fetches pet breed data from a REST API and displays breed names and descriptions in a native SwiftUI interface. The app leverages Swift's Combine framework to handle asynchronous network requests declaratively, using publishers and subscribers to stream data directly into the UI without callback nesting.

**What I learned**
Working with Combine deepened my understanding of reactive programming, specifically how to chain operators like `map`, `decode`, and `receive(on:)` to transform raw API responses into clean, UI-ready models. Managing subscribers with `AnyCancellable` and handling error states gracefully also reinforced best practices around memory management and user experience.

**How this improves my skillset**
This project bridges the gap between basic `URLSession` networking and production-grade async patterns. Understanding Combine makes adopting Swift's newer `async/await` concurrency model more intuitive, and the experience with publisher pipelines translates directly to working on larger iOS codebases where reactive data flow is common. It also strengthened my ability to structure an app using the MVVM pattern, keeping business logic cleanly separated from the view layer.

<!--more-->

## Gallery

<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
  <img src="/Omar_Said_Portfolio/media/Combine/DogsList.png" alt="Combine 1" class="rounded-lg shadow-md">
  <img src="/Omar_Said_Portfolio/media/Combine/CombineWork.png" alt="Combine 2" class="rounded-lg shadow-md">
  <img src="/Omar_Said_Portfolio/media/Combine/API.png" alt="Combine 3" class="rounded-lg shadow-md">
</div>
