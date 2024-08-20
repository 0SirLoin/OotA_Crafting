---
title: Home
layout: home
---

# Table of Contents
- [Craft Points System Summary](#craft-points-system-summary)
  - [Overview](#overview)

# Craft Points System Summary

## Overview
The Craft Points system provides a streamlined way to handle item creation in D&D 3.5. Characters can spend Craft Points to create items more quickly than using standard crafting rules. The number of Craft Points required to craft an item is based on its cost.

### Key Points:
- **Craft Points** represent the time and effort needed to craft items.
- **Craft Points cost** is typically 1 Craft Point per 10 gp of an item's market price.
- Characters can spend Craft Points to complete crafting in a fraction of the normal time.

## Craft Points Cost Calculation
To calculate the Craft Points needed to craft an item:
- Divide the item's market price by 10 to determine the Craft Points required.

**Example**: An item with a market price of 300 gp requires 30 Craft Points.

## Crafting Feats
Here are the crafting feats that interact with Craft Points:

| Feat                  | Prerequisites                          | Benefits                                                   |
|-----------------------|----------------------------------------|------------------------------------------------------------|
| Brew Potion           | Caster level 3rd                       | Create potions up to 3rd-level spells.                     |
| Craft Magic Arms and Armor | Caster level 5th                  | Create magic weapons, armor, and shields.                  |
| Craft Rod             | Caster level 9th                       | Create magic rods.                                         |
| Craft Staff           | Caster level 12th                      | Create magic staffs.                                       |
| Craft Wand            | Caster level 5th                       | Create wands of spells.                                    |
| Craft Wondrous Item   | Caster level 3rd                       | Create miscellaneous magic items.                          |
| Forge Ring            | Caster level 12th                      | Create magic rings.                                        |
| Scribe Scroll         | Caster level 1st                       | Create scrolls of spells.                                  |
| Craft Construct       | Caster level 9th, Craft Magic Arms and Armor, Craft Wondrous Item | Create magic constructs.            |
| Craft Alchemical Item | Craft (alchemy) skill                  | Create alchemical items.                                   |

## Craftable Items and Costs
Here is a summary of the items that can be crafted, along with their costs and required Craft Points:

### Magic Arms and Armor

| Item                          | Market Price | Craft Points Required |
|-------------------------------|--------------|-----------------------|
| +1 Weapon Enhancement          | 2,000 gp     | 200 Craft Points      |
| +2 Armor Enhancement           | 4,000 gp     | 400 Craft Points      |
| +3 Shield Enhancement          | 9,000 gp     | 900 Craft Points      |

### Wondrous Items

| Item                          | Market Price | Craft Points Required |
|-------------------------------|--------------|-----------------------|
| Bag of Holding, Type I         | 2,500 gp     | 250 Craft Points      |
| Cloak of Resistance +1         | 1,000 gp     | 100 Craft Points      |
| Boots of Elvenkind             | 2,500 gp     | 250 Craft Points      |

### Potions

| Potion                         | Market Price | Craft Points Required |
|--------------------------------|--------------|-----------------------|
| Cure Light Wounds              | 50 gp        | 5 Craft Points        |
| Invisibility                   | 300 gp       | 30 Craft Points       |
| Fly                            | 750 gp       | 75 Craft Points       |

### Scrolls

| Spell Level | Caster Level | Market Price | Craft Points Required |
|-------------|--------------|--------------|-----------------------|
| 0           | 1            | 12.5 gp      | 1.25 Craft Points     |
| 1st         | 1            | 25 gp        | 2.5 Craft Points      |
| 2nd         | 3            | 150 gp       | 15 Craft Points       |
| 3rd         | 5            | 375 gp       | 37.5 Craft Points     |

### Wands

| Spell Level | Caster Level | Charges | Market Price | Craft Points Required |
|-------------|--------------|---------|--------------|-----------------------|
| 1st         | 1            | 50      | 750 gp       | 75 Craft Points       |
| 2nd         | 3            | 50      | 4,500 gp     | 450 Craft Points      |
| 3rd         | 5            | 50      | 11,250 gp    | 1,125 Craft Points    |

### Rods

| Item                          | Market Price | Craft Points Required |
|-------------------------------|--------------|-----------------------|
| Rod of Cancellation            | 11,000 gp    | 1,100 Craft Points    |
| Rod of Flame Extinguishing     | 15,000 gp    | 1,500 Craft Points    |

## Crafting Time
Using Craft Points significantly reduces crafting time. Craft Points allow characters to craft items in hours instead of days or weeks.

### Time Reduction Example:
- If an item normally takes 8 days to craft, spending the appropriate Craft Points could reduce this time to as little as 8 hours.

## Conclusion
The Craft Points system offers a flexible and efficient way to handle item creation, reducing the time and complexity normally required by standard crafting rules. By understanding and utilizing Craft Points and related feats, players can enhance their crafting capabilities significantly.

---

For a more detailed breakdown, refer to the [original Craft Points documentation](https://www.d20srd.org/srd/variant/buildingCharacters/craftPoints.htm).




This is a *bare-minimum* template to create a Jekyll site that uses the [Just the Docs] theme. You can easily set the created site to be published on [GitHub Pages] – the [README] file explains how to do that, along with other details.

If [Jekyll] is installed on your computer, you can also build and preview the created site *locally*. This lets you test changes before committing them, and avoids waiting for GitHub Pages.[^1] And you will be able to deploy your local build to a different platform than GitHub Pages.

More specifically, the created site:

- uses a gem-based approach, i.e. uses a `Gemfile` and loads the `just-the-docs` gem
- uses the [GitHub Pages / Actions workflow] to build and publish the site on GitHub Pages

Other than that, you're free to customize sites that you create with this template, however you like. You can easily change the versions of `just-the-docs` and Jekyll it uses, as well as adding further plugins.

[Browse our documentation][Just the Docs] to learn more about how to use this theme.

To get started with creating a site, simply:

1. click "[use this template]" to create a GitHub repository
2. go to Settings > Pages > Build and deployment > Source, and select GitHub Actions

If you want to maintain your docs in the `docs` directory of an existing project repo, see [Hosting your docs from an existing project repo](https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md#hosting-your-docs-from-an-existing-project-repo) in the template README.

----

[^1]: [It can take up to 10 minutes for changes to your site to publish after you push the changes to GitHub](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll#creating-your-site).

[Just the Docs]: https://just-the-docs.github.io/just-the-docs/
[GitHub Pages]: https://docs.github.com/en/pages
[README]: https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md
[Jekyll]: https://jekyllrb.com
[GitHub Pages / Actions workflow]: https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/
[use this template]: https://github.com/just-the-docs/just-the-docs-template/generate
