---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "circtools"
summary: "Circtools is a software for circRNA research that covers the complete workflow of circRNA of detection, analysis, primer and siRNA design for follow-up wet lab experiments."
authors: [Tobias Jakobi]
tags: [circRNA, software]
categories: []
date: 2021-03-01T17:33:48+02:00
weight: 2

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:

- name: Code
  url: https://github.com/dieterich-lab/circtools
  icon_pack: fas
  icon: code

- name: Docs
  url: https://docs.circ.tools/en/latest/
  icon_pack: fas
  icon: tools
    
- name: Publication
  url: https://academic.oup.com/bioinformatics/article/35/13/2326/5194340
  icon_pack: fas
  icon:  file-alt


#  icon_pack: fab
#  icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

slides: "/test"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Circular RNAs (circRNAs) originate through back-splicing events from linear
primary transcripts, are resistant to exonucleases, typically not
polyadenylated, and have been shown to be highly specific for cell type and
developmental stage. Although few circular RNA molecules have been shown to
exhibit miRNA sponge function, for the vast majority of circRNAs however, their
function is yet to be determined.

The prediction of circular RNAs is a multi-stage bioinformatics process starting
with raw sequencing data and usually ending with a list of potential circRNA
candidates which, depending on tissue and condition may contain hundreds to
thousands of potential circRNAs. While there already exist a number of tools for
the prediction process (e.g. DCC and circTest), publicly available downstream
analysis tools are rare.

We developed circtools, a modular, Python3-based framework for circRNA-related
tools that unifies several functionalities in single command line driven
software. The command line follows the circtools subcommand standard that is
employed in samtools or bedtools. Circtools includes modules for RBP enrichment
screenings, circRNA primer design, as well as interfaces to the processing tools
FUCHS and DCC; miRNA seed analysis and differential exon usage will we available
in the upcoming release.

We intend to add more and more modules in the future in order to provide a
comprehensive bioinformatics toolbox and also encourage users to contribute
modules to circtools.
