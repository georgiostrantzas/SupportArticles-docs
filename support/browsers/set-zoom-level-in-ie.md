---
title: How to set the zoom level in IE9
description: Describes how to set the default zoom in Internet Explorer 9 and later versions to a custom level so that you can make the screen display larger or smaller for a webpage.
ms.date: 04/21/2020
ms.prod-support-area-path: 
---
# How to set the zoom level in Internet Explorer 9 and later versions

Internet Explorer Zoom lets you make the screen display larger or smaller so that a webpage is easier to read. Unlike changing the font size, zoom enlarges or reduces everything on the page, including text and images. You can zoom from 10% to 1,000%. This article describes how to set the default zoom in Internet Explorer 9 and later versions to a custom level.

_Original product version:_ &nbsp; Internet Explorer 9 and later versions  
_Original KB number:_ &nbsp; 2689447

> [!NOTE]
> If you are a Small Business customer, find additional troubleshooting and learning resources at the [Support for Small Business](https://smallbusiness.support.microsoft.com) site.

## How to set the zoom level temporarily or permanently

> [!IMPORTANT]
> This section, method, or task contains steps that tell you how to modify the registry. However, serious problems might occur if you modify the registry incorrectly. Therefore, make sure that you follow these steps carefully. For added protection, back up the registry before you modify it. Then, you can restore the registry if a problem occurs. For more information about how to back up and restore the registry, see [How to back up and restore the registry in Windows](https://support.microsoft.com/help/322756).

It's easy to set the zoom level. You can set it temporarily every time that you use it, or you can create a permanent setting.

### To temporarily set the zoom level

To temporarily set the zoom level in Internet Explorer 9 or a later version, use one of the following methods:

- In Internet Explorer, on the **View** menu, point to **Zoom**, and then select a different level.
- If you have a mouse with a wheel, hold down the Ctrl key, and then scroll the wheel to zoom in or out.
- If you click the **Change Zoom Level** button, ![Zoom Level](./media/set-zoom-level-in-ie/hundred-percent.png), it cycles through 100%, 125%, and 150%. This gives you a quick enlargement of the webpage.
- By using the keyboard, you can increase or decrease the zoom value in 10% increments. To zoom in, press Ctrl+Plus sign (+). To zoom out, press Ctrl+Minus sign (-). To restore the zoom to 100%, press Ctrl+0.

### To permanently set the zoom level

You can permanently set the default zoom in Internet Explorer 9 or a later version to a custom level if you want to. To do this, follow these steps:

1. Click **Start**, type *regedit* in the search box, and then click **regedit** in the **Programs** list.
2. Locate and then click the following registry subkey:  
   `HKEY_CURRENT_USERS\SOFTWARE\Microsoft\Internet Explorer\Zoom`

3. In the details pane, double-click **ZoomFactor**.

   :::image type="content" source="media/set-zoom-level-in-ie/zoomfactor.png" alt-text="zoom factor" border="false":::

4. Click **Decimal**.

   :::image type="content" source="media/set-zoom-level-in-ie/decimal.png" alt-text="Decimal" border="false":::

5. If you want to set the default zoom level to 125%, type *125000*, and then click **OK**.
6. Close Registry Editor.
7. Sign out Windows and then sign in again.
8. Open Internet Explorer. The zoom level should now be set to 125%.

## References

For more information, see [Internet Explorer Ease of Access options](https://support.microsoft.com/help/17456).