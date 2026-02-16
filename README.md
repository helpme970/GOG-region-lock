# GOG-region-lock
Information about and how to bypass GOG region-lock

> I don't whant to hurt anybody or do illegal things, I just want to play games that are region-locked because of old laws. The laws changed and many more things are allowed today, but some old games are not up to date with the laws and are still region-locked.

## Bypass
### Cookie
GOG stores a Cookie that store your region and with this, decides if an item can be displayed or not. This Cookie will reset every time you check out to buy and then it will delete region-locked items from your cart, so you can't buy things with this trick, but you can explore the Games without restrictions. (Maybe you can buy something when you have a browser extension that updates this cookie fast enough before it is read by the checkout script.)

Click F12 and navigate to the console tab.
Type this in the console:
```
document.cookie = "gog_lc=NL_EUR_de-DE; path=/; max-age=2147483647;"; 
```
This will set your region to Netherlands and your language to German-Germany.

### VPN
To buy items you need a VPN. For example the free VPN of Proton.
Connect to a region that is not affected (List of affected countrys: https://www.gog.com/forum/general/regional_locked_games_on_gog_v2/page1)
Do a hard-reload (F5 or SHIFT+CTRL+R) to update your location
Buy games you want

## Blocked Games
See here: https://www.gog.com/forum/general/regional_locked_games_on_gog_v2/

## Credits
Thanks to Gabelvampir who showed how to do this (https://github.com/Gabelvampir/Knowledge/blob/master/GOG%20anti-region%20lock)
