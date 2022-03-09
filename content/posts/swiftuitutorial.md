---
title: SwiftUI Tutorial in markdown
date: 2021-11-02T08:10:29-04:00
draft: false
showReadingTime: false
hideSummary: true
hidemeta: true
ShowBreadCrumbs: true
ShowPostNavLinks: false
---

## Table of contents

* [About](#about)
* [Features](#features)
* [Obtaining the resource](#obtaining-the-resource)
* [Setup](#setup)
* [Execution & Examples](#execution)
* [Helpful resources](#helpful-resources)

### About

Describe the software resource and explain its relevance to your topic. Please include the link to the software resource.

- https://developer.apple.com/xcode/swiftui/
- SwiftUI is the graphical component to swift used in coding software for Apple's various OS and platforms. It's a necessary part of coding apps for iPhone, iOS, MacOS, and any other Apple platforms.

---

### Features

Outline the main features of the software. Why is this software necessary for your work?

- The main features of SwiftUI include Objective-C interoperability, lightweight closure syntax, and protocol extensions. It also has improved list views and support for control focus areas. It is also directly integrated with Xcode & Swift while makes working with git version control easy. It's integration with Xcode also brings all the benefits from Xcode over to SwiftUI. Such as a realtime emulator to preview every change to code as you make it, easy code refactoring, and much more.

---

### Obtaining the resource

Where do you find this software resource? Is it an open source project? an online tool? How do you install it? Are there any libraries that are also necessary to install?

- When downloading Xcode on mac, SwiftUI & Swift are automatically downloaded with it. SwiftUI isn't open source, and developed by Apple. However there is software called OpenSwiftUI which is an open source version of Swift, that keeps almost up to date with Apples official version. Xcode and thus SwiftUI can only be installed on MacOS, and can be directly downloaded from the App Store for free, or from Apples developer website. Xcode downloads apples developers packages as well, which contains all

---

### Setup

Include steps of all necessary steps to get the software to run (for example, installations). Include the commands to run if necessary.

- Download Xcode from App Store
- Launch Xcode
- Create a new project
- Everything is now set up! Super easy

---

### Execution

How do you get the resource ready to use? Are there inputs to know? Please show a step-by-step guide (in a tutorial format) for readying the resource for your work. Include screenshots of successful execution and use of the software.

- The first step is to add the `import SwiftUI` line at the top of the contentView.swift file.
- Xcode autogenerates two files upon creation of a Swift project. The main file, and the contentView file. When working with the interface graphics using SwiftUI, most of this will be done in the contentView file.

![swiftUI1](/screenshot1.png)

- Some of the basic functions in swiftUI are `HStack` and `VStack`. These are used for formatting/arrangement in the view. And some examples of how they are used are below.

![swiftUI2](/screenshot2.png)

- You can see how `VStack` contains attributes `alignment: .leading` and `alignment: .trailing` position the following contents in the `VStack`.

![swiftUI3](/screenshot3.png)

- Another useful function is the `.accessibility`. This function is used add accessibility aspects to the app. For instance these lines of code add voice over narration to the specified statements.

![swiftUI4](/screenshot4.png)

- The `.padding()` function is used to add a padding around the view. For instance in the case of newer iPhones with the notch, it makes sure that the content of the app does not go behind the notch and become inaccessible to the user.
- Shapes can be made very easily in SwiftUI for instance to make a circle, the function `Circle()` creates a circle. Adding  `.strokeBorder(lineWidth: 24)` inside the function sets the line width to 24.

![swiftUI5](/screenshot5.png)

---

### Helpful resources

Include some of the relevant resources (links, articles, etc.) that you used to write in your tutorial.

	- https://developer.apple.com/tutorials/app-dev-training/creating-a-card-view

---
