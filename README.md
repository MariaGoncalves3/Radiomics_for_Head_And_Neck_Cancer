![image](https://user-images.githubusercontent.com/98060736/150524636-6c3f857d-f76a-428c-ad46-56378a0a15f6.png)

# Radiomics for Head and Neck Cancer Outcome Predictions

### Maria Gonçalves, Christina Gsaxner, Victor Alves and Jan Egger 

* __Collaboration between Centro Algoritmi, University of Minho, Braga, Portugal and Institute of Computer Graphics and Vision, Graz University of Technology, Graz, Austria__

> This project is the result of Maria Gonçalves (mariaa.goncalves31@gmail.com), Victor Alves (valves@di.uminho.pt) and Jan Egger (egger@icg.tugraz.at) work, having been developed as part of Maria Gonçalves' Master Thesis in Biomedical Engineering, Medical Informatics Branch from University of Minho.


# Abstract

Head and neck cancer has great regional anatomical complexity, as it can develop in different structures, exhibiting diverse tumour manifestations and high intratumoural heterogeneity, which is highly related to resistance to treatment, progression, the appearance of metastasis and tumour recurrences. Radiomics has the potential to address these obstacles by extracting quantitative, measurable, and extractable features from the region of interest of medical images. Nowadays, medical imaging is a common source of information in clinical practice, presenting a potential alternative to biopsy, as it allows the extraction of a large number of features that, although not visible to the naked eye, may be relevant for tumour characterisation. Taking advantage of Machine Learning techniques, the set of features extracted when associated to biological parameters, can be used for diagnosis, prognosis, and predictive accuracy valuable for clinical decision-making.

Therefore, the purpose of this research is to verify the effectiveness of translating the field of radiomics into standard cancer care, which allows a better characterization of the tumour phenotype for the construction of predictive models. Radiomics has been proven to be a fundamental concept for precision medicine, providing improvements in clinical decision making.

The main objective is to extract features from medical images that allow the identification of relevant prognostic factors in the evaluation of the aggressiveness and irregularity of the tumour. Through the construction and development of prediction models that use the learning capacities of Machine Learning techniques and using both radiomic data and clinical information from patients, the goal is to analyse the risk of locoregional recurrences (LR), evaluate the appearance of distant metastasis (DM) and estimate the overall survival (OS) rate in patients with head and neck cancer.


# Materials and Methods
### Data and Pre-Processing

For this study, a public dataset was used which is available on The Cancer Image Archive website (https://wiki.cancerimagingarchive.net/display/Public/Head-Neck-PET-CT). The information for patients with histologically proven head and neck cancer comes from four different institutions in Quebec: Centre Hospitalier de l’Université de Montréal (CHUM), Centre Hospitalier Universitaire de Sher-brooke (CHUS), Hôpital Général Juif (HGJ) and Hôpital Maisonneuve-Rosemont (HMR).
