# Prompty Color Style Guide

> **Tip:** Copy any HEX value by selecting the code block under each swatch.

<style>
  /* Simple responsive grid for swatches */
  .palette-grid {
    display: grid;
    gap: 1rem;
    grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
    margin-top: 1rem;
  }
  .swatch {
    border-radius: 0.75rem;
    overflow: hidden;
    box-shadow: 0 1px 4px rgba(0,0,0,0.08);
    transition: transform .15s ease;
  }
  .swatch:hover { transform: translateY(-4px); }
  .swatch-color { height: 96px; width: 100%; }
  .swatch-meta { padding: .5rem .75rem; font-size: .85rem; background: #fff; }
  .swatch-meta code { font-size: .75rem; display: block; margin-top: .25rem; text-align: center }
  h2 { margin-top: 2.5rem; font-size: 1.35rem; }
</style>

## 1 — Core Brand Colors

<div class="palette-grid">
  <div class="swatch">
    <div class="swatch-color" style="background:#2563EB;"></div>
    <div class="swatch-meta">Prompty Blue<br><code>#2563EB<br>HSL 221°, 81%, 56%</code></div>
  </div>
  <div class="swatch">
    <div class="swatch-color" style="background:#334155;"></div>
    <div class="swatch-meta">Slate Ink<br><code>#334155<br>HSL 210°, 26%, 26%</code></div>
  </div>
  <div class="swatch">
    <div class="swatch-color" style="background:#F9FAFB; border:1px solid #E5E7EB;"></div>
    <div class="swatch-meta">Cloud White<br><code>#F9FAFB<br>HSL 210°, 20%, 98%</code></div>
  </div>
</div>

## 2 — Variant Accent Shades (Normal<br>Dark<br>Light)

<h2>McPromptFace</h2>
<div class="palette-grid">
  <div class="swatch">
    <div class="swatch-color" style="background:#14B8A6;"></div>
    <div class="swatch-meta">Teal Spark (Normal)<br><code>#14B8A6<br>HSL 173°, 80%, 39%</code></div>
  </div>
  <div class="swatch">
    <div class="swatch-color" style="background:#08786B;"></div>
    <div class="swatch-meta">Teal Spark Dark<br><code>#08786B<br>HSL 173°, 88%, 25%</code></div>
  </div>
  <div class="swatch">
    <div class="swatch-color" style="background:#DBF0ED;"></div>
    <div class="swatch-meta">Teal Spark Light<br><code>#DBF0ED<br>HSL 171°, 41%, 90%</code></div>
  </div>
</div>

<h2>McProjectFace</h2>
<div class="palette-grid">
  <div class="swatch">
    <div class="swatch-color" style="background:#6366F1;"></div>
    <div class="swatch-meta">Indigo Beam (Normal)<br><code>#6366F1<br>HSL 239°, 84%, 67%</code></div>
  </div>
  <div class="swatch">
    <div class="swatch-color" style="background:#05077B;"></div>
    <div class="swatch-meta">Indigo Beam Dark<br><code>#05077B<br>HSL 239°, 92%, 25%</code></div>
  </div>
  <div class="swatch">
    <div class="swatch-color" style="background:#DBDBF0;"></div>
    <div class="swatch-meta">Indigo Beam Light<br><code>#DBDBF0<br>HSL 240°, 41%, 90%</code></div>
  </div>
</div>

<h2>McJourneyFace</h2>
<div class="palette-grid">
  <div class="swatch">
    <div class="swatch-color" style="background:#D946EF;"></div>
    <div class="swatch-meta">Fuchsia Pulse (Normal)<br><code>#D946EF<br>HSL 289°, 80%, 60%</code></div>
  </div>
  <div class="swatch">
    <div class="swatch-color" style="background:#630878;"></div>
    <div class="swatch-meta">Fuchsia Pulse Dark<br><code>#630878<br>HSL 289°, 88%, 25%</code></div>
  </div>
  <div class="swatch">
    <div class="swatch-color" style="background:#ECDBF0;"></div>
    <div class="swatch-meta">Fuchsia Pulse Light<br><code>#ECDBF0<br>HSL 289°, 41%, 90%</code></div>
  </div>
</div>

<h2>McResearchFace</h2>
<div class="palette-grid">
  <div class="swatch">
    <div class="swatch-color" style="background:#F59E0B;"></div>
    <div class="swatch-meta">Amber Focus (Normal)<br><code>#F59E0B<br>HSL 42°, 94%, 50%</code></div>
  </div>
  <div class="swatch">
    <div class="swatch-color" style="background:#805900;"></div>
    <div class="swatch-meta">Amber Focus Dark<br><code>#805900<br>HSL 42°, 100%, 25%</code></div>
  </div>
  <div class="swatch">
    <div class="swatch-color" style="background:#F1EADA;"></div>
    <div class="swatch-meta">Amber Focus Light<br><code>#F1EADA<br>HSL 42°, 45%, 90%</code></div>
  </div>
</div>

## 3 — Extended Palette

<div class="palette-grid">
  <div class="swatch">
    <div class="swatch-color" style="background:#10B981;"></div>
    <div class="swatch-meta">Emerald Verdict (Success)<br><code>#10B981<br>HSL 162°, 72%, 37%</code></div>
  </div>
  <div class="swatch">
    <div class="swatch-color" style="background:#F97316;"></div>
    <div class="swatch-meta">Sunset Caution (Warning)<br><code>#F97316<br>HSL 25°, 94%, 53%</code></div>
  </div>
  <div class="swatch">
    <div class="swatch-color" style="background:#EF4444;"></div>
    <div class="swatch-meta">Rose Alert (Danger)<br><code>#EF4444<br>HSL 0°, 84%, 58%</code></div>
  </div>
  <div class="swatch">
    <div class="swatch-color" style="background:#0EA5E9;"></div>
    <div class="swatch-meta">Sky Hint (Info)<br><code>#0EA5E9<br>HSL 198°, 86%, 48%</code></div>
  </div>
  <div class="swatch">
    <div class="swatch-color" style="background:#F3F4F6; border:1px solid #E5E7EB;"></div>
    <div class="swatch-meta">Gray 100 (Neutral‑Light)<br><code>#F3F4F6<br>HSL 210°, 20%, 96%</code></div>
  </div>
  <div class="swatch">
    <div class="swatch-color" style="background:#9CA3AF;"></div>
    <div class="swatch-meta">Gray 400 (Neutral‑Mid)<br><code>#9CA3AF<br>HSL 218°, 11%, 65%</code></div>
  </div>
  <div class="swatch">
    <div class="swatch-color" style="background:#374151;"></div>
    <div class="swatch-meta">Gray 700 (Neutral‑Dark)<br><code>#374151<br>HSL 210°, 15%, 29%</code></div>
  </div>
</div>

## 4 — Accessibility Notes

* **Contrast:** Prompty Blue on Cloud White and Slate Ink on Cloud White exceed WCAG AA for body text.
* **Swatch Borders:** Very light tones (e.g., Cloud White, Gray 100, Light variants) include a subtle gray outline to remain visible.
* **Guidelines:** When using accent colors for large backgrounds, overlay text in Cloud White or Slate Ink to maintain a 4.5 : 1 contrast ratio.

---

<small>© 2025 Prompty AGF  |  Generated <time datetime="2025-05
