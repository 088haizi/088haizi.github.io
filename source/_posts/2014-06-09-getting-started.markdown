---
layout: post
title: "Getting_started"
date: 2014-06-09 14:28:42 +0800
comments: true
categories: 
---
## Getting Started
<br>
To create the Mac app in this tutorial, you need Xcode 4.4 or later. Xcode is Apple’s integrated development environment (or IDE) for both OS X and iOS development.

`要创建本教程中的 iOS 应用程序，您需要 Xcode 4.4 或更高版本。Xcode 是 Apple 的集成开发环境（又称 IDE ），用于 iOS 和 Mac OS X 的开发。在 Mac 上安装 Xcode，也会同时安装了 iOS SDK ，它包含 iOS 平台的编程接口。`

```
Usage note: This tutorial lists the steps that are required to complete a task in a disclosable area that is defined by two horizontal blue lines and labeled with a blue dot and a phrase that describes the task, such as “To create a new project…” To reveal the steps in a task area, click inside the blue lines.

这份教程中列出了完成一个任务所必须的各个步骤，这些步骤包括在两条蓝色线中，并以蓝色点标记和标语来描述这个任务，例如“创建一个新的工程…”。在两条蓝线之间点击可打开这个任务区域的步骤。

When you complete the steps in a task, you can leave the task area open or you can close it by clicking the line with the blue dot and the descriptive phrase. (Clicking elsewhere in an open task area does not close it, so you can copy code from a step without closing the task.)

完成任务步骤后，可以不收起任务区域直接离开，也可以通过点击小三角形或者标语用于收起该区域（点击任务区域的其他地方是不会关闭它的，所以你可以从其中复制代码，这不会导致这段任务被收起。）
```

### Create and Test a New Project

### 创建并测试一个新的工程

To get started developing your app, you create a new Xcode project.

`先创建一个新的 Xcode 工程，以开启你的应用开发之旅。`<br><br>

***
#### To create a new project

#### 创建一个新的工程


  1. Launch Xcode (located in the Applications folder).
  
	`启动 Xcode (位于 Applications 文件夹).`

	If you’ve never created or opened a project in Xcode before, you should see a Welcome to Xcode window similar to this:

	`如果你之前从来没创建或者打开过一个 Xcode 工程，那么你应该会看到一个如下的 Xcode 欢迎窗口：`
	
	![image](../images/Getting_Started__01.png)

	If you’ve created or opened a project in Xcode before, you might see a project window instead of the Welcome to Xcode window. 
	
	`如果你之前曾经创建或开启的过一个 Xcode 的工程，那么你可能会看到一个工程窗口而不是这个欢迎界面。`
  2. In the Welcome to Xcode window, click “Create a new Xcode project” (or choose File > New > Project).
  
	`在这个欢迎界面，点击“Create a new Xcode project” (或者选择 File > New > Project)。`
	
	![image](../images/Getting_Started__02.png)

	Xcode opens a new window and displays a dialog in which you choose a template. Xcode includes several built-in app templates that you can use to develop common styles of Mac apps.
	
	`Xcode 将打开一个新的窗口并显示一个对话框，你可以在其中选择一个模版. Xcode 囊括了多个内置的应用程序模版，以便于你用来开发常见风格的 Mac 应用。`


  3. In the OS X section to the left of the dialog, select Application.
  
  	`在对话框左侧的 "OS X" 区域选择 "Application".`
  
  4. In the main area of the dialog, select Cocoa Application and click Next.
  
  	`在对话框的主要区域中，选择“Coacoa Application”并点按“Next”.`

  5. A new dialog appears that prompts you to name your app and choose additional options for your project.
  
    ![image](../images/Getting_Started__03.png)
	
	`在弹出的新对话框中命名你的应用程序，并给你的工程选取附加选项。`
	
	Choose the following options:
	
	`勾选以下选项：`
	
      * In the Product Name field, type TrackMix.
      
      	`在“Product Name”一栏中，输入“TrackMix”。`
      
      * In the Company Identifier field, type the identifier for your company, or com.MyCompany.
      
      	`在“Company Identifier”一栏中，输入你的的公司名，或者输入“com.MyCompany”。`
      
      * In the App Store Category pop-up, choose None.
      
      	`在名为“App Store Category”的下拉菜单中，选择“None”。`
      
	```
	Note: Xcode uses the product name you entered to name your project and the app. To keep things simple, this tutorial assumes that you named your product TrackMix and did not specify a class prefix value. (The prefix is used to create unique class names for your app that won’t conflict with classes in other frameworks.) The organization name property that appears in this dialog is not used in this tutorial.

	注: Xcode 将会以您输入产品名来命名您的工程和应用。为了方便起见，本教程假定您将您的产品命名为 TrackMix。
	```


  6. Make sure that the Use Automatic Reference Counting option is selected and that the Create Document-Based Application (appears above Document Extension), Use Core Data, and Include Unit Tests options are unselected.
  
  7. Click Next.

	Another dialog appears that allows you to specify where to save your project.
	
  8. Specify a location for your project (make sure that the Source Control option is unselected) and then click Create.

	Xcode opens your new project in a window (called the workspace window), which should look similar to this:
	
	![image](../images/Getting_Started__04.png)
	
***

Take a few moments to familiarize yourself with the workspace window that Xcode opens for you. You’ll use the buttons and areas identified in the window below throughout the rest of this tutorial.

![image](../images/Getting_Started__05.png)

If the utilities area in your workspace window is already open (as it is in the window shown above), you can close it for now because you won’t need it until later in the tutorial. The rightmost View button controls the utilities area. When the utilities area is visible, the button looks like this: ![image](../images/Getting_Started__icon1.jpeg)

If necessary, click the rightmost View button to close the utilities area.
Even though you haven’t yet written any code, you can build and run your app in Xcode.

***
#### To build and test the app


  1. Click the Run button in the Xcode toolbar (or choose Product > Run).

	If a dialog appears asking whether Xcode should enable developer mode on this Mac, click Disable.
	
	Xcode should build your project and launch the app. When your app starts up, it should have a standard menu bar and display a single window.
	
	![image](../images/Getting_Started__06.png)
	
	![image](../images/Getting_Started__07.png)
	
  2. Test the app.

	You can move and resize the window. However, if you close the window, there is no way to get it back. You should also find that menus display when you click them, and if you choose TrackMix > About TrackMix, an About window is displayed.
  3. Quit the app by choosing TrackMix > Quit TrackMix.

	Don’t mistakenly choose the Quit command in Xcode, or you’ll quit Xcode. You can also click the Stop button in Xcode.
	
***

Right now, your app is not very interesting: it simply displays a blank window. To understand where the blank window comes from, you need to learn about the objects in your code and how they work together to start the app.

### Find Out How an App Launches
Because you based your project on an Xcode template, much of the basic app environment is automatically set up when you run the app. For example, Xcode creates an app object which, among a few other things, establishes the run loop. (A run loop registers input sources and enables the delivery of input events to your app.) Most of this work is done by the NSApplicationMain function, which is supplied for you by the AppKit framework and is automatically called in your project’s main.m source file.

`您的项目是基于 Xcode 模板开发的，所以运行应用程序时，大部分基本的应用程序环境已经自动建立好了。例如， Xcode 创建一个应用程序对象（以及其他一些东西）来建立运行循环（运行循环将输入源寄存，并将输入事件传递给应用程序）。该工作大部分是由 NSApplicationMain 函数完成的，该函数由 AppKit 框架提供，并且在您的项目的 main.m 源文件中自动调用。`
<br><br>

```
Note: The AppKit framework provides all the classes that an app needs to construct and manage its user interface. The AppKit framework is just one of many object-oriented frameworks provided by Cocoa, which is the app environment for all Mac apps. 

注：AppKit 框架提供应用程序构建和管理其用户界面所需的全部类。 AppKit 框架只是 Cocoa 提供的面向对象的众多框架中的一个，而 Cocoa 是所有 MAc应用程序的应用环境。
```

***

#### To look at the main.m source file


  1. Make sure the project navigator is open in the navigator area.

	The project navigator displays all the files in your project. If the project navigator is not open, click the leftmost button in the navigator selector bar:
	
	![image](../images/Getting_Started__08.png)
	
  2. Open the Supporting Files folder in the project navigator by clicking the disclosure triangle next to it.
  
  3. Select main.m.

	Xcode opens the source file in the editor area of the window, which should look similar to this:
	
	![image](../images/Getting_Started__09.png)

***

The call to the NSApplicationMain function creates an instance of the NSApplication class and an instance of theAppDelegate class, which is provided for you by the Cocoa Application template. In this tutorial, the singleton instance of this class is referred to as the app delegate. The main job of the app delegate is to provide a window you can access through its window property. The window object provides a container for the app’s visible content and helps deliver events to other app objects. The app delegate can also perform some app configuration tasks before the app is displayed. You add your custom behavior and logic to the AppDelegate class and any other classes you create.

`调用 NSApplicationMain 会创建一个 NSApplication 类的实例和一个用用程序程序委托的实例，这是由 Cocoa 应用程序模版提供的。 在本教程中，应用程序委托是 AppDelegate。应用程序委托的主要作用是提供一个窗口，你可以通过这个窗口属性来访问它。 应用程序委托的主要作用是提供呈现应用程序内容的窗口，在应用程序呈现前，应用程序委托也执行一些配置任务。你可以添加你自定义的行为和逻辑到 AppDelegate 类或任何你创建的其他类中。`

The instance of the NSApplication class, called the app object, loads the main nib file when the app launches. Nib files are an archive of UI elements and other objects. The main nib file, MainMenu.xib, usually contains the parts of your user interface, such as the menu bar and window, that are visible the entire time your app is running. When a nib file is loaded, the objects it contains are instantiated.
NSApplication 

`类的实例称为应用程序对象，主 nib 文件将会在程序启动时加载。 Nib 文件是 UI 元素和其他对象的归档。MainMenu.xib 称为程序的主 nib 文件，通常包含了您的部分用户界面，例如程序运行时始终可用的菜单栏和窗口。 其包含的对象将在 nib 文件加载完毕后完成实例化。（这段原文中没有～另， Nib 文件意指 Interface Buidler 文档，用于组织创建应用程序的可视部分，即用户图形界面。具体定义和用处跳转去 Google 一下。）`

#### To look at the nib file, and the window in the nib file


  1. Click MainMenu.xib under the TrackMix group in the project navigator.

	The file has the extension .xib but by convention it is referred to as a nib file. Xcode displays the file on a canvas in the editor area.
	
	If an outline view appears instead of the standard editor, click the Standard editor in the Editor toolbar.
	
	![image](../images/Getting_Started__10.png)

  2. To display the window, click the window icon in the sidebar.
  
    ![image](../images/Getting_Started__11.png)
  
***

The sidebar contains several items split into two groups by a dividing line. Above the line are placeholders—objects that are not created as part of the nib file itself, but exist externally. Below the line are objects created as part of the nib file:

`边栏中包含的那几个小图标被分割线分为两组。位于分割线上方的为占位符对象，它不由 nib 文件创建，而是存在于外部的。分隔线下方的则是由 nib 创建的：`
   
   * A menu object
	
	This object is the app’s main menu displayed in the menu bar.
	
   * A window object

	This object is the window with a plain gray background that you see when the app launches.
	
   * An instance of AppDelegate (a dark blue cube), set to be the app object’s delegate
   
   	`一个 AppDelegate 的实例(一个深蓝色的小方块), 被设定为对象的代理`
   
   	When the app object has completed its setup, it sends its delegate an applicationDidFinishLaunching:message. This message gives the delegate an opportunity to configure the user interface and perform other tasks before the app is displayed.

   	`应用程序对象装置完毕后，会给自己的应用程序代理发送一个 applicationDidFinishLaunching: 的信息. 这个信息允许代理进行用户界面的设置并在应用程序显示前进行一些其他任务。`

   * An instance of NSFontManager (a dark blue cube)
	
	`一个 NSFontManager 的实例(另一个深蓝色的小方块，其实跟上面那个长的一样，只能通过看标签来区分)`

   * This object manages the app’s font menu, but you won’t use it in this example.

	`这个对象管理者应用程序的字体菜单，但在这个例子中你不会用到它。`
	<br><br>

### Recap

In this chapter you used Xcode to create a new project based on the Cocoa Application template and you built and ran the default app that the template defines. Then you looked at some of the basic pieces of the project, such as themain.m source file, and the nib file, and learned what objects are created and loaded from the nib file when the app launches.

`在本章中，您使用 Xcode 创建了一个基于 Cocoa 应用程序模版的新项目，生成并运行了该模版定义的默认应用程序。而后您查看了该项目的一些基本组成部分，例如： main.m 源文件、 nib 文件, 并了解了在应用程序启动时基于 nib 文件创建和加载的对象。`

In the next chapter, you’ll learn how to lay out and configure the user interface without writing any code.

`在下一章，你将学习如何在不需要写任何代码情况下设计和装配用户界面。`
<br><br>

© 2013 Apple Inc. All Rights Reserved. (Last updated: 2013-04-23)