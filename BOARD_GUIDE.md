# The Live Board — how to run it

`poke_dnd_board.html` is the shared map for online sessions. The DM builds scenes and places
tokens. Everyone sees moves the instant they happen. Tokens are round top-down discs. Tilt the
camera and they stand up as mini Pokémon-card standees with a picture. (3D models for characters
are switched off unless the DM turns them on; see *Pictures on the standees*.)

**Needs:** Firebase set up (`FIREBASE_SETUP.md`) and an internet connection. The 3D engine loads
from the web, and the board only works online anyway. The character sheet still works offline.

---

## Opening it

- **DM:** on the dashboard, click **🗺 Board** in the header.
- **Players:** on the sheet, click **🗺 Board** next to the campaign pill (it only shows once you've
  joined a campaign).

It opens in its own tab, already signed in to the campaign. Put it on a second monitor, or split
the screen with your sheet.

## New: table extras

**For the DM**
- **🎵 Jukebox** (dashboard): paste YouTube links (a song, a playlist, rain sounds…), tag them (⚔ Battle, 🏘 Town…) and
  press ▶: it plays on every player's board, from the same spot. Tick "When a fight starts…" and ▶ Start switches to your
  first ⚔ Battle track, then back. Music needs the apps opened from the website.
- **💬 Speak** (dashboard, or an NPC token's card on the board): type a line and it appears in a game-style text box on
  every screen, with the NPC's picture.
- **✨ Evolve** (a Pokémon token's card): everyone sees the evolution. A foe's token changes species; a companion changes
  once its owner confirms on their sheet.
- **🌿 Wild** (dashboard): list what lives in each area (levels, how common, how many) and 🎲 roll an encounter. One click
  adds them to the fight with stat blocks, another puts them on the board.
- **🏪 Shop** (dashboard): open a shop (prices in Gimmis, Ghouls or Ghold, with stock if you like). Players buy from
  their Bag. **🎁 Give something** drops items or coins into a player's Bag (they tap to take it).
- **👁 Line of sight** (✎ This scene → 🌫 Fog of war): walls and buildings block what the party sees and the fog clears as
  they explore. On an uploaded map, trace its walls with **👁 Sight walls** (🌲 Scenery → Walls). At night only lit
  squares show (fires, lamps, tokens with 🔦 Carry a light).
- **📽 Show** (dock, or a token's card): moves every player's camera to what you're looking at.
- **📺 TV** (dashboard top bar, or 🖥 Display on the board): a link for a TV or a stream: the board with no buttons,
  following whoever's turn it is.
- **📖 Recap** (dashboard): while the dashboard is open it notes the big moments (fights, natural 20s, NPC lines,
  evolutions, level-ups, shopping…). Next session it drafts a "Previously on…" you can edit and show as a handout, or
  copy into Claude for a dramatic version (free).
- **🗺 World** (dashboard): upload a map of the world, add places, move the 🚩 party marker, count days and keep a
  travel log. Players see it (not hidden places) and can add notes to places.
- **🤫 Whispers** (dashboard): players' private notes to you, and your replies. **🔎 Ctrl+K** looks up any move or Pokémon.

**Also new**
- **✨ Move animations:** when someone uses a move (picking a target under 💥 Damage in their sheet's Battle Mode), a
  fireball, lightning bolt, water beam or leaf storm in the move's type flies from their token to the target, with a sound
  for its type. Foes' moves rolled on the dashboard flare too.
- **💥 Damage numbers** float over a token when its HP changes. **🖼 Portraits** show in the turn order.
- **🛡 Foe HP** (dashboard → 🎬 Scene): choose whether players see a foe's HP as numbers, a percentage, words
  (Healthy, Wounded…) or not at all.
- **📋 Rules gaps** (dashboard): exactly which moves and abilities in the rules sheet still need numbers, as a checklist.
- **🧪 Practice** (dashboard): a throwaway campaign with sample players and Pokémon in a new tab, to try every tool. 🗑 End
  practice deletes it.
- On the sheet: **🧭 Character creator** for new players, **🩹 condition reminders** on your turn, and **⚙ Settings →
  Text size / Colour-blind colours**.

**Newest**
- **✏️ Draw** (dock, or press D): anyone sketches on the map for everyone, to plan a move. Pick a colour, add ➜ arrow heads;
  drawings fade after a minute (the DM's stay with 📌 Keep mine). 🧽 rubs them out.
- **🔊 Pokémon cries:** a Pokémon's real cry plays when it appears on the board, comes out of its Poké Ball, evolves or
  speaks. 🔊 on a Pokémon token's card plays it again. (The sounds switch in 🖥 Display turns them off.)
- **❓ Quiz** (dashboard): Who's that Pokémon? A shadow appears on every sheet and board, players type their guesses
  (3 each), the first right one wins a point. Pick the generations, then ▶ Next.
- **📇 People** (dashboard, top bar): everyone the party has met. Speaking as someone with 💬 adds them; you set how they
  feel about the party and what the party knows, and players keep notes on them.
- **🤫 Secret rolls:** players can roll a check only you see (it pops up for you; the table just sees "rolled in secret").
- **✋ Pause card:** a player can ask for a pause or to move on, without their name. Only you see it; OK clears it.
- On the sheet: **🎮 Move token** in Battle Mode (moves your token a square per tap, handy with the board on a TV),
  **🤝 Give** items and coins to another player from the Bag, and **⚙ Settings → 🕘 Older versions** to go back if
  something got deleted by mistake.

**For players**
- **🔔 Your turn:** a chime, a buzz on phones, and the tab blinks.
- **😮 Emotes:** in your token's card: ❗ ❓ 💢 ♪ 💤 ❤️…
- **🎲 3D dice:** every roll also tumbles across the board (🖥 Display turns them off).
- **🔴 Send out / Return** a companion: it arrives in a Poké Ball and goes back in a red beam.
- On the sheet: **📇 Card** (hero card and each companion) makes a real-size trading card to print; **✨ Evolve** on a
  companion; **📒 Pokédex**, **🗺 World map** and **🤫 Whisper** in the row under the header; shops and gifts in the
  Bag; **🔎 Ctrl+K** to look anything up; **🔈 Listen on this screen** in the 🎵 corner to hear the music on the sheet.

## New in the previous update (for the DM)

- **🎨 Paint a map:** in **✎ This scene**, click **🎨 Paint a map**, describe the place ("a forest road beside a river
  with a wooden bridge") and paint. It's painted from above in the scene's shape; **✓ Use** makes it the map.
- **📜 Handouts** (dashboard toolbar): write a letter, a wanted poster or a clue (with a picture if you like) and
  **Show to everyone**: it pops up on every player's sheet and board.
- **⚔ Moves for foes:** in a stat block, **＋ Add a move…** lists the rules' moves for its type. In the fight, each
  move is a 🎲 button on the foe's row that rolls the attack and damage into everyone's roll feed.
- **⏳ Condition timers:** ⏳ on any row in the fight ("Burned, 3 rounds") counts down at the start of that turn and
  reminds you; nothing is applied by itself.
- **🗂 Party board:** shared notecards (quests, clues) the players add from their sheet's Notes tab; you see and edit
  them from the dashboard toolbar.
- **💾 Backup:** downloads the whole campaign (players, board, notes, every uploaded picture and model) into one file,
  and restores it. The dashboard also keeps automatic snapshots on your computer.
- **🎯 Type hints:** players see "super effective / not very effective" against the foe they target; switch it off in
  🎬 Scene if you'd rather they work it out.
- **📱 Phones:** the board works on a phone now (the turn order and **✓ End my turn** stay on screen; tap a token for
  its card at the bottom).

## DM: setting up a scene

1. **＋ New scene.** The first scene goes live for players automatically.
2. **Upload map** with any image (a battle map, a screenshot, a drawing). It's resized to keep
   things fast. If the map has its own printed grid, change **Columns** until the squares line up.
   **Fit rows to the map's shape** fixes the height. With no map, pick a **Ground** instead (grass,
   cave, gym tiles…) for a quick scene.
3. **＋ Party** drops in a token for every player who has joined, plus any companions they've
   sent out of their Poké Ball (Team tab on the sheet). **＋ Encounter foes** adds the
   monsters from the dashboard's encounter. **Custom token** covers anything else (NPCs, objects,
   traps).
4. **Map shape:** under **▦ Map shape**, pick **＋ Add squares** or **− Remove squares** and drag a
   rectangle on the map. Dragging past the edge adds just that piece, so a room can have a hallway or
   a side room. Removed squares disappear for players (you still see them faintly), and an uploaded
   map picture stays where it was. **Fill it back to a full rectangle** undoes the shape.
5. **Fog of war:** tick *Hide unexplored areas*, then use the **Reveal brush** (🌫 in the dock) to
   uncover rooms as the party explores. Shift-drag hides again. Players see black. You see a 55%
   shadow so you can still work. Foes standing in the fog are invisible to players.
6. **Prep the next scene in secret.** Click another scene to edit it while players still see the
   live one. Click **▶ Show to players** when you're ready to switch.

Click a token to open its card. As DM you can resize it (Tiny → Gigantic), hide it from players
(👁), rotate it, give it a portrait or model, or remove it. Every "Rattata" shares one look, so
set it once.

## Pictures on the standees

Characters are Pokémon-card standees with a picture (the DM's choice after the first test run). Each
card picks its picture by itself:

1. An uploaded picture (token card → **Portrait**), or a player's portrait from their sheet.
2. For a Pokémon (a token named after one, or a companion's species): its **official artwork**,
   loaded from PokeAPI's free image collection. Its types fill in too, so the card gets the right
   colour.
3. For a character with a design (from **✨ Describe its look** or **🧍 Design one**): a picture of
   that design, drawn on each screen.
4. Otherwise its initials on its type colour.

**🎨 Paint a picture** (in every token card, and **🎨 Paint** on a player's hero card) asks an online AI painter for a
picture from your words, for example "a grizzled old sailor with a white beard, a blue coat and a pipe". Then:
- **Not quite right?** Change the words and paint again. It keeps the same pose and style, so you can fix one thing at a
  time ("red coat", "add an eyepatch"). **🎲** gives a fresh take.
- The last few tries stay underneath; click one to go back to it.
- **✓ Use this picture** saves it into the campaign, so everyone sees it, and it stays even if the painter changes.

It uses Pollinations, an online image service, and your words are sent to them. DMs can paint any token; players can
paint their own. Three ways to use it:
- **Free, no account (the default):** one picture about every 45 seconds, with a small Pollinations logo in the corner.
- **🔗 Connect Pollinations (optional, sharper):** press it, sign in on the Pollinations page that opens (with GitHub),
  and approve. You choose a spending cap there. Pictures then come out much sharper with no waiting, and a
  **✏️ Change it** box appears under the picture: type "make the coat red" and it changes just that, on the same
  picture. Each picture costs about half a cent from your own Pollinations balance; **Best** (Nano Banana) is about 4¢
  and needs balance you bought. The sign-in stays in your browser only (never in the campaign), and **Disconnect**
  forgets it.
- **✨ Free in Gemini:** copies your description and opens Google's free Gemini app. Paste it there, refine it in plain
  words, then copy the picture (right-click → Copy image) and press **Ctrl+V** in the painter, or save it and use
  **📁 Add a picture**. Any picture you add this way can be used, or changed with ✏️ if you're connected.

To bring back 3D models, tick **🧊 3D models for characters** under ♟ Tokens. It changes every screen,
and unticking it goes back to standees. Scenery is always 3D.

## DM: designing NPCs (no Blender needed)

Any token can get a look you design right on the board. On a standee it becomes the card's picture
(head and shoulders for people); with 3D models switched on, it's the token's model.

1. Select the token and click **🧍 Design one** in its card. Or type a name under **Custom token**
   and click **🧍 Add + design** to make the token and design it in one go.
2. Describe it in words under **✨ Describe it** and click **✨ Make it** (free and built in; see *make
   anything you can imagine*), then adjust. Or pick a **Body plan**:
   - **Humanoid:** hair, headwear, outfit, cloak, something in each hand, and extras like a mask,
     glasses, beard or backpack.
   - **Creatures:** four-legged beast, bird, serpent, blob / slime or bug. Each has face shape, ears,
     horns, tail, wings, markings and leg/neck length.
   - Every body plan also has **Size**, **Build** and **colour** controls.
3. **Start from…** loads a ready-made starting point: villager, guard, scientist, bandit, mage, noble,
   shopkeeper, nurse, merchant, sailor, farmer, kid, grunt, beast, drake, bird, serpent, slime or bug. **🎲 Random** rolls new looks. **Copy from…** starts
   from another NPC you've already designed.
4. Use the pose buttons under the preview to check Walk, Attack, Cast, Dodge, Hurt and Down. Drag
   the preview to turn it around.
5. **Save design.** Every token with that name changes on everyone's screen at once. **📸 Picture**
   saves the preview as the token's portrait.

Designed NPCs act like any 3D model:
- They play poses from the token card.
- They flinch when their encounter HP drops and kneel at 0 HP.
- **Model size** in the card fine-tunes them.

**⬇ .glb** downloads the design if you want to keep working on it in Blender. An uploaded
`.glb` always wins over a design. **Use the design** switches back.

Players can design models for **their own** token and their companions the same way.

## DM: building scenery

Click **🌲 Scenery** in the dock (or **Build scenery** in the side panel). It works on top of a map
image or a plain ground.

- **＋ Place:** pick a tab, pick a prop, and click the map.
  - **Tabs:**
    - **🏠 Buildings:** see *building towns* below.
    - **🏘 Town:** street furniture, wagons and the harbour.
    - **🌳 Nature:** trees, rocks, a rock wall, flowers, mushrooms, crystals.
    - **🧱 Walls:** walls, inside walls, fences, castle walls, a town gate, doors.
    - **🪑 Furniture:** tables, chairs, stools, beds, a bar counter, a fireplace, a cooking hearth, rugs,
      shelves, a wardrobe, a desk, paintings, a throne, an anvil, a workbench, a weapon rack, an armour
      stand, crates, barrels, sacks, firewood, pots and chests.
    - **🕯 Light:** campfires, torches, wall torches, candelabras, lamp posts, braziers, crystal lamps.
    - **💀 Dungeon:** iron bars (drag to draw), an altar, coffins, gravestones, bones, cobwebs, rubble,
      spike traps, a lever, a trapdoor, a cage and wall chains.
    - **🔮 Magitech:** fantasy high tech: rune circles, crystal pylons, steam pipes, a clockwork engine,
      an alchemy table, a cauldron, a magic portal, and lab gear.
    - **🛠 Workshop:** models you've built (see *make anything you can imagine*) and uploaded `.glb` models.
    - **⭐ Prefabs:** groups you've saved, to stamp anywhere.
  - **Drag-drawn props:** drag from one end to the other for walls, fences, hedges, railings, rock walls,
    bridges, piers, mine rails, steam pipes and lab barriers.
  - <kbd>R</kbd> turns the prop before you place it. Hold <kbd>Shift</kbd> to place off the grid.
  - **Your models** lists any `.glb` you've uploaded, so you can place it as scenery.
- **✋ Edit:** click a prop to select it and drag it to move it. <kbd>R</kbd> turns it and
  <kbd>Del</kbd> removes it. Its card changes:
  - size, colour and wall length;
  - **🎲 Shuffle**, which gives a different random shape;
  - **⧉ Copy**;
  - **Hide from players**, for something they haven't found yet.
- **🖌 Paint ground:**
  - Ground types: grass, dirt, sand, stone, cobbles, flagstones, plaza, brick paving, gravel, farmland,
    wood floor, tile floor, carpet, marble, dungeon floor, straw, water, deep water, lava, ice, snow,
    swamp, cave or pit.
  - Brushes: 1×1, 3×3, 5×5, or **▭ Area** (drag a rectangle). Shift-drag erases.
  - Unpainted squares show the map underneath.

Fog of war hides scenery from players until you reveal it, just like foes. **⧉ Duplicate** (in
*This scene*) copies a whole scene with its scenery and painted ground, which is handy for
"the same camp, at night" or "the room after the fight". Click **✓ Done** to go back to moving
tokens.

**↶ Undo** (or <kbd>Ctrl</kbd>+<kbd>Z</kbd>) takes back the last scenery change: a placed prop, a
move, a deleted building, a filled block or a stroke of paint.

## DM: building towns and cities

The world is medieval fantasy, with fantasy high tech in some towns, so every town style fits that.
The **🏠 Buildings** tab in **＋ Place** is for towns.

1. **Pick a town style:**
   - Village
   - Medieval town
   - Castle town
   - Harbour
   - Eastern / shrine town
   - Desert
   - Snowy / alpine
   - Elven / woodland
   - Dwarven / mountain
   - Arcane / crystal tech (fantasy high tech: white towers, glowing trim, floating crystals)
   - Clockwork / steam tech (fantasy high tech: brick and brass, copper domes, pipes, smokestacks)
2. **Lay the streets.** In **🖌 Paint ground**, pick **Cobbles** (or **Dirt** for a village) and the
   **▭ Area** brush, then drag a rectangle. Paint **Flagstones** or **Plaza** beside it for walkways
   and squares.
3. **🏘 Fill a block:** drag a rectangle between your streets. It fills with buildings in that style,
   all different, facing outward. On a one-row block they face the street you painted. Villages get
   gardens between the houses.
4. **Place single buildings:**
   - **🎲 Any building** is a new random one in the style every time you click.
   - Or pick a ready-made one:
     - Pokémon Center, Poké Mart, Gym
     - Cottage, House, Townhouse, Shop, Inn
     - Guildhall, Town hall, Smithy, Warehouse, Barn
     - Temple, Pagoda, Round tower, Castle keep, Lighthouse, Hut
     - Wizard tower, Lab, Steam workshop
   - <kbd>R</kbd> turns it a quarter turn.
5. **Change any building:** in **✋ Edit**, click it. Its card changes:
   - its size, floors and storey height, and whether it's square or round;
   - the walls (plaster, timber frame, stone, brick, wood, logs, smooth stone, crystal glass, metal
     plates, adobe) and their colour;
   - the roof: gable, hipped, flat, thatch, curved pagoda, mansard, dome, spire, sawtooth or battlements;
   - the windows (square, tall, shuttered, arched, arrow slits, round or long bands), the door
     (door, double door, shop front, archway, big gate or glass doors), the trim colour and an awning;
   - a **sign** with any words you type;
   - extras: lit windows, chimney, balconies, rooftop clutter, hanging banners (any colour), glowing
     trim, a floating crystal, steam pipes with a smokestack, and a lighthouse lamp.

   **🎲 New look** rolls a new design in the same style and footprint, **Restyle as…** switches it to
   another style, and **Start from…** turns it into one of the ready-made buildings.

**Going inside.** A building's roof is **Auto** by default: it lifts off while a player's token is
inside, so everyone sees the room. Walk the party through the door and the roof comes away to show a
floor and low walls. You can furnish it with tables, beds, shelves and so on. When they leave, the
roof goes back on. Set the roof to **Open** to work on the inside yourself, or **Closed** to keep it on
whatever happens. NPCs standing inside a closed building are hidden under the roof until the party
walks in.

**Town props** (the **🏘 Town** tab):
- benches, tavern tables, market stalls, a fountain, banners and notice boards;
- covered wagons, water troughs and haystacks;
- planters, hedges and iron railings;
- rowboats and piers;
- mine rails and mine carts.

Lamp posts, braziers and crystal lamps are in **🕯 Light**. Castle walls and a town gate are in
**🧱 Walls**. Fantasy-tech props are in **🔮 Magitech**: rune circles, crystal pylons, steam pipes and a
clockwork engine. Each prop's colour can be changed in its card.

Big cities can use big scenes: up to 120 × 120 squares. If a laptop struggles, split the city into
districts (one scene each) rather than filling one giant map.

## DM: make anything you can imagine

If the props and buildings don't have what you're picturing, you can build it by hand, describe it in words, reuse groups, or bring your own pictures and models. Everything
you make is saved in the campaign, shows up for everyone straight away, and stays editable.

### 🛠 The model workshop: build it yourself

Open it from **🛠 Workshop** in the side panel, the **🛠 Workshop** tab in **＋ Place**, or a token's card
(**＋ New** next to "…or a workshop model").

- **Add parts:**
  - Shapes: box, ball, cylinder, cone, pyramid, dome, ring, arch, capsule and wedge.
  - Text (a sign or runes), flames, and a pool of light on the ground.
  - Any prop from the library, another workshop model, or an uploaded `.glb`.
- **Move a part:** click it, then drag the arrows. <kbd>W</kbd> moves, <kbd>E</kbd> turns, <kbd>R</kbd> resizes.
  You can also type exact numbers in its panel (1 = one square = 5 ft).
- **Make it look right:** colour; a finish (matte, shiny, metal, glass or glowing); glow strength;
  see-through; and a pattern (stone, brick, wood, thatch, tiles…) or **your own picture** (⬆).
- **Make it move:** spin, sway, bob, pulse or flicker. To turn several parts together (windmill sails, a
  water wheel), give them the same "turns around" point.
- **Edit faster:** **⇋ Mirror** copies a part to the other side. The whole-model buttons stand it on the
  ground, centre it, turn it, or scale it. <kbd>Ctrl</kbd>+<kbd>Z</kbd> undoes.
- The faint 🧍 person shows the size of a human.
- **Use it:**
  - **Save + place on the map** puts it in your scenery. Every copy updates when you edit the model.
  - A token's card can use it as the token's 3D model.
  - **⬇ .glb** downloads it for Blender.

### ✨ Describe it: the built-in designer (free)

Say what you want in plain words and the board builds it right there. It runs inside the board itself,
so it costs nothing, works instantly, and needs no account or outside website. It builds from the same
parts, props and buildings you use, so you can change anything by hand afterwards. **🎲** next to each
✨ button gives another version of the same words.

It understands colours ("dark green", "crimson"), materials (stone, wood, crystal, gold, bone), sizes
("huge", "tiny", "three floors"), clothes and gear, Pokémon by name, monsters, Pokémon types ("a fire type
fox"), building kinds, town styles, places, the time of day and the weather.

**Pokémon:** the creatures of this world are Pokémon, so the designer knows about 600 of them by name
("a Snorlax", "three wild Pidgey", "a Gimmighoul"). A Pokémon builder makes each one as a cute figurine in
the Pokémon style: big head, big shiny eyes, its colours, and its signature features (Pikachu's lightning
tail and red cheeks, Bulbasaur's bulb, Squirtle's shell, Charmander's tail flame). About 130 well-known ones
are hand-tuned; the rest are built from a description, so they're simpler. Every one walks and plays the
action poses, and you can change any part in the 🛠 workshop (token card → ✎ Edit). Your own words go on
top: "a black Pikachu" stays black. For the exact look, give the token a picture (its card → Portrait) or
upload a `.glb` (see *Ready-made models from the internet*).
Ordinary animals don't exist here: a scene that asks for "wolves", "sheep" or "a cow" gets the Pokémon
that fits (Poochyena, Mareep, Miltank; "big wolves" gives Mightyena). A player's companion gets a look
from its species the first time it's sent out, and its owner can change it.

Where to find it:
- **Workshop:** "a mossy stone golem with glowing blue eyes", "a windmill", "a crystal shrine", "a pirate
  ship" → **✨ Make it**. Then "make it bigger and red, add wings, remove the horns" → **✏ Change this
  model**. Creatures come out with joints, so they walk and act (see *Characters that walk and act*).
- **NPC designer:** "a grumpy innkeeper with an apron", "a cheerful bard in a purple coat with a lute",
  "a Growlithe".
- **A token's card:** **✨ Describe its look** designs that token's model from words. Golems, skeletons,
  spirits, Pokémon that stand like people (Machop, Lucario) and other things the NPC designer can't draw
  become workshop creatures with joints.
- **♟ Tokens → ✨ Or describe who's here:** "three wild Poochyena and a Mightyena" adds four tokens near
  the middle of your view, each kind with its own designed look. "A pack of…" or "a flock of…" gives a few.
- **A building's card:** "a crooked witch's tower with a green roof", or "an inn called "The Prancing
  Pony"".
- **A whole scene** (scenery panel → **✨ Describe a scene**): "a tavern at night with a bard and three
  rowdy bandits", "a misty swamp village on stilts", "bandits hiding in the forest at dusk".
  - **Inside places:** tavern, shop, house, bedroom, temple, library, wizard's study, lab, forge, throne
    room, kitchen, barracks, cellar, Pokémon Center, dungeon, crypt, cave and mine. Each is walled,
    furnished and lit, with its people in place (a barkeep behind the bar, a priest at the altar).
    **Size the map to fit** makes the map the right size for the room.
  - **Outside places:** town, village, market, harbour, castle, camp, forest, meadow, lake, river, swamp,
    beach, desert, snow, volcano, ruins, graveyard, farm, road and battlefield. Towns use the town styles
    ("an elven village", "an arcane town with a wizard tower").
  - Name buildings ("with an inn and a smithy"), props ("four barrels and a well"), people and Pokémon
    ("two guards", "a wild Onix"), the time ("at night") and the weather ("in the rain").
  - **New layout** replaces the scenery, and the characters an earlier description made. Players' tokens
    and tokens you added yourself stay. **Add to it** keeps what's there and adds what you name.
  - **↶ Undo** takes back the whole step: scenery, ground and the characters it added or removed.
- New NPCs get **DM notes**: a personality, a voice and something they want. See *During play*.

Results are a starting point, so expect to tweak them. Press it again for another version, or change
anything by hand.

### Optional: ask Claude instead

Every ✨ box also has an **Ask Claude instead** button, for when you want an AI to design something more
unusual. You don't need it; the built-in designer covers the everyday things.
- **Free way (no key):** the board opens a window with the request. Click **📋 Copy it**, paste it into
  **claude.ai** (a free Claude account works), copy Claude's whole reply, paste it back, and click **Use
  this answer**. For a picture or sketch, attach it in Claude too.
- **Pay-per-use way (optional):** with your own Anthropic API key (side panel → ✨ Describe it → Optional:
  Claude), the request runs right inside the board. That costs a few cents a design, billed by Anthropic.
  The key is saved only in that browser, never in the campaign, so players can't see it.

### 🦴 Characters that walk and act

A workshop model becomes a character when its parts have joints. Select a part and pick **Moves as**:
body, head, jaw, arms, legs (two or four), tail or wings. Parts with the same joint move together.

Once it has joints, **🦴 Character poses** shows buttons to try Idle, Walk, Attack, Cast, Dodge, Hurt and
Down. A token using that model plays them on the board like any designed NPC: it walks when it moves,
acts from the pose buttons, flinches when hurt and goes down at 0 HP. **⇋ Mirror** swaps left and right
joints for you. Creatures made from words already have their joints.

### 📸 A picture for the token

In the NPC designer, or in the workshop when it's open for a token, **📸 Picture** saves the current view
as that token's portrait (its round token and standee art). Turn the model to the angle you like first.

### 🏠 Insides of buildings

Select a building in **✋ Edit**. Under **Inside**, add a few words if you like ("cosy, with a bard by the
fire") and click **🏠 Design its inside**. The board makes a new scene for the inside, furnished to
match: an inn gets a bar and tables, a smithy gets a forge and an anvil, a temple gets an altar and pews.
It works out the kind from the building's sign and look. Then:
- **🚪 Go inside** (on the building's card) takes you to it;
- **🚪 Back outside** (under ✎ This scene) brings you back;
- **▶ Show to players** when the party walks in.

**↻** next to Go inside designs it again.

### 🌅 Time of day, weather and light

Under **✎ This scene**, pick the **Light** (day, dawn, dusk, night, indoors, or dark for caves and
dungeons) and the **Weather** (rain, snow, falling ash, embers, falling leaves, fireflies, mist or magic
sparkles). Everyone sees it.

At dusk, at night, indoors and in the dark, fires, torches, lamps, candles, crystals, braziers, glowing
tanks and portals really light up what's around them. That includes workshop models with flames or
glowing parts. Scenes made from words set these for you ("at night in the rain").

### ⭐ Prefabs: reuse a group

In **✋ Edit**, **Shift-drag** over an area to select everything in it (a furnished tavern room, a market
square, a campsite).
- Drag any selected piece to move them all. <kbd>R</kbd> turns the group and <kbd>Del</kbd> deletes it.
- **⭐ Save prefab** stores the group, with the painted ground under it if you tick the box.
- It appears in **＋ Place → ⭐ Prefabs**. Click to stamp a copy in any scene; <kbd>R</kbd> turns it first.

### 🖼 Your own textures

Any picture can be a surface: a mossy wall, a mosaic floor, a painted mural.
- **Walls and roofs:** the building card's **⬆ Texture** buttons.
- **Workshop parts:** the ⬆ next to the pattern list.
- **Ground:** in **🖌 Paint ground**, **⬆ Your own** adds it to the ground palette, ready to paint.

Square, seamless pictures look best. They're shrunk to 512 px, so they stay quick to load. Uploaded
textures are listed in **📦 Files**.

### Outside AI tools: real 3D meshes and art

Some AI websites turn a description or a picture into a full 3D mesh (for example Meshy, Tripo or
Rodin; check their sites for current plans and terms). They're good for detailed creatures and statues.

1. Generate the model and download it as **GLB** (`.glb`). Ask for low-poly or a reduced polygon count
   if the site offers it.
2. Keep it under about 5 MB, because everyone downloads it. If it's bigger, reduce it in the site's own
   options, at **gltf.report**, or in Blender (*Decimate*, see "Real 3D models from Blender" below).
3. Use it in any of these ways:
   - As a token's 3D model: **⬆ Upload .glb** in the token card.
   - As scenery: **＋ Place → 🛠 Workshop → Your uploaded models**.
   - Inside a workshop model: **🧊 Add an uploaded .glb**, for example to put an AI-made statue on a
     plinth you built.

If the model comes with animations, the board matches them to the poses (see **🎬 Animations** below).
Models without animations hop when they act.

AI image tools are handy too. Maps go in through **Upload map**, character art as a token's
**Portrait**, and seamless textures through the **⬆ Texture** buttons.

## During play

| Do this | How |
|---|---|
| Move your token | Drag it. The yellow tag shows feet moved (red if over your speed). In a fight it counts your **whole turn** ("25 / 30 ft this turn"); **💨 Dash** on your token's card doubles it. Arrow keys also work. |
| See the rolls | Everyone's rolls (players' 🎲, the DM's NPC moves, initiative) pop up at the bottom left; **🎲 Rolls** in the top bar lists the recent ones. |
| Read a handout | When the DM shows one, it pops up; **📜 Handouts** in the top bar keeps them. |
| Pan / zoom | Drag empty space / mouse wheel or pinch |
| Ping a spot | Double-click (or long-press on a phone), or the 📍 tool |
| Measure | 📏 tool or `M`. 5 ft per square, and diagonals count as 5 ft (5e rule). |
| Area of effect | 📏 tool, then pick **🔺 Cone**, **➖ Line** (5 ft wide), **⬛ Cube**, **⚪ Sphere**, **🛢 Cylinder** or **✴ Emanation** in the bar above the dock and drag from where it starts. It snaps to 5 ft, lights up the squares it covers, and everyone sees it with your name. An emanation dragged from a token moves with it. **✕ Clear mine** takes it away (the DM can clear everyone's). |
| Tilt for drama | 🎬 or `T`. Swoops in, tokens stand up. Right-drag (two fingers) to orbit. |
| Back to the full map | ⌖ or `C` |

**Action poses.** Using a move on your sheet plays a pose on your token. Slashing moves play Sword, Special
moves and spells play Cast, Protect-style moves play Dodge, and other attacks play Attack. Taking damage
plays Hurt, and hitting 0 HP drops the character to one knee until they're healed. You can also trigger a pose
from your token's card. Standees hop or shake. With 3D models switched on, models from the Studio, the NPC
designer and the workshop have all the poses, and uploaded models use the animations they come with
(**🎬 Animations** in the token card).

Players can only move **their own** token and their companions'. The DM can move everything.
Players can also send out a companion themselves from the board's side panel.

**DM notes.** Select an NPC token: its card has **📝 DM notes** for anything you want to remember about it
(personality, voice, secrets). NPCs made from words start with a personality, a voice and a want;
**🎲 Roll a personality** gives new ones. Every token of that NPC shares the notes. Players' screens don't
show them (like the rest of the board, that's on the honour system: the data is in the shared campaign).

**The encounter ties in automatically.** When the DM runs a fight on the dashboard, the board shows
the initiative order in the top bar, a gold glow under whoever's turn it is, live HP rings, and
condition icons (🔥 Burned, ⚡ Paralyzed…). Downed characters tip over. With **🎯 Follow turn** on
(players' default), the camera glides to whoever is up.

**Initiative and damage come from the players.** When the DM clicks **▶ Start** on the dashboard, each
player is asked for their initiative, both in Battle Mode on their sheet and by a **🎲 Roll initiative** button in
the board's top bar: type the roll you made at the table, or roll d20 + DEX. It drops into the DM's order by itself (**🎲 Roll missing** covers anyone who
doesn't). In a fight, Battle Mode also has **💥 Damage**: pick the foe you hit, type the damage (a move
you rolled fills it in) and **Send**. It comes off that foe's HP on the dashboard and the board, and the
roll feed shows it. The DM can still type over any number.

**Turns from the board.** The DM's top bar has **⏭ Next turn**; on your turn, yours has **✓ End my turn**. Both move
the encounter on (the DM's dashboard has to be open somewhere, since it runs the fight).

## Ready-made models from the internet

Want a Pokémon that looks just like the games? People share free fan-made models on Sketchfab, and the
board takes them as they are.

1. Select the token. In its card, **🔎 Find one online** opens Sketchfab's search for its name, showing
   only models you can download. (Downloading needs a free Sketchfab account.)
2. Pick one and check its licence, shown under the model. Most are **CC Attribution**: credit the maker,
   for example in the token's 📝 DM notes. The Pokémon designs belong to Nintendo and Game Freak, so keep
   these to your own private game.
3. **Download 3D model → GLB**. The "glTF" choice is a zip; the board wants the single `.glb` file.
4. **⬆ Upload .glb** in the token card. Every token with that name gets the model.
5. When it loads, a message says which animations it found. The board knows the usual names (Idle, Walk,
   Attack, Hit, Death…) and the Pokémon games' own (wait, walk, *buturi* = physical attack, *tokusyu* =
   special attack, damage, down).
6. Check them in the card's **🎬 Animations**: one list per pose. Picking a clip plays it once so you can
   see it, and every token with that look uses it. Sword and Cast borrow the Attack clip if the model has
   none of its own; **None** makes a pose a hop again.
7. Facing sideways or backwards? **↻ Turn** turns it a quarter turn per click. Too big or small next to
   the others? **Model size**.

**Keep files small.** Everyone downloads every model, and the upload limit is 15 MB. Plenty of Sketchfab
models are bigger than that. To shrink one, drop it into **gltf.report** (free, works in your browser),
use its compression options, and export a new `.glb`. The board opens compressed models (Draco, meshopt,
KTX2). It also shrinks big textures to 1024 px when it shows them, so phones don't run out of memory,
but that doesn't make the download smaller.

The same steps work for models from AI generators and asset packs.

## Real 3D models from Blender

Anyone can give **their own** character a model. Select your token and, in its card, choose
**Upload .glb**. The DM can do it for any token.

1. Model the character standing on the ground, facing the **front view** (numpad 1).
2. **File → Export → glTF 2.0**:
   - Format: **glTF Binary (.glb)**
   - Include: **Selected Objects**
   - Mesh: **Apply Modifiers**
3. Optional animations: name the actions **Idle**, **Walk**, **Attack**, **Sword**, **Cast**, **Dodge**,
   **Hurt** and **Down**. The board plays Idle while standing, Walk while moving and the rest as action
   poses, on everyone's screen. Other names often work too; check them in **🎬 Animations**.
4. **Keep it light.** Everyone downloads the model, so aim for under ~30k triangles, textures at
   1024 px, and a file under 5 MB (hard limit 15 MB). In Blender: *Decimate* modifier, and
   *Image → Resize* for textures.
5. **Size doesn't matter.** The board scales any model to fit its square. Fine-tune with the
   **Model size** slider.

No model yet? Upload a **portrait** instead. It goes on the round token and on the card standee.
You can also paste a link to a `.glb` hosted somewhere, as long as the site allows other pages to
load it. Uploading is the reliable option.

## Good to know

- Everything saves as it happens. Close the tab and reopen it later, and the scenes, tokens, fog and
  models are all still there.
- The **📦 Files** list (DM panel) shows every map, portrait and model uploaded to the campaign.
  Delete what you don't need. The free Firebase plan holds 1 GB, which is a lot of maps.
- Big models take a few seconds to appear for everyone the first time. After that they're instant
  until the page is reloaded.
- **Slow board or a warm phone?** Side panel (☰) → **🖥 Display** → **🐢 Low graphics**. It turns off
  shadows and draws fewer pixels and frames, on that device only.
