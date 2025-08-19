# JOSS

A key goal of JOSS is to raise the quality of research software.

## Software Guidelines

The following is a summary of the [JOSS guidelines](https://joss.readthedocs.io/).

### General checks

- [ ] Is the source code for the software available at the repository URL?
- [ ] Does the repository contain a plain-text LICENSE or COPYING file (see https://opensource.org/licenses)?
- [ ] Is the author list determined from the commit history? Note: purely financial contributions do not constitute authorship.

### Functionality

- [ ] Installation: does installation proceed as outlined in the documentation?
- [ ] Functionality: have the functional claims of the software been confirmed?
- [ ] Performance: if there are any performance claims, have they been validated?

### Documentation

- [ ] Statement of need: do the authors clearly state what problems the software is designed to solve, who the target audience is, and its relation to other work?
- [ ] Installation instructions: is the software simple to install, including dependencies, and does it follow established distribution approaches (e.g., pip for Python, Makefile for Fortran)? Reviewers are expected to install the software they are reviewing and to verify core functionality.
- [ ] Examples: do the authors include examples of how to use the software (ideally to solve real-world analysis problems)?
- [ ] Functionality documentation (API): are all classes and functions documented, including example inputs and outputs?
- [ ] Tests: do the authors include an automated test suite covering core functionality, integrated with continuous integration (e.g., GitHub Actions, CircleCI), and instructions for running the tests?
- [ ] Community guidelines: are there clear guidelines for third parties to a) contribute to the software, b) report issues or problems, and c) seek support?
- [ ] Documentation format: a website or a set of Markdown files.
- [ ] README: a high-level overview (for non-specialists) of the software.
- [ ] Issues: does the repository provide GitHub issue templates to help reviewers open issues?

### Substantial scholarly effort

- [ ] Age of the software: is this a well-established project (at least 3 months old)?
- [ ] Feature completeness: is the software feature-complete (i.e., not a half-baked solution) and designed for maintainable extension (not a one-off modification of existing tools)? Minor utilities and thin API wrappers are not acceptable.
- [ ] Number of commits
- [ ] Number of authors
- [ ] Lines of code (LOC)
- [ ] Has the software already been cited in academic papers?
- [ ] Is the software sufficiently useful that it is likely to be cited by other researchers in the domain?

### Novelty

- [ ] Are existing software packages that solve similar problems cited?
- [ ] Does the paper avoid focusing on new research results accomplished with the software?
- [ ] Does the software enable new research challenges to be addressed, or make addressing them significantly better (e.g., faster, easier, simpler)?

## The paper should include

### Paper structure

- [ ] The paper is between 250–1000 words.
- [ ] Authors: list of the software authors and their affiliations.
- [ ] Summary: a clear description of the high-level functionality and purpose of the software for a diverse, non-specialist audience.
- [ ] Statement of need: a section titled “Statement of need” that clearly states what problems the software is designed to solve, who the target audience is, and its relation to other work.
- [ ] State of the field: description of how the software compares to commonly used packages.
- [ ] Quality of writing: the paper is well written (does not require editing for structure, language, or writing quality).
- [ ] References: the reference list is complete, with appropriate citations (e.g., papers, datasets, software), using proper citation syntax (https://pandoc.org/MANUAL.html#citations). References should include full names of venues (e.g., journals and conferences), not abbreviations only understood within a specific discipline.
- [ ] Use cases: mentions of ongoing research projects using the software or recent scholarly publications enabled by it.
- [ ] Acknowledgements: of any financial support.
- [ ] Style: https://joss.readthedocs.io/en/latest/paper.html
- [ ] Compilation to PDF: https://github.com/marketplace/actions/open-journals-pdf-generator

### Paper submission

- [ ] Ensure your software is publicly available and includes all necessary documentation and guidelines.
- [ ] Use the `paper.md` and `paper.bib` templates.
- [ ] Generate metadata using the `generate_metadata` script.
- [ ] Fill out the submission form: https://joss.theoj.org/papers/new
- [ ] Wait for the managing editor to start a pre-review issue in the JOSS Reviews repository: https://github.com/openjournals/joss-reviews

### Paper hosting

- [ ] The paper (`paper.md` and BibTeX files, plus any figures) must be hosted in a Git-based repository together with your software.
- [ ] The paper may live on a short-lived branch that is never merged with the default branch; if you do this, make sure the branch is created from the default so that it includes the source code of your submission.