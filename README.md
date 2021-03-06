# Automated PELOD-2 calculation

This script calculates the Pediatric Logistic Organ Dysfunction-2 (PELOD-2). It has been tested and validated on SQL Server 2008 revision 2 at Sainte-Justine Hospital (Montreal, Canada). It requires minor adaptation in order to collect data with a different electronic medical record.

*Inputs*: key-value structure\
*Intermediate output*: PaO2/FiO2 ratio using the last FiO2 available in the 60 minutes preceding the PaO2\
*Outputs*: Most abnormal value per PELOD-2 categories, automated PELOD-2 (aPELOD-2) [summation of the categories], estimated death probability

# References

1. Sauthier M, Landry-Hould F, Leteurtre S, Kawaguchi A, Emeriaud G, Jouvet P. Comparison of the Automated Pediatric Logistic Organ Dysfunction-2 Versus Manual Pediatric Logistic Organ Dysfunction-2 Score for Critically Ill Children. Pediatr Crit Care Med 2020. Available from: http://journals.lww.com/10.1097/PCC.0000000000002235 

2. Leteurtre S, Duhamel A, Salleron J, et al (2013) PELOD-2: An update of the PEdiatric logistic organ dysfunction score. Crit Care Med 41:1761–1773. Available from: https://doi.org/10.1097/CCM.0b013e31828a2bbd
