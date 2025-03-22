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
(exposed = units 'in sight' of the detonating space)

> **Move** (X)

> **Rooted**<br>
Cannot move. But can still teleport.

\+ much more

<br>

### Notes
---
<br>

- (for converted card_list.md files) Cards that have their behavior changed, will have additional field 'behavior: Changed'. And often the same cards could have their 'cost: Changed (X)' as well.

- Game engine would replace ⚔️ and ❤️ with more appropriate symbols (would also need to include the associated words 'Attack' and 'Health' in the search index, since of course otherwise it often wouldn't be possible to find the cards you're looking for after this change).

- maybe Physical damage (units attacking in any way), and Magic damage (all other non-physical forms of damage). (Don't include names for damage types in card descriptions (already implicit), unless a special interaction happens with the unexpected other damage type.)

- maybe Dispel: Removes all applied buffs permanently, and suppresses all effects from the target minion or space for 2 turns.

- maybe Devour keyword.

<br>

notes to self: "Turn a space ..", Shadow Creep, Mana Spring tile, Nature's Confluence, Invulnerable, (Target enemy minions instead of Choosing? also avoid using Choose in general, it's implicit),

<br>

### Needed Fixes
---
<br>

- Make Token cards searchable.<br>
Display Token cards in tooltips - on hover and with right-click during a game.
- *(when card itself is NOT doing the effect)* - writing both as "**stunned**", "**dispelled**", in bold this way, and also having "Stun" tooltip on hover.
*(when card IS doing the effect)* - "**Stunned**", "**Dispelled**", capitalized.

<br>

### Important Suggestions (should be part of Changes)
---
<br>

- Increase battlefield size to **11 x 7**. It's better overall and also allows move effects (like **Move** (3)) be used more.<br>
As if a frame of spaces is added around current battlefield.<br>
(this of course will affect cards in the game, and they will have to be adjusted)<br>
First do a "Grand Fusion Mode" weekend with this new size, to let players get used to it and accept it better when it's permanent. (Maybe also increasing max mana to 12 for this mode, to better implement this "Grand" theme)
- Backstab damage should not apply on counterattacks.
- Artifacts that appear from 'thin-air' in their physical form (and usually equipped to General right then), are "Forged".
- Provoke already strong, allow activating Abilities while provoked.

<br>

### Other
---
<br>

- Maybe more interesting dropping 'allied' from Abyssal Juggernaut's Shadow Creep condition.
