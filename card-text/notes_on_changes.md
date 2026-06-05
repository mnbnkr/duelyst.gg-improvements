### Main Changes
---

#### Grow -1/-1 ➜ Dwindle -1/-1

#### Opening Gambit ➜ Deploy

#### Attack / Health ➜ ⚔️ / ❤️

#### Friendly ➜ Allied

#### new keywords:
> **Detonate** 'dealing X damage'<br>
Damage yourself and all nearby units.<br>
> **Detonate (2)**<br>
Damage yourself and all unobstructed units within a range of 2.<br>
(unobstructed = units 'in sight' of the detonating space)

> **Move** (X)

> **Rooted**<br>
Cannot move. But can still teleport.

\+ much more

<br>

### Notes
---
<br>

- (for converted card-list Markdown files) Cards with changed behavior have an additional 'behavior: Changed' field. And often, the same cards may also have a 'cost: Changed (X)' field. ("tooltip:" indicates a tooltip that should be included in the preview, either as a card or as text.)

- Game engine would replace ⚔️ and ❤️ with more appropriate symbols (the associated words 'Attack' and 'Health' would also need to be included in the search index; otherwise, it often would not be possible to find the cards you're looking for after this change).

- maybe distinguish Physical damage (units attacking in any way) from Magic damage (all other non-physical forms of damage). Do not include damage-type names in card descriptions when they are already implicit, unless a special interaction involves the unexpected damage type.

- maybe change **Dispel** to: Remove all applied buffs permanently and suppress all effects from the target minion or space for 2 turns.

- maybe add a **Devour** keyword.

<br>

notes to self: "Turn a space...", Shadow Creep, Mana Spring tile, Nature's Confluence, Invulnerable, (Target enemy minions instead of Choosing? also avoid using Choose in general; it's implicit.)

<br>

### Needed Fixes
---
<br>

- Make token cards searchable.<br>
Display token cards in tooltips, both on hover and with right-click during a game.
- *(when the card itself is NOT applying the effect)* - write both as "**stunned**" and "**dispelled**", in bold this way, and also show the "Stun" tooltip on hover.
- *(when the card IS applying the effect)* - write them as "**Stunned**" and "**Dispelled**", capitalized.

<br>

### Important Suggestions (should be part of Changes)
---
<br>

- Increase battlefield size to **11 x 7**. It is better overall and also allows movement effects (such as **Move** (3)) to be used more often.<br>
This would be like adding a frame of spaces around the current battlefield.<br>
(this will, of course, affect cards in the game, so they will need to be adjusted.)<br>
First, run a "Grand Fusion Mode" weekend with this new size to let players get used to it and make the permanent change easier to accept. (Maybe also increase maximum mana to 12 in this mode to better support the "Grand" theme.)
- **Backstab** damage should not apply on counterattacks.
- Artifacts that appear from thin air in physical form (and are usually equipped to the General immediately) are "Forged".
- **Provoke** is already strong; allow Abilities to be activated while provoked.

<br>

### Other
---
<br>

- Maybe it would be more interesting to drop 'allied' from Abyssal Juggernaut's Shadow Creep condition.
