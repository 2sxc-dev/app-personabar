# PersonaBar App: v01.00.00

## Overview

DNN PersonaBar can be problematic on mobile devices. Many users with edit permissions do not need the PersonaBar regularly. However, it consumes nearly 20% of the mobile screen space and significantly slows down page load times, especially on slower mobile connections.

This App introduces a button on the page to remove or re-add the PersonaBar. This approach genuinely removes the bar rather than using a JavaScript-based show/hide method, which would still consume bandwidth and CPU resources for loading and running scripts.

## Dependencies

This app relies on the `ToSic.Sxc.PersonaBar.Utils.dll` from the [PersonaBarUtils](https://github.com/2sxc-dev/PersonaBarUtils) C# class library. Ensure this DLL is in the DNN bin folder for the 2sxc app to function correctly. The library manages the visibility of the PersonaBar based on the `HidePersonaBar` cookie.

## Repository

This app is maintained by 2sic. The official repository can be found at [app-personabar](https://github.com/2sxc-dev/app-personabar).
