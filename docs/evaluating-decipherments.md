# Evaluating Decipherments

This section gives a **proposed protocol**, synthesized here; no tests were run and no measurements are reported. It lets a reader compare linguistic and non-linguistic proposals without assuming either.

## Three different claims
1. **Structure detected:** sign sequences are non-random. Rao et al. (2009) use a statistical measure (conditional entropy) and present the result as evidence for a linguistic role.
2. **Language demonstrated:** the structure comes from a spoken language. Sproat (2010) criticizes the Rao et al. work and Rao et al. (2010) reply, so this step is disputed.
3. **Reading recovered:** specific sign values are justified. Structure alone cannot show this.

## Proposed checks
Each check names an outcome that would weaken a proposal.
1. **Corpus and segmentation:** state the corpus source, sign-variant merging and text-boundary rules. *Weakened if* conclusions change under reasonable alternative sign lists.
2. **Consistent rules:** fix sign-to-value rules before reading, with no per-inscription rebus choices. *Weakened if* the same sign needs different values in similar contexts, or many ad hoc exceptions are needed.
3. **Held-out prediction:** develop the proposal on part of the corpus, then predict withheld inscriptions. *Weakened if* accuracy is no better than a baseline model.
4. **Independent corroboration:** seek archaeological or cross-text support, such as a bilingual text. *Weakened if* readings conflict with find contexts.
5. **Fair controls:** apply the same statistic to known linguistic and non-linguistic systems. *Weakened if* a non-linguistic control scores as language does.

## Limits on inference
- Short texts give small samples: Farmer et al. (2004) report a longest inscription of 17 symbols and a mean of 4.6 signs, and treat this brevity as a major constraint on any reading.
- Flexible rebus choices let many readings fit a short text; fit alone is weak evidence.
- Statistical regularity does not by itself show language; this is the point at issue between Rao et al. (2009) and Sproat (2010).
- The sources above were checked by their text or abstract only where stated in the repository notes; Sproat (2010) and Rao et al. (2010) were not read in full here.

## References
- Farmer, S., Sproat, R., Witzel, M. 2004. The Collapse of the Indus-Script Thesis. *Electronic Journal of Vedic Studies* 11(2):19-57. https://safarmer.com/fsw2.pdf
- Rao, R. et al. 2009. Entropic Evidence for Linguistic Structure in the Indus Script. *Science* 324:1165. https://doi.org/10.1126/science.1170391
- Rao, R. et al. 2010. Entropy, the Indus Script, and Language: A Reply to R. Sproat. *Computational Linguistics* 36(4):795-805. https://doi.org/10.1162/coli_c_00030
- Sproat, R. 2010. Ancient Symbols, Computational Linguistics, and the Reviewing Practices of the General Science Journals. *Computational Linguistics* 36(3):585-594. https://doi.org/10.1162/coli_a_00011
