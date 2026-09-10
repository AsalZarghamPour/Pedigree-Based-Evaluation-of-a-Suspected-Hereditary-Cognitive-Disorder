# Pedigree-Based Evaluation of a Suspected Hereditary Cognitive Disorder

**Helix Institute for Medical and Biological Science**
**Genomics Laboratory**

**Author:** Asal ZarghamPour

**Institution:** Helix Institute for Medical and Biological Science
**Genomics Laboratory:** Genomics Laboratory

---

## 1. Introduction

### 1.1. Hereditary Cognitive Disorders and Neurodevelopmental Disorders

Inherited cognitive disorders can be considered in the category of neurodevelopmental disorders (NDDs). These disorders are a set of conditions that appear during development and can affect cognitive functions, learning, language, motor skills, behavior and social functioning of the individual.

One of the most important manifestations of this group is Intellectual Disability (ID), which is associated with limitations in cognitive functions as well as adaptive skills.

Clinically, cognitive disorders have a very wide spectrum, such that in some individuals they can be associated with learning difficulties or delays in cognitive development, and in others, in addition to cognitive impairment, they show symptoms such as speech and motor delay, epilepsy, behavioral disorders, dysmorphic features, movement disorders, brain development abnormalities or other systemic problems. This diversity in these disorders is one of the main reasons for the difficulty in diagnosing their molecular cause.

### 1.2. Genetic Basis of Cognitive and Neurodevelopmental Disorders

Genetic factors play an important role in the development of cognitive disorders and NDDs. More than 1700 ID-related disorders have been identified with genetic factors. This diversity means that a similar phenotype can result from pathogenic changes in completely different genes.

Therefore, simply observing a variant in a gene known as an “ID-related gene” is not sufficient to determine the cause of the disease, and the variant, the specific disease, the phenotype, and the inheritance pattern must be examined simultaneously.

The aim of this study is to identify and prioritize the variants and genes that are most consistent with the clinical phenotype, pedigree pattern, and family inheritance model, and to assess the level of evidence for their possible role in the observed cognitive impairment.

Ultimately, this approach can help identify the most likely candidate genes and determine the necessary pathways for complementary studies and confirmation of the molecular diagnosis.

---

# 2. Case Description

In this case, a consanguineous family has two children, a boy and a girl, with learning disabilities.

The affected individuals were 35 and 32 years old at the time of examination, respectively, and their head circumferences were 58 (-2.18 SD) and 53 (-1.42 SD) centimeters, respectively.

The family also has a healthy boy and a girl. The paternal cousin also shows the same symptoms.

**Figure 1. Pedigree**

> *Pedigree figure should be added here.*

---

# 3. Materials and Methods

## 3.1. NGS Data

Raw next-generation sequencing (NGS) data were processed using CLC Genomics Workbench 26 software and converted into an Excel file for better processing and analysis through standard Variant Call Format (VCF) data steps.

Also, variant information was examined in terms of genetic and clinical characteristics including chromosomal location, reference and alternative allele, involved gene, functional consequence of the variant, allele frequency in the population, clinical annotations and pathogenicity information.

In order to reduce the number of unrelated variants and identify variants that could contribute to the studied phenotype, a step-wise process for quality control, variant filtering and prioritization was performed.

## 3.2. Variant Filtering

To identify the main and influential variants, we filtered the variants in the file in a stepwise manner.

In this step, the quality of the available variants was examined and the variants that did not have sufficient quality were eliminated. Also, to achieve more accurate filtering, the frequency of the variants in the general population was also examined.

Given that variants that are observed with high frequency in the population are less likely to be the cause of a rare Mendelian genetic disorder, common variants were therefore removed from the analysis.

Then, to obtain more accurate data, exonic variants were selected and their information in databases such as ClinVar was evaluated, as well as classifications obtained from annotation and interpretation tools.

Variants reported as Pathogenic or Likely Pathogenic were given higher priority; however, the absence of annotation in ClinVar was not considered as evidence for the benignity of the variant.

The remaining variants were screened using ACMG criteria, and those that were Pathogenic, Likely Pathogenic VUS were retained for further steps.

## 3.3. Zygosity and Inheritance Filtering

Given the consanguineous marriage and the observed family pattern (healthy parents and the same disease in the paternal family), autosomal recessive inheritance was considered as one of the main models.

Also, homozygous variants were prioritized due to the presence of healthy individuals in genes that had a reliable association with recessive diseases and the phenotype of interest.

---

## Table 1. Filtered Variants Prioritized by Phenotype Association and Inheritance Compatibility

| Gene        | Zygosity   | Variant Classification | Association with Cognitive/NDD Phenotype                                                                                 | Current Priority | Inheritance |
| ----------- | ---------- | ---------------------- | ------------------------------------------------------------------------------------------------------------------------ | ---------------- | ----------- |
| **F5**      | Homozygous | Likely Pathogenic      | Weak/No direct association with ID; primarily Factor V deficiency/thrombophilia                                          | Exclude          | AD-AR       |
| **TRMT44**  | Homozygous | VUS                    | Reported association with X-linked intellectual disability; inheritance is less compatible with this pedigree            | Secondary        | XLR         |
| **DST**     | Homozygous | VUS                    | Weak/uncertain evidence for ID; established disorders mainly include neuropathy and epidermolysis bullosa                | Secondary        | AR          |
| **TBC1D32** | Homozygous | VUS                    | Associated with microcephaly and impaired intellectual development                                                       | Primary          | AR          |
| **CUX1**    | Homozygous | VUS                    | Strong association with developmental delay/ID; mainly reported with heterozygous pathogenic variants                    | Primary          | AD          |
| **TCAF2**   | Homozygous | VUS                    | Indirect; developmental delay reported in 13q14 deletions, but not evidence for isolated TCAF2 SNVs                      | Exclude          | AR          |
| **NOS3**    | Homozygous | Likely Pathogenic      | No established Mendelian NOS3–ID disorder                                                                                | Exclude          | AR          |
| **ALG2**    | Homozygous | VUS                    | Biallelic ALG2 variants associated with developmental delay and intellectual disability                                  | Primary          | AR          |
| **ACAN**    | Homozygous | VUS                    | Possible secondary association; primarily skeletal disorders/short stature; cognitive phenotype is not a primary feature | Exclude          | AD-AR       |
| **PRODH**   | Homozygous | Likely Pathogenic      | Biallelic variants cause hyperprolinemia type I; severe cases can include neurological manifestations and ID             | Primary          | AD-AR       |
| **AMER1**   | Homozygous | VUS                    | Associated with osteopathia striata with cranial sclerosis; mild ID may occur; phenotype dependent and X-linked          | Secondary        | XLD         |
| **TRMT2B**  | Homozygous | VUS                    | Reported in developmental/epileptic encephalopathy, but phenotype match is incomplete                                    | Secondary        | —           |
| **GABRE**   | Homozygous | VUS                    | Reported association with epilepsy and developmental/ID phenotypes; evidence is limited                                  | Secondary        | XLR         |

---

# 4. Results

## 4.1. Analysis of Final Candidate Genes

### TBC1D32

TBC1D32 (TBC1 domain family member 32) is a protein involved in primary cilia function and regulation of the Sonic Hedgehog (Shh) pathway, a pathway that plays an important role in embryonic development and patterning, particularly in the development of the brain, hypothalamus, and other tissues.

Human studies and animal models have shown that disruption of TBC1D32 can cause defects in cilia formation and function, and consequently, disruption of Shh signaling.

In studies of patients with rare variants, especially biallelic/recessive variants in TBC1D32, a diverse spectrum of manifestations including microcephaly, developmental delay, intellectual disability, growth disorders, and congenital anomalies has been reported; for example, in one patient with a homozygous variant, microcephaly was observed with moderate-to-severe intellectual disability.

Therefore, TBC1D32 was selected as a potential candidate in this case because, on the one hand, the homozygous variant is consistent with the expected autosomal recessive pattern in a consanguineous family, and on the other hand, the known association of this gene with microcephaly and developmental disorders is consistent with the patient's main phenotype, namely cognitive/developmental impairment.

However, since the variant identified in this study is a VUS, its association with the disease requires further investigation of the variant and segregation evidence.

---

### ALG2

ALG2 is a gene that encodes the enzyme alpha-1,3/1,6-mannosyltransferase; this enzyme is involved in the early stages of N-linked glycosylation and the synthesis of dolichol-linked oligosaccharides in the endoplasmic reticulum membrane.

Disturbances in this process can affect the function of many glycoproteins, and therefore, ALG2 deficiency can cause a multisystem disease with neurological manifestations.

Biallelic variants in ALG2 are associated with ALG2 congenital disorder of glycosylation (ALG2-CDG), an autosomal recessive disorder that can be associated with global developmental delay, intellectual disability, delayed speech and motor development, hypotonia, seizures, and other neurological abnormalities.

ClinGen also assessed the association of ALG2 with ALG2-CDG as Strong and reported an autosomal recessive inheritance pattern.

Therefore, ALG2 was selected as a prime candidate because of the homozygous nature of the variant, the compatibility of inheritance with consanguinity, and the existence of a direct and reliable association between biallelic ALG2 variants and developmental/intellectual impairment.

Compared with some other candidates, the strength of ALG2 is that both the inheritance pattern and the gene-disease association are remarkably consistent with the findings in this family.

---

### PRODH

PRODH (proline dehydrogenase 1) is a gene encoding the enzyme proline dehydrogenase/proline oxidase, which is located in mitochondria and catalyzes the first step in the breakdown of the amino acid proline; in this reaction, proline is converted to pyrroline-5-carboxylate (P5C), which is then coupled to glutamate.

Disruption of PRODH function results in reduced proline breakdown and hyperprolinemia type I; this disease has an autosomal recessive inheritance pattern, and ClinGen has assessed the association of PRODH with hyperprolinemia type I as Definitive.

Although many affected individuals may be asymptomatic, in more severe cases, neurological manifestations including seizures and intellectual disability have been reported.

Clinical studies have also reported cases of patients with homozygous PRODH variants with mild intellectual disability.

PRODH was therefore considered a potential candidate in this study, especially since the identified variant was homozygous and Likely Pathogenic, and its inheritance pattern was consistent with the autosomal recessive pattern expected in the family.

However, there is an important limitation: intellectual disability is not a consistent and primary manifestation of hyperprolinemia; therefore, to determine whether PRODH is indeed the cause of this patient's phenotype, it will be important to examine clinical evidence such as plasma proline level and other features associated with hyperprolinemia.

---

### CUX1

CUX1 (cut-like homeobox 1) is a transcription factor involved in the regulation of gene expression and important neurodevelopmental processes.

CUX1 is expressed in the developing brain, particularly in cortical neurons, and is involved in the formation of dendritic arbors and neuronal connections.

Pathogenic variants of CUX1, particularly heterozygous loss-of-function variants, are associated with a well-known neurodevelopmental disorder with global developmental delay and intellectual disability.

In a study of 34 affected individuals, the most common manifestations included speech delay, motor delay, and varying degrees of intellectual disability, and some patients also had hypotonia and seizures.

NCBI also associates CUX1 with global developmental delay with or without impaired intellectual development, and ClinGen reports sufficient evidence for haploinsufficiency of this gene.

Therefore, CUX1 is a very strong candidate in terms of phenotype match, as it has a direct and relatively strong association with developmental delay and ID.

However, in the present case, the variant is homozygous, whereas the known pathogenic mechanism of CUX1 is predominantly heterozygous loss-of-function/haploinsufficiency.

Therefore, despite the strong phenotypic match, the relative inconsistency between the observed zygosity and the known inheritance mechanism of CUX1 makes this gene a lower priority than TBC1D32 and ALG2.

Despite the strong phenotypic association of CUX1 with developmental delay and intellectual disability, the homozygous state of the identified variant is not fully consistent with the established haploinsufficiency mechanism of CUX1-related neurodevelopmental disorder.

Therefore, a de novo event should also be considered and, if parental samples are available, parental testing would be important to determine whether the variant is absent in both parents.

Confirmation of a de novo occurrence could provide additional evidence for pathogenicity; however, the unusual zygosity would still require careful interpretation.

---

## Table 2. Summary of the Prioritization of Final Candidate Genes

| Gene        | Variant           | Zygosity   | Variant Evidence | Phenotype Match | Inheritance Match | Priority |
| ----------- | ----------------- | ---------- | ---------------- | --------------- | ----------------- | -------: |
| **TBC1D32** | VUS               | Homozygous | Limited          | High            | High              |    **1** |
| **ALG2**    | VUS               | Homozygous | Limited          | High            | High              |    **2** |
| **PRODH**   | Likely Pathogenic | Homozygous | Strong           | Moderate        | High              |    **3** |
| **CUX1**    | VUS               | Homozygous | Limited          | High            | Low               |    **4** |

---

# 5. Discussion

In this study, with the aim of identifying genes likely associated with the cognitive and developmental disorder phenotype in a family with a familial pattern consistent with a hereditary disease, NGS data were filtered and prioritized after transforming the identified variants into an analyzable set.

In the first step, variants were screened based on features such as zygosity, clinical classification, and evidence available in databases. Among the remaining variants, genes with known or possible association with neurodevelopmental disorders, developmental delay, or intellectual disability were evaluated, with particular attention to the phenotype and inheritance pattern of the family.

The final analysis showed that not all remaining variants had equal value in explaining the patient's phenotype.

For example, although variants in F5, NOS3, and some other genes had relatively strong classification, the lack of a direct and reliable association between these genes and the patient's underlying phenotype led to their removal from clinical priority.

This finding highlights the importance of distinguishing between pathogenicity of a variant and causality for the phenotype under study; in other words, a Likely Pathogenic variant is not necessarily the cause of the disease observed in a patient unless it is also supported by gene-disease association and phenotypic concordance.

Among the higher priority genes, TBC1D32 showed a significant concordance with the clinical features and inheritance pattern of the family.

This gene is involved in the function of primary cilia and the regulation of the Sonic Hedgehog pathway, a pathway that is important for normal nervous system development and embryonic development.

The association of TBC1D32 with microcephaly and neurodevelopmental disorders, together with the homozygous nature of the variant and the compatibility of autosomal recessive inheritance with the family background, made this gene one of the most important candidates for the study.

However, since the variant identified in TBC1D32 is classified as a VUS, the available evidence is insufficient to definitively attribute the disease to this gene and it should be considered a priority candidate, not a definitive cause.

ALG2 was also another important candidate due to the known association between biallelic variants of this gene and developmental disorders with intellectual disability.

The compatibility of the autosomal recessive pattern and homozygous nature of the variant with the family background increased the value of this gene in prioritization.

However, ALG2-related disorders can often have multisystem manifestations, and therefore the extent to which other clinical features of the patient fit the full spectrum of ALG2-related disorders can be important in determining the final location of this gene.

In the case of PRODH, a different situation was observed.

The homozygous variant of this gene, classified as Likely Pathogenic, with autosomal recessive inheritance, was significant in terms of evidence for the variant itself.

PRODH is involved in proline metabolism, and its deficiency can cause hyperprolinemia type I; in some severe cases, neurological manifestations, including cognitive impairment, have also been reported.

However, since intellectual disability is not a consistent and specific feature in all individuals with PRODH disorders, the phenotype agreement is more limited in this case than in TBC1D32 and ALG2.

Therefore, strong evidence for pathogenicity of a PRODH variant alone is not sufficient to establish it as a definitive cause of the phenotype, and examination of relevant clinical or biochemical evidence can be very helpful in its final evaluation.

CUX1 was a notable candidate for association with neurodevelopmental disorders and intellectual disability, and showed high phenotypic concordance.

CUX1 is a transcription factor important in the development and function of the nervous system, and its pathogenic variants, particularly heterozygous loss-of-function variants, have been associated with developmental delay and intellectual disability.

However, the homozygosity of the variant found in this study does not fully fit the known pathogenic mechanism of CUX1.

Therefore, despite strong phenotypic concordance, CUX1 was given a lower priority than candidates whose phenotype and inheritance were more consistent with the family.

If parental samples are available, segregation analysis and, in particular, the possibility of de novo variant occurrence could help clarify the clinical significance of this finding.

Overall, the comparison of these four genes suggests that no single criterion, including Variant Classification, can alone determine disease etiology.

The best candidate should be selected based on a combination of variant evidence, gene function, gene–disease association, phenotype, and inheritance pattern.

Based on this approach, TBC1D32 received the highest overall priority due to the concurrence of phenotypic concordance, inheritance pattern concordance, and homozygosity.

However, the VUS nature of the variant suggests that further studies are necessary to confirm its association with phenotype.

---

# 6. Conclusion

NGS data analysis and systematic prioritization of variants led to the identification of four major genes, including TBC1D32, ALG2, PRODH, and CUX1, as candidates associated with the cognitive and developmental disorder phenotype.

The selection of these genes was based on a combination of gene-disease association, phenotypic concordance, inheritance pattern, zygosity, and variant status.

Among the final candidates, TBC1D32 was selected as the most likely genetic candidate due to its association with microcephaly and neurodevelopmental disorders, as well as the compatibility of the homozygous variant with the autosomal recessive pattern of the family.

However, since the TBC1D32 variant is in the VUS category, this finding alone is not sufficient to prove the cause of the disease.

Finally, this study suggests that interpretation of NGS data should be based on a combination of genetic and clinical evidence and not based solely on the pathogenicity of a variant or the name of a gene.

Segregation studies in family members, more detailed evaluation of the ACMG evidence, and, if possible, functional studies could help in the future to determine the true role of TBC1D32 and other identified candidates in the phenotype of this family.

---

# 7. References

1. Richards S, Aziz N, Bale S, Bick D, Das S, Gastier-Foster J, et al.; ACMG Laboratory Quality Assurance Committee. Standards and guidelines for the interpretation of sequence variants: a joint consensus recommendation of the American College of Medical Genetics and Genomics and the Association for Molecular Pathology. *Genet Med.* 2015;17(5):405-424. doi:10.1038/gim.2015.30.

2. Landrum MJ, Lee JM, Benson M, Brown GR, Chao C, Chitipiralla S, et al. ClinVar: improving access to variant interpretations and supporting evidence. *Nucleic Acids Res.* 2018;46(D1):D1062-D1067. doi:10.1093/nar/gkx1153.

3. Amberger JS, Bocchini CA, Schiettecatte F, Scott AF, Hamosh A. OMIM.org: Online Mendelian Inheritance in Man (OMIM®), an online catalog of human genes and genetic disorders. *Nucleic Acids Res.* 2015;43(Database issue):D789-D796. doi:10.1093/nar/gku1205.

4. Karczewski KJ, Francioli LC, Tiao G, Cummings BB, Alföldi J, Wang Q, et al.; Genome Aggregation Database Consortium. The mutational constraint spectrum quantified from variation in 141,456 humans. *Nature.* 2020;581(7809):434-443. doi:10.1038/s41586-020-2308-7.

5. Danecek P, Auton A, Abecasis G, Albers CA, Banks E, DePristo MA, et al.; 1000 Genomes Project Analysis Group. The variant call format and VCFtools. *Bioinformatics.* 2011;27(15):2156-2158. doi:10.1093/bioinformatics/btr330.

6. Maia N, Sá MJN, Melo-Pires M, de Brouwer APM, Jorge P. Intellectual disability genomics: current state, pitfalls and future challenges. *BMC Genomics.* 2021;22(1):909. doi:10.1186/s12864-021-08227-4.

7. Strande NT, Riggs ER, Buchanan AH, Ceyhan-Birsoy O, Cooper GM, Hamosh A, et al. Evaluating the clinical validity of gene-disease associations: an evidence-based framework developed by the Clinical Genome Resource. *Am J Hum Genet.* 2017;100(6):895-906. doi:10.1016/j.ajhg.2017.04.015.

8. Adly N, Alhashem A, Ammari A, Alkuraya FS. Ciliary genes TBC1D32/C6orf170 and SCLT1 are mutated in patients with OFD type IX. *Hum Mutat.* 2014;35(1):36-40. doi:10.1002/humu.22477.

9. Hietamäki J, Gregory LC, Ayoub S, Iivonen AP, Vaaralahti K, Liu X, et al. Loss-of-function variants in TBC1D32 underlie syndromic hypopituitarism. *J Clin Endocrinol Metab.* 2020;105(6):1748-1758. doi:10.1210/clinem/dgaa078.

10. Alsahan N, Alkuraya FS. Confirming TBC1D32-related ciliopathy in humans. *Am J Med Genet A.* 2020;182(8):1985-1987. doi:10.1002/ajmg.a.61717.

11. Harris SC, Chong K, Chitayat D, Gilmore KL, Jorge AAL, Freire BL, et al. Diagnosis of TBC1D32-associated conditions: expanding the phenotypic spectrum of a complex ciliopathy. *Am J Med Genet A.* 2023;191(5):1282-1292. doi:10.1002/ajmg.a.63150.

12. Thiel C, Schwarz M, Peng J, Grzmil M, Hasilik M, Braulke T, et al. A new type of congenital disorders of glycosylation (CDG-Ii) provides new insights into the early steps of dolichol-linked oligosaccharide biosynthesis. *J Biol Chem.* 2003;278(25):22498-22505. doi:10.1074/jbc.M302850200.

13. Clinical Genome Resource (ClinGen). ALG2–ALG2-congenital disorder of glycosylation: Gene-Disease Validity Curation. Classification: Strong; Autosomal recessive; 15 November 2023. ClinGen Curation ID: CCID:004102.

14. Guilmatre A, Legallic S, Steel G, Willis A, Di Rosa G, Goldenberg A, et al. Type I hyperprolinemia: genotype/phenotype correlations. *Hum Mutat.* 2010;31(8):961-965. doi:10.1002/humu.21296.

15. Hama R, Kido J, Sugawara K, Nakamura T, Nakamura K. Hyperprolinemia type I caused by homozygous p.T466M mutation in PRODH. *Hum Genome Var.* 2021;8:28. doi:10.1038/s41439-021-00159-5.

16. Clinical Genome Resource (ClinGen). PRODH–hyperprolinemia type 1: Gene-Disease Validity Curation. Classification: Definitive; Autosomal recessive; 27 April 2021. ClinGen Curation ID: CCID:005892.

17. Platzer K, Cogné B, Hague J, Marcelis CLM, Mitter D, Oberndorff K, et al. Haploinsufficiency of CUX1 causes nonsyndromic global developmental delay with possible catch-up development. *Ann Neurol.* 2018;84(2):200-207. doi:10.1002/ana.25278.

18. Oppermann H, Marcos-Grañeda E, Weiss LA, Gurnett CA, Jelsig AM, Vineke SH, et al. CUX1-related neurodevelopmental disorder: deep insights into phenotype-genotype spectrum and underlying pathology. *Eur J Hum Genet.* 2023;31(11):1251-1260. doi:10.1038/s41431-023-01445-2.

19. Clinical Genome Resource (ClinGen). CUX1 dosage sensitivity curation. Haploinsufficiency: Sufficient Evidence for Haploinsufficiency (HI Score 3); last evaluated 16 July 2026.

---

# Database / Software

The following databases, software, and resources were used in the analysis:

* CLC Genomics Workbench 26
* NCBI
* ClinVar
* OMIM
* GeneCards
* Reactome
* Microsoft Excel
* ACMG guidelines

---

## Project Workflow

```text
NGS Data
   ↓
VCF Generation
   ↓
Excel Conversion
   ↓
Quality & Variant Filtering
   ↓
Population Frequency Filtering
   ↓
Exonic Variant Selection
   ↓
Clinical Annotation
   ↓
ACMG-based Evaluation
   ↓
Zygosity & Inheritance Analysis
   ↓
Phenotype–Gene Association
   ↓
Candidate Gene Prioritization
   ↓
Final Candidate Genes
   ↓
TBC1D32
ALG2
PRODH
CUX1
```

## Final Candidate Ranking

|  Rank | Gene        | Main Reason for Prioritization                                               |
| ----: | ----------- | ---------------------------------------------------------------------------- |
| **1** | **TBC1D32** | Strong phenotype and inheritance concordance; homozygous VUS                 |
| **2** | **ALG2**    | Strong gene–disease association and AR inheritance compatibility             |
| **3** | **PRODH**   | Homozygous Likely Pathogenic variant with established AR disease association |
| **4** | **CUX1**    | Strong phenotype match but lower inheritance/zygosity compatibility          |

---

## Disclaimer

This project represents a bioinformatic and genomic variant prioritization analysis. Candidate gene prioritization does not establish a definitive molecular diagnosis. Further segregation, clinical, biochemical, and/or functional studies may be required for confirmation.
