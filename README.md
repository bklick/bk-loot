# BK's Loot

![Screenshot of the module's content](preview.png)

## Installation

In Foundry's setup screen, go to "Add-on Modules," click "Install Module," and paste this manifest URL into the field at the bottom:

```
https://github.com/bklick/bk-loot/releases/latest/download/module.json
```

Then enable "BK's Loot" in your world under Game Settings > Manage Modules.

Alternatively, download `bk-loot.zip` from the [latest release](https://github.com/bklick/bk-loot/releases/latest) and extract it into your Foundry `Data/modules` folder.

This is a compendium of treasure items for the D&D 5e system in Foundry VTT version 14, so that DMs can easily drag loot into their players' inventories without having to spend a lot of time hand-crafting loot.

I am making these compendiums because when I give out loot I hadn't prepared in the VTT in advance, my players have told me that they felt like it was "pity loot" that I made up on the spot. As I literally never do this, I figured I would fix the problem for the foreseeable future for myself.

Clearly, then, loot with an icon and a description adds to the enjoyment (or perhaps the sense of fairness?) of the game for some players. I aim to provide that here, and to expand the module periodically.

These are meant to be items that you can plug and play into any session. While nothing here is necessarily specific to D&D 5.5e, I created it with that system in mind. I used that game's pattern to determine how much gold each gem is worth. Also, you know, I measure value in gold, which plenty of systems do not.

The first release was a collection of gemstone items. The gems do not have weight because even at my worst, most spendthrifty trip to a gem and mineral show, I have never had so many gems that I couldn't carry more of them. Later releases added crafting materials, weapon affixes, and tables for naming magic items.

Enjoy, and please feel free to raise any questions, comments, thoughts, or concerns [here](https://github.com/bklick/bk-loot/issues).

## Contents to Date

* 86 types of gemstones with custom art, gold values, and short encyclopedia-style descriptions, each in cut, rough, and fragment forms.
* Two compendia with the gemstones sorted into value tiers of 10, 50, 100, 500, 1000, and 5000gp. One compendium has the same gemstones, but in an unidentified state for DMs who prefer to use rules and mechanics related to identifying loot.
* A Materials compendium with 88 crafting materials, including metals, herbs and fungi, glands, and leathers, sorted into six tiers.
* A Weapon Affixes compendium with prefixes and suffixes for eleven elements, suffixes for all eight schools of magic, and a Named Item effect for renaming enchanted weapons. These are made in the image of the magic item system from the Diablo series. For now, they're all just reflavored enspelled weapons and flametongues, but balanced around different elements and tiers of play.
* An Item Names compendium with roll tables for generating names for magic weapons and armor.

## Using this Content

This module will create a new compendium folder called "BK's Loot," which will expand to show the contents. If these are not visible, check to make sure that the module has been activated.

To create a quick loot table with these items, right-click on any of the folders one level above the gemstone items in their compendia and in the context menu, select "create rollable table." The table will appear in your tables tab.

To enchant a weapon, open one of the affix items in the Weapon Affixes compendium and drag a prefix or suffix from its effects tab onto a nonmagical weapon. A weapon can carry as many affixes as you like, but the name will become very strange, and the item description will become monstrously huge. This is the problem that "Named Item" solves, and the reason I added the random name generator.

Each affix item's description explains how its prefixes and suffixes work.

## Changelog

### 1.4.0

* Suffixes now hold one spell chosen by the DM or by the crafter: a cantrip at Tier 1, a 1st- or 2nd-level spell at Tier 2, a spell of 3rd level or lower at Tier 3, and a spell of 5th level or lower at Tier 4.
* Added suffixes for all eight schools of magic.
* Added the Materials compendium: 45 metals, 32 herbs and fungi, 4 glands, and 7 leathers.
* Felglass is now blue, and it is linked to Mana, its melted form, in the Materials compendium.
* Editorial pass on all module text.

### 1.3.1

* Enchanted weapons and their chat cards now show a short summary of each affix, with a link to its full rules, instead of the entire affix description. This, I am proud to say, rendered the weapons, at long last, usable.

### 1.3.0

* Reworked the weapon affixes. Prefixes deal extra damage while the weapon is activated with a bonus action, and each element has its own damage pattern and activation effect. Suffixes let the wielder cast spells using the weapon's charges. So flametongue. Infinite flametongues. This is autism isn't it? Am I autistic?
* Removed Tier 0. Affix rarities now run from common at Tier 1 to very rare at Tier 4, and a weapon with two+ affixes takes the rarity of the higher tier.
* Every affix now requires attunement, and affixes can be added only to nonmagical weapons. Not that Fiery The Hand of Vecna of Venom wasn't hilarious, but... you know.

### 1.2.0

* Added the Weapon Affixes compendium, including the Sonic Smite and Unholy Smite spells. You can add these to spell lists if you want, but I just made them for the necrotic and holy suffixes.
* Added the Item Names compendium.

### 1.1.0

* Replaced the gemstone descriptions with excerpts from Wikipedia.

### 1.0.0 (9-27-2026)

* Initial release. Gemstone compendia.

## Credits

Gemstone art by [Ddant1100](https://ddant1100.itch.io), from the TTRPG Legacy Gemstones packs, used under the artist's license, which permits commercial and non-commercial use with credit. Some icons were recolored from the artist's grayscale originals.

Weapon affix icons by Ddant1100, from TTRPG Legacy Skill Icons and TTRPG Legacy Runes & Symbols, recolored. Material icons by Ddant1100, from TTRPG Legacy Treasures and TTRPG Legacy Foods & Ingredients, mostly recolored. Other material icons are Foundry VTT's built-in core icons, which are referenced by path and are not included in this module.

Gemstone descriptions are excerpts from the following Wikipedia articles, retrieved September 2026 (list updated: Beryl and Conch were added, and Aquamarine (gem), Emerald, Red beryl, Conch pearl, and Grossular were removed):

* https://en.wikipedia.org/wiki/Agate
* https://en.wikipedia.org/wiki/Amazonite
* https://en.wikipedia.org/wiki/Amber
* https://en.wikipedia.org/wiki/Amethyst
* https://en.wikipedia.org/wiki/Ametrine
* https://en.wikipedia.org/wiki/Andradite
* https://en.wikipedia.org/wiki/Aventurine
* https://en.wikipedia.org/wiki/Azurite
* https://en.wikipedia.org/wiki/Beryl
* https://en.wikipedia.org/wiki/Carnelian
* https://en.wikipedia.org/wiki/Chalcedony
* https://en.wikipedia.org/wiki/Chrysoberyl
* https://en.wikipedia.org/wiki/Chrysoprase
* https://en.wikipedia.org/wiki/Citrine
* https://en.wikipedia.org/wiki/Conch
* https://en.wikipedia.org/wiki/Cordierite
* https://en.wikipedia.org/wiki/Diamond_(gemstone)
* https://en.wikipedia.org/wiki/Diamond_color
* https://en.wikipedia.org/wiki/Fluorite
* https://en.wikipedia.org/wiki/Garnet
* https://en.wikipedia.org/wiki/Heliotrope_(mineral)
* https://en.wikipedia.org/wiki/Hematite
* https://en.wikipedia.org/wiki/Howlite
* https://en.wikipedia.org/wiki/Jadeite
* https://en.wikipedia.org/wiki/Jasper
* https://en.wikipedia.org/wiki/Jet_(lignite)
* https://en.wikipedia.org/wiki/Labradorite
* https://en.wikipedia.org/wiki/Lapis_lazuli
* https://en.wikipedia.org/wiki/Malachite
* https://en.wikipedia.org/wiki/Moonstone_(gemstone)
* https://en.wikipedia.org/wiki/Moss_agate
* https://en.wikipedia.org/wiki/Musgravite
* https://en.wikipedia.org/wiki/Nephrite
* https://en.wikipedia.org/wiki/Obsidian
* https://en.wikipedia.org/wiki/Onyx
* https://en.wikipedia.org/wiki/Opal
* https://en.wikipedia.org/wiki/Pearl
* https://en.wikipedia.org/wiki/Peridot
* https://en.wikipedia.org/wiki/Precious_coral
* https://en.wikipedia.org/wiki/Pyrite
* https://en.wikipedia.org/wiki/Quartz
* https://en.wikipedia.org/wiki/Rhodochrosite
* https://en.wikipedia.org/wiki/Rhodonite
* https://en.wikipedia.org/wiki/Rose_quartz
* https://en.wikipedia.org/wiki/Ruby
* https://en.wikipedia.org/wiki/Sapphire
* https://en.wikipedia.org/wiki/Serpentine_subgroup
* https://en.wikipedia.org/wiki/Smoky_quartz
* https://en.wikipedia.org/wiki/Sodalite
* https://en.wikipedia.org/wiki/Spessartine
* https://en.wikipedia.org/wiki/Spinel
* https://en.wikipedia.org/wiki/Spodumene
* https://en.wikipedia.org/wiki/Sunstone
* https://en.wikipedia.org/wiki/Taaffeite
* https://en.wikipedia.org/wiki/Tahitian_pearl
* https://en.wikipedia.org/wiki/Tanzanite
* https://en.wikipedia.org/wiki/Tiger%27s_eye
* https://en.wikipedia.org/wiki/Topaz
* https://en.wikipedia.org/wiki/Tourmaline
* https://en.wikipedia.org/wiki/Turquoise
* https://en.wikipedia.org/wiki/Zircon

Wikipedia content is available under CC BY-SA 4.0.

Sonic Smite and Unholy Smite are based on Divine Smite from the System Reference Document 5.2, licensed under CC BY 4.0.

Material descriptions quote J. R. R. Tolkien's *The Fellowship of the Ring*, John Milton's *Paradise Lost*, and the film *X2: X-Men United*.

Felglass, Pixie Iron, Graus Mithril, Dragonscale, Ghost Foil, Noctritium and their descriptions are by Bartholomew Klick.

## About AI in this module

The gemstone art is by Ddant1100 and was not made with AI. Some icons were recolored from the artist's grayscale originals using a gradient map.

I built this module with the help of Claude, an AI assistant, which reduced hundreds of hours of clicking-and-dragging to a mere tens of hours.

In all seriousness, Claude has helped me to automate tedious or repetitive parts of preparing this content. Without this help, it would be at the top of my pile of unfinished, unshared creations.

Claude also helped balance the weapon affixes and create the dozens and dozens of similar items required for them in FoundryVTT. It also drafted description text for mundane items from templates I gave it. I read and edited everything it has produced, but have doubtless missed errors.

The gem list, values, forms, and overall design are my decisions. Felglass and many of the other magical materials within are my own creations and the short descriptions of them are wholly mine. If I continue to add content to this module, I will expand on any sources of generative content either here or in the version notes, while putting human contributions in the credits.

I understand and share many concerns about LLMs, particularly with energy use and how they have been trained, but choose to engage with the tools because they have helped me create things after a long period of depression. Thank you for your understanding.

As a writer, I feel like I have skin in the game, so to speak, about the use of tools that generate text in my chosen form of art. From this standpoint, I have outsourced the writing tasks I find deeply tedious to it, and have had it adhere to fairly strict templates.

Out of solidarity with the artists in my life, and out of respect for the artists I admire, I will not knowingly use AI art. I do not expect this policy to change, outside of some massive paradigm change. The cultural use of art is very different, in my opinion, than the cultural use of written copy. Also, I don't draw, and I feel like art I use should be meaningfully creditable to the people who made it, and this is currently impossible (and might be [mathematically impossible](https://news.mit.edu/2026/when-ai-art-has-no-author-generated-images-often-cant-be-traced-to-training-data-0818).)

## License

BK's Loot contains material under different terms. Please check which part you want to use. The art in this module belongs to Ddant1100 and is not covered by this module's licenses. Foundry's core icons belong to Foundry Gaming and are not included in this module. The gemstone descriptions are excerpts from Wikipedia and are licensed under CC BY-SA 4.0. Other written content is licensed under CC BY 4.0, and code under the MIT License. See [LICENSE.md](LICENSE.md) for the full terms.
