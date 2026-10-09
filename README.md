# Mathematics 6 — Solution Manuals (Units 9–12)

Complete, step-by-step worked solutions to every exercise and review exercise in
Units 9–12 of **Mathematics 6**, Balochistan Textbook Board, Quetta.

Each unit ships as a typeset A4 PDF plus the LaTeX source that produced it, so the
material can be printed as-is, projected in class, or edited to suit a different
scheme of work.

The repository also carries three **Google Colab notebooks** that take a scanned unit
PDF and carry it through to a finished manual — reading the pages, typesetting the
solutions, and checking the arithmetic.

> **Prepared by Muhammad Idrees** — M.Phil (Mathematics), Lecturer, Department of
> Mathematics, Government Boys Postgraduate College, Sariab Road, Quetta.

---

## Contents

| Unit | Title | Exercises covered | Pages | PDF | Source |
|:----:|-------|-------------------|:-----:|:---:|:------:|
| 9  | Symmetry | 9.1 · 9.2 · 9.3 · Review 9 | 13 | [PDF](pdf/Unit_09_Symmetry_Solutions.pdf) | [.tex](tex/Unit_09_Symmetry_Solutions.tex) |
| 10 | Geometrical Constructions | 10.1 · 10.2 · Review 10 | 10 | [PDF](pdf/Unit_10_Geometrical_Constructions_Solutions.pdf) | [.tex](tex/Unit_10_Geometrical_Constructions_Solutions.tex) |
| 11 | Data Management | 11.1 · 11.2 · 11.3 · 11.4 · Review 11 | 16 | [PDF](pdf/Unit_11_Data_Management_Solutions.pdf) | [.tex](tex/Unit_11_Data_Management_Solutions.tex) |
| 12 | Probability | 12.1 · 12.2 · Review 12 | 9 | [PDF](pdf/Unit_12_Probability_Solutions.pdf) | [.tex](tex/Unit_12_Probability_Solutions.tex) |

**48 pages in total**, covering every numbered question and sub-part in the four units.

---

## The Colab notebooks

**The only file you ever upload is the scanned unit PDF.** Nothing is cloned, no
`.tex` is uploaded, and nothing needs installing on your own machine — the LaTeX
template lives inside the notebook.

| # | Notebook | What you upload | What you get back | Launch |
|:-:|----------|-----------------|-------------------|:------:|
| 1 | **Inspect Textbook Unit** | the unit PDF | every page rendered as an image, any region zoomed at up to 600 dpi, the text pulled out (or OCR'd), page images as a zip | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/REPLACE-ME/math6-solutions/blob/main/notebooks/01_Inspect_Textbook_Unit.ipynb) |
| 2 | **Build Solution Manual** | the unit PDF | a typeset A4 solution manual in this house style, plus its `.tex` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/REPLACE-ME/math6-solutions/blob/main/notebooks/02_Build_Solution_Manual.ipynb) |
| 3 | **Verify Answers** | nothing | every mean, median, mode, pie-chart angle and probability re-computed and asserted against the printed manual | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/REPLACE-ME/math6-solutions/blob/main/notebooks/03_Verify_Answers.ipynb) |

> **Before publishing:** replace `REPLACE-ME/math6-solutions` in the three badge URLs
> above with your own `username/repository`, or the badges will point nowhere. That is
> the only place the repository name appears.

### How the three fit together

```
   your scanned unit PDF
            │
            ▼
   ┌──────────────────────┐
   │ 1 · Inspect          │   render every page · zoom a faint figure at 300–600 dpi
   │    the unit          │   · extract or OCR the text · download the page images
   └──────────┬───────────┘
              │  you read the exercises off the page images
              ▼
   ┌──────────────────────┐
   │ 2 · Build the        │   house-style LaTeX template · you write the solutions
   │    solution manual   │   · compile · three quality gates · preview · download
   └──────────┬───────────┘
              │  the finished PDF and .tex
              ▼
   ┌──────────────────────┐
   │ 3 · Verify           │   recompute every number independently of what you typed
   │    the answers       │
   └──────────────────────┘
```

**Notebook 1 is where the care goes.** Angle diagrams and bar-graph labels on these
scans are often too faint at normal size to tell which side of a transversal a label
sits on — and `2c°` sitting upper-left rather than upper-right changes the answer. The
zoom tool in Step 4 takes a page to 300 or 600 dpi and crops any region of it, which
is how every figure in Units 9–12 was read.

**Notebook 2 carries its own template.** Step 3 sets the unit number, title and your
name; Step 4 is the one cell you live in, pre-filled with a worked example of each
pattern — ordinary working, a TikZ figure, a multiple-choice table — so you can see
every building block in use before deleting them and writing your own. Step 5 compiles
and reports the three quality gates, and you loop between 4 and 5 until it is right.

**A word on the OCR in notebook 1.** It reads body prose reasonably well but mangles
fractions, exponents, angle symbols and anything inside a figure. Use it to find a
question quickly, never to copy one — always take the actual numbers off the page
image.

---

## How the solutions are written

Every question follows the same shape, so a pupil always knows where to look:

1. **The question restated** in a blue box, keeping the textbook's own numbering —
   including sub-parts the book skips or repeats.
2. **`Given:`** the data pulled out of the question and out of the figure.
3. **The working**, one line per step: formula → substitution → simplification →
   result with units, with the *reason* for each step named in the right-hand margin
   (*vertically opposite angles*, *corresponding angles*, *angles on a straight line*,
   and so on).
4. **A green answer box** with the final result.
5. **An orange note** wherever a question is defective, ambiguous, or worth a word of
   warning.

Other conventions:

- The **textbook's own method** is used for each exercise, even where a shorter route
  exists, so the working matches what pupils are taught in class.
- Fractions are given in **lowest terms**; probabilities as fractions, not decimals.
- Figures are **redrawn in TikZ** rather than described — angle diagrams, compass
  constructions with their arcs, bar graphs, pie charts and the 6 × 6 two-dice grid.
- Checks are shown where they are cheap (`122° + 58° = 180° ✓`, `Σ P = 1 ✓`).

---

## Errata found in the printed textbook

Five printed problems needed a judgement call. Each is solved as faithfully as the
printed data allows and flagged in an orange note at that point in the PDF.

| Where | Issue | How it is handled |
|-------|-------|-------------------|
| Ex 9.2 Q4(ii) | The figure gives `2c = 147°`, so `c = 73.5` — the only non-integer answer in the exercise. | Solved as printed; a note points out that a coefficient of 3 would have given the whole number 49. The label positions were confirmed against a 300 dpi render of page 170: `2c°` upper-left, `7d°` lower-right, `147°` lower-right. |
| Ex 10.1 Q2(iii) | **130° cannot be constructed with compass and straightedge** — it is not a multiple of 15°. | Solved with a protractor, with the nearest compass-constructible angles (127.5°, 135°) named and the reason explained. |
| Ex 10.1 Q2(ii) | The activity box prints "120° − 15° = 115°". | Noted as a slip: 120° − 15° = 105°. The method itself is sound. |
| Ex 10.2 Q3(ii) | `mCD = 80 cm` will not fit on a notebook page; every other length in the exercise is a single digit. | Solved for the printed 80 cm, with a note that 8 cm is almost certainly intended. |
| Ex 11.2 Q2 | The table's fourth column is headed "Food", but the question says "…and on foot respectively". | Read as **on foot**, with a note. |

---

## Repository layout

```
.
├── README.md
├── pdf/                                  ← ready-to-print A4 PDFs
│   ├── Unit_09_Symmetry_Solutions.pdf
│   ├── Unit_10_Geometrical_Constructions_Solutions.pdf
│   ├── Unit_11_Data_Management_Solutions.pdf
│   └── Unit_12_Probability_Solutions.pdf
├── tex/                                  ← LaTeX source, one self-contained file per unit
│   ├── Unit_09_Symmetry_Solutions.tex
│   ├── Unit_10_Geometrical_Constructions_Solutions.tex
│   ├── Unit_11_Data_Management_Solutions.tex
│   └── Unit_12_Probability_Solutions.tex
├── scripts/
│   ├── generate_unit11_tex.py            ← rebuilds Unit 11's .tex, charts and all
│   └── verify_answers.py                 ← re-computes every numerical answer
└── notebooks/
    ├── 01_Inspect_Textbook_Unit.ipynb
    ├── 02_Build_Solution_Manual.ipynb
    └── 03_Verify_Answers.ipynb
```

Each `.tex` file is **self-contained** — it carries its own preamble and needs no
shared class file, so a single unit can be copied out and compiled on its own.

**Unit 11 is generated.** Its bar graphs and pie charts are emitted by
`scripts/generate_unit11_tex.py`, which computes every bar height and sector angle
rather than trusting hand-typed coordinates. Edit the script and re-run it to change
the charts; edit the `.tex` directly only for one-off text fixes you do not mind
losing on the next regeneration.

---

## Building locally

The notebooks remove any need for this, but the manuals build offline just as well.

**Requirements:** a TeX distribution with `pdflatex`, `tcolorbox`, `tikz`, `booktabs`,
`enumitem`, `multicol`, `mathptmx` and `helvet`. On Debian or Ubuntu:

```bash
sudo apt-get install texlive-latex-recommended texlive-latex-extra \
                     texlive-fonts-recommended texlive-pictures poppler-utils
```

**Build one unit** (run `pdflatex` twice so the page references settle):

```bash
cd tex
pdflatex -interaction=nonstopmode Unit_09_Symmetry_Solutions.tex
pdflatex -interaction=nonstopmode Unit_09_Symmetry_Solutions.tex
```

**Build all four:**

```bash
cd tex
for f in Unit_*.tex; do
  pdflatex -interaction=nonstopmode "$f" >/dev/null
  pdflatex -interaction=nonstopmode "$f" >/dev/null
done
```

**Regenerate Unit 11's source from the chart script:**

```bash
cd scripts && python3 generate_unit11_tex.py   # writes Unit_11_Data_Management_Solutions.tex
```

**Re-check every number:**

```bash
python3 scripts/verify_answers.py
```

### Quality gates

The same three checks notebook 2 reports after every compile. Worth re-running after
any edit:

```bash
# 1. No LaTeX errors and no overfull lines
pdflatex -interaction=nonstopmode FILE.tex | grep -iE "^!|overfull"

# 2. No Type 3 bitmap fonts (they print badly and look blurry on screen)
pdffonts FILE.pdf | grep -i type3        # must print nothing

# 3. Eyeball the pages
pdftoppm -r 60 -png FILE.pdf page
```

All four units currently build with **zero errors, zero overfull boxes and zero Type 3
fonts**.

---

## Adapting the manuals

**Change the credit line.** Each `.tex` has the name in exactly two places — the
`\fancyfoot[L]` line in the preamble and the credit `tcolorbox` just under the title.
To drop the credit entirely, delete that `tcolorbox` and the `\fancyfoot[L]` line. In
notebook 2 this is the `SHOW_CREDIT` switch in Step 3.

**Change the colours.** All six are defined together near the top of each file:

```latex
\definecolor{mainorange}{HTML}{E8731A}   % section banners, notes
\definecolor{deepblue}{HTML}{1F4E79}     % title, headers, question boxes
\definecolor{softblue}{HTML}{E8F1FA}     % question-box fill
\definecolor{softgreen}{HTML}{E6F4EA}    % answer-box fill
\definecolor{ansgreen}{HTML}{1E7B34}     % answer text
\definecolor{softyellow}{HTML}{FFF6DD}   % note-box fill
```

**Print in black and white.** Set all six to greys — the layout depends on the boxes,
not on hue.

**Start a new unit.** Use notebook 2: it is the same template with the content
stripped out.

---

## Source material and licence

This repository contains **only original worked solutions**. The textbook itself —
its text, its figures and its scanned pages — is **not** redistributed here, and
`.gitignore` is set up to keep scans out of the history. Readers need their own copy
of *Mathematics 6* (Balochistan Textbook Board) to use these manuals, since the
questions are referenced by the book's own numbering.

The solutions, the LaTeX source and the notebooks are the author's own work. A
permissive-but-attributed licence such as **CC BY-NC-SA 4.0** suits teaching material
of this kind: it lets other teachers copy and adapt the manuals for their classes while
keeping the attribution and keeping the result free. Add your chosen licence as a
`LICENSE` file in the repository root — GitHub will then display it in the sidebar.

---

## Contributing

Corrections are welcome, especially from teachers using these in class.

- **A wrong answer or a slipped step** — open an issue naming the unit, exercise and
  question number (for example, "Unit 11, Ex 11.4 Q1(iii), median"), and say what the
  answer should be.
- **A figure misread from the scan** — the angle figures in Unit 9 and the bar graph in
  Ex 11.1 Q5 were read off printed pages. If a value looks wrong against a clean copy,
  say which page and what it should read; notebook 1 Step 4 will settle it.
- **A fix** — edit the `.tex`, rebuild, confirm the three quality gates still pass, and
  open a pull request. For Unit 11, edit `scripts/generate_unit11_tex.py` rather than
  the generated `.tex`.
