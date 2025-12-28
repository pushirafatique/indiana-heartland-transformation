# The Indiana Heartland Transformation Project

A collaborative digital history project analyzing the urbanization of early 20th-century Indiana through local newspapers.

## Project Overview

This repository hosts a semester-long undergraduate history course project focused on the social, economic, and cultural transformations of rural Indiana communities during the 1910s and 1920s. Students will transcribe and analyze newspaper articles from small-town Indiana newspapers to document the tensions, changes, and shifts that accompanied early urbanization.

The project aims to build a shared digital archive that can be used for further historical research while teaching students the fundamentals of collaborative digital humanities work, version control, and open scholarship.

## How to Contribute

Students in the course will follow these steps to contribute:

1. **Claim a newspaper issue** – Browse the open issues in the repository and select an unclaimed newspaper/date.
2. **Create a branch** – From the main branch, create a new branch named after your claimed issue (e.g., `fort-wayne-sentinel-march-1917`).
3. **Transcribe articles** – Add plain-text transcriptions of at least one relevant article to the `transcriptions/` folder.
4. **Log metadata** – Update the central metadata file `data/articles.csv` with information about the article(s) you transcribed.
5. **Write analysis** – Compose a short (approx. 200-word) analytical reflection and place it in the `analysis/` folder.
6. **Submit a Pull Request** – Open a Pull Request (PR) from your branch back to the main branch for instructor review.

## Folder Structure

The repository is organized as follows:

- `transcriptions/` – Contains plain-text files (`.txt`) of newspaper articles transcribed by students.
- `data/` – Contains structured data files (`.csv`, `.json`) that log article metadata (newspaper title, date, page, key themes, etc.).
- `analysis/` – Houses short analytical essays or reflections (`.md` format) written by students about their assigned newspaper issues.
- `sources/` – Stores bibliographic references, links, and citations to the digitized newspapers used in the project.

## Code of Conduct

Please read our [Code of Conduct](CODE_OF_CONDUCT.md) before participating in this project. We are committed to providing a welcoming and respectful environment for all contributors.

## Submission and Review Process

All student contributions **must** be submitted via a Pull Request (PR). This ensures that work is reviewed before being merged into the main archive.

**Pull Request Title Format:**  
`[Town Name]: [Article Headline/Topic]`

Example: `[Fort Wayne]: Local Factory Expansion Discussed in Editorial`

When you open a PR, please reference the issue number you are addressing (e.g., `Closes #1`). The instructor will review the transcription, metadata, and analysis, then either request changes or approve and merge the PR.

## Getting Started

If you are new to Git and GitHub, we recommend completing the [GitHub Hello World](https://guides.github.com/activities/hello-world/) tutorial before the project begins. The instructor will also provide a brief workshop on the basic Git commands needed for this project.

## Contact

For questions about the project, please contact the course instructor via the issue tracker or email.