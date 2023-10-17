---
layout: post
title:  "SwiftDemos iOS App - Demos for Swift, Testing, CI/CD etc by Amos"
date:   2023-02-01 12:00:00 -0400
categories: xcode ios swift swiftui development cicd uitesting unittesting
---

A demo project including an iOS app which demonstrates Swift, SwiftUI, Unit and UI Testing, CI/CD, REST API, MVVM, etc by [Amos](https://github.com/amostodman). The iOS app is built natively with Xcode and automated using GitHub actions.

The app has Unit Tests, UI Tests and runs through a CI/CD Pipeline for deployments.

The pipeline adds automation to make deployments more efficient.
- Uses [GitHub Actions](https://docs.github.com/en/actions) via the repo and [Github hosted virtual machines](https://docs.github.com/en/actions/using-github-hosted-runners/about-github-hosted-runners) to run the pipeline automatically on new commits.
- Uses [Match](https://docs.fastlane.tools/actions/match/) to allow hosted VMs to codesign the builds.
- The app is archived, an ipa is created and stored in artifacts of the commit (on GitHub).
- Unit Tests and UI Tests are run and results are stored in artifacts of the commit (on GitHub).
- Screenshots are taken to prepare for upload to App Store/TestFlight and also stored in artifacts of the commit (on GitHub).

Check out the [actions tab](https://github.com/DontSnooze/SwiftDemos/actions) to see the latest pipeline runs for logs and artifacts. 

Related Documentation:

[SwiftUI](https://developer.apple.com/xcode/swiftui/)
- Build apps across all Apple platforms with the power of Swift and less code.

[GitHub Actions](https://docs.github.com/en/actions)
- Automate, customize, and execute development workflows from GitHub repositories.

[FastLane](https://docs.fastlane.tools)
- Automate beta deployments and releases for your iOS and Android apps. It handles tedious tasks like generating screenshots, dealing with code signing, and releasing your application.


[See it on github](https://github.com/DontSnooze/SwiftDemos)

by [@amos](https://amostodman.github.io/)
