# Free Kicks at Football (1882) — Human–AI Engagement Gallery

**AI for the Arts and Humanities (B) | University of Glasgow | 2781431**

---

## Project Overview

Showcase of the "Real vs Generated" gallery centered around
*Free Kicks at Football* (Glasgow, 1882), a 19-page Victorian ephemeral pamphlet from
the University of Glasgow Special Collections (Sp Coll Mu2-i.38, David Murray Collection).

Gallery made with DALL-E 3 / Flux image generation, presented with Python. Original 1882 illustrations and advertisements are displayed next to AI-generated images in the same genre. It hopes to achieve two things: open up a fragile archival object to popular audiences, and use the shortcomings of AI as a critical framework - what doesn't the model know highlights what is historically specific about the originals.

Image generation is **editorial** work: choosing scenes to recreate, writing prompts, framing the juxtapositions. The computer runs the algorithm; you tell it what to think.
---

## Repository Contents

| File / Folder | Description |
|---|---|
| `free_kicks_human_ai_project.ipynb` | Main portfolio notebook (run from project root) |
| `requirements.txt` | Python dependencies |
| `ai_generated/` | AI-generated images (DALL-E 3 / Flux via Pollinations.ai) |
| `original_scans/` | 9 original pamphlet scan JPEGs (covers, illustrations, advertisements) |
| `5ee3a4397e23f1f6dca042d5e7893ca9.mp4` | Supporting video material |

---

## How to Run

### Prerequisites

```bash
pip install -r requirements.txt
```

Or with `uv`:

```bash
uv pip install -r requirements.txt
```

### Run the notebook

```bash
jupyter notebook free_kicks_human_ai_project.ipynb
```

The notebook requires **no API keys** and works fully offline once the repository is cloned.
All AI-generated images are pre-saved in `ai_generated/`.

Run cells top-to-bottom (Kernel → Restart & Run All).

---

## Data and Tools

| Tool | Purpose | Access |
|---|---|---|
| DALL-E 3 / Flux via [Pollinations.ai](https://pollinations.ai) | Victorian scene image generation | Free, no account required |
| Python 3 / matplotlib | Image display and gallery layout | Open source |
| Pillow | Image validation | Open source |
| Jupyter / nbformat | Notebook format | Open source |

### Original images

All pamphlet scans were photographed during a supervised Special Collections visit at
University of Glasgow Library. They are reproduced here for educational and research purposes only.

---

## Attribution and Licensing

| Asset | Source | Rights |
|---|---|---|
| Pamphlet scans (`original_scans/` folder) | University of Glasgow Special Collections, Sp Coll Mu2-i.38 | Reproduced for educational use; copyright remains with the University of Glasgow |
| AI-generated images (`ai_generated/*.jpg`) | Generated via Pollinations.ai / DALL-E 3 / Flux | No copyright claimed on AI outputs; created for educational purposes |
| Video (`5ee3a4397e23f1f6dca042d5e7893ca9.mp4`) | Supporting documentary material | Educational use |
| Python code | Original work by the author | Educational use |

---

## Five Gallery Scenes

1. **Hampden Park Eviction** — the 1881–82 Queen's Park / Third Lanark ground dispute
2. **The Charity Match** — performative committee generosity vs genuine philanthropy
3. **Monday Morning at the Club** — the aftermath of brutal Saturday play (*Lay On, Leather!*)
4. **Percy's Football Boots Advertisement** — early sports equipment commercialisation
5. **McNeil's Outfitters Advertisement** — football consumer market in 1882 Glasgow
