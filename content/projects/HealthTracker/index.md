---
title: Health Tracker - CoreData, Notifications & SwiftUI Lists
date: 2026-03-01
tags:
  - Swift
  - SwiftUI
  - CoreData
---

## Description

Built an iOS health tracking application that allows users to log and monitor personal health data such as daily metrics, habits, or wellness entries with all information persisted locally using CoreData. The app displays saved records in a dynamic SwiftUI `List`, and uses `UNUserNotificationCenter` to schedule local notifications that remind users to log their health data at set intervals.

**What I learned**

This project provided hands-on experience with CoreData’s full lifecycle defining an `.xcdatamodeld` schema, performing fetch requests, and handling create, read, update, and delete (CRUD) operations. Integrating local notifications added another layer of complexity, requiring an understanding of notification permissions, trigger types, and how to manage scheduled alerts without overwhelming the user.

**How this improves my skillset**

Persistent storage and notifications are two core skills in iOS development almost every real-world app relies on them. This project demonstrates the ability to build a complete data-driven feature end to end, from storing user input to surfacing it through the UI and re-engaging users with timely reminders. It also strengthened my MVVM architecture skills by keeping CoreData logic in a dedicated persistence layer, reflecting the kind of structured, maintainable code expected in a professional iOS engineering environment.

<!--more-->

## Gallery

<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
  <img src="/media/HealthCompanion/HomePage.png" alt="HealthCompanion 1" class="rounded-lg shadow-md">
  <img src="/media/HealthCompanion/AddPage.png" alt="HealthCompanion 2" class="rounded-lg shadow-md">
  <img src="/media/HealthCompanion/Intro.png" alt="HealthCompanion 3" class="rounded-lg shadow-md">
  <img src="/media/HealthCompanion/NotesPage.png" alt="HealthCompanion 4" class="rounded-lg shadow-md">
</div>
