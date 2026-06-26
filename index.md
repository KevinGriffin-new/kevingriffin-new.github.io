---
title: Kevin Griffin
type: page
summary: Surveys, Sensors & Systems — geomatics, drones, electronics, and code.
---

<p class="tagline">Surveys, Sensors &amp; Systems</p>
<p class="sub">Intersections and integrations of odd problems.</p>

I work where geomatics, robotics, and electronics meet — the kind of jobs that need a survey crew, a soldering iron, and a few thousand lines of code in roughly equal measure.

## What I work on

<p class="field"><strong>Geomatics.</strong> Field surveys, GNSS, lidar, photogrammetry — turning sites into data and data into something a builder, planner, or scientist can act on.</p>

<p class="field"><strong>Drone design — aquatic and aerial.</strong> Custom airframes and ROV / USV platforms built to be <em>affordable, accessible, and repairable</em>. Usually sensor-carrying: bathymetry, mapping, inspection.</p>

<p class="field"><strong>Electronics.</strong> Bench-built sensor boards, power, and comms — for systems that have to keep working in cold rain, hot sun, and salt water.</p>

<p class="field"><strong>Computing.</strong> Code to drive the sensors and arrange the captures, plus enough post-processing to make the bits digestible. Firmware on the boards, scripts in the field. A weakness for Lisp.</p>

## Selected work

A throughline runs through these: take a specialized, expensive survey
workflow and rebuild it as something open, scriptable, and cheap enough for a
small crew — or a citizen scientist — to actually use.

<p class="field"><strong><a href="https://github.com/KevinGriffin-new/opencad-landsurvey-plugin">OpenCAD LandSurvey plugin</a></strong> — a land-survey add-on for Open CAD Studio, written in Rust as a native plugin: survey points, PNEZD import/export, COGO, and recognized-plan import. The survey toolbox most people pay four figures a seat for, as a free, listed extension.</p>

<p class="field"><strong><a href="https://github.com/KevinGriffin-new/plat2json">plat2json</a></strong> — turns a survey-plat PDF into structured plan-JSON geometry that CAD tools (including the LandSurvey plugin) can ingest. The unglamorous, genuinely hard middle step between a published plan and a working drawing.</p>

<p class="field"><strong><a href="https://github.com/KevinGriffin-new/shoalkit">shoalkit</a></strong> — a linear and Stokes wave-transformation calculator with theory gating, wrapped so the results are citable rather than black-box. Coastal numbers you can put your name next to.</p>

<p class="field"><strong><a href="https://github.com/KevinGriffin-new/geom2120-trainer">geom2120-trainer</a></strong> — a gamified, single-file study trainer for survey computations, using backward-chained step drills. Built to teach the math by making you walk every step, not just trust the answer.</p>

More on <a href="https://github.com/KevinGriffin-new">GitHub</a>.

## Approach

The price of hardware is tending toward zero. The interesting work isn't squeezing one more dollar out of a sensor — it's making the resulting tools **affordable, accessible, and repairable** enough that citizen scientists, makers, hobbyists, and small field crews can pick them up, fix them, and adapt them.

If we're going to spend the next decade instrumenting rivers, coastlines, forests, and farms, we may as well keep the journey interesting and useful for the people doing the looking.

## Contact

- Email — [kevin@slowcado.ca](mailto:kevin@slowcado.ca)
- GitHub — [@KevinGriffin-new](https://github.com/KevinGriffin-new)

---

<small>Built with <a href="https://collards.kingcons.io/">Collards</a>, deployed via GitHub Actions.</small>
