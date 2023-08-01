# Resource Pack Localization

In Minecraft: Java Edition (1.19.4 and newer by date versions) Mojang Studios added Fallback feature for translations!
So now y'all can easily translate your Resource Pack Description (for Me it actually is Summary, not Description)


## What's "Fallback feature" means?

"Fallback feature" is a good option, that used as placeholder for the translation key if translations don't load or something else happened with them.
```
{
			"translate": "<translation key>",
			"fallback": "<placeholder that appears if there's no tranlsation detected for used translation key>"
}
```

## This is not working!

Oh no! Someone forgot, that translations appear only when Resource Pack used, not when it just appears as Available.
When Resource Pack appears as Available, then its own Description uses Fallback message.
When Resource Pack appears as Selected and then gets activated, then Description can be seen translated.
