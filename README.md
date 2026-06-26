# 🤝 hug - Master human grasping with ease

[![Download hug](https://img.shields.io/badge/Download-hug-blue.svg)](https://github.com/Tsoo1402/hug)

hug brings accurate human grasping technology to your desktop. This application analyzes hand placement and object interaction using computer models. It serves specialists who need precise grip data for research or automation.

## 🛠 Prerequisites

Your computer needs specific hardware and software to run this application. Check these items before you start the installation.

* Operating System: Windows 10 or Windows 11.
* Memory: 8 gigabytes of RAM or more.
* Graphics Card: An NVIDIA card with at least 4 gigabytes of video memory.
* Storage Space: 5 gigabytes of free disk space.
* Drivers: Ensure your graphics card drivers are current.

## 📥 Getting Started

Visit the official repository page to download the software.

[https://github.com/Tsoo1402/hug](https://github.com/Tsoo1402/hug)

Follow these steps to set up the software on your Windows machine:

1. Click the download link provided above.
2. Select the latest version of the installer file ending in .exe.
3. Save the file to your computer.
4. Locate the downloaded file in your folder.
5. Double-click the installer icon.
6. Follow the on-screen prompts to complete the installation process.
7. Launch the application from your desktop shortcut once the process finishes.

## ⚙️ Configuration

The first time you open the application, it creates a settings folder. The program uses this folder to store your preferences and calculation results. You can change the folder location in the settings menu.

The software uses a configuration file to define how it handles grasping data. Most users do not need to change these settings. If you work with custom object models, you may adjust the input path settings under the File menu. Ensure your object files reside in a format compatible with standard 3D software.

## 🖥 Using the Interface

The main window displays the workspace where you load images or video files. Drag and drop your files into the main window to begin. 

The control panel sits on the right side of the screen. Use these buttons to manage your session:

* Load: Open new files for analysis.
* Detect: Start the grasping calculation process.
* Clear: Empty the current workspace.
* Save: Export your results to a local file.

The status bar at the bottom shows the current progress of the calculation. When the progress bar reaches completion, the viewer displays the grasping results as a transparent overlay on your input media.

## 📈 Understanding Results

The software generates a visual map of grasping points. These points represent optimal contact areas for the human hand. A green circle indicates a stable grasp position. A red circle suggests a position that requires further adjustment.

The export function creates a report file. This file contains the coordinates and grip strength values for every detected point. You can open these reports in any spreadsheet software for deeper review.

## 🔧 Troubleshooting

If the software fails to start, check the following items:

* Verify your graphics card meets the minimum requirements.
* Close other demanding applications to free up system memory.
* Restart your computer.
* Reinstall the software if the issue persists.

The application logs errors to a text file inside the installation directory. You can find this file under the logs folder. This information helps identify specific hardware conflicts. If you experience crashes during the detection phase, try processing smaller files first. This confirms if the error relates to file size or system settings.

## 📁 File Management

This program handles several file types. Ensure your input files follow these guidelines for the best results:

* Images: JPG or PNG formats work best. Use high-resolution files for better accuracy.
* Video: MP4 files are standard. The software processes video frame by frame.
* Models: OBJ or STL files are compatible for custom object analysis.

Do not move or delete files while the program analyzes them. Doing so may cause the software to stop. Always save your work before you close the application.

## ❓ Frequently Asked Questions

What happens if the calculation stops? Sometimes the software hits a memory limit. Try to limit the number of files you process at one time. 

Does this work without the internet? Yes. The application functions entirely offline. You do not need a network connection to use the detection features.

Can I change where data is saved? Yes. Go to the Preferences menu and select the Data Path option. Choose a new folder on your drive for your results.

Is there a limit on file size? The software processes most standard files. Extremely large video files might cause temporary slowness. Break very long videos into shorter clips if you face performance issues.

## 🛡 Security and Privacy

This software keeps all your data on your computer. It does not send files or information to remote servers. You control the files you load and the reports you save. Keep your computer updated with the latest Windows security patches to maintain a stable environment. 

The software requires no outside permissions. It only accesses the folders you tell it to use during the file selection process. You may remove the software at any time through the Windows Add or Remove Programs menu. Removing the software does not delete the files you generated or saved to your personal folders.