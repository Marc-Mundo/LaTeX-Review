# Visual Cortical Prostheses Systematic Review

This repository contains the source files for a systematic review on visual cortical prostheses, emphasizing the latest technological advancements, particularly in electrode design, signal processing, and AI integration. The review also investigates the optimization of phosphene patterns and real-time image processing through AI.

## Structure

- **Main Document:** [`review_main.tex`](review_main.tex) - This LaTeX file is the primary document containing the systematic review, divided into sections on technological advancements, AI integration, key articles, and future directions. It includes figures such as the block diagram of the Visual Prosthesis Simulation Framework.
- **Bibliography:** [`references.bib`](references.bib) - This BibTeX file includes all the citation information for the references used in the review.
- **Images:** `imgs` directory - Contains images used in the review, including the block diagram of the Visual Prosthesis Simulation Framework.

## Building

To build the review, ensure you have a LaTeX distribution installed. Compile `review_main.tex` to produce a PDF of the review:

```bash
pdflatex review_main.tex
bibtex review_main
pdflatex review_main.tex
pdflatex review_main.tex
```

## Contents Overview

### Abstract

The review explores visual cortical prostheses, focusing on AI's role in enhancing functionality and effectiveness. It covers the optimization of phosphene patterns, real-time image processing, and compares visual cortical prostheses with other prosthetic devices.

### Key Sections

1. **Introduction**
   - Background on visual cortical prostheses and their significance.
   - Research questions addressed in the review.
2. **Technological Advances**
   - Advancements in biomaterials and electrode design.
   - Improved signal processing and integration techniques.
   - Software and algorithmic enhancements, including real-time data processing.
   - Functional improvements like closed-loop feedback systems and multi-modal sensory integration.
3. **AI Integration**
   - The role of AI in optimizing stimulation patterns and image processing.
   - Overview of deep learning algorithms used in prosthetic vision.
4. **Comparison with Other Visual Systems**
   - Comparisons between visual cortical prostheses, retinal prostheses, and optic nerve prostheses.
   - Discussion on the differences between AI-enhanced prosthetic vision and natural visual processing.
5. **Clinical Applications**
   - Clinical trials and personalized prosthetic solutions.
   - Rehabilitation strategies leveraging neuroplasticity.
6. **Limitations and Challenges**
   - Current drawbacks and areas for improvement in visual cortical prosthesis technology.
7. **Future Perspectives**
   - Future research directions and potential advancements.
   - Ethical and societal implications of advanced neural interfacing technology.

### Figures and Diagrams

- **Functional schematic representation of a visual cortical prothesis:** Figure
describing the general design of a visual cortical prothesis and its design.
- **Visual Prosthesis Simulation Framework:** Detailed block diagram illustrating the framework for simulating and optimizing prosthetic vision using AI.
