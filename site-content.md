# Carson.Engineers: Site Content (rev 2)
Written to fit the Spectral (HTML5 UP) template. Now four pages: index.html (personal), cars.html (new, clone generic.html), formula-hybrid.html (new, clone generic.html), and generic.html repurposed as the brand page. Placeholders to fill are marked like [THIS]. No em dashes appear anywhere in the site copy.

---

# DESIGN NOTES: COLOR PALETTE (black and red)

Spectral ships purple/blue. Swap to this palette (colors live in `assets/sass/libs/_vars.scss`, or override directly in `assets/css/main.css`):

- Page background / dark wrappers: `#0E0E10` (near black)
- Secondary surface (alternating sections): `#1A1A1D`
- Primary accent (buttons, links, valve-open moments): `#D1202F` (deep red; `#E10600` if you want louder, motorsport style)
- Accent hover / pressed: `#9E1824`
- Body text: `#F2F2F2`, muted text `#9C9C9C`
- Banner: replace the purple gradient overlay with black at ~60 to 80 percent opacity over a garage or car photo, red used only on the button
- Keep red scarce. Black carries the site; red marks actions and highlights. That restraint is what makes it look intentional instead of gamer-rig.

---

# GLOBAL NAV (all pages)

- **Site title (h1):** Carson.Engineers
- **Menu:** Home (`index.html`) · The Cars (`cars.html`) · Formula Hybrid (`formula-hybrid.html`) · Carson.Engineers (`generic.html`)
- **Menu action button:** **Get in Touch** → `mailto:[YOUR EMAIL]`
- Remove Elements/Sign Up/Log In links.

# GLOBAL FOOTER (all pages)

- Icons: LinkedIn → `[YOUR LINKEDIN URL]` · GitHub → `https://github.com/Kiyo615` · Instagram → `[carson.engineers INSTAGRAM URL]` · Email → `mailto:[YOUR EMAIL]`
- Copyright: `© 2026 Carson.Engineers`
- (The free Spectral license, CCA 3.0, requires keeping the HTML5 UP attribution line.)

---

# PAGE 1: index.html (PERSONAL, employer-facing)

## Banner (`#banner`)

- **h2:** Carson [LAST NAME]
- **Subtitle:**
  > Mechanical engineer focused on powertrain and control systems, from Formula Hybrid race cars to the machines that make industry run. Building toward something bigger.
- **Primary button:** **See My Work** → `#two`

## Section One (`#one`): About

- **h2 (two lines):**
  > Line 1: Engineer first,
  > Line 2: founder in progress
- **Paragraph:**
  > I'm a final-year Mechanical Engineering student at the Milwaukee School of Engineering, with minors in Computer Engineering and Aerospace Engineering. I lead a six-subteam Formula Hybrid race team as Engineering Manager, spend my days as a mechanical engineering intern in industry, and spend my nights with an engine on a stand. I've been leading builds since before college: my Eagle Scout project put 600+ hours into leading scout crews through heavy-equipment fence construction for a therapy ranch. I work best where mechanical hardware meets embedded control, and my long-term goal is to build cars people are actually allowed to fix.
- **Icons:** `fa-cogs`, `fa-microchip`, `fa-car`

## Section Two (`#two`): Experience & Projects (3 spotlights)

### Spotlight 1: image `pic01.jpg` (MOZEE car or shop photo)
- **h2 (two lines):**
  > Line 1: PM to EM,
  > Line 2: MOZEE Motorsports
- **Paragraph:**
  > I first served as Project Manager of MSOE's Formula Hybrid team, [ONE LINE ON YOUR PM SCOPE: timeline ownership, budget, sponsor coordination, etc.], then stepped into the Engineering Manager role, leading six subteams across powertrain, controls, chassis, and electrical systems. The hands-on work spans ECU integration, electronic throttle control, STM32-based sensing, and LV/HV harness design. The bigger project is structural: turning an ad-hoc build cycle into a documented, repeatable engineering process that outlives any single class of students.
- **Link under paragraph:** More on Formula Hybrid → `formula-hybrid.html`

### Spotlight 2: image `pic02.jpg` (machine or CAD photo)
- **h2 (two lines):**
  > Line 1: Engineering Intern,
  > Line 2: Unisig
- **Paragraph:**
  > As a mechanical engineering intern at UNISIG, a Wisconsin manufacturer of deep hole drilling machines, I do real engineering work inside a production organization: drawings that get built, tolerances that get held, and decisions that get reviewed. It's where classroom analysis meets the shop floor.

### Spotlight 3: image `pic03.jpg` (engine on stand or exhaust photo from Instagram)
- **h2 (two lines):**
  > Line 1: The garage as
  > Line 2: an R&D program
- **Paragraph:**
  > My project cars are where I take full ownership of a system, end to end. On my daily-driver Audi A4 I'm completing my first full engine rebuild, and I designed and built its valved exhaust: cutting and welding the piping myself, wiring remote electronic valve control, and diagnosing and replacing a failed actuator motor along the way, all tucked cleanly under the car with no rattles. My BMW E36 is the long game, with a supercharged M54 swap in the works. Every build is deliberate practice in engineering, in diagnostics, and toward the company I plan to found.
- **Link under paragraph:** Meet the cars → `cars.html`

## Section Three (`#three`): Skills (heading + 6 features)

- **h2:** What I bring to a team
- **Intro paragraph:**
  > A powertrain and controls engineer with real manufacturing exposure, embedded systems experience, and the leadership record to coordinate work across disciplines.

1. `fa-tachometer-alt`: **Powertrain & Controls**
   > ECU integration, electronic throttle control, and hybrid powertrain systems developed through Formula Hybrid competition work.
2. `fa-microchip`: **Embedded Systems**
   > STM32-based sensor development and integration; comfortable at the firmware and hardware boundary.
3. `fa-bolt`: **LV/HV Electrical**
   > Low and high voltage harness design for a hybrid race vehicle, built to competition electrical rules.
4. `fa-drafting-compass`: **Mechanical Engineering**
   > Industry engineering experience on production machinery, plus CNC machining background from a manufacturing internship.
5. `fa-terminal`: **Software & Systems**
   > Python, Linux server administration, and Git, including a fully deterministic algorithmic trading system I designed, spec'd, and deployed as a hardened service with risk gates and kill switches.
6. `fa-users`: **Engineering Leadership**
   > Project Manager turned Engineering Manager of a six-subteam race program, a habit of leading builds that started with a 600-hour Eagle Scout construction project.

## CTA strip (`#cta`)

- **h2:** Beyond the resume
- **Paragraph:**
  > Everything above is what I do today. Carson.Engineers is where it's going: a long-term plan to build a performance car company around the right to repair.
- **Primary button:** **Explore Carson.Engineers** → `generic.html`
- **Secondary button:** **Contact Me** → `mailto:[YOUR EMAIL]`

---

# PAGE 2: cars.html (NEW: clone generic.html, article layout)

## Article title
- **h2:** The Cars
- **Subtitle:**
  > Two platforms, one purpose: learn cars, learn engineering, and build toward the business.

## Banner image
Best wide garage shot you have; the Instagram exhaust content is a good source.

## Body (h3 subheads + prose)

### h3: Audi A4: the daily that earns its keep

> My 2005 Audi A4 is a daily driver that doubles as a classroom. It's currently getting my first full engine rebuild, done properly: parts researched and sourced, torque specs verified against factory documentation, and the engine built on a stand rather than rushed in the car. Timing, flywheel, and clutch are the last steps before it goes back in.

### h3: The valved exhaust

> Before the rebuild, the A4 got a valved exhaust I designed and built myself. That meant cutting and welding the piping (and learning the hard way why you tack weld before committing instead of eyeballing it), wiring up remote electronic valve control, and later diagnosing an actuator failure where a cheap heat barrier melted the motor. I rebuilt it, ran the numbers, and replaced it when replacement proved cheaper. The result is the part I'm proud of: everything tucked away with no rattles, and a seamless transition between quiet and loud. Full build evidence is on the [Instagram](INSTAGRAM URL).

### h3: BMW E36: the long game

> The E36 is a project car in the most honest sense: it breaks constantly, and fixing it is the point. After almost three years of ownership it's finally running with no oil leaks. The chassis still needs work, including repairs at the jack points, fresh bushings, and engine mounts, and that's all part of the plan.

### h3: The supercharged M54 swap

> The real build is sitting in front of the house: a spare M54B30 in teardown, with fresh bearings on the shopping list and an Audi 3.0T water-cooled supercharger already purchased and waiting. The plan is to build the blown M54 on the stand, swap it into the E36 as an OBD2 conversion, and run it on the MS43 ECU, effectively convincing the car it's an E46 so it can be tuned with well-documented open resources. Forced induction, engine management, and platform integration, all on my own hardware.

### h3: Why bother

> Every hour in the garage is deliberate practice. These cars teach the diagnostics, fabrication, and systems integration that classrooms can't, and they're the working proof behind Carson.Engineers. Watch the builds unfold on [Instagram](INSTAGRAM URL).

---

# PAGE 3: formula-hybrid.html (NEW: clone generic.html, article layout)

## Article title
- **h2:** Formula Hybrid at MSOE
- **Subtitle:**
  > MOZEE Motorsports: a student-built hybrid race car, and the engineering organization behind it.

## Banner image
Car on track or team shop photo.

## Body (h3 subheads + prose)

### h3: The competition

> Formula Hybrid challenges university teams to design, build, and race an open-wheel hybrid-electric car, judged on engineering design as much as on-track performance. It's the closest thing a student can get to running a small vehicle program: real deadlines, real rules compliance, real budgets, and a car that either works or doesn't.

### h3: Project Manager

> I served as the team's Project Manager, [2 TO 3 SENTENCES IN YOUR WORDS: what years, what you owned (schedule, budget, sponsors, competition logistics), and one concrete win from that season]. That season taught me how a race program actually moves: not through heroic all-nighters, but through planning that survives contact with reality.

### h3: Engineering Manager

> As Engineering Manager I now lead six subteams spanning powertrain, controls, chassis, and electrical systems. My technical background on the team includes ECU integration, electronic throttle control, STM32-based sensor work, and LV/HV harness design, which lets me review work across every subteam rather than managing from a distance.

### h3: Building a process that outlives us

> Student teams reset every year, and knowledge walks out the door with every graduating class. My current initiative is a full documentation system for the team: standardized templates for change proposals, new projects, iterations, emergency fixes, and guides, with a defined review and approval workflow and a SharePoint document hub behind it. The goal is simple: a freshman in three years should be able to open a document and know exactly what was done, why, and what to do next.

## Closing CTA (reuse the CTA block style)
- **h2:** Want the details?
- **Paragraph:** Happy to walk through the car, the org chart, or the documentation system.
- **Button:** **Get in Touch** → `mailto:[YOUR EMAIL]`

---

# PAGE 4: generic.html (BRAND, investor/customer-facing)

## Article title
- **h2:** Carson.Engineers
- **Subtitle:**
  > A performance car company that doesn't exist yet, being built one bolt at a time.

## Banner image
Garage/workbench or road photo; honest rather than corporate.

## Body (h3 subheads + prose)

### h3: The problem

> Modern cars are increasingly closed systems. Diagnostics live behind proprietary tools, parts are serialized against replacement, and the gap between base model and performance model is often software and marketing rather than engineering. Owners are being converted from drivers into subscribers, and enthusiasts, independent shops, and ordinary people who just want to fix their own car are all paying for it.

### h3: The mission

> Carson.Engineers exists to build performance-oriented cars that respect their owners: repairable by design, tunable by design, and honest about what you're buying. Full documentation. Accessible diagnostics. A platform you're allowed to work on.

### h3: The vision

> An accessible base-model car that's genuinely good to drive, and a catalog of OEM-engineered upgrade parts that let an owner take that same car as far as they want it to go. Not trim levels; an upgrade path. The car you buy at 22 becomes the car you build at 30, with factory support the whole way.

### h3: The road there

> Nobody starts at "car company." The plan is a deliberate assembly, where each bolt torqued down funds and de-risks the next:
>
> 1. **Operating businesses now:** small, real, revenue-generating ventures that build operational discipline and first capital.
> 2. **OEM parts & performance kits:** engineering and selling upgrade components for existing platforms, building the brand's technical reputation.
> 3. **A custom modification shop:** full-vehicle builds that prove out the engineering philosophy on real customer cars.
> 4. **The manufacturer:** a ground-up vehicle designed around repairability and tunability from day one.

### h3: Where things stand today

> Honestly: at the first bolt. Carson.Engineers is currently one engineer, finishing a Mechanical Engineering degree, leading a hybrid race team's engineering organization, working in industry, and running a first small operating business. There is no product, no funding round, and no inflated claims. What exists is the direction, the technical foundation being built deliberately toward it, and this page as a public commitment to the plan. The project cars documented on the Carson.Engineers Instagram are the working lab: real fabrication, forced induction, and ECU integration work, done in public.

### h3: Follow along or get involved

> If you're an enthusiast who wants cars like this to exist, a potential customer for future parts and builds, or an investor interested in the long game, reach out. Early conversations shape early companies.
>
> **[YOUR EMAIL]**

---

# NOTES / OPEN ITEMS

- **PM section needs your words.** Two bracketed placeholders (index Spotlight 1, Formula Hybrid page) want your actual PM scope: years, what you owned, one concrete result. I deliberately didn't invent it.
- **No em dashes** anywhere in site copy, per your preference. Colons, commas, and periods do the work instead.
- **Two new files:** duplicate `generic.html` as `cars.html` and `formula-hybrid.html`, then swap the copy in.
- Lawn care stays abstract on the brand page; trading system stays on the personal skills grid only.
- Remaining placeholders: last name, email, LinkedIn URL, Instagram URL, PM details.
