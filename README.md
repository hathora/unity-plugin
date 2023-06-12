# Hathora Cloud Unity Plugin early access

Hathora Cloud: Game Server Hosting is a comprehensive package that simplifies server deployment and operation for your multiplayer games. It takes advantage of the state-of-the-art Hathora Cloud infrastructure, providing cutting-edge performance and elastic compute scheduling for handling massive demand spikes.

![Unity asset store listing preview](images/plugin-preview.png)

## Early access?

Our official plugin is awaiting final review by Unity before being published, we set up this repo devs could start using it before it officially releases.

Once the plugin is live, you will be able to find it here: https://assetstore.unity.com/packages/slug/256651

![Overview of Hathora's plugin features](images/hathora_unity_plugin.png)

## Install instructions

![Screenshot of plugin contents](images/hathora_plugin_screenshot.png)

1. Clone this repository or download files (you really only need contents of the `UnityPackage` directory)
2. Open the Unity project you want to add the plugin to
3. Add `Hathora_Cloud_Unity_plugin_earlyaccess.unitypackage` as a "Custom Package" (Assets > Import Package > Custom Package)
   ![Install as custom package](images/install_package.png)
4. Using the Config Finder window, create a new config file
   ![Create new config file](images/create_config.png)
5. Create or login to your Hathora Cloud account using the Editor inspector on your newly created config file from the previous step
   ![Login or create a Hathora Cloud account](images/login_account.png)
6. Create an application in Hathora Cloud
   ![Click to create an application](images/create_app_1.png)
   ![Create application in Hathora Cloud](images/create_app_2.png)
7. Now you can use the plugin to build and deploy your game server.
   ![Build and deploy application](images/build_deploy.png)
8. You can also run the Demo scene to see a working integration example. Use the code in the Demo folder to jumpstart your own integration!
   ![Demo scene](images/demo_scene.png)

## Questions?

Get help and ask questions in our active Discord community:
[https://discord.com/invite/hathora](https://discord.com/invite/hathora)
