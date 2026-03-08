# 🚀 ExoMetric - Real-Time Minecraft Server Monitoring

[![Download ExoMetric](https://img.shields.io/badge/Download-ExoMetric-brightgreen)](https://github.com/WALIDYTYT/ExoMetric/releases)

## 📋 What is ExoMetric?

ExoMetric is a tool that tracks your Minecraft server and system information in real time. It works with Fabric, a popular mod loader. The software sends data through a secure internet link called an HTTP API. This helps you monitor how well your server runs and keeps an eye on its stats.

You do not need to know code or run complicated commands. ExoMetric is designed for anyone who wants to keep tabs on their Minecraft server easily.

## 💻 System Requirements

To run ExoMetric on a Windows PC, your system should meet the following:

- Windows 10 or newer (64-bit recommended)
- At least 4 GB of RAM
- Java 17 or newer installed
- Minecraft server running with Fabric mod loader
- Internet connection for API access

You do not need to be an expert to check or install Java. Simple guides are available online if needed.

## 🎯 Key Features

- Live tracking of Minecraft server performance  
- Monitor CPU, memory, and network usage on your PC  
- Secure data transfer via HTTP API  
- Works with Fabric-based Minecraft servers  
- Easy to set up and use without coding  

## ⚙️ How ExoMetric Works

ExoMetric runs alongside your Minecraft server. It collects data from your computer and server, then shares it through a safe HTTP endpoint you can access with apps or dashboards. This real-time data helps you see how the server performs and when it needs attention.

## 🚀 Getting Started

### Step 1: Download ExoMetric

Visit the release page to get the latest version of ExoMetric:

[![Download ExoMetric](https://img.shields.io/badge/Download-ExoMetric-blue)](https://github.com/WALIDYTYT/ExoMetric/releases)

This page contains all available versions, including updates and fixes.

Choose the version that fits your system, typically the Windows installer or .jar file.

### Step 2: Install Java

ExoMetric requires Java 17 or newer to run. If you are unsure whether Java is installed:

- Press `Windows Key + R`, type `cmd`, and hit Enter.  
- In the command window, type `java -version` and press Enter.  
- If Java is installed, the version number will show. If not, download and install the latest Java from the official website: https://adoptium.net/

Follow the installation instructions provided by the Java site.

### Step 3: Run Minecraft with Fabric

Make sure your Minecraft server uses Fabric, a mod loader that works with ExoMetric. If you do not have Fabric installed:

- Download Fabric installer from https://fabricmc.net/use/  
- Run the installer and select your Minecraft version and server type  
- Follow the steps to set up Fabric on your server  

### Step 4: Download and Run ExoMetric

Once Java and Fabric are ready, download ExoMetric from the release page linked above.

If you downloaded an executable (.exe), just double-click the file to start ExoMetric.

If you downloaded a .jar file, follow these steps:

- Open Command Prompt (press `Windows Key + R`, type `cmd`, then Enter).  
- Navigate to the folder where the .jar file is saved using the `cd` command.  
- Type `java -jar ExoMetric.jar` and press Enter. Replace `ExoMetric.jar` with the actual file name.

You should see ExoMetric running in a terminal window or as a background process.

### Step 5: Access the Monitoring API

ExoMetric runs a secure HTTP API on your computer. To view your server stats:

- Open a web browser  
- Enter the local address shown by ExoMetric (usually `http://localhost:PORT`, where PORT is the number displayed in the terminal or app)  

You can use this link with dashboard tools or check data directly via browser.

## 🔧 Configuration Tips  

ExoMetric comes with default settings that work for most servers. To change settings:

- Locate the `config.json` or settings file in the ExoMetric folder  
- Open the file with Notepad or any plain text editor  
- Adjust port numbers, authentication options, or metrics frequency as needed  
- Save the file and restart ExoMetric for changes to take effect  

Be careful editing settings. Use the examples in the config file to avoid errors.

## 🔄 Updating ExoMetric

Check the release page regularly for new versions. Updates can improve stability and add features.

To update:

- Download the new version from the release page  
- Replace the old files with the new ones  
- Restart the application  

No extra steps should be needed.

## 🛠 Troubleshooting

- If ExoMetric does not start, confirm Java version and ensure Fabric is installed correctly  
- Check for blocked ports in your firewall settings that may stop API access  
- Use log files in the ExoMetric folder to see detailed error messages  
- Restart your computer to clear network or software conflicts  

## 📖 More Resources

- Fabric Mod Loader: https://fabricmc.net/  
- Java Installation Guide: https://adoptium.net/  
- Minecraft Server Setup: https://minecraft.net/en-us/download/server  

---

[![Download ExoMetric](https://img.shields.io/badge/Download-ExoMetric-brightgreen)](https://github.com/WALIDYTYT/ExoMetric/releases)