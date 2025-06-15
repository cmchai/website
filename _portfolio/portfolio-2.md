---
title: "Brain decoding on cognitive processes"
excerpt: "Applying machine learning algorithms to decode people's mind using brain imaging data <br/><img src='/website/images/brain_decoding.png' style='width: 50%; height: auto;'>"
collection: portfolio
---

### hosting organization: Ghent University and Unversity Hospital
### project status: wraping up

## The aim of this research project
In this research project, we are interested in the neural mechanism that enables us to flexibly prepare for various tasks by \(re\)combining elementary task components.

## Main research tools and techniques

**Behavioral experimentation**: 
Previously, we have developed a behavioral paradigm in which participants were encouraged to dynamically modulate their task preparation process when they are not certain of the task they are going to perform \(for more information regarding the paradigm itself, please see our [published article](https://www.sciencedirect.com/science/article/abs/pii/S0010027724000702)\). In this study, we still used the same behvaioral paradigm.

**Neural imaging**: 
We recorded the brain activity using the MRI scanner. Participants were asked to do the task in the scanner while brain activity was measured at the same time. These functional MRI\(fMRI\) images and structural images were further processed before being decoded.

**Medical image processing and machine learning techniques**
![](https://raw.githubusercontent.com/cmchai/website/refs/heads/master/images/brain_scan.jpg){: style="float: right; margin: 0 0 1em 1em;" width="350px"}
The images we collected from the MRI scanner went through various processing steps, including motion correction, bandpass filtering, and linear regression. The resulting data were further fed into a machine learning decoder \(such as SVM, logistic regression, random forest etc.\) to quantify how stronly a certain information is represented in the brain.

## Key findings
We found that the tasks that we are preparing for can be decoded in certain brain regions, such as frontal cortex. Importantly, this task information was represented in different formats. Namely, the tasks were represented in both compositional and conjunctive format. Interestingly, we found that these two representational formats can be separately controlled to maximize our flexibility in a uncertain task environment.

## Research output
This study was included as part of my PhD thesis, which you can find via [this link](https://biblio.ugent.be/) after my defense which is scheduled in September 2025.

The results of this study have been presented at various national and international academic conferences in the format of either oral presentation or a poster. Please go to the Talks page to find more details about them.

The manuscript for journal submission is currently in preparation.