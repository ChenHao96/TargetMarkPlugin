# TargetMarkPlugin
This is an efficient target tagging plugin that maintains a good frame rate even when there are a lot of tags.

Marketplace: [Link](https://www.fab.com/listings/0cf55e9c-412e-4a95-a621-d32e3c4b7785)

![Title](Title.jpg "Title")
<br/><br/>
## Overview.
What does our TargetMarkPlugin?

This is an efficient target tagging plugin that maintains a good frame rate even when there are a lot of tags.

1. Activation plugin.

![Title](02.png "Title")

2. You can see pre created assets in this directory
![Title](03.png "Title")
3. Next Step. you need to add Widget "UI_MarkContainer " to the Player Screen in the PlayerController.

![Title](01.jpg "Title")
**Note:** that OwnerPlayer needs to be set, otherwise Mark will not be displayed on the screen.

4. Add the Component 'TargetActorMarkComponent' to the Actor you created,And add it to the scene.

![Title](04.png "Title")

5. Select the 'Target Actor Mark' Component and choose the Mark icon you want in the MarkClass property.

![Title](05.png "Title")
6. Run the game and you will see the Actor marked on the screen. It's as simple as that.
![Title](06.png "Title")

## Customize

### You can design your own pattern to replace the pre provided pattern
![Title](07.png "Title")
![Title](08.png "Title")

## Function 
You can also manually Add or Remove actors that require Mark

1. Add Actor Mark

   **Note**: Actor Has "Component" Will not Added
3. Remove Actor Mark

   **Note**: Only manually added Actor will be removed
5. Clear All Actor Marks

   **Warning**: Be cautious as it will also clear fixed "Mark" in the scene
7. ReSet Screen Value

   **Note**: When splitting or adjusting the split screen size, this function needs to be called

![Title](09.png "Title")

![Title](10.png "Title")

<br/>

**Number of Blueprints**: 3 Widget

**Code Modules**: TargetMarkPlugin (Runtime)

**Number of C++ Classes**: 5 Class

**Network Replicated**: No

**Supported Development Platforms**: Windows

**Supported Target Build Platforms**: Win64, Win32, Linux, Mac, IOS, Android
