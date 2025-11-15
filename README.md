# get-in-the-robot-shinji
You read that right, this repo is made so Gendo doesnt need to convince Shinji to get in the robot

# Get in the Robot Shinji: Exploring Factors that Encourage Users to Get Into Robot Cockpits

## Abstract

This project investigates the factors that motivate users to enter robot cockpits, emphasizing the transition from observer to embodied operator. While cockpit and teleoperation research often focuses on usability once users are already inside, little is known about the perceptual, spatial, and affective cues that *invite* users to step in. Using virtual reality (VR) as both simulation and design probe, this work explores how cockpit form, openness, lighting, affordances, narrative framing, and perceived safety influence willingness to enter. The project integrates insights from robotics HCI, speculative cockpit design, space ergonomics, and immersive interaction. Four phases guide the study: (1) a literature review spanning HRI, space habitat design, and VR affordances; (2) a VR ecological validity and space-readiness pilot; (3) development of multiple VR cockpit prototypes; and (4) a mixed-methods evaluation. Inspired by SPACE CHI methodologies, this project aims to produce design guidelines for future robot and space cockpit systems.

---

## Project Concept

“Get in the Robot Shinji” explores how humans decide to step into robot cockpits—an action shaped by trust, curiosity, spatial cues, and immersive framing. Science fiction frames cockpit entry as symbolic and emotional; future robotics, teleoperation, and space systems require evidence-based design of what encourages people to take this step.

Using VR, this project examines:

* Spatial invitation cues
* Cockpit transparency and openness
* Environmental mood (lighting, sound, motion)
* Perceived safety and comfort
* Psychological readiness
* Narrative framing and context

The goal is to contribute a design framework for future cockpit interfaces across robotics, aerospace, and immersive systems.

---

## Research Phases

### **Phase 1 — Literature Review**

A systematic review across:

* HRI cockpit and teleoperation station design
* Space habitat and spacecraft ergonomics
* VR affordance, spatial design, and invitation cues
* SPACE CHI research on readiness, immersion, and spatial comfort

**Output:** Annotated literature, design principles, and refined research questions.

---

### **Phase 2 — Ecological Validity & Space-Readiness Pilot**

A preliminary VR study examining:

* Whether VR effectively simulates cockpit approach and entry
* How immersion and spatial cues affect willingness to enter
* Adapted SPACE CHI metrics (readiness, spatial pressure, comfort)

**Output:** Verified measurement tools and prototype requirements.

---

### **Phase 3 — VR Cockpit Prototype Development**

Unity-based cockpit designs exploring:

* Open, semi-open, and enclosed forms
* Manual, hybrid, and gestural control metaphors
* Mood variations (lighting, color, audio, animation)
* Narrative contexts (robotics, space, exploration themes)

**Output:** An interactive VR prototype suite.

---

### **Phase 4 — Evaluation**

A mixed-methods experiment involving:

* Behavioral measures (hesitation time, approach patterns)
* Willingness-to-enter ratings
* Trust, perceived safety, and affect
* SPACE CHI-inspired readiness evaluation
* Semi-structured interviews

**Output:** Factors influencing cockpit entry + design guidelines.

---

## Repository Structure

```
get-in-the-robot-shinji/
├── README.md
├── LICENSE
├── .gitignore
├── unity-project/
│   ├── Assets/
│   ├── Packages/
│   └── ProjectSettings/
├── data/
│   ├── raw/
│   ├── processed/
│   └── analysis/
├── docs/
│   ├── literature/
│   ├── experiment-design/
│   └── figures/
└── scripts/
    ├── analysis/
    ├── kotlin/
    └── vr-prototype-utils/
```

---

## Kotlin Usage

Kotlin may be used for Android plugin development or utility scripts if needed.
Use the **`.kt`** extension:

```
scripts/kotlin/CockpitDataPlugin.kt
```

Potential uses:

* Unity Android plugins
* Telemetry or data logging utilities
* VR hardware interfacing
* Standalone tooling

---

## YAML Usage

YAML files use the **`.yml`** extension and serve three purposes:

### **1. GitHub Actions CI**

```
.github/workflows/unity-build.yml
```

### **2. Dataset Metadata**

```
data/metadata.yml
```

Example:

```yaml
experiment:
  name: Get in the Robot Shinji Study
  participants: 12
  conditions:
    - open_cockpit
    - semi_closed_cockpit
    - enclosed_cockpit
data_format:
  - timestamp
  - position
  - orientation
  - questionnaire_scores
```

### **3. Python Environment Setup**

```
environment.yml
```

Ensures reproducible analysis.

---

## License

Released under the **MIT License** to support open research and reproducibility.

---

## Contact

For questions or collaboration inquiries, please contact Jordan.

