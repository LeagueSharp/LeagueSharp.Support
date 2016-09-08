**Loader configuration file** is the place where information about your installed assemblies and libraries is stored as well as the way they are systemized, such as profiles and the list order.
If you decide to switch to the new loader or you don't want to waste your time installing same assemblies on the other computer, you will want to transfer your configuration file. Two most common cases will be reviewed in this article: transfering **from the old loader to the new one**(➊) and transfering between **both new loaders**(➋).

➊In order to transfer your configuration from old loader to the new one, open new PlaySharp loader, open the **tab with your nickname** on it, press "**Import config**" ([how does it look like?](https://s.put.re/vYRBTKL.png)) button and locate the **config.xml** file in your old LeagueSharp loader folder where executable file is located.

➋In order to transfer your configuration between new loaders, copy **loader.lol.json** from `**loader folder**\Config` and paste it in the corresponding folder of your another loader. If you only need to share one assembly profile, you can simply right click on it in loader and press "**Share Profile**" ([how?](https://s.put.re/Kmpv68w.gif)), it will quickly copy the link to the clipboard so you can send it anyone you want or use it to install the same profile with assemblies inside it on your other computer.

You can also transfer your **assemblies configuration**, which includes settings of all your assemblies you adjust within in-game LeagueSharp menu. It may be handy for those who want to share their settings for most advanced assemblies, such as activators, evaders, champion assemblies with lots of options.

In order to transfer your assemblies configuration, copy **MenuConfigCommon** and **MenuConfigSDK** (*for assemblies which use LeagueSharp.Common and LeagueSharp.SDK libraries respectively*) folders from '`%appdata%\LSXXXXXXX`(*X stands for random letter or number*) and paste it in the same folder on your another computer.

###Useful articles
>[New Loader Guide](https://www.joduska.me/forum/topic/221357-new-loader-guide/)
