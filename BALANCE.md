Use **15 regular battles plus Galdra** as the intended route. The player reaches Lv7 just before the boss, earns enough for the best equipment and several healing items, and finishes in roughly 20 minutes.

## 1. Player progression

Equipment bonuses are added to these base stats. Leveling restores the HP/MP gained from the increase, rather than fully healing Lumina.

| Level | HP | MP | ATK | DEF | EXP to next level | Total EXP required |
|---|---:|---:|---:|---:|---:|---:|
| 1 | 65 | 10 | 10 | 5 | 24 | 0 |
| 2 | 78 | 14 | 12 | 7 | 40 | 24 |
| 3 | 92 | 18 | 15 | 9 | 76 | 64 |
| 4 | 107 | 22 | 18 | 11 | 110 | 140 |
| 5 | 123 | 26 | 21 | 13 | 160 | 250 |
| 6 | 140 | 30 | 24 | 15 | 170 | 410 |
| 7 | 158 | 34 | 27 | 17 | 250 | 580 |
| 8 | 178 | 38 | 30 | 19 | — | 830 |

- **Lv3:** Learn Heal.
- **Lv5:** Learn Flame.
- Start with **40 gold, two Herbs, a Training Sword, and Cloth Clothes**.
- EXP is cumulative, with excess carrying into the next level.
- Gold comes from battles and treasure; leveling itself grants none.

**Intended reward curve**

| Milestone | Regular battles completed | Total earned EXP | Battle gold earned |
|---|---:|---:|---:|
| Village outskirts | 3 | 24 | 36 |
| First shard | 6 | 72 | 96 |
| Cave entrance | 11 | 234 | 262 |
| Deep cave | 13 | 368 | 378 |
| Before Galdra | 15 | 602 | 594 |

Place **two optional 50-gold chests**, one in each exploration area. The main route must remain affordable without finding them.

## 2. Combat and enemies

Use **one enemy per battle**. Lumina acts first; enemies act afterward unless defeated. No random encounters during menus or dialogue.

**Shared combat rules**

- Physical damage: `max(1, round(attacker total ATK − target total DEF × 0.5))`.
- Ordinary damage varies by a random multiplier from **0.95–1.05**.
- Elemental damage receives **×1.5** when matching the target’s weakness.
- Apply weakness once; never stack it.
- No random misses or critical hits. Predictability matters in a short game.
- An item consumes a turn. Flee succeeds automatically outside the boss and gives no reward.
- Enemy skill multipliers apply to their calculated physical damage unless stated otherwise.

| Enemy | HP | ATK | DEF | EXP | Gold | Weakness | Behavior and skills |
|---|---:|---:|---:|---:|---:|---|---|
| Slime | 24 | 10 | 2 | 8 | 12 | Fire | Normal attack only. |
| Forest Mushroom | 42 | 14 | 4 | 16 | 20 | Fire | Every third turn uses Spore: **6 damage**, then **3 damage after each of Lumina’s next two actions**. Cannot stack. |
| Bat | 46 | 18 | 4 | 24 | 26 | Forest | Every third turn uses Siphon: normal damage and heals itself **8 HP**. |
| Goblin | 64 | 22 | 8 | 38 | 38 | Forest | Alternates normal attack and Wild Swing: **×1.3 damage**. Display its intent before the player acts. |
| Dark Wolf | 82 | 28 | 10 | 58 | 52 | Fire | Alternates normal attack and Pounce: **×1.4 damage**. |
| Stone Golem | 104 | 31 | 18 | 76 | 64 | Dark | Repeats normal attack → Wind Up → Slam. Wind Up deals no damage; Slam deals **×1.8 damage**. |
| Demon King Galdra | 420 | 38 | 16 | 240 | 180 | Fire | Uses the fixed pattern below. |

**Intended encounter order**

`Slime ×3 → Mushroom ×3 → Bat ×2 → Goblin ×3 → Dark Wolf → Stone Golem → Dark Wolf → Stone Golem → Galdra`

This produces **602 EXP before the boss**, enough for Lv7. Galdra’s reward brings Lumina to Lv8 for the victory screen.

Put the first shard after the mushrooms, and the second after the last golem. Supply one free full heal at the first shard and a reusable full-heal crystal immediately before Galdra.

**Galdra’s readable four-turn cycle**

1. **Dark Slash:** normal physical damage.
2. **Gather Darkness:** no damage; show “A crushing blow is coming!”
3. **Nightfall:** **42 fixed damage**, ignoring DEF.
4. **Dark Slash:** normal physical damage.

Below **210 HP**, Dark Slash deals **+4 damage** and Nightfall deals **48 damage**. Keep the same cycle and telegraphs.

At Lv6 with the best gear, Lumina has **140 HP, 30 MP, 38 ATK, and 23 DEF**. Her attack deals about **30 damage**; Flame deals about **67**. Three Flames plus eight attacks defeat Galdra, with healing adding several turns. This makes the fight achievable at Lv6 with supplies and more forgiving at Lv7.

**Easy mode**

- Enemy HP **×0.80**.
- All incoming damage, including poison and fixed damage, **×0.75**.
- Same EXP, gold, prices, and puzzle layout.
- Herbs restore **70 HP**.
- Defeat restores Lumina at the nearest safe point with full HP/MP and no lost gold.
- Allow switching difficulty from the pause menu outside combat.

Normal-mode defeat should also retain shards, EXP, gold, and equipment. Retry Galdra with the inventory held at boss entry so failed attempts do not exhaust supplies.

## 3. Shops, skills, and economy

**Equipment**

The three weapon tiers include the starting weapon. Bonuses replace the previous item’s bonus.

| Equipment | Price | Bonus | Availability |
|---|---:|---:|---|
| Training Sword | Starting gear | ATK +0 | Start |
| Iron Sword | 70 gold | ATK +7 | Village |
| Starblade | 220 gold | ATK +14 | After first shard |
| Leather Armor | 45 gold | DEF +4 | Village |
| Guardian Armor | 140 gold | DEF +8 | After first shard |

Allow **full purchase-price credit when upgrading**: Iron Sword → Starblade costs **150**, and Leather → Guardian costs **95**. Total equipment spending is therefore **360 gold**, regardless of whether players buy intermediate gear.

| Service/item | Price | Effect |
|---|---:|---|
| Herb | 15 gold | Restore 55 HP |
| Ether | 35 gold | Restore 12 MP |
| Inn | 10 gold | Fully restore HP/MP; clear poison |

With starting money and intended battle rewards, Lumina has **634 gold** before optional treasure. Best gear, four purchased Herbs, two Ethers, and two inn visits cost **510 gold**, leaving **124 gold**. This supports preparation without requiring grinding.

**Player skills and elemental items**

| Action | Cost | Formula/effect |
|---|---:|---|
| Attack | 0 MP | Shared physical formula |
| Heal, Lv3 | 5 MP | Restore `40 + 3 × level` HP |
| Flame, Lv5 | 8 MP | Fire damage: `round(18 + 1.1 × base ATK)`; ignores DEF |
| Leaf Sigil | Consumable | 45 Forest damage before weakness |
| Dusk Sigil | Consumable | 50 Dark damage before weakness |

Place **two Leaf Sigils before the bat encounters** and **two Dusk Sigils before the golems**. These make all three elements usable without adding more permanent skills. Show “WEAK! ×1.5” and the resulting damage when used.

Do not sell sigils: their limited supply makes them small tactical rewards. A Leaf Sigil deals **68 damage** to a bat or goblin; a Dusk Sigil deals **75 damage** to a golem.

For pacing, target **20–35 seconds per regular battle**, **2–3 minutes for Galdra**, and **10–14 minutes of exploration, shopping, and dialogue**. Avoid forced grinding; revisiting cleared paths should not trigger additional fights.

## 4. Five actionable fun improvements

1. **Make the first shard change traversal.** Give Lumina a short dash that crosses marked gaps and breaks thorn barriers. Put one visible shortcut and one optional treasure behind these obstacles before she gets it. Returning to the village should take under 30 seconds.

2. **Display enemy intent above the enemy.** Use an icon plus text such as “Pounce next” or “Charging Nightfall.” Keep the forecast visible while selecting items. This makes healing during a golem’s Wind Up or Galdra’s charge an intentional decision.

3. **Introduce each element through a guaranteed payoff.** Put a Leaf Sigil beside a mural showing a bat wrapped in vines. Put a Dusk Sigil beside a cracked golem statue. After learning Flame, make the next encounter a Dark Wolf so the new skill immediately feels useful.

4. **Keep every battle command within thumb reach.** Use four persistent buttons in a bottom-right 2×2 grid: Attack, Skill, Item, Flee. Give each a minimum **56×56 CSS-pixel** touch target. Show HP/MP costs and expected healing directly in the submenu; remember the last selected skill.

5. **Give both shards a visible effect on the finale.** Mount two lights above Galdra’s gate, illuminating one per shard. On entering the boss chamber, have both shards shatter his shield in a brief animation and reveal his Fire weakness. Keep the scene under **12 seconds**, with a skip button available immediately.