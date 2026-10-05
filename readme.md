# Culinary Horizons: From Curbside to Culinary Empire

**Culinary Horizons** is an audio simulation game designed from the ground up for blind and visually impaired players, audio game enthusiasts, and simulation fans. Built with pure stereo spatial audio, dynamic acoustics, and zero visual dependency, it places you directly into the sights and sounds of urban street courier delivery, high-pressure line cooking, and commercial restaurant tycoon management.

Start on the rain-slicked asphalt of a bustling metropolis on a fixed-gear bike or a battered two-stroke scooter, hustle through traffic to deliver piping-hot orders, master auditory rhythm and thermal cooking cues on the kitchen line, and eventually build a multi-location culinary franchise.

---

## Highlights

- **Acoustic Navigation & City Grid**: Full spatial audio simulation of city avenues, one-way streets, intersections, traffic lights, and hazards. Navigate using real-time binaural beacon pulses, intersection echo-sonar, and voice guidance.
- **Physical Vehicle Modeling**: Longitudinal physics with dynamic torque curves, wheel slip, suspension damping, and cargo inertia. Don't take corners too fast or hit potholes—delicate soufflés and pizza stacks will slide and lose value!
- **Auditory Cooking Stations**: Cook without sight using real-time sound cues:
  - Match chopping rhythms to knife impact timbres.
  - Listen to pan sizzles transition from wet boiling hiss to high-frequency sears and Maillard crust crackles.
  - Track oil bubbling frequencies to pull crispy fries before they burn.
  - Knead, stretch to pitch, and stone-bake artisan pizzas.
- **Deep Economic Tycoon**: Acquire, renovate, and run 6 distinct restaurant archetypes (Neapolitan Pizzerias, Tokyo Izakayas, 24-Hour Diners, Street Taco Carts, Ghost Kitchens, and Michelin Fine Dining).
- **1,000+ Recipe Combinations & Custom Lab**: Formulate signature dishes, adjust menu pricing against demographic demand elasticity, manage ingredients, and navigate health inspections.
- **Screen Reader Native**: Powered by the **Prism** speech engine, automatically communicating via your active screen reader (NVDA, JAWS, etc.

---

## Quick Start & Installation

Because this is a pre-compiled standalone release, **no Python installation or extra dependencies are required**.

### Windows Standalone (Executable)
1. Download the latest release archive (`CulinaryHorizons-win32.zip`) from the **Releases** tab.
2. Extract the ZIP folder to any location on your PC (e.g., `Documents` or `Desktop`).
3. Ensure your headphones or stereo speakers are properly oriented (Left and Right).
4. Launch your preferred screen reader (NVDA, JAWS, etc.).
5. Run `CulinaryHorizons.exe`. The game will immediately announce itself through your screen reader or default system voice.

---

## Audio Orientation & Acoustics

**Headphones are strongly recommended.** All driving, guidance, and kitchen elements rely on accurate stereo placement:

- **Navigation Beacon**: A directional ping that pans toward your next required turn. As you approach the turn, the ping rate accelerates from a slow pulse ($1\text{ Hz}$) to a rapid alert ($10\text{ Hz}$). When you signal your turn, the pitch shifts higher to confirm your turn indicator is active.
- **Intersection Sonar (`Space`)**: Emits an acoustic sweep. Closer objects reflect faster echoes. Listen for the distinct high-pitch pulses of red lights, chime echoes of green lights, deep thuds of road potholes, and side-panning engine hums of cross traffic.
- **Thermal Sizzle Dynamics**: 
  - *Low, wet hiss ($300\text{–}600\text{ Hz}$)*: Water is boiling off the food surface.
  - *Crisp, energetic fry ($2\text{k}\text{–}6\text{k}\text{ Hz}$)*: Maillard browning is taking place—ideal sear.
  - *Dry crackle & popping hiss*: Burning threshold. Pull or flip immediately!

---

## How to Play

### 1. The Four Origin Paths
When beginning a new career, choose how your story starts:
- **The Pavement Roamer**: Start with \$150 and a single-speed courier bicycle. Earn every dollar through speed, careful riding, and generous customer tips.
- **The Scullery Hand**: Start with \$300 as a line-cook assistant in a greasy-spoon highway diner. Get paid by the shift while learning recipe masteries.
- **The Inheritor**: Take ownership of a distressed, debt-saddled neighborhood pizzeria with \$800, a broken-down 50cc scooter, and skeptical regulars. Turn it profitable before loan payments consume you.
- **The Culinary Visionary**: High-stakes sandbox. Start with \$120,000 in seed capital and a massive business loan. Lease prime real estate, build high-end kitchens, and assemble a professional brigade from day one.

### 2. City Addresses & Navigation
Metropolitan maps (Manhattan Grid, Tokyo Wards, London Square Mile) follow a consistent spatial coordinate system:
- **Avenues** run North–South.
- **Streets** run East–West (watch for alternating one-way streets).
- **Address Numbers** represent distance in meters along that road. For example, *742 5th Street* is located 42 meters past 7th Avenue.
- **Parity / Sides**:
  - **Odd Numbers**: Located on the **North** side of streets and the **West** side of avenues.
  - **Even Numbers**: Located on the **South** side of streets and the **East** side of avenues.

### 3. Courier Delivery Shifts
- Pick up food from your partner restaurant or your own franchise doors.
- Keep an ear on your cargo: high-speed turns generate lateral G-forces. If you hear items slide (`cargo_slide`), you are damaging food integrity and losing tips.
- Hitting potholes (`echo_pothole`) at speeds above $15\text{ km/h}$ damages your vehicle suspension and knocks the food container.
- Deliver orders while hot: food cools down over time according to Newton’s law of cooling. Install thermal foil linings or heated top-boxes to preserve temperature across long distances.

### 4. Kitchen Stations
Each culinary ticket requires sequential station work:
- **Prep Station**: Count the 4 high intro beats, then strike `Space` in rhythm with the metronome ticks. Audio timbre changes depending on whether you chop crisp onions, dense carrots, or soft tomatoes.
- **Sauté & Grill Station**: Adjust burner flame levels (`Up`/`Down`). Lay food onto the pan with `Space` once the metal reaches searing temperature. Listen for moisture evaporation, press `F` to flip when the sear reaches peak brownness, and press `Enter` to plate. Use `Space` to discharge fire extinguishers if grease catches fire!
- **Immersion Station (Boil / Fry)**: Wait for the pot or fryer to heat up. Press `Space` to submerge ingredients. For boiling, count the ticks and pull with `Enter`. For frying, wait until violent steam settle into a steady crackle.
- **Pizza & Bakery Station**: Alternate `Left` and `Right` arrow keys in a steady cadence to knead. Hold `Space` during the stretch phase and release exactly when the pitch matches the reference tone. Load into the stone oven and press `Enter` right as the crust begins crackling.
- **Assembly Station**: Move your hands across the ingredient bins using `Left` and `Right` (pan audio guides your position). Press `Space` to drop the exact item called by the ticket in order.

### 5. Managing Your Restaurant Empire
- **Staffing**: Hire prep cooks, line cooks, sous chefs, dishwashers, and delivery drivers. Monitor their traits (e.g., *Speed Demon Courier*, *Steady Hands*, *Hothead*) and manage wages to keep morale high.
- **Menu Engineering & Price Elasticity**: Adjust prices based on neighborhood wealth and dish prestige. Set prices too high and customers walk away; set prices too low and food margins collapse.
- **Suppliers & Inventory**: Choose between cheap wholesale food distributors or expensive organic local farms. Set your inventory par days—carrying too little stock causes sell-outs, while carrying too much leads to spoilage.
- **Hygiene & Inspections**: Dirty kitchens bring health inspectors, heavy fines, and forced closures. Keep equipment maintained and staff the dish pit.

---

## Universal Key Reference Card

### General & Menus
| Key | Action |
| :--- | :--- |
| `Up` / `Down` | Navigate menu items (wraps around with audio earcons) |
| `Left` / `Right` | Adjust sliders (volume, prices, marketing budget) |
| `Enter` / `Space` | Activate option / toggle checkbox |
| `Home` / `End` | Jump to top / bottom of menu |
| `A` – `Z` | First-letter jump to matching menu entry |
| `Escape` / `Backspace` | Back / Exit submenu |
| `F1` | Read extended help for the selected item |
| `F2` / `R` | Repeat the last spoken message |

### Shift Telemetry & Spoken HUD (Usable Anywhere)
| Key | Spoken Information |
| :--- | :--- |
| `C` | Current street coordinate, avenue, heading, and district |
| `T` | Current in-game clock time, day, and weather report |
| `V` | Vehicle diagnostics (speed, gear, RPM, fuel/battery %, condition) |
| `S` | Current order status, delivery address, or kitchen ticket rail |
| `M` | Wallet balance, bank accounts, outstanding debts, and today's profit |
| `H` | Context-sensitive help explaining controls for the current screen |

### Driving & Delivery Controls
| Key | Action |
| :--- | :--- |
| `Up Arrow` | Accelerate / Throttle |
| `Down Arrow` | Apply Brakes |
| `Left Arrow` | Signal Left turn at upcoming intersection (press again to cancel) |
| `Right Arrow` | Signal Right turn at upcoming intersection (press again to cancel) |
| `U` | Perform U-Turn (vehicle must be stopped below $2.5\text{ km/h}$) |
| `Space` | Emit acoustic sonar radar ping (detects lights, hazards, potholes) |
| `Enter` | Pick up order at restaurant / Hand over order at customer address |
| `G` | Repeat current turn-by-turn GPS instruction |
| `B` | Sound vehicle horn |
| `I` | Start combustion engine |
| `A` | Shift gear UP (Manual transmission mode) |
| `Z` | Shift gear DOWN (Manual transmission mode) |
| `Left Shift` | Clutch pedal (Manual transmission mode) |
| `Escape` (twice) | Abandon current run / end shift |

### Kitchen Controls
| Key | Action |
| :--- | :--- |
| `Space` | Universal action (Chop rhythm / Drop in pan / Add ingredient / Extinguisher) |
| `Up` / `Down` | Increase / decrease burner heat level |
| `F` | Flip food on grill or pan |
| `Left` / `Right` | Alternate hands while kneading / Move across assembly bins |
| `Enter` | Pull food from pan/fryer, load oven, or finalize plate |
| `Escape` (twice) | Step off the kitchen line |

---

## Vehicles & Fleet Specifications

| Vehicle | Class | Sound Profile | Cargo Capacity | Top Speed | Best Used For |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Foot Courier** | Human | Footstep cadence | 1 Slot | $16\text{ km/h}$ | Dense, short-hop downtown drops |
| **Fixed-Gear Bike** | Human | Chain rattle & freewheel | 1 Slot | $38\text{ km/h}$ | Low-cost zero-fuel courier work |
| **50cc Scooter** | ICE | 2-stroke buzz | 2 Slots | $55\text{ km/h}$ | Agile urban alley navigation |
| **150cc Motorbike**| ICE | Single-cylinder 4-stroke | 2 Slots | $85\text{ km/h}$ | High-tempo multi-district runs |
| **400cc Dual-Sport**| ICE | Twin-cylinder thumper | 3 Slots | $125\text{ km/h}$| Rapid all-weather delivery |
| **Cargo E-Trike** | Electric | High-torque motor whine | 5 Slots | $45\text{ km/h}$ | Heavy bulk catering runs |
| **Hatchback** | ICE | 4-cylinder sedan | 6 Slots | $145\text{ km/h}$| Enclosed cargo, high storm stability |
| **Commercial Van** | ICE | Low-rev turbo diesel | 14 Slots | $110\text{ km/h}$| Massive catering & franchise supply |
| **Tuned Turbo Sedan**| ICE | Turbo spool & blow-off | 5 Slots | $210\text{ km/h}$| VIP express gourmet orders |

---

## Save Files & Data Integrity

Game data is managed automatically through a transaction-safe SQLite persistence layer.
- Saves are stored under your operating system user profile:
  - **Windows**: `%APPDATA%\CulinaryHorizons\saves\`
- **Fail-Safe Backup Rotation**: Prior to overwriting save files, the engine archives up to three numbered rotating backups (`slot1.bak1`, `slot1.bak2`, etc.). If your machine loses power mid-session, the game automatically detects corruption on launch, restores the newest valid backup, and alerts you via speech.

---

## Troubleshooting & Audio Settings

- **No Screen Reader Speech**: Ensure NVDA, JAWS, or your operating system's screen reader is active *before* launching the game. If no screen reader client is detected, the engine falls back to standard platform text-to-speech (SAPI5).
- **Audio Output Device**: Culinary Horizons uses low-latency hardware stream buffers. If you connect USB headphones or a Bluetooth headset after the game has already launched, restart the executable so it can bind to the new default audio output device.
- **Screen Reader Interruption**: By default, critical menu shifts and driving alerts interrupt ongoing speech for rapid reaction time. Story logs, chef feedback, and dialogue are queued sequentially without interrupting vehicle safety warnings.

---

## Credits & Acknowledgements

- **Procedural Sound Engine**: Sound design, synthesizer patches, and vehicle acoustics are powered by **[Genny](https://github.com/ogomez92/genny)** by **Oriol Gomez** ([@ogomez92](https://github.com/ogomez92)).
- **Accessibility & Speech**: Screen reader detection and text-to-speech integration powered by **[Prism](https://github.com/ethindp/prism)** (`prismatoid`) by **Ethin Probst** ([@ethindp](https://github.com/ethindp)).
- **Audio Output**: Low-latency audio streaming handled via PortAudio and `sounddevice`.

---

## Community & Feedback

Found a bug, want to discuss menu recipes, or have an idea for new vehicle upgrades?
- Open an issue in the **Issues** tracker.
- Join the discussion threads under the **Discussions** tab.

*Bon Appétit, and keep both wheels on the pavement!*