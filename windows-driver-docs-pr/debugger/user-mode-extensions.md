---
title: User-Mode Extensions
description: User-Mode Extensions
ms.assetid: 83b0aca1-ad08-4384-a035-3d7bd2c1b4fe
keywords: ["extension commands ( commands), user-mode extensions", "ntsdexts.dll (user-mode extensions)", "uext.dll (user-mode extensions)", "user-mode extensions (ntsdexts.dll and uext.dll)"]
ms.author: domars
ms.date: 05/23/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
---

# User-Mode Extensions


## <span id="ddk_user_mode_extensions_dbg"></span><span id="DDK_USER_MODE_EXTENSIONS_DBG"></span>


This section of the reference describes extension commands that are primarily used during user-mode debugging.

The debugger will automatically load the proper version of these extension commands. Unless you have manually loaded a different version, you do not have to keep track of the DLL versions being used. See [Using Debugger Extension Commands](using-debugger-extension-commands.md) for a description of the default module search order. See [Loading Debugger Extension DLLs](loading-debugger-extension-dlls.md) for an explanation of how to load extension modules.

Each extension command reference page lists the DLLs that expose that command. Use the following rules to determine the proper directory from which to load this extension DLL:

-   If your target application is running on Windows XP or a later version of Windows, use winxp\\Ntsdexts.dll.

In addition, user-mode extensions that are not specific to any single operating system can be found in winext\\Uext.dll.

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20[debugger\debugger]:%20User-Mode%20Extensions%20%20RELEASE:%20%285/15/2017%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")




