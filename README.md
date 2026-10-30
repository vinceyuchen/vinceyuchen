<a href="https://github.com/vinceyuchen">
  <img src="assets/profile-hero.svg" width="100%" alt="Vince. Software Engineering and Applied AI. Building reliable intelligent systems and software products." />
</a>

## Selected work

> ### 01 · [Perceptinet](https://github.com/vinceyuchen/Perceptinet)
>
> **Cooperative perception & risk-aware braking in CARLA.**
>
> [Demos](https://github.com/vinceyuchen/Perceptinet#demo-showcase) · [Architecture](https://github.com/vinceyuchen/Perceptinet/blob/main/docs/ENGINEERING_NOTES.md) · [Verified Python checks](https://github.com/vinceyuchen/Perceptinet/actions/workflows/core-checks.yml)

<table>
  <tr>
    <td width="50%" align="center" valign="top">
      <a href="https://github.com/vinceyuchen/Perceptinet/blob/main/assets/scenario-1.mp4">
        <img src="https://raw.githubusercontent.com/vinceyuchen/Perceptinet/main/assets/scenario-1.gif" width="100%" alt="Real CARLA recording: clear-weather cooperative perception, live dual-camera feeds and dashboard showing the ego stop." />
      </a>
      <br />
      <strong>Scenario 01 · Cooperative baseline</strong>
      <br />
      <sub>Clear weather · Normal V2I · Controller stop</sub>
      <br />
      <a href="https://github.com/vinceyuchen/Perceptinet/blob/main/assets/scenario-1.mp4">Full recording (MP4)</a>
    </td>
    <td width="50%" align="center" valign="top">
      <a href="https://github.com/vinceyuchen/Perceptinet/blob/main/assets/scenario-2.mp4">
        <img src="https://raw.githubusercontent.com/vinceyuchen/Perceptinet/main/assets/scenario-2.gif" width="100%" alt="Real CARLA recording: rainy simulation with injected V2I disruption and dashboard reporting simulated geometric contact." />
      </a>
      <br />
      <strong>Scenario 02 · V2I stress test</strong>
      <br />
      <sub>Rain · Injected delay/loss · CONTACT (SIM)</sub>
      <br />
      <a href="https://github.com/vinceyuchen/Perceptinet/blob/main/assets/scenario-2.mp4">Full recording (MP4)</a>
    </td>
  </tr>
</table>

<sub>Recorded CARLA experiments, not concept renders. V2I faults are injected separately from weather. Scenario 02's CONTACT (SIM) indicates kinematic footprint overlap, not a physics-validated collision.</sub>

<details>
<summary>Read implementation details and experimental scope</summary>

**What I built:** Dual-camera YOLO26n perception, simulation-assisted localization, timestamped V2I delivery with fault injection, spatial/temporal fusion, TTC risk assessment, deterministic braking, and live dashboards.

**Evaluation:** Clear-weather and degraded-V2I scenarios with per-cycle telemetry. The ego uses kinematic motion; these experiments do not validate physical collision avoidance.

[Watch both recordings](https://github.com/vinceyuchen/Perceptinet#demo-showcase) · [Source code](https://github.com/vinceyuchen/Perceptinet)

</details>

---

> ### 02 · [Behind the Shelter Doors](https://github.com/vinceyuchen/animal-shelter-dv2)
>
> **Interactive data storytelling for animal shelter outcomes.**
>
> [Live website](https://vinceyuchen.github.io/animal-shelter-dv2/) · [Design methodology](https://github.com/vinceyuchen/animal-shelter-dv2/blob/main/design/visual-design-system.md) · [Source code](https://github.com/vinceyuchen/animal-shelter-dv2)

<details>
<summary>View real website screenshot and engineering highlights</summary>

<a href="https://vinceyuchen.github.io/animal-shelter-dv2/">
  <img src="https://raw.githubusercontent.com/vinceyuchen/animal-shelter-dv2/main/assets/real-site-preview.png" width="680" alt="Real Chromium screenshot of the published Behind the Shelter Doors data visualization, showing the website and its Australian map." />
</a>

**What I built:** A responsive single-page data story with 14 Vega/Vega-Lite visualizations, interactive comparisons, documented source boundaries, and automated visual and data-integrity checks.

[Explore the interactive site](https://vinceyuchen.github.io/animal-shelter-dv2/) · [Project repository](https://github.com/vinceyuchen/animal-shelter-dv2)

</details>

---

### Technical focus

**Languages:** Python · JavaScript · TypeScript

**Systems & vision:** CARLA · YOLO26n · OpenCV · sensor fusion · V2I modeling

**Web & engineering:** HTML/CSS · Vega-Lite · Git · GitHub Actions · automated testing

### Contact

[Open a project inquiry](https://github.com/vinceyuchen/vinceyuchen/issues/new?template=project-inquiry.yml) for project questions and technical collaboration. GitHub Issues are public; please don't include private information.
