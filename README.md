<div align="center">

# 🍥 NARUTO SHINOBI 🍥
### *Interactive Lore, Clan & Family Tree Encyclopedia*

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![D3.js](https://img.shields.io/badge/D3.js_v7-F9A03C?style=for-the-badge&logo=d3.js&logoColor=white)](https://d3js.org/)
[![Tone.js](https://img.shields.io/badge/Tone.js-Audio_FX-7B61FF?style=for-the-badge)](https://tonejs.github.io/)

**An interactive, standalone collection of web encyclopedias and D3.js mindmaps exploring the bloodlines, Kekkei Genkai, Tailed Beasts, and major clans of the *Naruto* & *Boruto: Two Blue Vortex* universe.**

🌐 *Available in **English (`[EN]`)** & **Vietnamese (`[VI]`)***

</div>

---

## 📖 Overview

**Naruto Shinobi** brings complex shinobi lore, Dojutsu evolutions, Jinchūriki lineages, and multi-generational family trees into sleek, interactive browser experiences. Every page is a **self-contained HTML application**—no bundlers, servers, or installations required.

---

## ✨ Encyclopedia Modules

### 1. 🦊 Tailed Beasts & Ōtsutsuki Chronicles (`bijuu_jinchuuriki/`)

| File | Lang | Highlights & Lore Covered |
| :--- | :---: | :--- |
| [`bijuu_jinchuuriki_overview.html`](./bijuu_jinchuuriki/bijuu_jinchuuriki_overview.html) | `VI` | Profiles of all **9 Tailed Beasts** (*Ichibi* → *Kyūbi*) & the **Ten-Tails** (*Jūbi*), origin diagrams, Jinchūriki host chains, chakra rankings, and Ten-Tails evolution stages. |
| [`naruto-otsutsuki-chronicles.html`](./bijuu_jinchuuriki/naruto-otsutsuki-chronicles.html) | `VI` | Genealogical lineage descending from **Kaguya Ōtsutsuki**, Indra & Asura reincarnation cycles, Black Zetsu's millennia-long manipulation, White Zetsu/God Tree origins, and Ōtsutsuki clan laws. |

---

### 2. 🌀 Great Clan Encyclopedias (`clan/`)

| File | Lang | Highlights & Lore Covered |
| :--- | :---: | :--- |
| [`uchiha_clan_dojutsu_susanoo_encyclopedia.html`](./clan/Uchiha/uchiha_clan_dojutsu_susanoo_encyclopedia.html) | `EN` | **Sharingan** evolution stages, **Mangekyō** abilities, **Susanoo** forms, and forbidden *kinjutsu* (*Izanagi*, *Izanami*) from the Warring States era to *Boruto: Two Blue Vortex*. Includes **Tone.js** Dojutsu sound effects, era filters, and character inspection modals. |
| [`b_ch_khoa_nh_n_thu_t_gia_t_c_uchiha.html`](./clan/Uchiha/b_ch_khoa_nh_n_thu_t_gia_t_c_uchiha.html) | `VI` | Full Vietnamese edition of the **Uchiha Dojutsu & Susanoo Encyclopedia** with interactive audio synthesis, search, and detailed character stats. |
| [`b_ch_khoa_to_n_th_s_c_m_nh_gia_t_c_uzumaki.html`](./clan/Uzumaki/b_ch_khoa_to_n_th_s_c_m_nh_gia_t_c_uzumaki.html) | `VI` | Chronicles the **Uzumaki Clan's** immense life force, Adamantine Sealing Chains, and *Fūinjutsu* across four eras (*Genesis & Uzushio*, *Konoha & Akatsuki*, *Naruto Era*, and *Boruto: Two Blue Vortex*). |

---

### 3. 🌳 Interactive Family Trees & Mindmaps (`family_tree/`)

| File | Lang | Highlights & Lore Covered |
| :--- | :---: | :--- |
| [`Naruto-Family-Tree-Mindmap.html`](./family_tree/Naruto-Family-Tree-Mindmap.html) | `EN` | Powered by **D3.js v7** with smooth zoom/pan, collapsible nodes, live search, and category quick-jumps (*Ōtsutsuki, Uchiha, Senju, Uzumaki, Hyūga, Konoha, Great Villages, Akatsuki, Tailed Beasts*). Includes **High-Res PNG** & **Standalone HTML** export tools. |
| [`Cay-Pha-He-Naruto-Mindmap.html`](./family_tree/Cay-Pha-He-Naruto-Mindmap.html) | `VI` | Full Vietnamese edition of the interactive **D3.js Shinobi Family Tree & Clan Mindmap** with search, filtering, and export features. |
| [`Naruto – Cây phả hệ từ Kaguya.html`](./family_tree/Naruto%20–%20Cây%20phả%20hệ%20từ%20Kaguya.html) | `VI` | Clean hierarchical tree tracing shinobi bloodlines directly from **Kaguya Ōtsutsuki**. |
| [`Naruto – Mindmap phả hệ từ Kaguya (circle).html`](./family_tree/Naruto%20–%20Mindmap%20phả%20hệ%20từ%20Kaguya%20(circle).html) | `VI` | Radial/circular mindmap visualization expanding outward from **Kaguya Ōtsutsuki**. |

---

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/minadara95/naruto_shinobi.git
   cd naruto_shinobi
   ```

2. **Launch any encyclopedia**
   * **Option A:** Double-click any `.html` file to open it directly in your browser.
   * **Option B:** Start a lightweight local server to browse all files easily:
     ```bash
     python3 -m http.server 8000
     ```
     Then open `http://localhost:8000` in your browser.

<details>
<summary>💡 <b>Tips for the Best Experience</b></summary>

* **Internet Connection:** Pages load **Tailwind CSS**, **D3.js**, **Tone.js**, **Font Awesome**, and **Google Fonts** via CDN, so staying online ensures full styling, graphs, and audio effects.
* **Audio Effects:** In the Uchiha Dojutsu Encyclopedias, click anywhere on the page or trigger a Dojutsu preview to initialize Web Audio via **Tone.js**.
* **Exporting Mindmaps:** Use the toolbar inside `Naruto-Family-Tree-Mindmap.html` / `Cay-Pha-He-Naruto-Mindmap.html` to export your expanded tree view as a crisp **PNG** image.

</details>

---

## 🛠️ Tech Stack

* **Core:** HTML5, Vanilla JavaScript (ES6+), CSS3
* **Styling & Icons:** Tailwind CSS (CDN), Font Awesome 6, Google Fonts (`Cinzel`, `Inter`, `Plus Jakarta Sans`, `Chakra Petch`, `Be Vietnam Pro`)
* **Visualization & Audio:** D3.js v7 (Collapsible & Radial Trees), Tone.js (Web Audio Synthesizer)

---

<div align="center">

*Crafted for Shinobi lore enthusiasts — Dattebayo!* 🍥

</div>