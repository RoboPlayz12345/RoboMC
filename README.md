# RoboPlayz Launcher

A simple, all-in-one launcher for Minecraft that handles Fabric mods for you.

## What you need first

- **Python 3.9+** installed on your PC ([python.org](https://www.python.org/downloads/) if you don't have it)
- **Java 21 or newer** installed (needed for the newer Minecraft versions this launcher targets)
- That's it. No other downloads, no extra libraries to install.

## How to run it

1. Download the full file as a zip. 
2. Extract the zip file. 
3. Make sure you get all requirements stated above 
4. Double click the PlayMC.bat file.

Thats it then you are all set. 

## This client features a mod loader 

1. It uses the modrinth API and can get dependencies for whatever you mods you add. 
2. You can play vanilla or with mods. 

## Using the launcher

**First time setup:**
1. Type a username in the "Username" box (anything you want — this is offline play, no account needed).
2. Leave the Minecraft Version and Mod Loader dropdowns on their defaults, unless you know you want something specific.
3. Click **Run Setup**. This downloads Minecraft and Fabric for the first time — it can take a few minutes depending on your internet.
4. Once setup finishes, click **Launch**.

That's the whole process. Every time after this, you can just click **Launch** directly — setup only needs to happen once per version, and the launcher will automatically re-run it if you switch versions or loaders.

## Adding mods

1. Go to the **Browse Mods** box on the left and type a mod name (e.g. "Sodium").
2. Hit **Search**.
3. Click a result, then click **Install Selected**.

If that mod needs other mods to work (like a library it depends on), the launcher grabs those automatically too — you don't need to hunt them down yourself.

Your installed mods show up in the **Installed Mods** box on the right. Click one and use **Toggle On/Off** to disable it without deleting it, or **Remove** to delete it for good.

## Switching Minecraft versions or mod loaders

Use the dropdowns at the top. Each version + loader combination keeps its own separate set of mods, so switching between them won't mix things up or lose your setup.

If a version you want isn't in the dropdown, tick the **Manual** box next to it and type the version number in yourself.


## Troubleshooting

- **"Setup required" won't go away** → Click Run Setup, and check the Output box at the bottom for what's happening.
- **Java not found / wrong version** → Install Java 25+ and make sure it's on your system PATH. On Windows, the launcher can offer to install it for you if your PC has Software Center available.
- **A mod isn't showing up in search** → Double check it actually supports the Minecraft version and loader you have selected — mods are version and loader specific.
- **Something crashed** → Check the Output box at the bottom of the window first; it logs what the launcher was doing right before the error.
- IF THERE IS ANY ISSUES OR FEATURES YOU WOULD LIKE, PLEASE DM ME/ or find me irl. 

I hope you enjoy!
