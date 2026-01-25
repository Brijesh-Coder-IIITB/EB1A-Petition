# EB-1A I-140 Petition

This repository contains a LaTeX template for an EB-1A (Alien of Extraordinary Ability) I-140 immigrant petition. It is structured to help organize evidence, criteria arguments, and legal summaries into a professional document.

[**Download Compiled PDF Example**](https://github.com/rahvis/EB1A-Petition/blob/main/build/petition.pdf)

## Legal Disclaimer

**IMPORTANT: READ THIS FIRST**

This document and the associated files are provided for informational and educational purposes only.

**THIS IS NOT LEGAL ADVICE.**

The content within this repository does not constitute legal advice, nor does it create an attorney-client relationship. Immigration laws and regulations are complex, subject to change, and heavily dependent on individual circumstances.

**It is strictly up to the reader to reference this material. You should NOT rely on this template as a substitute for professional legal counsel. You are strongly advised to consult with a qualified immigration attorney regarding your specific case and before submitting any documents to USCIS.**

The authors of this repository assume no responsibility or liability for any errors or omissions in the content of this repository or for the results obtained from the use of this information.

## How to Run

This project relies on a standard LaTeX distribution (such as TeX Live, MacTeX, or MiKTeX).

### Prerequisites
- A LaTeX distribution installed on your system.
- `pdflatex` command-line tool.

### Build Steps
1. Open your terminal or command prompt.
2. Navigate to the root directory of this project.
3. Run the following command to compile the PDF:

```bash
pdflatex -interaction=nonstopmode petition.tex
```

4. If there are cross-references (like citations or labels), you may need to run the command multiple times:

```bash
pdflatex -interaction=nonstopmode petition.tex
pdflatex -interaction=nonstopmode petition.tex
```

5. The output file `petition.pdf` will be generated in the same directory.

## Frequently Asked Questions (FAQ)

**Can I use this template for my own EB-1A petition?**
Yes, this repository is intended to serve as a structural template. You will need to replace all petitioner-specific information (names, research details, citations, exhibits, etc.) with your own evidence.

**Do I need to be an expert in LaTeX to use this?**
Basic familiarity with LaTeX is helpful, but the template is designed to be modular. You primarily need to edit the content files in the `cover/` and `criteria/` directories.

**Does using this template guarantee approval?**
No. Approval depends entirely on the strength of your evidence and how well it meets the USCIS criteria. This template only provides a professional format for presenting your case.

**Where should I add my own evidence content?**
Most text content is located in the `.tex` files within the `cover/` and `criteria/` directories. You should modify these files to reflect your specific achievements.

## Acknowledgments and References

This document was prepared by referring to the open-source work of several individuals who have generously shared their EB-1A journeys.

**Primary Reference:**
- **Razvan Marinescu**: Special thanks to Razvan for his comprehensive blog and for making his petition structure open source.
    - Blog: [https://razvanmarinescu.github.io/green-card-I-140/](https://razvanmarinescu.github.io/green-card-I-140/)
    - GitHub: [https://github.com/razvanmarinescu/EB1A](https://github.com/razvanmarinescu/EB1A)

**Additional References:**
- **Kirill Nikitin**:
    - GitHub: [https://github.com/nikirill/eb1a](https://github.com/nikirill/eb1a)
    - Website: [https://nikirill.com/](https://nikirill.com/)

- **Ryan-Rhys Griffiths**:
    - Blog: [https://ryan-rhys.com/ryan__rhys/blog/2025/eb1a/](https://ryan-rhys.com/ryan__rhys/blog/2025/eb1a/)
    - GitHub: [https://github.com/Ryan-Rhys/EB1A.git](https://github.com/Ryan-Rhys/EB1A.git)

We extend our gratitude to these contributors for helpful resources.
