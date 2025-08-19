# JOSS

A key goal of JOSS is to raise the quality of research software.

## Software guidelines

The following text is a summary of the [JOSS guidelines](https://joss.readthedocs.io/)

### General Checks

- [ ] is the source code for the software is available at the repository url?
- [ ] does the repository contains plain-text LICENSE or COPYING license file: https://opensource.org/license?
- [ ] The authors list is checked and determined by the commit history. Purely financial contributions are not considered as authorship

### Functionality

- [ ] installation - does installation proceed as outlined in the documentation?
- [ ] functionality - have the functional claims of the software been confirmed?
- [ ] performance - if there are any performance claims of the software, have they been confirmed?

### Documentation

- [ ] A statement of need - the authors should clearly state what problems the software is designed to solve, who the target audience is, and its relation to the other work.
- [ ] Installation instructions - the software is simple to install, including dependencies, and follows established distribution approached e.g. pip install for Python and makefile for Fortran. Reviewers are expected to install the software they are reviewing and to verify the core functionality of the software
- [ ] Examples - the authors should include examples of how to use the software (ideally to solve real-world analysis problems)
- [ ] Functionality documentation - API - All classes, functions, are documented including examples inputs and outputs
- [ ] Authors are strongly encourage to include an automated test suite covering the core functionality of their software. An automated test suite hooked up to continouos integration (GitHub Actions, Circle CI, or similar). Explanation how to run the tests.
- [ ] Community guidelines - there should be clear guidelines for third-parties to: a) contribute to the software, b) repost issues or problems with the software, c) seek support.
- [ ] Documentation format - a website or a list of markdown files
- [ ] README - with a high-level (for non specialists) overview of the software
- [ ] Issues - a reviewer can make issues of a GitHub repository, therefore it is a good idea to have github issue templates

### Substantial Scholarly Effort

- [ ] age of a software (is this a  well-established software project)
- [ ] number of commits
- [ ] number of authors
- [ ] line of code (LOC)
- [ ] Whether the software has already been cited in academic papers
- [ ] Whether the software is sufficiently useful that it is likely to be cited by other researchers in the working domain

### Novelty

- [ ] Submissions that implement solutions already solved in other software packages must be cited.

## Paper should have

- [ ] Summary - Has a clear description of the high-level functionality and purpose of the software for a diverse, non-specialist audience been provided?
- [ ] A statement of need - Does the paper have a section titled "Statement of need" that clearly states what problesm the sofware is desiegned to solve, who the target audiece is, and its relation to the other work?
- [ ] State of the field - Do the authors describe how this software compares to other commonly-used packages?
- [ ] Quality of writing - Is the paper well written (e.g. it does not require editing for structure, language or writing quality)?
- [ ] References - Is the list of references complete, and is everything cited appropriately that should be cited (e.g. papers, datasets, software)? Do references in the use the proper citation syntax - https://pandoc.org/MANUAL.html#citations
- [ ] Authors - a list of the authors of the software and their affiliations
- [ ] Use cases - mentions of any ongoing research projects using the software or recent scholarly publications enabled by it




