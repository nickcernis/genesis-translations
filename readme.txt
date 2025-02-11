=== Genesis Translations ===
Contributors: thememix, DeFries
Donate link: https://remkus.devries.frl/donate/
Tags: genesis, translations,
Requires at least: 4.3
Tested up to: 5.2
Stable tag: 2.10.1

This plugin translates the Genesis Framework into one of the available languages.

== Description ==

This plugin translates the Genesis Framework into one of the available languages. No need to fuss about with your `functions.php` file or uploading `.mo` and `.po` files. Just install this plugin et voil&aacute;! If you're curious about the status of your translations you can check out the [translations here](https://translate.studiopress.com/) and if you'd like the improve your language you will need to register [here](https://translations.studiopress.com/) first.

Check [Translate StudioPress](https://translate.studiopress.com) to see which languages are currrently supported and how far along the translations are.


So you don't see your language up here and you would like to see it added? [Please contact me](https://remkus.devries.frl/contact/ "Please contact me") and we'll get you sorted.

This plugin only works on the [Genesis Framework](https://remkus.devries.frl/recommends/genesis/ "Genesis Framework").

== Installation ==

Installation of this plugin works like any other plugin out there. Either:

1. Upload the zip file to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

Or search for "Genesis Translations" via your plugins menu.

== Frequently Asked Questions ==

= Why is the plugin not translating my entire site? =

This plugin translates the text strings of the Genesis Framework and ONLY those. So, this plugin does not translate your content (post / pages). 

= Why is the plugin not translating my Genesis Child Theme? =

This plugin translates the text strings of the Genesis Framework and ONLY those. You'll most likely need translation files for your Genesis Child Theme. Send us an email at translations@studiopress.com and we'll do our best to help you on your way.

= How can I see my language added to this plugin? =

[Please contact us](https://twitter.com/thememix/ "Please contact us") and we'll get you sorted.

= Can I make a suggestion =

You most certainly can. [Please contact us](https://twitter.com/thememix/ "Please contact us") and we'll get you sorted.

= Where can I find the list of languages being worked on? =

Visit the [StudioPress GlotPress installation](http://translate.studiopress.com/projects/genesis/ "GlotPress installation") to see the complete list of languages being worked on.

= I have your plugin activated but I don't see an options page =

That's because there isn't any. If you have one of the provided languages properly configured in your `wp-config.php` file, then upon activation you should see all matters Genesis automagically translated.

= When I've activated your plugin there are still some words in English on my site =

Most likely you either have words hardcoded in your child theme's `functions.php` file or you're working with outdated (or incomplete) WordPress translation.

= I'd like to help out with the translations =

Fantastic! Go ahead and register [here](https://translate.studiopress.com/ "here") and we'll get you sorted.


== Changelog ==

= 2.10.1 =
* Fixing more incorrect translations creating printf warnings.

= 2.10.0 = 
* Updated to Genesis 2.10.0 text strings
* Updated various languages
* Fixed [bug](https://wordpress.org/support/topic/warning-printf-too-few-arguments-5/)

= 2.8.0 = 
* Updated to Genesis 2.8 text strings
* Various translation updates

= 2.7.2 = 
* Added nl_BE and sr_RS
* Various translation updates

= 2.7.1 =
* Updated to be in sync with Genesis 2.7 branch 
* Added a lot of translations updates across the board

= 2.7.0 =
* Updated to be in sync with Genesis 2.6 branch 
* Added a lot of translations updates across the board

= 2.6.0 =
* Updated to be in sync with Genesis 2.6 branch 

= 2.5.0 =
* Various translations updates
* Removing i18n module
* Removing fallback translations for anyone still on a Genesis version older than 2.0
* Updated admin page slightly. 

= 2.4.1 = 
* Translation updates

= 2.4.0 = 
* Bumping a version number, bad, bad semver, I know, to match Genesis release version.
* Updated all the languages.

= 2.2.0 =

* Updated various languages
* Added Amharic (am), Czech (cs_CZ), Slovenian (sl_SI) and Ukranian (uk).

= 2.1.0 =

* Adding system for testing translate.wordpress.org

= 2.0.7 =

* Updated hu_HU and sv_SE

= 2.0.6 =

* Updated fr_FR, nl_NL and bg_BG

= 2.0.5.1 =

* Adding fa_IR

= 2.0.5 =

* Updated fr_FR, zh_CN, hu_HU, nl_NL and da_DK

=  2.0.4 =

* Updated bg_BG, da_DK, hr, hu_HU, it_IT, nl_NL and ro_RO

= 2.0.3.1 =

* Updated Dutch translation

= 2.0.2 =

* Proper fix for deprecated version check with get_theme_data

= 2.0.1 =

* Fixed notice for $theme_info on L104

= 2.0.0 =

* Large update to (finally) reflect the changes made in Genesis 2.0. Lots of improved translations across the board. Too many to mention specifically.

= 1.9.2 =

* Updates to various languages + added Welsh (cy)

= 1.9.1 =

* Updated a few things in readme

= 1.9.0 =

* Added Arabic (ar), Afrikaans (af) & Croatian (hr)
* Updated es_MX, da_DK, sv_SE, pt_PR, hu_HU,

= 1.8.4 =

* Updated Hungarian language files. Again.

= 1.8.3 =

* Updated Danish, Dutch, German, Hebrew, French and added Mexican Spanish

= 1.8.2 =

* Updated various languages

= 1.8.1 =

* Accidentally deleted helper function. Sorry about that folks.

= 1.8.0 =

* Updated the translations to reflect the changes made to in the genesis.pot file related to the Genesis 1.9 update
* Updated German (de_DE), Finnish (fi) and Dutch (nl_NL)

= 1.7.0 =

Added Norwegian ( nb_NO ) and huge update to Portuguese Brazilian. Small updates to French, Danish and Russian

= 1.6.0 =

Few minor updates Bulgarian, Romanian, Chinese and Portuguese Brazilian, but mostly added Russian (ru_RU) and Icelandic (is_IS).

= 1.5.0 =

Basically all of the languages saw small updates. Swedish and Danish got a big overhaul in grammar and such. Hungarian, Portuguese and Chinese is added as well as Icelandic for the front-end only.

= 1.4.1 =

SVN somehow did not pick up the languages files. Second try.

= 1.4.0 =

Updated a bunch of translations from http://translate.studiopress.com/
Added Hungarian, Turkish and Portuguese.

= 1.3.1 =

* Added the Vietnamese translation and re-added the Greek version to make the file was accurate.

= 1.3 =

* Updated a bunch to translations to match the translation strings of Genesis 1.8: nl_NL, de_DE, fr_FR, da_DK, fi, ro_RO, id_ID, es_ES, el_GR and sv_SE.

= 1.2 =

* Added the Danish translation that was ready for about 87%.
* Re-added the Portuguese translation files as they had gotten lost somehow. Apologies to all who got affected.
* Updated the Finnish version.

= 1.1 =

Added Greek el_GR to the translations. Note, not all strings have been properly translated to Greek yet, but most of the important stuff has.

= 1.0.1 =

Fixing a typo. It happens.

= 1.0 =

* Stable release. Updated some code here and there. Added the Portuguese Brazilian, Hebrew, Japanese and Romanian languages.

= 0.1 =

* First release. Just testing things out.

== Upgrade Notice ==

= 2.0.2 =

* Lots of changes in pretty much every single translation file plus some necessary cleanup in functions so there are no notices anymore.

= 1.8.1 =

* Update to reflect changes in Genesis 1.9

= 1.1 =

* Adding Greek to translations.

= 0.1 =

Upgrade from nothingness just to be one of the cool kids.


== Other Notes ==

You can find me here:

* [ThemeMix](https://thememix.com/ "ThemeMix")
* [Find me on twitter](https://twitter.com/remkusdevries "Remkus de Vries on Twitter")
* [Remkus de Vries](https://remkus.devries.frl/ "Remkus de Vries")