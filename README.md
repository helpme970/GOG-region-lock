# GOG-region-lock
Information about and how to bypass GOG region-lock

## Bypass
GOG stores a Cookie that activates the region lock. This Cookie will reset every time you check out to buy and then it will delete region-locked items from your cart. 

Click F12 and navigate to the console tab. 
Type this in the console:
```
document.cookie = "gog_lc=NL_EUR_de-DE; path=/; max-age=2147483647;"; 
```
This will set your region to Netherlands and your language to German-Germany.
