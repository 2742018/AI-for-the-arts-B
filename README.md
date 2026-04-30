# Access Through Touch

## A human–AI mini-exhibit for a raised-type New Testament in University of Glasgow Special Collections

**Selected object:** Tactile New Testament printed in high relief for blind readers, c. 1850  
**Collection reference:** University of Glasgow Special Collections, Sp Coll RF 256 / RF 257  

## Project summary

This repository contains the Part I project portfolio for **AI for the Arts and Humanities (B)**. The project is presented as a Jupyter Notebook mini-exhibit for a general audience.

The selected object is a tactile New Testament printed in high relief for blind readers. The project’s central argument is that **accessibility is part of cultural heritage**. The object shows that reading is not only a visual activity. It can also depend on bodies, surfaces, materials, technologies, and decisions about who is imagined as a reader.

The mini-exhibit uses photographs, Python-generated relief-enhanced visual aids, plain-language labels, and access-description writing to help non-specialist audiences understand the object as a historical accessibility technology.

The project does not try to replace the physical object or reproduce the full experience of reading by touch. Instead, it creates a digital access layer that helps viewers notice the tactile, material, and social significance of the raised-type page.

## Project objective

The project asks:

> How can human–AI collaboration help a general audience understand accessibility as part of cultural heritage, rather than as an extra feature added afterwards?

The aim is to engage viewers who may not have prior knowledge of rare books, disability history, tactile reading, digitisation, or artificial intelligence.

The mini-exhibit helps visitors:

- understand what raised type is;
- notice the surface and layout of a tactile page;
- connect the object to wider questions about access and reading;
- reflect on what can be lost when tactile heritage is digitised as flat images;
- understand how AI can support interpretation without replacing human judgement.

## Human–AI collaboration

This project uses generative AI as a drafting and variation tool, not as an authority.

The human role remains responsible for:

- selecting the object;
- choosing image fragments;
- defining the public-engagement aim;
- checking factual claims;
- editing language for accuracy and accessibility;
- avoiding unsupported historical claims;
- making final ethical and interpretive decisions.

Generative AI was used to help draft possible exhibit labels, access-description writing, and explanatory text. These outputs were reviewed and revised by the human author before being included in the notebook.

Python image processing was also used to create visual aids from the photographs. These are not scientific scans of the object. They are interpretive visual aids that help viewers notice surface variation in a flat digital image.

## AI and technical concepts demonstrated

The notebook explains the tools through the machine-learning workflow:

| Stage | How it appears in this project |
|---|---|
| Input | Object photographs, human-written prompts, and project aims |
| Model/tool process | Generative text AI predicts likely wording; Python transforms image data |
| Output | Draft labels, access descriptions, cropped images, and relief-enhanced visual aids |
| Human verification | Outputs are checked, edited, contextualised, and labelled as evidence-based or interpretive |

The project does not implement a generative model from scratch. Instead, it uses existing tools in a documented and critically supervised workflow.

## Tools used

| Tool | Use in project |
|---|---|
| Jupyter Notebook | Main portfolio and mini-exhibit format |
| Python | Image inventory, cropping, relief-enhanced visual aids, tables, and exhibit display |
| Pillow | Image opening, resizing, cropping, filtering, and enhancement |
| NumPy | Simple image-array calculations |
| Pandas | Tables embedded directly inside the notebook |
| Generative text AI / ChatGPT | Drafting alternative labels, access descriptions, and explanatory text under human supervision |

## Data and image access

The images in the `images/` folder are photographs of the selected Special Collections object used for coursework portfolio purposes.

The object should be credited as:

**Tactile New Testament printed in high relief for blind readers, c. 1850, University of Glasgow Special Collections, Sp Coll RF 256 / RF 257.**

Before sharing the images beyond coursework assessment, reuse permissions and licensing conditions should be confirmed with University of Glasgow Special Collections.

## Repository contents

| File or folder | Purpose |
|---|---|
| `2742018_AIArtsB_Project_Portfolio.ipynb` | Main project portfolio and mini-exhibit |
| `README.md` | Repository introduction, tool list, data/access notes, and integrity statement |
| `requirements.txt` | Python packages required to run the notebook |
| `images/` | Original photographs of the selected object |
| `processed_images/` | Generated crops, relief-enhanced visual aids, and comparison images |
| `outputs/contact_sheet/` | Generated contact sheet used as the visual entry point |

The folders `processed_images/` and `outputs/contact_sheet/` are created by the notebook when the code cells are run.

## How to run the notebook

Open the notebook in Jupyter Notebook, JupyterLab, GitHub Codespaces, or another compatible environment.

Install the required packages with:

```bash 
pip install -r requirements.txt

``` 

## Licensing and permissions note

This repository is prepared for coursework assessment. The object images should not be treated as openly licensed unless University of Glasgow Special Collections confirms the relevant reuse terms.

All generated outputs are presented as interpretive aids, not as replacements for the original object. Relief-enhanced images are visual aids for online viewers; they do not reproduce the full tactile experience of reading raised type.

## Integrity note

Generative AI was used as a drafting and variation tool, not as a source of archival fact.

AI-generated wording was edited by the human author for accuracy, accessibility, tone, and ethical suitability. The notebook includes examples of AI-style draft problems and human revision decisions to show how the collaboration shaped the final public-facing interpretation.

This repository contains the Part I project portfolio only. It does not include the separate Part II evaluation report.