# Hathora Cloud Unity Plugin \[Early Access]

<img src="images/hathora_unity_plugin.png" width="500" />

Download the plugin: [Hathora_Cloud_Unity_plugin_earlyaccess.unitypackage](https://raw.githubusercontent.com/hathora/unity-plugin-ea/main/UnityPackage/Hathora_Cloud_Unity_plugin_earlyaccess.unitypackage)

Hathora Cloud: Game Server Hosting is a comprehensive package that simplifies server deployment and operation for your multiplayer games. It takes advantage of the state-of-the-art Hathora Cloud infrastructure, providing cutting-edge performance and elastic compute scheduling for handling massive demand spikes.

To learn about how deploying your game on Hathora Cloud helps with **global scalability**, **low latency**, and **zero-downtime deployments** - check out [our documenation page](https://hathora.dev/docs)

## Install instructions

![Screenshot of plugin contents](images/hathora_plugin_screenshot.png)

Target Unity version: 2021.3.23 or higher (see "Version compatibility" below for more details)

1. Download [Hathora_Cloud_Unity_plugin_earlyaccess.unitypackage](https://raw.githubusercontent.com/hathora/unity-plugin-ea/main/UnityPackage/Hathora_Cloud_Unity_plugin_earlyaccess.unitypackage)
2. Open the Unity project you want to add the plugin to
3. Add `Hathora_Cloud_Unity_plugin_earlyaccess.unitypackage` as a "Custom Package" (Assets > Import Package > Custom Package)
<img src="images/install_package.png" width="400" />
4. Using the Config Finder window, create a new config file
<img src="images/create_config.png" width="400" />
5. Create or login to your Hathora Cloud account using the Editor inspector on your newly created config file from the previous step
   <img src="images/login_account.png" width="400" />
6. Create an application in Hathora Cloud
   <img src="images/create_app_1.png" width="400" />
   <img src="images/create_app_2.png" width="600" />
7. Now you can use the plugin to build and deploy your game server.
   <img src="images/build_deploy.png" width="400" />
8. You can also run the Demo scene to see a working integration example. Use the code in the Demo folder to jumpstart your own integration!

   ![Demo scene](images/demo_scene.png)

## Questions?

Get help and ask questions in our active Discord community:
[https://discord.com/invite/hathora](https://discord.com/invite/hathora)

## Version compatibility

Our plugin is built for Unity version 2021.3.23f1 or higher.

It does still work for earlier versions of 2021.3, but you will need to fix the Universal Render Pipeline (URP) package version. Note that URP is only used for our included demos, so if you simply ignore/delete the Demo folder, you can ignore the URP dependency. See the following steps to fix URP version:

1. `Window` > `Package Manager` > remove Universal RP
2. Find package via Unity Registry > install Universal RP (should be version compatible with your Unity version)
3. `Edit` > `Project Settings` > `Graphics` > set "Scriptable Render Pipeline Settings" to `StarterAssetsURP`

