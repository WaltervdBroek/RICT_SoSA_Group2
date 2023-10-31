Intro to user manual: This document is a user manual that describes how the Software Sustainability Assessment (SoSA) tool can be utilized. The manual is divided into two parts:  

A. Requirements & Accessibility: Provides guidance to access and install Microsoft Visual Studio 

B. Building your SoSa Model 

 

Intro to tool: The SoSA tool is a tool that can be used to identify all concerns of a software – describing its effects – both positive and negative – on different levels (life cycle, enabling and structural). 

A. Requirements & Accessibility  

  Download Microsoft Visual Studio and follow the Tutorial.  

Download here: https://visualstudio.microsoft.com/downloads/

Tutorial: https://www.youtube.com/watch?v=FBo5Cso-ufE 

Download the Zip-File from the GitHub repository and un-zip it. Open the file Testforproject.sln (type is Visual Studio Solution).  

Once the file is open, select ‘Solution explorer’ in the window on the right, then right click on ‘Solution ‘TestforProject’. Then click on ‘Clean solution’ and wait until ‘Output’ shows ‘Clean started at [time] and took [number] seconds’.  

Again, select ‘Solution explorer’ in the window on the right, then click on ‘Build solution’ (or use the shortcut Ctrl + Shift + B). The solution is now being built. Wait until ‘Output’ shows ‘Build started at [time] and took [number] seconds’. 

Select ‘Start’ in the navigation bar, the running area will now open. 

B. Building you SoSa Model 

In a new window, the running environment will open with the skeleton of the model already initialized. Open the ‘Toolbox’. If it is not already showing on the left side, go on “View” and select “Toolbox” (or Ctrl + Alt + X).  

In the Toolbox, you can select from some options: 

Pointer 
Impact Levels: Immediate, Enabling and Systematic 
Concerns: EnvironmentalConcern, SocialConcern, TechnicalConcern, EconConcern  
Connectors: ConncectorConcern (connects concerns with each other, ConnectorSoftware (connects Software with concerns) 
Software: The piece of software/ program we are analyzing 

 
Now, you can start building your own Sosa Model: 

First, place the Immediate level as the inner circle, followed by enabling as the middle circle and lastly, systematic as the outer circle.

Place concerns within the relevant impact levels.  

Connect the concerns with each other and/or with the Software. The relationships can either be positive (+) or negative (-).    

When you are done building your model, you can save it. Go to ‘File’ and select ‘Save + YourProjectname” (or Ctrl + S) and select the folder to save your project in.  
