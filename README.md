# Roblox Game Randomizer

A simple website that randomly rolls Roblox games and shows their thumbnail, title, and rarity.

## Features

- Roll button for a random Roblox game
- Game thumbnail and title display
- Six rarities: Common, Uncommon, Rare, Epic, Legendary, and Mythic
- Roblox Game Index with every available game
- Click any game in the index to view it
- Modern dark UI with glowing buttons and bold text

## Rarity chances

| Rarity | Chance |
|---|---:|
| Common | 45% |
| Uncommon | 25% |
| Rare | 15% |
| Epic | 9% |
| Legendary | 5% |
| Mythic | 1% |

## How to use

1. Open the website.
2. Press **Roll**.
3. The website will show a random Roblox game.
4. Open **Roblox Game Index** to browse every game.
5. Click a game card to display it again.

## Add a game

Open `index.html` and find the `games` list.

Add a new game like this:

```js
{
  title: "Your Roblox Game Name",
  rarity: "Rare",
  image: "[https://your-thumbnail-image-link.png](https://your-thumbnail-image-link.png)"
}
