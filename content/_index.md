---
title: 
date: 2022-10-24
type: landing

sections:
  - block: hero
    id: intro
    content:
      title: |
        KITSO Research Group
      image:
        filename: machine_learning_sketch_english_LMU_classification_inkl_histology_imaging.jpg
      text: |
        **KI-gestützte Therapiestratifizierung in der Onkologie**
        
        The KITSO group develops computational and machine learning approaches for personalized cancer therapy stratification. We are part of the [Department of Radiation Oncology](https://www.lmu-klinikum.de/strahlentherapie-und-radioonkologie/das-team/ki-therapiesteuerung/351a62edb06ec660) at LMU Hospital and the [Faculty of Medicine](https://www.med.lmu.de/en/faculty/who-we-are/persons/contact-page/kristian-unger-80e55ac7.html) at Ludwig-Maximilians-Universität Munich.
    design:
      spacing:
        padding: ['60px', '0', '40px', '0']

  - block: markdown
    id: research
    content:
      title: Research
      text: |
        Our main aim is to integrate multi-omics data, medical imaging, and clinical information to develop predictive models that support treatment decisions in oncology. We focus on translational applications that can directly impact patient care.

        Here are some research areas in which we are actively involved:

        **Radiomics and Medical Imaging**  
        Development of AI models for quantitative analysis of CT, MRI, and PET imaging data to support radiation therapy planning, treatment response assessment, and outcome prediction.

        **Digital Pathology**  
        Application of deep learning methods to histopathological images for automated tissue classification, biomarker discovery, and integration with molecular data.

        **Multi-omics Data Integration**  
        Computational frameworks for integrating genomic, transcriptomic, and proteomic data to characterize tumor heterogeneity and identify therapeutic vulnerabilities.

        **Clinical Decision Support**  
        Translation of predictive models into clinical workflows, with emphasis on interpretability and validation in prospective cohorts.

    design:
      columns: '1'
      spacing:
        padding: ['40px', '0', '40px', '0']

  - block: markdown
    id: collabs
    content:
      title: Collaborations
      text: |
        We have the privilege of collaborating with a number of excellent clinical, pathology, experimental medical physics, and artificial intelligence research groups at Ludwig-Maximilians-Universität, Helmholtz Munich, the Munich Center for Machine Learning, and other universities, research institutions, and hospitals across Germany. Our recent and current collaborators include [Carsten Marr](https://www.helmholtz-munich.de/en/aih/carsten-marr), [Horst Zitzelsberger](https://www.helmholtz-munich.de/tmo/horst-zitzelsberger), [Guillaume Landry](https://www.med.physik.uni-muenchen.de/personen/guests/dr_guillaume_landry/index.html), [Olivier Gires](https://www.med.lmu.de/de/fakultaet/wer-wir-sind/personen/kontaktseite/olivier-gires-90e51fed.html),
        [Julia Heß](https://www.helmholtz-munich.de/en/tmo/julia-hess), and [Patrick Harter](https://www.med.lmu.de/en/faculty/who-we-are/persons/contact-page/patrick-harter-d471333c.html).
    design:
      columns: '1'
      spacing:
        padding: ['40px', '0', '40px', '0']
  
        
  - block: collection
    id: news
    content:
      title: News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: compact
      columns: '1'
      spacing:
        padding: ['40px', '0', '40px', '0']



  - block: collection
    id: publications
    content:
      title: Selected Publications
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: publication
    design:
      view: citation
      columns: '1'
      spacing:
        padding: ['40px', '0', '60px', '0']
---
