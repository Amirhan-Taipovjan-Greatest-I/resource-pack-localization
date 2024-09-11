# Resource Pack Localization

In Minecraft: Java Edition (1.19.4 and newer by date versions) Mojang Studios added Fallback feature for translations!
So now y'all can easily translate your Resource Pack Description (for Me it actually is Summary, not Description)


## "What's "Fallback feature" means?"

"Fallback feature" is a good option, that used as Placeholder for the Translation Key if Translations don't load or something else happened with them.
```
{
	"translate": "<translation key>",
	"fallback": "<placeholder that appears if there's no tranlsation detected for used translation key>"
}
```

## "What Translation Key should I use for the Description and what Message should be in Fallback?"

You can choose by Yourself... but if I was in Your place, then I prefer `"resourcepack.descriptionTranslation.<Resource Pack ID (or its Name, but w/o any spaces)>"` and as Fallback message I prefer to use `en_us.json` Description.


## "This is not working!"

Oh no! Someone forgot, that Translations appear only when Resource Pack used, not when it just appears as Available.
When Resource Pack appears as Available, then its own Description uses Fallback Message.
When Resource Pack appears as Selected and then gets activated, then Description can be seen as translated.
