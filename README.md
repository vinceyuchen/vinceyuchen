<div align="center">
  <a href="https://github.com/vinceyuchen">
    <img src="assets/profile-hero.svg" width="100%" alt="Vince — Build what matters. Intelligent systems, reliable software, clear design." />
  </a>
  <p><strong>Software Engineering · Applied AI · Autonomous Systems</strong></p>
  <p>I build intelligent systems and interactive software — from working prototypes to measurable results.</p>
  <p>
    <a href="#selected-work">Projects</a> ·
    <a href="https://github.com/vinceyuchen/Perceptinet#demo-showcase">CARLA demos</a> ·
    <a href="https://vinceyuchen.github.io/animal-shelter-dv2/">Live experience</a> ·
    <a href="#contact-and-collaboration">Contact</a>
  </p>
</div>

---

I'm Vince, a software developer working across **computer vision, simulation, and data-driven interfaces**. I focus on the entire engineering lifecycle: designing components, implementing the pipeline, validating behavior, and making results understandable.

## Selected work

### 01 / [Perceptinet](https://github.com/vinceyuchen/Perceptinet)

**Cooperative perception & risk-aware braking in CARLA**

`Python` · `CARLA` · `YOLO26n` · `OpenCV` · `Sensor Fusion`

<a href="https://github.com/vinceyuchen/Perceptinet#demo-showcase">
  <img src="https://raw.githubusercontent.com/vinceyuchen/Perceptinet/main/assets/scenario-1.gif" width="620" alt="Recorded CARLA simulation showing onboard and roadside detections, live dashboard and ego braking." />
</a>

<sub>Recorded CARLA demonstration · Click to view the clear-weather and communication-stress scenarios.</sub>

Built an **end-to-end perception → communication → fusion → risk → braking** simulation: dual-camera YOLO26n detections, simulation-assisted localization, timestamped V2I observations, TTC-based assessment, and live Driver/Pro dashboards.

- **Reliability engineering:** simulation-time packet queues, latency, loss, blackouts, stale-observation rejection, and temporal fusion.
- **Evaluation:** per-cycle JSON/CSV telemetry, controlled scenario comparisons, and focused CPU-only regression tests.
- **Scope:** kinematic simulated braking; no claim of real-vehicle collision-avoidance validation.

**[Watch both demos](https://github.com/vinceyuchen/Perceptinet#demo-showcase)** · **[Architecture & trade-offs](https://github.com/vinceyuchen/Perceptinet/blob/main/docs/ENGINEERING_NOTES.md)** · **[Code & tests](https://github.com/vinceyuchen/Perceptinet)**

### 02 / [Behind the Shelter Doors](https://github.com/vinceyuchen/animal-shelter-dv2)

**Interactive data visualization & storytelling**

`JavaScript` · `Vega-Lite` · `HTML` · `CSS`

<a href="https://vinceyuchen.github.io/animal-shelter-dv2/">
  <img src="https://raw.githubusercontent.com/vinceyuchen/animal-shelter-dv2/main/assets/project-preview.svg" width="620" alt="Editorial design preview illustrating the project's geographic comparisons, animal-outcome charts, and trend explorations." />
</a>

<sub>Design-based illustration, not a captured screenshot or real chart values. Click for the interactive site.</sub>

Created a responsive, single-page data story with **14 Vega / Vega-Lite charts** examining Australian RSPCA outcomes and separately documented regional case studies.

- **Product engineering:** interactive visualizations, responsive layouts, filters, and guided navigation.
- **Data integrity:** documented dataset boundaries, chart semantics, and design/audit checks.

**[Explore live website](https://vinceyuchen.github.io/animal-shelter-dv2/)** · **[Source & methodology](https://github.com/vinceyuchen/animal-shelter-dv2)**

## Core toolkit

| Focus | Technologies |
| :--- | :--- |
| **Languages** | Python · JavaScript · TypeScript |
| **Computer vision** | Ultralytics YOLO26n · OpenCV · NumPy |
| **Systems & simulation** | CARLA · V2I modeling · sensor fusion |
| **Web & engineering** | HTML/CSS · Vega-Lite · Git · GitHub Actions · automated tests |

## Contact and collaboration

For questions about my public projects or potential technical collaboration, **[open a project inquiry](https://github.com/vinceyuchen/vinceyuchen/issues/new?template=project-inquiry.yml)**.

<sub>This creates a public GitHub Issue, not a private message. Please do not post confidential information. Personal contact and résumé links are intentionally omitted for now.</sub>

<div align="center">

---

<sub>Explore the implementation, the demos, and the design decisions behind the work.</sub>

[Perceptinet](https://github.com/vinceyuchen/Perceptinet) · [Live visualization](https://vinceyuchen.github.io/animal-shelter-dv2/) · [All repositories](https://github.com/vinceyuchen?tab=repositories)

</div>
