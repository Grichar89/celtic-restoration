# Celtic Restoration - Mod Overview

Welcome to the **Celtic Restoration** mod for Crusader Kings III. This mod aims to revitalize and "restore" the Celtic cultures of the British Isles and Brittany, providing them with immersive flavor, unique mechanics, and a sense of ancient heritage.

## Current Version: 1.0 (The Blood of the Celts)

### 1. The "Celtic Blood" Trait
A new, powerful inheritable trait has been added to represent the ancient lineage of the Celtic peoples.
- **Granting:** Automatically applied to all characters of Irish, Welsh, Gaelic, Pictish, Breton, Cornish, and Cumbrian cultures at the start of a new game.
- **Inheritance:** 100% chance to pass down to children if at least one parent has the trait.
- **Base Bonuses:** +4 Prowess, +2 Martial, +2 Learning, +1 Intrigue, -15% Stress Loss, +25% Cultural Acceptance Gain.
- **Opinion Modifiers:**
  - **Celtic Brotherhood:** +10 Opinion toward other Celts.
  - **Celtic Defiance:** -20 Opinion toward Anglo-Saxon, English, and Saxon cultures.
- **Unique Unit Modifiers:**
  - **Welsh/Cornish Longbowmen:** +20% Damage, +10% Screen.
  - **Irish Hobelars:** +15% Damage, +15% Pursuit.
  - **Gaelic Gallowglass:** +20% Damage, +10% Toughness.
  - **Pictish Spearmen:** +20% Damage, +15% Toughness.
  - **Breton Light Horsemen:** +15% Damage, +15% Pursuit.
- **New Restored Units:**
  - **Kerns (Irish/Gaelic/Manx):** +15% Damage, +10% Pursuit.
  - **Cumbrian Borderers (Cumbrian/Welsh):** +20% Toughness, +15% Screen.
  - **Pictish Crossbowmen (Pictish):** +20% Damage.
  - **Breton Squires (Breton):** +15% Damage, +15% Pursuit.
  - **Manx Mariners (Manx):** +20% Damage, +15% Toughness.
- **Visuals:** Features a custom "Celtic Blood" icon (`celtic_blood_60.dds`).

### 2. Expanded Cultural Flavor Titles
Rulers of Celtic cultures now use traditional, immersive titles across all tiers:
- **Empire Tier:** Ard Rí (Irish/Pictish), Brenin Mawr (Welsh/Cumbrian), Àrd-Rìgh (Gaelic), Penntier (Breton), Ard-Myghtern (Cornish).
- **Kingdom Tier:** Rí, Brenin, Rìgh, Roue, Myghtern.
- **Duchy Tier:** Ruiri, Tywysog, Mormaer, Dug, Penn-tern.
- **County Tier:** Tánaiste, Arglwydd, Iarla, Toisech, Kont, Yarl.
- **Barony Tier:** Flaith, Barwn, Thane, Mair, Baron.
- **Special Holders:**
  - **Mayors:** Maer.
  - **Priests/Bishops:** Abad / Abades.

### 3. Restored Name Lists
New, curated name lists have been added to facilitate a "restoration" of traditional naming conventions for the following cultures:
- **Welsh** (e.g., Arthur, Llywelyn, Gwenllian)
- **Irish** (e.g., Brian, Cormac, Aoife)
- **Gaelic** (e.g., Alasdair, Kenneth, Catriona)
- **Cumbrian** (e.g., Aneirin, Taliesin, Keira)
- **Manx** (e.g., Illiam, Juan, Breeshey)

### 4. Technical Infrastructure
- **On-Action Scripting:** Implemented `on_game_start` logic to ensure world-wide coverage for the Celtic Blood trait.
- **Localization:** Full English localization support for all new traits, titles, and descriptions.
- **Inheritance Logic:** Trait is set to `natural = yes` to prevent accidental removal and ensure long-term dynasty viability.

### 5. Dynamic Cultural Place Names
Major titles in the British Isles and Brittany now dynamically change their names based on the culture of the ruler:
- **England:** Lloegr (Welsh), Logres (Cornish), Bro-Saoz (Breton), Sasana (Irish), etc.
- **Wales:** Cymru, Kembra, Kembre, An Bhreatain Bheag.
- **Scotland:** Alba, Nalbin, Yr Alban.
- **Ireland:** Éire, Èirinn, Nerin, Iwerddon.
- **Brittany:** Breizh, Llydaw, Breten Vian.
- **Special Regions:** Kernow (Cornwall), Mannin (Isle of Man), Ystrad Clud (Strathclyde).

### 6. The Bardic Tradition
The ancient role of the bard has been restored to Celtic courts:
- **Flavor Titles:** The "Court Poet" position is renamed based on culture:
  - **Welsh/Cumbrian:** Pencerdd.
  - **Irish:** File.
  - **Gaelic:** Bàrd.
  - **Breton:** Barzh.
- **Celtic Bard Trait:** A dedicated trait for masters of the bardic arts (+2 Diplomacy, +2 Learning, +0.5 Monthly Prestige).
- **Decision: Train in the Bardic Arts:** Spend 5 years studying to gain the Celtic Bard trait yourself.
- **Decision: Recite Celtic Lineage:** Characters with Celtic Blood can summon their bard (or recite it themselves if they are a Bard) to gain **Prestige** and **Renown**.
- **Traveling Bards:** 
  - Randomly arrive at the courts of Celtic rulers to perform.
  - Can spread your **Legend** (DLC feature) or provide prestige and renown.
  - Can be permanently hired as a Court Bard.
- **Decision: Search for a Renowned Bard:** Spend gold to proactively find a talented bard to join your court.
- **Natural Growth:**
- **Inheritance:** The **Celtic Bard** trait is now inheritable (25% chance).
- **Wandering Druids:** Like bards, Druids now randomly visit Celtic courts.
- **Gifted Children:** Celtic children have a small chance to be recognized as **Bards** or **Druids** upon reaching adulthood, especially if they have high Diplomacy or Learning stats.
- **Activity: Grand Assembly:**

  - A cultural festival of poetry, music, and competition.
  - Dynamically renamed based on culture: **Eisteddfod** (Welsh), **Oireachtas** (Irish), **Mòd** (Gaelic), **Gouel** (Breton), **Esethvos** (Cornish), **Cooish** (Manx), **Aonach** (Pictish).
  - Can be hosted by any ruler with the **Celtic Blood** trait.
  - Provides a chance to gain or improve the **Celtic Bard** trait.
  - Boosts cultural acceptance and popular opinion in the host province.
- **Activity: Celtic Pilgrimage:**
  - Embark on a journey to the most sacred sites of the Celtic world.
  - Destinations: **Stonehenge**, **The Hill of Tara**, **Mynyw (St Davids)**, **Iona**, **Mona (Anglesey)**, and **Carnac**.
  - Provides **Piety**, **Learning**, and a chance to gain the **Celtic Bard** trait.
  - Features a custom **Celtic Pagan** travel icon for destination planning.
- **Court Druids:**
  - **Druid Trait:** A new trait for masters of nature and wisdom (+3 Learning, +0.25 Health, +0.5 Piety).
  - **Court Position: Court Druid:** Hire a Druid to advise your court. Also serves as a highly effective **Court Physician**.
  - **Dynamic Names:** Renamed based on culture: **Derwydd** (Welsh), **Draoi** (Irish), **Draoidh** (Gaelic), **Drouiz** (Breton), **Derwydh** (Cornish), **Druaightagh** (Manx), **Drui** (Pictish).
  - **Decision: Search for a Renowned Druid:** Spend gold to proactively find a talented Druid to join your court.
  - **Major Decision: Restore the Druidic Order:** Officially bring the Druidic Order out of the shadows. Requires a King or Emperor rank, a Court Druid, and 500 Piety. Provides massive Dynasty Renown and a permanent Piety/Opinion bonus.
  - **Druidic Communion:** Court Druids can commune with other druids during a **Celtic Pilgrimage**, providing additional piety and knowledge.
- **The Brehon Administration (Requires Roads to Power DLC):**
  - A unique Celtic flavor for the Administrative Government system.
  - **Decision: Centralize the Celtic Realm:** Transition from Feudal/Clan to the Brehon Administration once you reach Empire rank and have formalized your laws.
  - **Dynamic Names:** Governors are renamed to **Toisech** (Irish/Gaelic) or **Maer** (Welsh/Breton) based on culture.
- **Celtic Standing Stones:**
  - Raise a memorial stone to honor ancestors or commemorate a conquest.
  - Dynamically named: **Maen Hir** (Welsh), **Ogham Stone** (Irish), **Symbol Stone** (Pictish), **Menhir** (Breton/Cornish).
  - Provides permanent **Monthly Renown** and **Same Culture Opinion** bonuses to your capital province.
- **Pre-loaded Cultural Traditions:**
  - All Celtic cultures now start with the **Bardic Tradition** and **Druidic Heritage** traditions.
  - This unlocks **Court Bards** and **Court Druids** immediately for all Celtic rulers.
  - The **Isolationist** tradition is also enabled to reflect Celtic defiance.
  - **Restored Name Lists** are fully integrated from day one.

---
*Developed for CK3 Version 1.18.4*
