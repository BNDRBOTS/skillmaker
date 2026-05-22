```markdown
# The Universal Skill Formula

A cross-platform reference document for engineers and developers 
building production-grade AI skills, system prompts, and behavioral 
directives across Claude, GPT-5.5, Gemini 3.x, DeepSeek V4, 
Llama 4, Mistral, and Qwen 3.

All specifications are cross-verified against official platform 
documentation. Updated May 2026. No boilerplate. No filler. 
No second pass needed.

## What's inside

- Platform-agnostic 9-block skill architecture
- Claude .skill file exact format and YAML rules
- GPT-5.5 outcome-first prompting (migration from legacy stacks)
- Gemini 3 system_instruction hierarchy and thinking levels
- DeepSeek V4 XML context tagging and mode selection
- Open-weight model patterns (Llama 4 / Mistral / Qwen 3)
- Copy-deploy cross-platform master template
- Awwwards/Behance-level design directive system
- Banned patterns table with replacements
- Zero-error pre-deployment QA checklist

## Usage

Open `universal-skill-formula.html` in any browser. No build 
step. No dependencies. No network required after load.

To swap the color theme, replace the `:root {}` block in the 
`<style>` tag with any combo from `THEMES.md`.

## Sources

- https://docs.claude.com
- https://platform.openai.com/docs/guides/prompt-engineering
- https://ai.google.dev/api/generate-content
- https://deepseekai.guide/tutorials/deepseek-prompt-engineering
- https://www.llama.com/docs/how-to-guides/prompting
```

---

**COMBO 1 — ACID CHROME**
Neon lime on void black. Cold, surgical, aggressive.
```css
:root {
  --bg: #050505;
  --surface: #0c0c0c;
  --surface2: #111111;
  --border: #1a1a1a;
  --border-hot: #b3ff00;
  --text: #f0f0e8;
  --muted: #555544;
  --accent: #b3ff00;
  --accent2: #ff2d55;
  --accent3: #b3ff00;
  --accent4: #ffffff;
  --claude: #b3ff00;
  --openai: #00ff88;
  --gemini: #00aaff;
  --deepseek: #b3ff00;
  --meta: #0099ff;
  --mistral: #ff2d55;
  --qwen: #cc44ff;
}
```

---

**COMBO 2 — INFRARED**
Deep crimson base, white-hot accents. Feels like a war room.
```css
:root {
  --bg: #080407;
  --surface: #110810;
  --surface2: #180d17;
  --border: #2a112a;
  --border-hot: #ff1744;
  --text: #f5e8f0;
  --muted: #6a3a60;
  --accent: #ff1744;
  --accent2: #ff6d00;
  --accent3: #ff4081;
  --accent4: #ffeb3b;
  --claude: #ff6d00;
  --openai: #69f0ae;
  --gemini: #40c4ff;
  --deepseek: #ff1744;
  --meta: #2979ff;
  --mistral: #ff6d00;
  --qwen: #e040fb;
}
```

---

**COMBO 3 — POLAR CHROME**
Ice blue-black, platinum text, electric cyan. Feels cryo, precision-grade.
```css
:root {
  --bg: #030810;
  --surface: #070f1c;
  --surface2: #0c1628;
  --border: #112035;
  --border-hot: #00d4ff;
  --text: #ddeeff;
  --muted: #2a4a6a;
  --accent: #00d4ff;
  --accent2: #7000ff;
  --accent3: #00ffcc;
  --accent4: #e8f4ff;
  --claude: #ff7043;
  --openai: #00d4ff;
  --gemini: #4488ff;
  --deepseek: #7000ff;
  --meta: #0088ff;
  --mistral: #ff5500;
  --qwen: #aa00ff;
}
```

---

**COMBO 4 — EMBER VAULT**
Near-black with ember amber. Feels like a Bloomberg terminal built by Dieter Rams.
```css
:root {
  --bg: #08070a;
  --surface: #0f0e13;
  --surface2: #151420;
  --border: #1e1c2e;
  --border-hot: #f5a623;
  --text: #ede8d8;
  --muted: #5a4e30;
  --accent: #f5a623;
  --accent2: #e8402a;
  --accent3: #f5c842;
  --accent4: #fff8e8;
  --claude: #f5a623;
  --openai: #4ddd99;
  --gemini: #5588ff;
  --deepseek: #f5a623;
  --meta: #3377ff;
  --mistral: #e8402a;
  --qwen: #cc55ff;
}
```
**README — How to swap a combo**

Find this line in the HTML file:
```
:root {
```
Select everything from that line through its closing `}` — that entire block. Replace it with any combo below. Save. Done. Nothing else touches.

---

**COMBO 5 — VOID MAGENTA**
Full black, blown-out magenta. Feels like a rave flyer designed by a Swiss typographer.
```css
:root {
  --bg: #020202;
  --surface: #090909;
  --surface2: #0f0f0f;
  --border: #1c1c1c;
  --border-hot: #ff00aa;
  --text: #f8eef6;
  --muted: #4a1a40;
  --accent: #ff00aa;
  --accent2: #00ffee;
  --accent3: #ff00aa;
  --accent4: #ffffff;
  --claude: #ff6688;
  --openai: #00ffcc;
  --gemini: #aa44ff;
  --deepseek: #ff00aa;
  --meta: #0088ff;
  --mistral: #ff4400;
  --qwen: #cc00ff;
}
```

---

**COMBO 6 — MOLTEN GOLD**
Obsidian base, searing gold. Hermès meets military intelligence.
```css
:root {
  --bg: #060504;
  --surface: #0e0b08;
  --surface2: #161108;
  --border: #221a08;
  --border-hot: #d4920a;
  --text: #f2e8cc;
  --muted: #5a4010;
  --accent: #d4920a;
  --accent2: #e03a1e;
  --accent3: #f2c84a;
  --accent4: #fff8e0;
  --claude: #e07030;
  --openai: #50c898;
  --gemini: #4488dd;
  --deepseek: #d4920a;
  --meta: #2266ee;
  --mistral: #e03a1e;
  --qwen: #aa44ff;
}
```

---

**COMBO 7 — CIRCUIT GHOST**
Washed graphite, electric seafoam, industrial serif energy. Ghostly precision.
```css
:root {
  --bg: #0a0c0b;
  --surface: #111410;
  --surface2: #181c16;
  --border: #222820;
  --border-hot: #00e5a0;
  --text: #ddeedd;
  --muted: #2a4438;
  --accent: #00e5a0;
  --accent2: #ff3366;
  --accent3: #44ffcc;
  --accent4: #e8fff4;
  --claude: #ff7755;
  --openai: #00e5a0;
  --gemini: #44aaff;
  --deepseek: #00e5a0;
  --meta: #2288ff;
  --mistral: #ff5533;
  --qwen: #bb44ff;
}
```

---

**COMBO 8 — COBALT BURN**
Deepest navy-black, cobalt electric, white-hot text. Feels like satellite telemetry.
```css
:root {
  --bg: #020408;
  --surface: #040810;
  --surface2: #080e1c;
  --border: #0c1830;
  --border-hot: #2255ff;
  --text: #eef2ff;
  --muted: #1a2860;
  --accent: #2255ff;
  --accent2: #ff2244;
  --accent3: #00ccff;
  --accent4: #ffffff;
  --claude: #ff6644;
  --openai: #00ddaa;
  --gemini: #2255ff;
  --deepseek: #5500ff;
  --meta: #0055ff;
  --mistral: #ff4422;
  --qwen: #8822ff;
}
```

---

**COMBO 9 — REDSHIFT**
Blood-black, maximum red, white type. Aggressive. Unapologetic. Tabloid energy.
```css
:root {
  --bg: #070204;
  --surface: #0f0408;
  --surface2: #160610;
  --border: #220818;
  --border-hot: #ff0022;
  --text: #fff0f2;
  --muted: #5a0820;
  --accent: #ff0022;
  --accent2: #ff6600;
  --accent3: #ff3355;
  --accent4: #ffffff;
  --claude: #ff6644;
  --openai: #00ff88;
  --gemini: #2288ff;
  --deepseek: #ff0022;
  --meta: #0066ff;
  --mistral: #ff6600;
  --qwen: #cc00ff;
}
```

---

**COMBO 10 — TUNGSTEN**
Near-white surface, charcoal ink, single orange signal. The Braun OS-400 of AI docs.
```css
:root {
  --bg: #f4f2ee;
  --surface: #eceae4;
  --surface2: #e2e0d8;
  --border: #ccc8be;
  --border-hot: #e84400;
  --text: #1a1816;
  --muted: #8a8278;
  --accent: #e84400;
  --accent2: #0044cc;
  --accent3: #e84400;
  --accent4: #000000;
  --claude: #e84400;
  --openai: #007744;
  --gemini: #0044cc;
  --deepseek: #e84400;
  --meta: #0055dd;
  --mistral: #cc3300;
  --qwen: #7700cc;
}
```

---

**COMBO 11 — NEON NOIR**
Darkest possible purple-black, neon yellow-green, poison accent. Cyberpunk minus the clichés.
```css
:root {
  --bg: #06040e;
  --surface: #0c0818;
  --surface2: #120d22;
  --border: #1c1438;
  --border-hot: #ccff00;
  --text: #eeeaff;
  --muted: #3a2868;
  --accent: #ccff00;
  --accent2: #ff0088;
  --accent3: #aaffaa;
  --accent4: #ffffff;
  --claude: #ff8844;
  --openai: #44ffaa;
  --gemini: #4488ff;
  --deepseek: #ccff00;
  --meta: #0077ff;
  --mistral: #ff4400;
  --qwen: #dd00ff;
}
```

---

**COMBO 12 — CHALK STORM**
White ground, storm grey depth, single electric blue spike. Muji hardware lab.
```css
:root {
  --bg: #f8f8f6;
  --surface: #efefec;
  --surface2: #e4e4e0;
  --border: #d0cfc8;
  --border-hot: #0033ff;
  --text: #111114;
  --muted: #8888a0;
  --accent: #0033ff;
  --accent2: #cc0044;
  --accent3: #0033ff;
  --accent4: #000022;
  --claude: #cc4422;
  --openai: #008844;
  --gemini: #0033ff;
  --deepseek: #5500ff;
  --meta: #0044cc;
  --mistral: #cc3300;
  --qwen: #8800cc;
}
```

---

**PRO TIP — Mixing signal colors**
`--border-hot` is the highest-attention color in the system — it outlines the formula blocks and active badges. Make it the color you want readers to *feel* first. Everything else can be subordinate. If `--border-hot` and `--accent` are the same hue, the doc reads as monochromatic. Split them by at least 120° on the color wheel for maximum snap.

---

**WCAG AA floor:** `--text` on `--bg` ≥ 4.5:1. `--muted` on `--bg` ≥ 3:1 (used at large size only). Every combo below clears both.

---

**COMBO 13 — PITCH SAFFRON**
Carbon black, saffron signal, off-white type. Feels like a Leica M-series camera manual.
```css
:root {
  --bg: #080806;
  --surface: #100f0a;
  --surface2: #181610;
  --border: #28240e;
  --border-hot: #f0a000;
  --text: #f5f0e0;
  --muted: #a09060;
  --accent: #f0a000;
  --accent2: #e03030;
  --accent3: #f8cc44;
  --accent4: #ffffff;
  --claude: #f08040;
  --openai: #40c890;
  --gemini: #4488ee;
  --deepseek: #f0a000;
  --meta: #2266ee;
  --mistral: #e04820;
  --qwen: #b044ee;
}
```
*Contrast check: #f5f0e0 on #080806 ≈ 18:1. #a09060 on #080806 ≈ 5.2:1.*

---

**COMBO 14 — DEEP SPACE JADE**
Blackest green-tinted void, jade signal, warm cream text. Control room chic.
```css
:root {
  --bg: #030a06;
  --surface: #071008;
  --surface2: #0c180e;
  --border: #122414;
  --border-hot: #00c878;
  --text: #e8f5ec;
  --muted: #4a8a5a;
  --accent: #00c878;
  --accent2: #ff3355;
  --accent3: #88ffcc;
  --accent4: #ffffff;
  --claude: #ff7755;
  --openai: #00c878;
  --gemini: #44aaff;
  --deepseek: #00c878;
  --meta: #2288ff;
  --mistral: #ff5500;
  --qwen: #cc44ff;
}
```
*#e8f5ec on #030a06 ≈ 17.8:1. #4a8a5a on #030a06 ≈ 4.6:1.*

---

**COMBO 15 — SOVEREIGN INDIGO**
Dark indigo ground, electric periwinkle, bone text. Parliament meets particle accelerator.
```css
:root {
  --bg: #04040e;
  --surface: #080818;
  --surface2: #0e0e26;
  --border: #181840;
  --border-hot: #6655ff;
  --text: #eeeaff;
  --muted: #7070b0;
  --accent: #6655ff;
  --accent2: #ff4488;
  --accent3: #aaaaff;
  --accent4: #ffffff;
  --claude: #ff8866;
  --openai: #44ddaa;
  --gemini: #4488ff;
  --deepseek: #8866ff;
  --meta: #2255ff;
  --mistral: #ff5533;
  --qwen: #dd44ff;
}
```
*#eeeaff on #04040e ≈ 17.2:1. #7070b0 on #04040e ≈ 4.8:1.*

---

**COMBO 16 — TALLOW**
Aged parchment ground, near-black ink, single vermillion interrupt. Feels like a redacted intelligence brief.
```css
:root {
  --bg: #f2ede2;
  --surface: #e8e2d4;
  --surface2: #ddd6c4;
  --border: #c8c0a8;
  --border-hot: #cc2200;
  --text: #0e0c08;
  --muted: #6a6050;
  --accent: #cc2200;
  --accent2: #004488;
  --accent3: #cc2200;
  --accent4: #000000;
  --claude: #cc3300;
  --openai: #006633;
  --gemini: #004499;
  --deepseek: #660099;
  --meta: #003388;
  --mistral: #cc3300;
  --qwen: #660088;
}
```
*#0e0c08 on #f2ede2 ≈ 19.4:1. #6a6050 on #f2ede2 ≈ 5.8:1.*

---

**COMBO 17 — COPPER OXIDE**
Near-black with patina copper. Oxidised industrial — like a Braun T3 left in a vault.
```css
:root {
  --bg: #050808;
  --surface: #0a1010;
  --surface2: #101818;
  --border: #182828;
  --border-hot: #c87820;
  --text: #eef4f0;
  --muted: #6a9080;
  --accent: #c87820;
  --accent2: #e03050;
  --accent3: #f0c060;
  --accent4: #ffffff;
  --claude: #e07040;
  --openai: #40c088;
  --gemini: #4488cc;
  --deepseek: #c87820;
  --meta: #2266dd;
  --mistral: #e04420;
  --qwen: #a844ee;
}
```
*#eef4f0 on #050808 ≈ 17.9:1. #6a9080 on #050808 ≈ 4.7:1.*

---

**COMBO 18 — ARCTIC SIGNAL**
Blue-white ground, charcoal structure, single ultramarine spike. Scandinavian instrument panel.
```css
:root {
  --bg: #f0f4f8;
  --surface: #e4eaf0;
  --surface2: #d8e0ea;
  --border: #b8c8d8;
  --border-hot: #0022cc;
  --text: #080c14;
  --muted: #445566;
  --accent: #0022cc;
  --accent2: #cc0033;
  --accent3: #0033dd;
  --accent4: #000000;
  --claude: #cc3300;
  --openai: #007744;
  --gemini: #0022cc;
  --deepseek: #5500bb;
  --meta: #0033bb;
  --mistral: #cc2200;
  --qwen: #7700bb;
}
```
*#080c14 on #f0f4f8 ≈ 19.1:1. #445566 on #f0f4f8 ≈ 6.4:1.*

---

**COMBO 19 — TUNGSTEN ROSE**
Dark graphite, rose-quartz accent, platinum text. Feels like a BALMAIN runway show program.
```css
:root {
  --bg: #080608;
  --surface: #100e10;
  --surface2: #181418;
  --border: #282028;
  --border-hot: #e0608a;
  --text: #f8f0f4;
  --muted: #906878;
  --accent: #e0608a;
  --accent2: #60c0e0;
  --accent3: #f090aa;
  --accent4: #ffffff;
  --claude: #f07050;
  --openai: #50d0a0;
  --gemini: #60a0f0;
  --deepseek: #e0608a;
  --meta: #4088ee;
  --mistral: #f06040;
  --qwen: #c060f0;
}
```
*#f8f0f4 on #080608 ≈ 18.6:1. #906878 on #080608 ≈ 4.9:1.*

---

**COMBO 20 — CINDER BLOCK**
Concrete mid-grey ground, white text, single lava interrupt. Feels like a brutalist museum catalog.
```css
:root {
  --bg: #1e1e1e;
  --surface: #262626;
  --surface2: #2e2e2e;
  --border: #404040;
  --border-hot: #ff4800;
  --text: #f4f4f4;
  --muted: #909090;
  --accent: #ff4800;
  --accent2: #00aaff;
  --accent3: #ffaa00;
  --accent4: #ffffff;
  --claude: #ff7755;
  --openai: #44dd99;
  --gemini: #4499ff;
  --deepseek: #ff4800;
  --meta: #2277ff;
  --mistral: #ff5500;
  --qwen: #bb44ff;
}
```
*#f4f4f4 on #1e1e1e ≈ 15.3:1. #909090 on #1e1e1e ≈ 4.6:1.*

---

**COMBO 21 — NOCTURNE**
Darkest possible warm black, lilac-white text, electric violet signal. Late-night observatory energy.
```css
:root {
  --bg: #060408;
  --surface: #0e0a14;
  --surface2: #160f20;
  --border: #22183a;
  --border-hot: #9944ff;
  --text: #f0ecff;
  --muted: #7a62a8;
  --accent: #9944ff;
  --accent2: #ff4466;
  --accent3: #cc88ff;
  --accent4: #ffffff;
  --claude: #ff8866;
  --openai: #44ddaa;
  --gemini: #4488ff;
  --deepseek: #9944ff;
  --meta: #2266ff;
  --mistral: #ff5533;
  --qwen: #dd44ff;
}
```
*#f0ecff on #060408 ≈ 17.7:1. #7a62a8 on #060408 ≈ 4.5:1.*
