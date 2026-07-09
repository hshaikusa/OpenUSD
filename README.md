<img width="250" height="250" alt="nvidia-certified-professional-openusd-development" src="https://github.com/user-attachments/assets/d18bd947-bc86-43f1-987e-afe4689666fc" />

# OpenUSD Study Notes

**A Study Companion for the NCP-OpenUSD Certification Preparation**

📄 [`OpenUSD_QuickReviewStudyNotes.pdf`](./OpenUSD_QuickReviewStudyNotes.pdf) · 346 pages

## Abstract

This is a supplemental document collecting personal study notes compiled while preparing
for the **NVIDIA-Certified Professional (NCP): OpenUSD Development** exam. It's intended
as a quick reference for concepts covered by the certification, and includes conceptual
explanations, code snippets, cheat sheets, diagrams, and three full sets of practice
questions (70 questions each) mapped to the official exam domains. In addition to the document,
provided 3 practice tests to simulate the test experience.

## Author

**Hashim Shaik, Ph.D.**
NVIDIA Certified Professional | OpenUSD Development
[linkedin.com/in/hashimshaik](https://www.linkedin.com/in/hashimshaik/)

## Contents

Notes are organized loosely around the eight official NCP OpenUSD Development exam
domains, in roughly the order the topics were encountered while studying:

| Domain | Official Exam Weight |
|---|---|
| Composition | 23% |
| Data Exchange | 15% |
| Pipeline Development | 14% |
| Data Modeling | 13% |
| Debugging & Troubleshooting | 11% |
| Content Aggregation | 10% |
| Visualization | 8% |
| Customizing USD | 6% |

Also included:
- **Model Kind Hierarchy**, **Asset Structure Principles**, **Composition Arcs**, and other
  cross-cutting deep dives (e.g. `UsdShade`, `UsdSkeleton`, `UsdGeomCamera`, `usdLux`,
  Scenegraph/Point Instancing, Asset Resolution, `TF_DEBUG`)
- **Appendix**: three independent 70-question practice exams (210 questions total),
  each broken out by domain with an answer key
- Front matter: author's note, disclaimer, acknowledgments, and references

See the in-document Table of Contents (page 4) for the full breakdown with page numbers.

## How to Use This Document

Don't read it front to back. Suggested approach:

1. Skim the [Learn OpenUSD](https://docs.nvidia.com/learn-openusd/latest/index.html) course
   catalog first so the domain structure below is familiar.
2. Use the table of contents to jump to the domain you're weakest in.
3. Skim the "Key Insight" and "Cheat Sheet" callouts before reading the full explanation.
4. Work the practice questions in the Appendix, then revisit weak domains.
5. Cross-check anything exam-critical against the official documentation linked throughout
   — these are personal notes, not a replacement for the source material.

## Disclaimer

> This document is a set of independently compiled personal study notes for the
> NVIDIA-Certified Professional: OpenUSD Development exam. It is not an official NVIDIA or
> Pixar/AOUSD publication and is not endorsed by either organization. Content has been
> paraphrased, summarized, and synthesized with the help of AI tools from public
> documentation, personal experimentation, and third-party sources, and may contain errors,
> omissions, or simplifications. Always verify technical details against the authoritative
> sources before relying on them in production.

## References

- [NVIDIA Learn OpenUSD](https://docs.nvidia.com/learn-openusd/latest/index.html)
- [NVIDIA Omniverse USD Documentation](https://docs.omniverse.nvidia.com/usd/latest/index.html)
- [OpenUSD.org (Pixar/AOUSD official docs)](https://openusd.org/release/index.html)
- [OpenUSD API Reference](https://openusd.org/release/api/index.html)
- [USD Glossary](https://openusd.org/docs/USD-Glossary.html)
- [NVIDIA-Certified Professional: OpenUSD Development Exam Study Guide (v1.1.0)](https://nvdam.widen.net/s/6kxsqcsrrw/ncp-openusd-development-study-guide)
- [The Alliance for OpenUSD (AOUSD)](https://aousd.org)

## Known Limitations

- Section-specific citations are not included inline throughout the document.
- Some sections cover overlapping topics from different angles (e.g. Composition arcs,
  Model Hierarchy, and Variants each appear in more than one section) rather than being
  fully de-duplicated.
- Content was AI-assisted in research and synthesis; treat it as a study aid, not a
  verbatim source of truth. Corrections and pull requests are welcome.

## Contributing

Found an error, a stale link, or an outdated API reference? Issues and pull requests
correcting technical inaccuracies or improving clarity are welcome.

## License

No formal license is currently attached to this document — it's shared for personal,
non-commercial study purposes. If you plan to redistribute, adapt, or publish this
content beyond personal use, please reach out to the author first before doing so.
