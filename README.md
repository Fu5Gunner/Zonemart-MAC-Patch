# Zonemart-MAC-Patch
Zonemart 0.40.1 – MAC Patch adds Zonemart to the Mod App Creator PDA launcher as its own app icon.


Zonemart 0.40.1 – MAC Patch adds Zonemart to the Mod App Creator PDA launcher as its own app icon.

The problem it solves: Zonemart normally adds a visible “Market” tab to the PDA strip and resizes all existing buttons. With MAC, that would un-hide MAC’s hidden app tabs and scramble the layout.

What’s in it:

fmk_market_mac.script (new): registers Zonemart with MAC as app_zonemart, opening Zonemart’s own PDA view. It does nothing if MAC isn’t installed.
modxml_fmk_market_pda.script (replaces Zonemart’s version): when MAC’s launcher tab is present, it adds Zonemart as a hidden tab and leaves the other buttons alone. Without MAC, it behaves like stock 0.40.1.
Icon files (new): a market-stall icon in fmk_market_app.dds, plus its texture entries in fmk_market_app.xml.

Install: add it as a separate MO2 mod, with higher priority than both Zonemart and MAC.

Unchanged: trader dialogue and the offline NPC market work as before.



I received permission from the mod creator [Fomok] to create a patch. 
All rights to the main Zonemart Mod go to [Fomok] give love to the mod and what its doing.


