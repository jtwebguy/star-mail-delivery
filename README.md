# Star Mail Delivery

An 8-bit, third-person stagecoach game set in California's Gold Country in 1852, built with Three.js in a single HTML file.

Drive the U.S. Mail coach between 25 real Mother Lode camps, from Sacramento and Coloma to Downieville, Sierra City and Sonora. Carry letters, newspapers, parcels, registered mail and gold dust, and ride shotgun against road agents, wolf packs and grizzlies with a Colt revolver and a double-barrel coach gun.

## Play

Open `index.html` in a browser (it loads Three.js r128 from cdnjs), or turn on GitHub Pages for this repo (Settings → Pages → deploy from the `main` branch).

## Controls

| Action | Keys |
| --- | --- |
| Drive | W A S D / arrows |
| Whip the team | Shift |
| Rest the team | Stop (faster in town) |
| Aim / fire | Mouse / click |
| Revolver / shotgun / dynamite | 1 / 2 / 3 / Q |
| Reload | R |
| Look back | C / right-drag |
| Map with town names | N / click the minimap |
| Post office | E |
| Repair a broken bridge | F |
| Zoom | Mouse wheel |
| Music / pause | M / P |

Touch controls appear on phones and tablets.

## Features

- Wide terrain map (about 6,100 × 8,100 units) with towns placed from real latitude and longitude, long winding roads, the Sacramento River and Sierra snowfields
- Road hazards: deadfall logs across the road (some hide a robber ambush), rockslides in the mountains, and creek bridges, some washed out so you must ford the creek
- Sporadic split-rail fences and treelines along the roads
- Shoot fallen logs apart to clear the road, and stop at a washed-out bridge to repair it: pay $15 for lumber and the county pays you for the work
- Escort jobs worth big money: bank money, iron safes (take 2 sacks) and prisoners. Each brings 2 armed deputies (up to 4) who ride beside the coach, shoot threats and stop robbers from looting while they live. The coach runs 10% slower while escorting, and road agents come hunting
- Dynamite: start with 1 stick (carry up to 3, $25 each at any post office). Throw it at the crosshair; it bursts on contact or after a short fuse, killing nearby enemies and blasting fallen logs off the road. Too close and it hurts your own coach
- Speech bubbles: the driver, your shotgun guard, deputies, road agents and prisoners react to raids, kills, hazards, deliveries and nightfall, and chat on quiet stretches
- One attacking group at a time (robbers, a wolf pack or a bear), with a 20-second breather after each fight
- Mail jobs with deadlines and pay, a wanted-poster bounty, gold nuggets near mine headframes
- Fatigue: the crew and team tire with distance (faster off-road, uphill, at night or when whipping). A tired team runs slower and your shots spread and sway. Stop to rest, or pay the livery or a fresh relay team at any post office
- Off-road travel is much slower than staying on the road
- Day/night cycle, coach lantern, chiptune music and synthesized sound effects
- Coach progression: start with a 2-horse mud wagon. Each driver rank unlocks a better coach to buy at any post office:

  | Coach | Horses | Cruise / whip speed | Mail sacks | HP | Unlock |
  | --- | --- | --- | --- | --- | --- |
  | Mud wagon | 2 | 20 / 29 | 5 | 80 | Start |
  | Celerity wagon | 4 | 24 / 34 | 6 | 100 | Mail Rider rank + $250 |
  | Concord coach | 6 | 28 / 40 | 8 | 140 | Jehu rank + $600 |
  | Treasure coach (iron-plated) | 6 | 30 / 43 | 10 | 180 | Whip rank + $1,200 |

- Store: ammunition, wheelwright repairs, livery rest, fresh relay teams and oats
- Progress saved in the browser
