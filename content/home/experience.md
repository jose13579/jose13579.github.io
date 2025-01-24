---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Software Engineering
    company: 1oggi
    company_url: https://www.loggi.com/
    company_logo: loggi-logo
    location: São Paulo
    date_start: '2021-08-01'
    date_end: ''
    description: |2-
        Responsibilities include:
        * Designed and implemented solutions to significantly reduce the time required to declare damaged packages, achieving a 10x improvement compared to the manual process. The new application uses machine learning for text detection to determine if a package is damaged, cloud storage via Amazon S3 to store damaged package photos, and programming languages like Python and JavaScript for development.
        * Developed a chatbot to assist users with common inquiries, such as tracking missing packages and monitoring packages in progress. The chatbot improved response times by 5x compared to manual handling, enhancing customer satisfaction and operational efficiency.
        
  - title: Researcher
    company: Unicamp
    company_url: ''
    company_logo: unicamp-logo
    location: Campinas
    date_start: '2020-03-01'
    date_end: '2024-04-01'
    description: |2-
        Responsibilities included:
        * Proposed of an image inpainting model leveraging both CNNs and transformers to address challenges posed by large missing regions, this proposal achieved competitive results in comparison with state-of-the-art methods.
        * Developed of a novel variable hyperparameter strategy applied to the transformer to reduce the computational complexity. We achieved superior results in efficiency in comparison with recent methods, 3x times more efficient.
        * Proposed of a image inpainting model by incorporating auxiliary information from the pencil sketch domain, aiming to deal with structural and textural inconsistencies. We achieved best results in some datasets like celebA and Paris StreetView datasets, and competitive resuls in Places 365 dataset.

  - title: Researcher
    company: Unicamp and Samsung Electronics America
    company_url: ''
    company_logo: samsung-logo
    location: Campinas
    date_start: '2020-04-01'
    date_end: '2021-06-30'
    description: |2-
        Responsibilities include:
        * Developed new algorithms based on scene representation (LDI and MPI) for the generation of parallax effect motion using a single image, achieving to propose a new light scene representation for restricted scenarios (e.g. cell phones). We published an paper related to our proposal using LDI and MPI, achieving competitive results with recent methods based on MPI and parallax effect motion.
        * Implemented and evaluated new algorithms based on GANs and visual transformers for image inpainting, achieving competitive results in comparison with state-of-the-art methods.

  - title: Researcher
    company: Unicamp and Samsung Electronics America
    company_url: ''
    company_logo: samsung-logo
    location: Campinas
    date_start: '2018-08-01'
    date_end: '2020-03-31'
    description: |2-
        Responsibilities include:
        * Implemented post-processing algorithms to solve problems related to text localization methods using Tesseract OCR, improving the accuracy by 4% in comparison with state-of-the-art methods.
        * Developed and evaluated new algorithms for multilingual text localization and recognition in images on devices with low computational cost.  

  - title: Researcher
    company: Unicamp
    company_url: ''
    company_logo: unicamp-logo
    location: Campinas
    date_start: '2018-06-01'
    date_end: '2020-01-31'
    description: |2-
        Responsibilities included:
        * Implemented and developed solutions to fuse text localization results using genetic algorithms (GP), achieving 5% when compared to several baselines.
        * Comaparative study of text localization and recognition approaches for restricted computing scenarios (e.g. mobile devices).  
        
  - title: Researcher
    company: UNSAAC
    company_url: ''
    company_logo: unsaac-logo
    location: Cusco
    date_start: '2016-06-01'
    date_end: '2017-06-30'
    description: |2-
        Responsibilities include:
        * Implemented and evaluated handcrafted and Deep Learning methods to detect and classify hand gesture images under different environments, achieving an accuracy of 96%.
        * Created a new hand gesture dataset based on sign language to train and test our hand gesture detection and classification method.
   
  - title: Software Engineering
    company: Brain Systems
    company_url: http://efactperu.com/
    company_logo: brainsystems-logo
    location: Cusco
    date_start: '2016-01-01'
    date_end: '2017-06-30'
    description: |2-
        Responsibilities include:
        * Implemented and developed software components to generate XML files and PDF reports of purchases and sales for the electronic invoicing project (BS EFACT), managing to be one of the first companies in the city (Cusco) on generating electronic invoicing in the market.
        * Implemented efficient SQL procedures and views for database queries.

design:
  columns: '2'
---
