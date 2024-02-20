<div align="center">
  <img src="https://cdn.discordapp.com/icons/1117373291095662623/cd7c44850a9a6e06b586abe05e035c7d.webp?size=1024&format=webp" alt="Server Discord Icon" width="100">
  <h1><strong>fakeProfile</strong></h1>
</div>
<p align="center">
  An all-in-one <a href="https://vencord.dev/"><strong> Vencord</strong></a> plugin for customizing your Discord profile.
</p>



<p align="center">
  <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"></a>
  <img src="https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white" alt="CSS"></a>
  <a href="https://discord.gg/ffmkewQ4R7"><img src="https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white" alt="Discord Server"></a>
</p>
<p align="center">
<a href="https://vencord.dev"><img src="https://img.shields.io/badge/This%20plugin%20for-Vencord-pink?labelColor=gray&style=flat&logo=https://lh3.googleusercontent.com/zDATisIeInAwNSjH9LgItgvGXwq3M4SDdoIZzctMZ3Hbl9IhoFVJtsHvzQPz_a7K5xbdURropceVQK6XGrmg4v4HSQ=s60&link=https://vencord.dev" alt="This plugin for" /></a>
</p>

<!-- Empty line -->

## 🖥️Selection

 - [fakeProfile](#fakeProfile)
   - [❓What is fakeProfile?](#❓what-is-fakeprofile?)
   - [🔨Installation](#🔨installation)
   - [❓Tutorial about plugin](#❓tutorial-about-plugin)
   - [❔QnA](#❔qna)

<!-- Empty line -->


## ❓What is fakeProfile?
<div align="center">
  <img src="https://cdn.discordapp.com/attachments/998071689009184870/1209377838571061298/bg.png?ex=65e6b3e1&is=65d43ee1&hm=d1e5af92057e9050ba3d2104b13315ee683931a43cd29aaa57695ae697ad41f2&" alt="Preview" width= "500">
</div>

**fakeProfile** is a plugin for **Vencord** that supports all features related to nitro profile editing `without` the need to use individual plugins to create a complete profile with features such as:
 - Custom banner (Animated)
 - Custom avatar (Animated)
 - Choose profile effect (Without Nitro)
 - Choose profile theme colors (Without Nitro)
 - Choose custom decoration (Coming Soon...)
 - Choose custom badges
 - Reload database without restart client (This plugin used `/reload` to reload database)

<!-- Empty line -->

## 🔨Installation
 ### 1. Requirement
 - The version you are using is **Vencord DEV Build**. If you don't know how to install then you can [click here](https://github.com/Vendicated/Vencord/blob/main/docs/1_INSTALLING.md) to read the installation instructions.

 - Youtube video install Vencord DEV Build by [@daveyy1](https://discord.com/users/549244932213309442): *Click image below to watch tutorial*

 [![Tutorial Install Third Party Plugin](https://img.youtube.com/vi/8wexjSo8fNw/maxresdefault.jpg)](https://www.youtube.com/watch?v=8wexjSo8fNw)

 ### 2. Install Plugin
 Open **Windows Explorer** and select the path where you installed **Vencord** and click on the `src` folder. In the folder you just clicked, create a new folder named `userplugins` *(in case you already have that folder, you can skip creating the `userplugins` folder)*.

 - In the `userplugins` folder click on the address bar and type **cmd** and press **enter**.

 In **Command Prompt** used this command:
 ```shell
 git clone https://github.com/sampathgujarathi/fakeProfile.git
 ```

 After typing the command line, wait until the download is completed and then type:
 ```shell
 pnpm build
 ```
 And that all. Now you can restart Discord and check **fakeProfile** in **Plugins** setting.

 ### 3. How to update fakeProfile plugin?
 - Goto `Vencord\src\userplugins\fakeProfile` in adress bar type **cmd** and click to **Command Prompt** type:
 ```shell
 git pull
 ```
 - Then type:
 ```shell
 pnpm build
 ```
 That all. Restart your Discord client and enjoy.

<!-- Empty line -->

## ❓Tutorial about plugin
> ✏️ **Note:** You must join our Discord server to request banners, avatars and badges. You can [click here](https://discord.gg/ffmkewQ4R7) and it will take you straight to our Discord server.

 ### 1. How to request banner?
 - Goto [#banner-request](https://discord.com/channels/1117373291095662623/1209033914769866833)
 - Upload a image have format `gif, png of jpg`.
   
   *⚠️ **Note:** You cannot use **image link** to request because it will not show your request in the [#fakeprofile-log](https://discord.com/channels/1117373291095662623/1209032677366431815) channel.*

 - All that's left for you is to wait until your request is approved in the [#fakeprofile-log](https://discord.com/channels/1117373291095662623/1209032677366431815) and use the `/reload` command to reload the database and enjoy.

 ### 2. How to request avatar?
 > **📄 Note:** The operation will be the same as requesting a banner but will only be different for each channel requested.
 - Goto [#avatar-request](https://discord.com/channels/1117373291095662623/1209035226018353152)
 - Upload a image have format `gif, png of jpg`.
   
   *⚠️ **Note:** You cannot use **image link** to request because it will not show your request in the [#fakeprofile-log](https://discord.com/channels/1117373291095662623/1209032677366431815) channel.*

 - All that's left for you is to wait until your request is approved in the [#fakeprofile-log](https://discord.com/channels/1117373291095662623/1209032677366431815) and use the `/reload` command to reload the database and enjoy.
 
 ### 3. How to choose a profile effect?
 - Goto [#vencord-commands](https://discord.com/channels/1117373291095662623/1185970757105360927)
 - Used command `/effects` like this:
  <img src="https://media.discordapp.net/attachments/998071689009184870/1209402089378422785/image.png?ex=65e6ca77&is=65d45577&hm=eddf86c225a7956b277fa9a1e596fcedcb42af670de49b16200c2f1459911013&=&format=webp&quality=lossless&width=1163&height=52" alt="effects commands">
  
 - Choose a effect and click **apply** button
 - After that used `/reload` to reload database and enjoy.

 ### 4. How to request badge?
 - Goto [#vencord-commands](https://discord.com/channels/1117373291095662623/1185970757105360927)
 - Used command `/badge_add` like this:
 <img src="https://media.discordapp.net/attachments/998071689009184870/1209412234866855996/image.png?ex=65e6d3ea&is=65d45eea&hm=361f4aa531ad23ca63ff63220602702b769054ee3584eb335d3eb88bd3005d4b&=&format=webp&quality=lossless&width=1164&height=51" alt="badge_add commands">

 - Wait your request approved in [#badge-log](https://discord.com/channels/1117373291095662623/1198555327730294844) and use `/reload` command to reload database and enjoy.

 ### 5. How to manager and remove my badges?
 - Goto [#vencord-commands](https://discord.com/channels/1117373291095662623/1185970757105360927)
 - Used `/my_badges` like this image:
 <img src="https://cdn.discordapp.com/attachments/998071689009184870/1209419333219000371/image.png?ex=65e6da86&is=65d46586&hm=542f580c9d20c1048b8e7e0ed2b431a25cc324844dbcd8ae629e4ec44de9545c&" alt="my_badges commands">

 - You can manager or remove badged with command
 <img src="https://cdn.discordapp.com/attachments/1198578773092745357/1209418170624901200/image.png?ex=65e6d971&is=65d46471&hm=d8be9a0ef89600b66046516b521db1a2d52bdd270bdc28438dc84b89f2a08551&" alt="bageds manager">

 - Used `/reload` to reload database and done.

<!-- Empty line -->

## ❔QnA
 ### 1. Can everyone in Discord see my profile?
 - No, only people who also use this plugin will see the changes.
 ### 2. If I leave the Discord server, will everything on my profile be lost?
 - No, because your requests will be saved in the plugin's database, so if you leave the server, nothing changes. *(unless you turn off the fakeProfile plugin, everything will return to the way it was when you didn't use this plugin)*
 ### 3. So what happens if I disable fakeProfile plugin?
 - As I answered in the 2nd QnA, everything will return to the way it was before you used this plugin. Of course, you can still turn it back on if you want to use it, but if you don't want to use it anymore, you have the right to turn this plugin off.

<!-- Empty line -->

---
<p align="center" style="color: gray;">
  @2023-2024 fakeProfile
</p>
