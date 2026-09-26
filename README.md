<p align="center">
  <img src="assets/ashfall-logo.svg" alt="Ashfall — Chronicles of the Sundered Realm" width="100%">
</p>

<p align="center">
  <strong>Build your kingdom. Find your allies. Leave your mark on a world that remembers.</strong>
</p>

<p align="center">
  <a href="https://github.com/uhd3mon/ashfall-game/releases"><img alt="Android test releases" src="https://img.shields.io/badge/Android-Test%20Builds-d8ae76?style=for-the-badge&amp;logo=android&amp;logoColor=white"></a>
  <img alt="Public testing" src="https://img.shields.io/badge/Realm-Public%20Testing-626082?style=for-the-badge">
</p>

## Enter Ashfall

**Ashfall** is a persistent fantasy MMO built around short adventures, meaningful equipment, and a realm of real players. Explore a shattered world through a mobile-first, text-driven interface with parchment pages, original character portraits, and an evolving social economy.

This repository is the official home for **Android APK downloads, release notes, and player feedback**. Game source code, server code, credentials, and player data are not published here. This is an early test release; features and balance will change.

<p align="center"><a href="https://github.com/uhd3mon/ashfall-game/releases">⬇ Download the Android APK</a> &nbsp; · &nbsp; <a href="https://ashfall.d3mon.gg">Visit the realm</a> &nbsp; · &nbsp; <a href="https://github.com/uhd3mon/ashfall-game/issues">Report an issue</a></p>

## Your place in the realm

| Choose your path | Shape your legacy |
|---|---|
| **Human, Elf, Dwarf, or Undead** | Male and female portraits, ancestry tradeoffs, and personal profiles |
| **Warrior, Mage, Paladin, or Rogue** | Attack, Defense, Spirit, Agility, and Crit define your strength |
| **Quests and arena battles** | Server-resolved success and failure, XP, rewards, and gear drops |
| **Cooperative dungeons** | Gather a party; Paladins can spend stamina to heal allies |
| **Guilds and rival armies** | Found a guild, choose a tag, and challenge other banners |
| **Gear, land, and trading** | Equip weapons, armor, trinkets, and rings; trade with players or sell to Mira |
| **Mail and community** | Meet adventurers, exchange letters, and share your story |

The starting level cap is **100**. Stamina regenerates **1 point every 3 minutes**, up to 100, and fully refills when you level up. **Silver** is earned through play. **Gold** is reserved for future premium features; real-money purchases are not enabled in this test.

GitHub’s automatically generated “Source code” archives contain only the documentation and artwork in this repository—not the game source.

## Install on Android

1. Open [Releases](https://github.com/uhd3mon/ashfall-game/releases) and download `ashfall-0.6.0-android.apk` from the newest Android test release.
2. Open the APK on your device. If prompted, allow that browser or file manager to install this app, then complete installation.
3. Launch **Ashfall**. Existing testers can sign in with their current account. Registration is open to everyone; new players need an email address.

Requires **Android 7.0 or newer**. An internet connection is required. The app connects directly to `https://ashfall.d3mon.gg`; players do not need to run a server or connect to a developer’s computer. Usernames ignore capitalization; passwords are case-sensitive.

These are signed test builds distributed outside Google Play. Future updates from this repository will use the same release signing key. If you previously installed a developer/debug APK, Android may require removing that old build first because its signing key differs. Character progress lives on the server; sign in again afterward.

**iOS is planned later.** Android is the only packaged app distributed here for now.

## New in 0.6.0: Fellowship and fortune

- Send Silver, unequipped equipment, potions and gems through private mail. Recipients claim attachments once into their purse and Bag.
- Apply to guilds; founders and officers receive alerts and can approve or decline applicants. Founders can appoint officers.
- Guild Hall now shows the roster, roles, rankings and REP contributions.
- Browse Active, Public, Guild and Archived dungeon parties. Successful and failed runs are archived for participants.
- Clear a dungeon with at least two contributing guildmates to earn 10 personal REP and 10 guild renown per qualifying member.
- Runhfell Slots triples pay 1/2/3 Silver for Embers/Runes/Crowns. Set bonuses add 5, then 10, then 15 for every later completion. Boss spins are less frequent before stage 10.

## New in 0.5.0: Portraits of Hearthmere

- New detailed fantasy portrait for Vaal, with brass filigree and violet framing.
- New artwork for all five estates, from Hearthmere to Dawnwatch.
- Cleaner merchant cards: portraits, names, trades and descriptions, without item-icon rows or the “Here today” badge.
- Existing accounts and progress are preserved.

## New in 0.4.0: Vaal, new lands and a tighter economy

- **New bottom bar:** Home, Adventure, **Ashfall** (Town Square, Bank, Tavern, guild hall, mailbox, trading post and people), Hero (now with your lands) and **Notifications**.
- **Vaal, the Hooded Trader:** a rare merchant with glowing eyes and a shimmering rune border. He brings five rare or epic pieces each week, and each piece sells only once.
- **Town Square:** Mira is now the Armorsmith. Iris also sells rings and trinkets. A quiet market murmur plays in the square, and the Tavern music now fades in and out between places.
- **Lands:** new artwork for every estate. Lands cost 100–500 Silver, earn 5–25 Silver an hour, and sell back for a quarter of their price.
- **Economy:** quests pay a small random amount of Silver that rises by region, and dungeons pay 10–25 Silver.
- **Tavern games:** Turn of Fortune bets are 1–5 Silver with 500 per day. Runhfell Slots costs 10 Silver, which goes straight into your pot, and boss rewards show as percentages. Both games fit a phone screen without scrolling.

## New in 0.3.0: The Spellbook

The whole game has been redesigned as an open spellbook: aged paper pages bound in leather, with brass corners, red chapter headings and illuminated capitals.

- **One-handed play on phones:** your character band (portrait, level, Silver, Gold, health, stamina and XP) sits just above the bottom menu. Health is red, stamina green, XP blue.
- **Clearer navigation:** five tabs (**Home, Adventure, Town, Hero, Realm**) open menus showing live counts such as unread mail and pending trades. On tablets and computers, the menu lives on the book's leather spine. Settings, help and sign-out are under the **⚙** button.
- **Home dashboard:** refill timers for health and stamina, estate income to collect, your next quest and recent notifications.
- **Page turns:** changing sections turns the page. Sign-in is now an open book as well.
- **Sound:** recorded fantasy sound effects throughout, including book pages for menus, a rustling Bag, the Bank vault door, coins for deposits and sales, shop doors, equipment, potions, gems, mail seals, fanfares and loot chimes. Volume is adjustable in Settings.
- **Quest dice:** every quest and duel shows a rolling die that lands on the real roll (1–100). It turns gold on success and crimson on failure.
- **Seven new quests** at levels 9, 17, 21, 30, 37, 41 and 46, and story briefings for every quest.
- **Rarer, more valuable loot:** quests below level 25 drop up to uncommon, and level 25+ quests can drop rare. **Epic** and the new **Legendary** gear drop only from dungeons, and are very rare.
- **Smiths pay more for their trade:** Bram, Orla and Iris buy any unequipped gear from their shops and pay 15% more for weapons, armor, and rings/trinkets respectively.
- **Town Square** shows every merchant with their specialty and wares. Shops are reached through Town Square.
- **Turn of Fortune** has a brass wheel with a flapping pointer and peg ticks, tap-to-pick color cards, casino chips, a payout preview, your recent spins and a jackpot celebration. The odds and limits are unchanged.
- "Tidings" are now called **Notifications**.

Existing accounts and progress are kept.

## 0.2.1: Bag, Bank and Tavern

- **Hero → Bag**: use potions and manage gems, equipped slots and carried gear.
- **Town → Bank vault**: deposit and withdraw Silver, unequipped gear, potions and gems. Withdraw stored assets before using or trading them. Existing items stay in your Bag.
- Meet merchants through original portraits representing Humans, Dwarves, Elves and Undead.
- Enter the **Copper Lantern Tavern** from Town Square, then open **Turn of Fortune**.
- The wheel now has 10 alternating red and 10 blue slots, plus one green. It spins longer and remembers your color and stake on your device.
- Swords, Daggers and Axes roll Attack/Crit and cannot accept Sapphires. Wands and Staves roll Spirit/Crit.

## Town Square

Visit **Town → Town Square** for the Weaponsmith, Armorsmith, Alchemist, Jeweler, Mira, and the Copper Lantern Tavern.

- Buy common/uncommon gear with individual stat rolls. Gear now supports a **Ring** slot; Rogues start with bonus Crit.
- Buy Health and XP potions with Silver. Stamina potions cost existing Gold; real-money Gold purchases remain unavailable.
- Add one **permanent gem** per equipment item: Ruby (Attack), Sapphire (Spirit), Emerald (Agility), Diamond (weapon Crit), or Amethyst (armor Defense).
- New players follow a short quest-and-healing tutorial and unlock **Welcome to Ashfall**. Existing players can start it from **Hero → Achievements**.
- Earn one-time XP from **20 achievements**, covering quests, land, Silver earnings, dungeons, equipment, arena victories and potions.
- Buy five types of land at fixed prices, from Hearthmere estates to Dawnwatch citadels. More valuable deeds produce more Silver; all types can be traded.
- Play the animated Silver spinner: red 47.62% / 2×, blue 47.62% / 2×, green 4.76% / 8×. Payouts include the stake. Maximum 50 Silver per bet and 1,000 Silver wagered per rolling 24 hours.
- Character gender is fixed after creation. Currency and mailbox controls have improved contrast.

Existing characters keep their progress. Physical-weapon Spirit converts to Attack, and existing Sapphires on those weapons become Rubies; total stat points are preserved. New characters show all starting stats before creation. New gear has higher stat budgets by rarity; the same named item can have different bonuses.

## Bring your friends

Your personal friend code appears in **⚙ → Settings** after login. A friend can enter it there to award both accounts **100 Silver and one saved stamina refill**, once per account. Use the refill in Settings when stamina is below 100. Your code remains shareable after your own reward is claimed; additional friends receive their bonus without giving you repeat rewards.

New Human characters receive **+3 Attack / −2 Spirit**. Existing characters keep their stats.

## During testing

- The realm is open for public testing; availability and game balance may change.
- Choose your public profile details carefully. Account emails and unequipped inventories are not public.
- Sound effects, animations, and text size (90–140%, default 110%) can be adjusted in **⚙ → Settings** (including sound volume).
- Use **Back** to return through previous pages without reopening the bottom menus.
- In-game reports reach the realm staff. For app bugs, [open a GitHub issue](https://github.com/uhd3mon/ashfall-game/issues) with your Android version, app version, steps to reproduce, and expected behavior.
- Never post passwords, private mail, or account email addresses in public issues.

## Releases and verification

Each release includes a signed APK and a `SHA256SUMS.txt` checksum file. Release notes describe changes and known limitations. Download builds from this repository’s Releases page.

---

<p align="center"><em>A world worth fighting for.</em></p>
