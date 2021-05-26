# Sketch DeepL Translate Plugin

Use DeepL to translate text layers and symbol overrides, localie your digital designs in minutes.

This plugin is based on symdesign's [Sketch Auto Translate Plugin](https://github.com/symdesign/sketch-auto-translate)
And modified to work with Sketch 72.1, using DeepL translation.


<table>
<tr>
<td>
This plugin requires you to <a href="#set-deepL-api-key">setup a DeepL API key</a>. <strong>
</td>
</tr>
</table>


## Supported Languages 
Bulgarian, Czech, Danish, German, Greek, English, Spanish, Estonian, Finnish, French, Hungarian, Italian, Japanese, Lithuanian, Latvian, Dutch, Polish, Portuguese, Romanian, Russian, Slovak, Slovenian, Swedish and Chinese


## Translate Selection
Translates your selection on the current page no matter which type, apart from Symbol Masters.

Shortcut: `⇧` `⌘` `Space` Translate Selection


## Translate Current Page
Translates all Text Layers and Symbol Overrides on Artboards in your current Page but skips them out if placed outside.

Shortcut: `⇧` `⌘` `P` Translate Current **P**age


## Translate Entire Document
Translates all Text Layers and Symbol Overrides in the file that are on Artboards but skips them if placed inside a Symbol or outside an Artboard. I made this decision to avoid messing with the file structure.

Shortcut: `⇧` `⌘` `D` Translate Entire **D**ocument



## Set DeepL API Key...

To create a DeepL Translate API Key key yourself, you can make a free account at [DeepL](https://www.deepl.com/pro#developer). 
There is a free trial option that allows you to translate max. 500,000 characters per month. 


#### 1. Create a free DeepL account
[Sign up for free](https://www.deepl.com/pro-checkout/account?productId=1200&yearly=false) Bear in mind that for the free account, a Credit Card is still required.
This plugin only works with the free plan API.

#### 2. Find your API key
After you created your account and loggen in, go to [your account plan page](https://www.deepl.com/pro-account/plan) and scroll down to `Authentication Key for DeepL API`

#### 4. Use API Key
Copy your API Key, go back to Sketch and select `Plugins > DeepL Translate > Set DeepL API Key...` in the menu. After that you get prompted to paste your key.
