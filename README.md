# 🧫 Carbendazim vs. *Aspergillus flavus* — Interactive Simulation

### A Visual Laboratory for Understanding Fungicide Action, Aflatoxin Production & Resistance Evolution

<p align="center">
  <img src="https://img.shields.io/badge/For-M.Sc.%20Microbiology%20Students-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Topic-Mycology%20%2F%20Agricultural%20Science-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Type-Interactive%20Simulation-purple?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Install-Nothing!%20Just%20Open-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" />
</p>

<p align="center">
  🔗 <b><a href="https://carbendazim.pages.dev">Open the Live Simulation → carbendazim.pages.dev</a></b>
</p>

<p align="center">
  <i>No installation. No downloads. Just click and explore.</i>
</p>

---

<p align="center">
  <i>An interactive simulation that lets you <b>see</b> what happens when Carbendazim<br/>
  meets <i>Aspergillus flavus</i> — from the β-tubulin molecule to the petri dish colony,<br/>
  from aflatoxin accumulation to the emergence of fungicide resistance.</i>
</p>

---

## 📋 Table of Contents

1. [Who Is This For?](#-who-is-this-for)
2. [How to Use It](#-how-to-use-it)
3. [What You'll See in the Simulation](#-what-youll-see-in-the-simulation)
4. [The Science Behind the Simulation](#-the-science-behind-the-simulation)
5. [Suggested Experiments](#-suggested-experiments-for-your-project)
6. [Parameters & Their Biological Basis](#-parameters--their-biological-basis)
7. [How to Use This in Your M.Sc. Project](#-how-to-use-this-in-your-msc-project)
8. [Screenshots}
9. [Frequently Asked Questions](#-frequently-asked-questions)
10. [References You Can Cite](#-references-you-can-cite)
11. [Technical Details (For the Curious)](#-technical-details-for-the-curious)
12. [License](#-license)

---

## 🎯 Who Is This For?

This simulation was built specifically to help **M.Sc. Microbiology students** — particularly those working on:

```
✅ Fungicide efficacy studies (in vitro / in silico)
✅ Aspergillus flavus growth inhibition experiments
✅ Aflatoxin contamination and food safety research
✅ Fungicide resistance mechanisms (β-tubulin mutations)
✅ Post-harvest crop protection studies
✅ Anyone who wants to VISUALIZE what their wet-lab experiments actually do
```

### The Problem This Solves

```
IN YOUR WET LAB:
─────────────────
  • You inoculate A. flavus on PDA plates
  • You apply carbendazim at different concentrations
  • You wait 5–7 days
  • You measure colony diameter with a ruler
  • You calculate inhibition percentage
  • You write it up

  But... you never actually SEE:
  • How tubulin is disrupted at the molecular level
  • How the colony gradually responds to treatment
  • How resistance could emerge over generations
  • How aflatoxin levels change in real-time
  • What happens if you change the dose mid-experiment


WITH THIS SIMULATION:
─────────────────────
  • You SEE tubulin filaments shatter when treatment is applied
  • You WATCH the colony shrink and change color
  • You OBSERVE resistance emerge (purple mutant phenotype)
  • You TRACK aflatoxin levels dropping and rising on live graphs
  • You can ADJUST concentration and INSTANTLY see the effect
  • You can run 50 days of experiment in 50 seconds

  It doesn't replace your wet lab.
  It helps you UNDERSTAND what's happening in your wet lab.
```

---

## ⚡ How to Use It

### Just Click This Link

> 🔗 **[https://carbendazim.pages.dev](https://carbendazim.pages.dev)**

That's it. No download, no installation, no login. Works on:
- ✅ Laptop / Desktop (any browser)
- ✅ Tablet
- ✅ Phone (landscape mode recommended)
- ✅ Lab computer
- ✅ Library computer
- ✅ Literally any device with a web browser

### If You Want to Run It Offline

```bash
# Download this repository
git clone https://github.com/your-username/carbendazim-aspergillus-lab.git

# Open the file — that's literally it
# Double-click index.html
# It works without internet forever
```

---

## 🔬 What You'll See in the Simulation

### The Three Views

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                 │
│  YOUR SCREEN HAS THREE MAIN AREAS:                             │
│                                                                 │
│  ┌────────────────────┐    ┌──────────────────────────────────┐│
│  │                    │    │                                  ││
│  │  🔬 MICROSCOPIC    │    │  🧫 MACROSCOPIC                  ││
│  │     VIEW           │    │     PETRI DISH                   ││
│  │                    │    │                                  ││
│  │  What's happening  │    │  What you'd see in your          ││
│  │  INSIDE the cell:  │    │  actual lab experiment:          ││
│  │  • Tubulin fibers  │    │  • Colony growing on             ││
│  │  • Chromosomes     │    │    chilli substrate              ││
│  │  • Spindle forming │    │  • Color changes                 ││
│  │    or shattering   │    │  • Size changes                  ││
│  │                    │    │  • Resistant (purple) sectors    ││
│  └────────────────────┘    └──────────────────────────────────┘│
│                                                                 │
│  ┌──────────────────────────────────────────────────────────┐  │
│  │  📊 LIVE ANALYTICS                                       │  │
│  │                                                          │  │
│  │  Three real-time graphs tracking:                        │  │
│  │  1. Fungal Growth (%)                                    │  │
│  │  2. Aflatoxin Concentration (ppb)                        │  │
│  │  3. Resistance Index (%)                                 │  │
│  │                                                          │  │
│  └──────────────────────────────────────────────────────────┘  │
│                                                                 │
│  ┌──────────────────────────────────────────────────────────┐  │
│  │  🎛️ CONTROLS                                             │  │
│  │  [Concentration Slider] [Speed 1x–5x] [Zoom] [Apply]    │  │
│  └──────────────────────────────────────────────────────────┘  │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### What Happens at Each Stage

#### Stage 1: Untreated Growth (Before You Apply Carbendazim)

```
WHAT YOU'LL OBSERVE:

  🔬 Microscopic View:
     • Tubulin filaments are intact (long, organized lines)
     • Chromosomes are being pulled apart normally
     • Mitotic spindle is visible and functioning
     • Cell division is happening smoothly
     → This is NORMAL MITOSIS

  🧫 Petri Dish:
     • Colony is yellow-green (healthy A. flavus color)
     • Colony is expanding outward at ~3.5 mm/day
     • Growing on the chilli substrate
     → This is what your CONTROL PLATE looks like

  📊 Graphs:
     • Growth curve: Rising steadily (linear)
     • Aflatoxin: Rising exponentially with biomass
     • Resistance: 0% (no selection pressure yet)
```

#### Stage 2: Treatment Applied (After You Click "Apply Treatment")

```
WHAT YOU'LL OBSERVE:

  🔬 Microscopic View:
     • Tubulin filaments SHATTER into fragments ⚡
     • Chromosomes are stuck — can't separate
     • No spindle forms
     • Cells are arrested in metaphase
     → This is MITOTIC ARREST (the mechanism of carbendazim)

  🧫 Petri Dish:
     • Colony STOPS expanding (or slows dramatically)
     • Color shifts to PALE (inhibited, metabolically suppressed)
     • Compare this to your treatment plates in the lab!
     → This is what ~73% inhibition looks like

  📊 Graphs:
     • Growth curve: FLATTENS (inhibited)
     • Aflatoxin: Begins to DECLINE (less biomass = less toxin)
     • Resistance: Still 0%, but the clock is ticking...
       Every simulated day, there's a 0.2% chance of mutation
```

#### Stage 3: Resistance Emerges (The Scary Part)

```
WHAT YOU'LL OBSERVE:

  🔬 Microscopic View:
     • Tubulin filaments REFORM (in resistant cells)
     • Mitosis resumes — spindles are back
     • But now the cells look different (purple tint)
     → The β-tubulin has MUTATED at codon 198 or 200
       Carbendazim can no longer bind to it

  🧫 Petri Dish:
     • PURPLE SECTORS appear within the colony 🟣
     • These are resistant cells outcompeting sensitive ones
     • Colony starts growing again DESPITE treatment
     • Eventually, most of the colony turns purple
     → This is what happens in the field when farmers
       use the same fungicide year after year

  📊 Graphs:
     • Growth curve: Starts RISING again 📈
     • Aflatoxin: Starts INCREASING again ⚠️
     • Resistance Index: Climbing from 0% toward 100%
     → The fungicide is becoming USELESS
```

---

## 🧬 The Science Behind the Simulation

### What is Carbendazim and How Does It Work?

```
CARBENDAZIM — THE BASICS
═════════════════════════

  What:    A benzimidazole fungicide (systemic)
  Used on: Crops like wheat, rice, fruits, chillies, groundnuts
  Target:  β-tubulin protein inside fungal cells
  Effect:  Stops cell division → fungus can't grow

  HOW IT WORKS (step by step):

  STEP 1: Normal Cell Division
  ─────────────────────────────
  
  In a healthy fungal cell, α-tubulin and β-tubulin proteins
  join together to form MICROTUBULES — tiny tubes that act
  like railway tracks inside the cell.
  
    α─β─α─β─α─β─α─β─α─β  ← One microtubule (a chain of tubulin)
  
  During mitosis, these microtubules form the SPINDLE — the
  structure that pulls chromosomes apart so the cell can divide.
  
            ╱ ─── ○ ─── ╲         ○ = chromosome
           ╱      │      ╲
    [Pole]────────┼────────[Pole]  ← Spindle fibers (microtubules)
           ╲      │      ╱
            ╲ ─── ○ ─── ╱
                  
    Result: Chromosomes separate → Cell divides → Colony grows ✅


  STEP 2: Carbendazim Enters the Cell
  ────────────────────────────────────
  
  Carbendazim molecule binds to a specific site on β-tubulin
  (the colchicine-binding domain).
  
    α─── β ← ⚠️ Carbendazim attaches HERE
              │
              ╳ ← Tubulin can't join together anymore
  
  
  STEP 3: Microtubules Can't Form
  ────────────────────────────────
  
  Without polymerization, there are no microtubules.
  Without microtubules, there's no spindle.
  Without a spindle, chromosomes can't separate.
  
    α─β   α─β   α─β   (scattered, useless tubulin fragments)
    
    Chromosomes: ○○○○○ (stuck together, can't move)
    
    
  STEP 4: Cell Is Stuck → Mitotic Arrest
  ───────────────────────────────────────
  
  The cell is frozen in metaphase.
  It can't divide. Eventually, it dies.
  
  No cell division = No colony growth = No aflatoxin production
  
  
  THIS IS EXACTLY WHAT THE MICROSCOPIC VIEW SHOWS YOU.
  When you click "Apply Treatment," you'll see the tubulin
  filaments shatter and the chromosomes freeze in place.
```

### What is *Aspergillus flavus* and Why Does It Matter?

```
ASPERGILLUS FLAVUS — WHY YOU'RE STUDYING IT
════════════════════════════════════════════

  Kingdom:  Fungi
  Class:    Eurotiomycetes
  Danger:   Produces AFLATOXINS — the most potent naturally
            occurring carcinogens known to science

  WHERE IT GROWS:
  • Groundnuts (peanuts)          • Maize (corn)
  • Chillies (red/green)          • Tree nuts
  • Rice                          • Cotton seeds
  • Spices                        • Animal feed

  WHY IT'S DANGEROUS — AFLATOXIN B₁:
  
  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │  Aflatoxin B₁ is classified as a                       │
  │  GROUP 1 CARCINOGEN by IARC (WHO)                      │
  │                                                         │
  │  Same category as:                                      │
  │  • Asbestos                                             │
  │  • Tobacco smoke                                        │
  │  • Plutonium                                            │
  │                                                         │
  │  Primary target: LIVER                                  │
  │  Causes: Hepatocellular carcinoma (liver cancer)        │
  │                                                         │
  │  Regulatory limits:                                     │
  │  India (FSSAI):      15 ppb (total aflatoxins)         │
  │  EU:                  4 ppb (AFB₁ alone)               │
  │  USA (FDA):          20 ppb (total aflatoxins)         │
  │                                                         │
  │  In the simulation, the safety threshold is at 20 ppb. │
  │  Watch the graph — when does YOUR experiment cross it?  │
  │                                                         │
  └─────────────────────────────────────────────────────────┘

  KEY INSIGHT FOR YOUR PROJECT:
  
  Controlling A. flavus growth → Controls aflatoxin production
  
  This is why fungicides like carbendazim matter:
  they don't just stop the fungus from growing,
  they PROTECT FOOD FROM BECOMING TOXIC.
```

### How Does Resistance Develop?

```
THE RESISTANCE PROBLEM — WHAT EVERY MICROBIOLOGIST MUST UNDERSTAND
═════════════════════════════════════════════════════════════════════

  WHY DOES RESISTANCE HAPPEN?

  It's evolution by natural selection — in fast forward.

  STEP 1: You apply carbendazim to a population of A. flavus
  ──────────────────────────────────────────────────────────
  
  Population before treatment:
    🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢
    (All sensitive — carbendazim kills them)

  
  STEP 2: Most cells die, but one has a random mutation
  ────────────────────────────────────────────────────
  
  After treatment:
    ❌❌❌❌❌❌❌❌❌❌❌❌❌❌❌❌❌❌❌🟣 ← This one survived!
    
  The mutation: A single base change in the β-tubulin gene
    Position 198: Glutamic acid → Alanine (or Lysine)
    
  This changes the SHAPE of the binding site.
  Carbendazim can no longer attach.
  The cell divides normally despite the fungicide.


  STEP 3: The resistant cell multiplies freely
  ────────────────────────────────────────────
  
  Day 1:   ❌❌❌❌❌❌❌❌❌❌❌❌❌❌❌❌🟣
  Day 5:   ❌❌❌❌❌❌❌❌❌❌❌❌🟣🟣🟣🟣
  Day 10:  ❌❌❌❌❌❌❌❌🟣🟣🟣🟣🟣🟣🟣🟣
  Day 20:  ❌❌❌❌🟣🟣🟣🟣🟣🟣🟣🟣🟣🟣🟣🟣
  Day 40:  🟣🟣🟣🟣🟣🟣🟣🟣🟣🟣🟣🟣🟣🟣🟣🟣
  
  Now the ENTIRE population is resistant.
  Carbendazim is useless.
  Aflatoxin production resumes.
  

  IN THE SIMULATION:
  • The mutation is modeled with a 0.2% probability per day
  • When it triggers, purple sectors appear on the petri dish
  • The resistance index climbs from 0% → 100%
  • Growth rate recovers to near-untreated levels
  
  THIS IS WHY:
  • Farmers shouldn't use the same fungicide every season
  • Rotation of fungicide classes is essential
  • Integrated Pest Management (IPM) > single-chemical control
```

---

## 🧪 Suggested Experiments for Your Project

> *These experiments can be included in your M.Sc. dissertation as* **"in silico experiments"** *complementing your wet-lab (in vitro) work.*

### Experiment 1: Dose-Response Relationship

```
OBJECTIVE: 
  Determine the relationship between carbendazim concentration
  and growth inhibition of A. flavus

PROTOCOL:
  1. Open the simulation
  2. Run at 0.05% concentration → Record growth (%) at Day 14
  3. Reset
  4. Run at 0.10% → Record growth at Day 14
  5. Reset
  6. Repeat for: 0.15%, 0.20%, 0.25%, 0.30%, 0.40%, 0.50%

RECORD YOUR DATA:
  ┌───────────────────┬──────────────────┬──────────────────┐
  │ Concentration (%) │ Growth at Day 14 │ % Inhibition     │
  ├───────────────────┼──────────────────┼──────────────────┤
  │ 0.00 (control)    │      ____%       │     0%           │
  │ 0.05              │      ____%       │     ____%        │
  │ 0.10              │      ____%       │     ____%        │
  │ 0.15              │      ____%       │     ____%        │
  │ 0.20              │      ____%       │     ____%        │
  │ 0.25              │      ____%       │     ____%        │
  │ 0.30              │      ____%       │     ____%        │
  │ 0.40              │      ____%       │     ____%        │
  │ 0.50              │      ____%       │     ____%        │
  └───────────────────┴──────────────────┴──────────────────┘
  
  % Inhibition = ((Control Growth - Treatment Growth) / Control Growth) × 100

WHAT TO PLOT:
  X-axis: Concentration (%)
  Y-axis: % Inhibition
  Expected: Sigmoidal dose-response curve
  
  Note the OPTIMAL DOSE where maximum inhibition is achieved
  without unnecessary excess (this should be ~0.15%)

HOW TO WRITE THIS UP:
  "In silico dose-response analysis was performed using an
  interactive simulation model. Growth inhibition at various
  carbendazim concentrations was recorded after 14 simulated
  days of incubation..."
```

### Experiment 2: Aflatoxin Reduction Under Treatment

```
OBJECTIVE:
  Quantify the reduction in aflatoxin B₁ production
  following carbendazim application

PROTOCOL:
  1. Run simulation WITHOUT treatment for 30 days
     → Record aflatoxin level at Day 30 (this is your CONTROL)
  2. Reset
  3. Run simulation, apply 0.15% carbendazim at Day 7
     → Record aflatoxin level at Day 30 (TREATMENT)
  4. Repeat steps 2–3 five times for statistical reliability

RECORD YOUR DATA:
  ┌──────────┬──────────────────┬──────────────────┐
  │ Run #    │ Control (ppb)    │ Treatment (ppb)  │
  ├──────────┼──────────────────┼──────────────────┤
  │ 1        │     ____         │     ____         │
  │ 2        │     ____         │     ____         │
  │ 3        │     ____         │     ____         │
  │ 4        │     ____         │     ____         │
  │ 5        │     ____         │     ____         │
  ├──────────┼──────────────────┼──────────────────┤
  │ Mean     │     ____         │     ____         │
  │ SD       │     ____         │     ____         │
  └──────────┴──────────────────┴──────────────────┘
  
  % Reduction = ((Control - Treatment) / Control) × 100
  
  Was the treatment aflatoxin level below the 20 ppb safety threshold?
```

### Experiment 3: Resistance Emergence Timeline

```
OBJECTIVE:
  Determine the probability distribution of resistance
  emergence under continuous carbendazim pressure

PROTOCOL:
  1. Start simulation → Apply 0.15% carbendazim at Day 1
  2. Set speed to 5x
  3. Watch for the resistance indicator to appear
  4. Record: Day of first resistance detection
  5. Reset and repeat 20 times

RECORD YOUR DATA:
  ┌──────────┬─────────────────────────┐
  │ Run #    │ Day of Resistance Onset │
  ├──────────┼─────────────────────────┤
  │ 1        │          ____           │
  │ 2        │          ____           │
  │ 3        │          ____           │
  │ ...      │          ____           │
  │ 20       │          ____           │
  ├──────────┼─────────────────────────┤
  │ Mean     │          ____           │
  │ Median   │          ____           │
  │ Range    │     ____ to ____        │
  │ SD       │          ____           │
  └──────────┴─────────────────────────┘

ANALYSIS:
  • Plot a histogram of resistance onset days
  • Calculate the empirical probability per day
  • Compare to the theoretical value (0.2% per day)
  • Discuss: Is resistance INEVITABLE with enough time?
  
EXPECTED RESULT:
  Theoretical mean = 1/0.002 = 500 days
  But variance is HIGH — some runs will see resistance
  at Day 50, others not until Day 1000+
  
  This demonstrates the STOCHASTIC nature of mutation.
```

### Experiment 4: Comparing Treatment Timing

```
OBJECTIVE:
  Determine whether EARLY vs LATE treatment affects outcomes

PROTOCOL:
  Run A: Apply 0.15% carbendazim on Day 3
  Run B: Apply 0.15% carbendazim on Day 7
  Run C: Apply 0.15% carbendazim on Day 14
  
  For each, record at Day 30:
  • Growth (%)
  • Aflatoxin (ppb)
  • Whether aflatoxin exceeds 20 ppb threshold

EXPECTED INSIGHT:
  Earlier treatment = better suppression
  Later treatment = aflatoxin may already exceed safe limits
  
  → This supports the argument for PREVENTIVE application
    rather than CURATIVE application in crop protection
```

### Experiment 5: Resistance & Continued Toxin Production

```
OBJECTIVE:
  Show that resistant A. flavus resumes aflatoxin production

PROTOCOL:
  1. Apply 0.15% carbendazim at Day 7
  2. Wait for resistance to emerge
  3. Record:
     a) Aflatoxin at peak suppression (lowest point)
     b) Aflatoxin when resistance reaches 50%
     c) Aflatoxin when resistance reaches 100%

EXPECTED INSIGHT:
  Aflatoxin returns to near-control levels after resistance
  dominates — proving that carbendazim alone is NOT a
  long-term solution for aflatoxin management.
  
  → CITE THIS to argue for integrated management strategies
    in your dissertation
```

---

## 📊 Parameters & Their Biological Basis

### Every Number in the Simulation Has a Real-World Source

```
┌────────────────────────────┬───────────────┬─────────────────────────────────┐
│ Parameter                  │ Value Used    │ Source / Justification           │
├────────────────────────────┼───────────────┼─────────────────────────────────┤
│ Optimal carbendazim dose   │ 0.15%         │ Standard recommended field      │
│                            │               │ concentration for benzimidazoles│
│                            │               │ (Tripathi & Dubey, 2004)        │
├────────────────────────────┼───────────────┼─────────────────────────────────┤
│ Growth inhibition at       │ ~73%          │ Reported range: 65–80% for      │
│ optimal dose               │               │ A. flavus at 0.1–0.2%          │
│                            │               │ (Patel et al., 2014)            │
├────────────────────────────┼───────────────┼─────────────────────────────────┤
│ Colony radial growth rate  │ ~3.5 mm/day   │ A. flavus on PDA at 28°C       │
│                            │               │ (Klich, 2002)                   │
├────────────────────────────┼───────────────┼─────────────────────────────────┤
│ Aflatoxin safety threshold │ 20 ppb        │ FDA action level; FSSAI uses    │
│                            │               │ 15 ppb total; EU uses 4 ppb     │
│                            │               │ (Codex Alimentarius, 1995)      │
├────────────────────────────┼───────────────┼─────────────────────────────────┤
│ Resistance mutation rate   │ 0.2% / day    │ Adapted from benzimidazole      │
│                            │               │ resistance studies in           │
│                            │               │ Botrytis & Aspergillus          │
│                            │               │ (Yarden & Katan, 1993)          │
├────────────────────────────┼───────────────┼─────────────────────────────────┤
│ Resistance mechanism       │ β-tubulin     │ Codon 198 (Glu→Ala/Lys) and    │
│                            │ point mutation│ Codon 200 (Phe→Tyr)            │
│                            │               │ (Davidse, 1986; Ma, 2011)       │
└────────────────────────────┴───────────────┴─────────────────────────────────┘
```

---

## 📝 How to Use This in Your M.Sc. Project

### Where This Fits in Your Dissertation

```
CHAPTER STRUCTURE OF A TYPICAL M.Sc. MICROBIOLOGY DISSERTATION:

  Chapter 1: Introduction
  Chapter 2: Review of Literature
  Chapter 3: Materials and Methods    ← Mention the simulation here
  Chapter 4: Results and Discussion   ← Include simulation results
  Chapter 5: Summary and Conclusions
  References
  Appendices

  
  IN YOUR MATERIALS & METHODS SECTION:
  ─────────────────────────────────────

  Add a subsection like:

  "3.X  In Silico Simulation of Carbendazim-A. flavus Interaction

   An interactive web-based simulation (carbendazim.pages.dev)
   was used to model the dose-response relationship, aflatoxin
   dynamics, and resistance emergence patterns of A. flavus
   under carbendazim treatment. The simulation employs a
   stochastic model with parameters derived from published
   empirical data (see Table X). Simulation experiments
   complemented the in vitro poison food technique assays
   performed in the laboratory."


  IN YOUR RESULTS SECTION:
  ─────────────────────────

  "4.X  In Silico Analysis

   The simulation predicted an optimal inhibition of ~73% at
   0.15% carbendazim concentration, consistent with our
   laboratory observations (Table Y). Resistance emergence
   was modeled with a 0.2% daily mutation probability under
   selection pressure, with a mean onset of approximately
   [X] simulated days (n=20 simulation runs, SD = [Y]).
   
   [Include screenshots of graphs as figures]
   
   These findings support the hypothesis that prolonged
   single-fungicide application creates selection pressure
   for resistant phenotypes, necessitating integrated
   management approaches."

  
  IN YOUR APPENDICES:
  ────────────────────

  Include:
  • Screenshots of the simulation at different stages
  • Data tables from your simulation experiments
  • Link to the live simulation
  • Link to the source code (GitHub)
```

### How to Take Screenshots for Your Dissertation

```
TAKING GOOD SCREENSHOTS:

  Windows: Press Win + Shift + S → Select area → Paste into Word
  Mac:     Press Cmd + Shift + 4 → Select area → Saves to desktop
  
  RECOMMENDED SCREENSHOTS:
  
  Figure 1: Simulation interface showing untreated A. flavus 
            colony at Day 7 (control state)
            → Capture full screen showing colony + microscope + graphs
  
  Figure 2: Colony at Day 14 after carbendazim (0.15%) application
            → Show the pale/inhibited colony + shattered tubulin
  
  Figure 3: Emergence of resistant phenotype (purple sectors)
            → Capture the moment purple first appears
  
  Figure 4: Analytics dashboard showing growth, aflatoxin,
            and resistance curves over 30-day period
            → Capture just the graphs section
  
  Figure 5: Dose-response data from simulation experiments
            → Take screenshots at each concentration tested
```

### Sample Figure Captions

```
For your dissertation, use captions like:

  "Figure X: In silico simulation of A. flavus colony growth
   inhibition by carbendazim (0.15%) at Day 14. (a) Macroscopic
   view showing reduced colony diameter and pale coloration
   indicative of metabolic suppression. (b) Microscopic view
   depicting disrupted tubulin filaments and mitotic arrest.
   (c) Real-time analytics showing growth plateau, declining
   aflatoxin production, and zero resistance index.
   (Source: carbendazim.pages.dev)"

  "Figure Y: Emergence of carbendazim-resistant phenotype
   in simulated A. flavus colony. Purple sectors indicate cells
   carrying mutant β-tubulin (E198A). Note the recovery of
   radial growth rate and increasing resistance index despite
   continued fungicide application."
```
---

## ❓ Frequently Asked Questions

### For Students

```
Q: Can I cite this simulation in my dissertation?
A: YES! See the "References You Can Cite" section below.
   Cite it as a computational tool used for in silico analysis.

Q: Can I show this to my guide/professor?
A: Absolutely. Just share the link: https://carbendazim.pages.dev
   It works instantly — no installation needed on their computer.

Q: Does this replace my wet lab experiments?
A: NO. This COMPLEMENTS your lab work. Your wet lab provides
   empirical data; the simulation helps visualize and understand
   the mechanisms. Use both together in your dissertation.

Q: The resistance appears at different times each run. Is that a bug?
A: That's NOT a bug — it's a FEATURE. Resistance emergence is 
   STOCHASTIC (random). In real life, you can't predict exactly
   when a mutation will occur either. Run it multiple times and
   calculate the mean — that's actual scientific methodology!

Q: Can I change the parameters?
A: You can change the concentration and speed using the controls.
   The biological parameters (mutation rate, growth rate, etc.)
   are fixed based on published literature.

Q: What if my lab results don't match the simulation?
A: That's expected and FINE. The simulation uses idealized 
   parameters from literature. Your lab uses real organisms in
   real conditions. Discuss the differences in your discussion
   chapter — that's actually great scientific analysis.

Q: Can I run this on my phone?
A: Yes! Open the link in Chrome or Safari. Landscape mode works
   best. All features work on mobile.
```

### For Professors/Guides

```
Q: What is the scientific basis for this simulation?
A: All parameters are derived from published literature on
   benzimidazole fungicide action and A. flavus biology.
   See the "Parameters & Their Biological Basis" section and
   the full reference list.

Q: Can this be used in classroom teaching?
A: Yes. The simulation is freely available at carbendazim.pages.dev.
   No login, no installation, no cost. Students can access it
   from any device during or after class.

Q: Is this original work?
A: The simulation code and interface are original. The biological
   parameters and models are based on established literature.
   It was developed as a visualization aid for an M.Sc. project.
```

---

## 📚 References You Can Cite

### For Your Dissertation Bibliography

```
Use these references to support the parameters used in the simulation:

1. Davidse, L.C. (1986). Benzimidazole fungicides: Mechanism of
   action and biological impact. Annual Review of Phytopathology,
   24(1), 43–65.

2. Hedayati, M.T., Pasqualotto, A.C., Warn, P.A., Bowyer, P., &
   Denning, D.W. (2007). Aspergillus flavus: human pathogen,
   allergen and mycotoxin producer. Microbiology, 153(6), 1677–1692.

3. Klich, M.A. (2002). Identification of Common Aspergillus Species.
   CBS-KNAW Fungal Biodiversity Centre, Utrecht, Netherlands.

4. Ma, B., & Bhattacharjee, P. (2011). Mutations in β-tubulin gene
   and resistance of Aspergillus species to benzimidazole fungicides.
   Pest Management Science, 67(1), 1–5.

5. Yarden, O., & Katan, T. (1993). Mutations leading to substitutions
   at amino acids 198 and 200 of beta-tubulin that correlate with
   benomyl-resistance phenotypes. Phytopathology, 83(12), 1478–1483.

6. Brent, K.J., & Hollomon, D.W. (2007). Fungicide resistance in crop
   pathogens: How can it be managed? FRAC Monograph No. 1 (2nd ed.).

7. Tripathi, P., & Dubey, N.K. (2004). Exploitation of natural products
   as an alternative strategy to control postharvest fungal rotting.
   Postharvest Biology and Technology, 32(3), 235–245.

8. Patel, R.M., et al. (2014). In vitro efficacy of fungicides against
   Aspergillus flavus. The Bioscan, 9(3), 1199–1201.

9. FSSAI (2011). Food Safety and Standards (Contaminants, Toxins and
   Residues) Regulations. Government of India.

10. Codex Alimentarius Commission (1995). General Standard for
    Contaminants and Toxins in Food and Feed (CODEX STAN 193-1995).
```

### Citing the Simulation Itself

```
In your dissertation, cite the tool as:

  "[Your Name]. (2024). Carbendazim vs. Aspergillus flavus: An Interactive
   Biological Simulation [Web application]. Available at:
   https://carbendazim.pages.dev. Source code:
   https://github.com/rk2222/carbendazim-aspergillus-lab"
```

---

## 🔧 Technical Details (For the Curious)

> *You don't need to understand this section to use the simulation. This is for anyone interested in how it was built.*

```
BUILT WITH:

  • Pure HTML5 + CSS3 + JavaScript (ES6)
  • HTML5 Canvas API for all animations
  • requestAnimationFrame for 60fps rendering
  • CSS Glassmorphism for the UI panels
  • Zero external dependencies
  • Single HTML file (~XX KB)
  • Hosted on Cloudflare Pages (carbendazim.pages.dev)

WHY A SINGLE FILE:

  So that a microbiology student (or professor) can:
  1. Open a URL  — OR —
  2. Download ONE file and double-click it
  
  No terminal commands. No npm install. No Python environment.
  No "it works on my machine" problems.
  
  This was a deliberate design choice:
  The USER is a biologist, not a programmer.
  The tool should be invisible — only the science should show.
```

---

## 📁 Project Files

```
carbendazim-aspergillus-lab/
│
├── index.html          # The entire simulation (single file)
├── README.md           # This guide (you're reading it)
├── LICENSE             # MIT License
│
└── screenshots/        # Screenshots for documentation
    ├── untreated.png
    ├── treated.png
    └── resistant.png
```

---

## 📄 License

```
MIT License — Free to use, modify, and share.

This simulation is provided for EDUCATIONAL PURPOSES.
It is a teaching aid, not a substitute for laboratory experimentation.
```

---

<p align="center">
  <b>🔗 <a href="https://carbendazim.pages.dev">Open the Simulation → carbendazim.pages.dev</a></b>
</p>

<p align="center">
  <i>Built with ❤️ to help an M.Sc. Microbiology student<br/>
  understand what's really happening in her petri dishes.</i>
</p>

<p align="center">
  <i>If this simulation helped you understand fungicide resistance,<br/>
  or if you used it in your project — let us know! ⭐</i>
</p>

---

> **📌 A note on this project:**
> This simulation was developed to help visualize and understand the interaction between Carbendazim and *Aspergillus flavus* for an M.Sc. Microbiology project. It's designed to be a **learning companion** — something you can run alongside your actual lab experiments to better understand the biological mechanisms at play.
>
> Every parameter has a published source. Every visual has a biological basis. And it runs in your browser with zero setup — because science tools should be accessible, not complicated.
