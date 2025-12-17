# Repository template for ECEM202A/CSM213A projects

## 🧩 Structure Overview
* docs/ for GitHub Pages website content
* software/ for code used in your project
* data/ for data data used in your project

You may add additional files and folders as necessary.

The doc/ folder has a simple *starter template* for a GitHub Pages website using markdown. However, you can put any static html content there, including files for a website you may have prepared elsewhere. GitHub Pages looks for index.html as the root file for the website and if that is not found then index.md, and then README.md. Jekyll (the static site generator used by GitHub Pages) will convert markdown content into html.


Please update docs/\_config.yml with your project's metadata such as title and description.

## ✅ Expectations for a Strong Project Website

* Introduction: Clear motivation, context, and goals.
* Related Work: 5–12 relevant references with explanation.
* Technical Approach: Architecture diagram, pipeline, algorithm details.
* Evaluation: Multiple clear plots/tables, baselines, and analysis.
* Figures: High-quality diagrams, plots, and qualitative examples.
* Reproducibility: Datasets and software described with links.
* Polish: Well-written, structured, and visually clean.

Your website is your final report – treat it like a conference-style project writeup, but more visual and accessible.


## 🧭 Guidelines for a Strong Project Website


### 1. Include Figures & Visuals Liberally

Every major section should have at least one figure:
* Architecture diagram
* Data pipeline
* Example outputs
* Evaluation plots
* Comparative charts

Projects with few or no visuals will feel incomplete.


### 2. Make the site readable to a smart non-expert

Avoid jargon, especially in the introduction.

### 3. Use structured subsections

Every major section should have 3–5 subsections.

### 4. Provide reproducibility

Include:
* Hyperlinks to datasets
* Clear algorithm descriptions
* Parameters and configuration details
* Implementation notes

### 5. Present results professionally

Figures must:
* Have readable labels
* Use consistent color palettes
* Include units and legends
* Provide captions explaining what the figure shows

### 6. Cite generously

A typical project should cite 5–12 relevant papers.

## 📊 Minimum vs. Excellent Rubric


| **Component**        | **Minimum (B/C-level)**                                         | **Excellent (A-level)**                                                                 |
|----------------------|---------------------------------------------------------------|------------------------------------------------------------------------------------------|
| **Introduction**     | Vague motivation; little structure                             | Clear motivation; structured subsections; strong narrative                                |
| **Related Work**     | 1–2 citations; shallow summary                                 | 5–12 citations; synthesized comparison; clear gap identification                          |
| **Technical Approach** | Text-only; unclear pipeline                                  | Architecture diagram, visuals, pseudocode, design rationale                               |
| **Evaluation**       | Small or unclear results; few figures                          | Multiple well-labeled plots, baselines, ablations, and analysis                           |
| **Discussion**       | Repeats results; little insight                                | Insightful synthesis; limitations; future directions                                      |
| **Figures**          | Few or low-quality visuals                                     | High-quality diagrams, plots, qualitative examples, consistent style                      |
| **Website Presentation** | Minimal formatting; rough writing                           | Clean layout, good formatting, polished writing, hyperlinks, readable organization        |
| **Reproducibility**  | Missing dataset/software details                               | Clear dataset description, preprocessing, parameters, software environment, instructions   |
