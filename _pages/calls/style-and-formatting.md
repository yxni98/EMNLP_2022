---
title: NAACL-HLT 2021 Style Files and Formatting
layout: single
permalink: /calls/style-and-formatting/
sidebar:
    nav: "calls"
toc: false
---

The templates are available as an [Overleaf template](https://www.overleaf.com/latex/templates/naacl-hlt-2021-latex-template/kvjhhyjsvmxf) and can also be downloaded directly ([LaTeX](/downloads/naacl2021-latex.zip), [Word](/downloads/naacl2021.docx)).

## Formatting Guidelines

* Please follow the formatting documentation general to \*ACL conferences available [here](https://acl-org.github.io/ACLPUB/formatting.html). The templates themselves contain only specific notes (e.g., LaTeX notes in the .tex file).

* **Extra space for ethical considerations:** Please note that extra space is allowed after the 8th page (4th page for short papers) for an ethics/broader impact statement.  At submission time, this means that if you need extra space for the ethical considerations section, it should be placed after the conclusion so that it is possible to rapidly check that the rest of the paper still fits in 8 pages (4 pages for short papers).  For camera-ready versions 9 pages of content will be allowed for long (5 for short)  papers. Ethical considerations sections, acknowledgements, and references do not count against these limits.

**Notable changes in the templates** (by Matt Post and David Chiang) **are:**

* NAACL-HLT 2021 is using latex templates based on the new organization of templates and formatting guidelines for \*ACL papers [here](https://github.com/acl-org/ACLPUB).

* We now use the "lineno" package instead of writing pseudo-numbers down the margins. Line numbers now line up, and many other simplifications were enabled by this change.

* We will not use the `\aclfinalcopy` command. Instead, the review copy (anonymized, page and line numbers) is enabled by passing "review" as an "acl" package argument:

  ```
  \usepackage[review]{acl}
  ```

* There is no `\aclpaperid` macro. Softconf will add the submission ID stamp.

* A few bug fixes that have cropped up over the years and then sometimes inadvertently reintroduced.
