---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:       
  - block: about.biography
    id: about
    content:
      title: Hi there!
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  
  - block: experience
    content:
      title: Education
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many experience `items` below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: MSc in Computer Science
          company: Federal University of São Carlos (UFSCar)
          company_url: 'https://www.ufscar.br/'
          company_logo: org-ufscar
          location: Sorocaba, Brazil
          date_start: '2024-10-14'
          date_end: ''
          description: >
            _Current overall GPA: 3.83 / 4.0_
            <ul style="margin-left:0; padding-left:0; list-style-position: inside">
              <li>"LLM-based data augmentation for continuous learning models in pedestrian trajectory prediction'', supervised by Dr. Tiago A. Almeida</li>
              <li><a href="https://www.ppgcc.ufscar.br/pt-br" target="_blank">Graduate Program in Computer Science (PPGCC)</a>, machine learning and natural language processing thematic track, <a href="https://lasid.dcomp.ufscar.br/" target="_blank">Intelligent Systems and Data Science Laboratory (LaSID)</a></li>
            </ul>
        - title: BSc Exchange Student
          company: University of Chile
          company_url: 'https://uchile.cl/'
          company_logo: org-uchile
          location: Santiago, Chile
          date_start: '2022-03-01'
          date_end: '2022-07-01'
          description: >
            _Final score: 5.2 / 7.0_
            <ul style="margin-left:0; padding-left:0; list-style-position: inside">
              <li>Virtual Mobility Pilot Program of the <a href="https://grupomontevideo.org/site/" target="_blank">Association of Universities of the Montevideo Group (AUGM)</a>, completed the online course "Spatial Data Analysis and Geographic Information Systems"</li>
              <li>Spatial and demographic data analysis applied to decision-making, building interactive maps and dashboards using QGIS and Power BI</li>
            </ul>
        - title: BSc in Computer Science
          company: Federal University of São Carlos (UFSCar)
          company_url: 'https://www.sorocaba.ufscar.br/'
          company_logo: org-ufscar
          location: Sorocaba, Brazil
          date_start: '2019-03-14'
          date_end: '2024-09-01'
          description: >
            _Final overall score&#58; 9.03 / 10.0_
            <ul style="margin-left:0; padding-left:0; list-style-position: inside">
              <li>Received broad training in Computer Science, including topics such as artificial intelligence, data science, deep learning, and machine learning</li>
              <li>Conducted a funded research internship abroad, which resulted in the publication of a peer-reviewed article in an international journal</li>
              <li>Worked as undergraduate teaching assistant in mathematics-related disciplines and organized student-led events</li>
            </ul>
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'

  - block: experience
    content:
      title: Research Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many experience `items` below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Graduate Academic Visitor
          company: Technische Hochschule Ingolstadt (THI)
          company_url: 'https://www.thi.de/'
          company_logo: org-thi
          location: Ingolstadt, Germany
          date_start: '2025-08-04'
          date_end: ''
          description: >
            <ul style="margin-left:0; padding-left:0; list-style-position: inside">
              <li>Fully-funded international graduate research internship on LLM-based data augmentation for continuous learning models in pedestrian trajectory prediction</li>
              <li>Collaboration with the <a href="https://www.thi.de/en/research/carissma/c-iad/" target="_blank">Institute of Automated Driving (C-IAD)</a> at the <a href="https://www.thi.de/en/research/carissma/" target="_blank">Center of Automotive Research on Integrated Safety Systems and Measurement Area (CARISSMA)</a></li>
            </ul>
        - title: Undergraduate Academic Visitor
          company: University of Sheffield
          company_url: 'https://www.sheffield.ac.uk/'
          company_logo: org-uos
          location: Sheffield, United Kingdom
          date_start: '2022-09-01'
          date_end: '2022-12-10'
          description: >
            <ul style="margin-left:0; padding-left:0; list-style-position: inside">
              <li>Fully-funded international undergraduate research internship supervised by Dr. Carolina E. Scarton</li>
              <li>Collaborated with the <a href="https://sheffield.ac.uk/cs/research/groups/natural-language-processing" target="_blank">NLP Research Group</a> at the <a href="https://www.sheffield.ac.uk/cs" target="_blank">School of Computer Science</a>, investigating the use of deep bidirectional transformers to uncover latent knowledge from unstructured biomedical cancer literature</li>
            </ul>
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'

  - block: experience
    content:
      title: Teaching Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many experience `items` below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Graduate Assistant
          company: Federal University of São Carlos (UFSCar)
          company_url: 'https://www.ufscar.br/'
          company_logo: org-ufscar
          location: Sorocaba, Brazil
          date_start: '2025-03-31'
          date_end: '2025-07-31'
          description: >
            <ul style="margin-left:0; padding-left:0; list-style-position: inside">
              <li>Facilitated the learning experience for BSc Computer Science students in a Natural Language Processing (NLP) course</li>
              <li>Designed and proposed assignments aligned with course objectives, delivered lectures on core topics</li>
            </ul>
        - title: Undergraduate Assistant
          company: Federal University of São Carlos (UFSCar)
          company_url: 'https://www.ufscar.br/'
          company_logo: org-ufscar
          location: Sorocaba, Brazil
          date_start: '2020-09-01'
          date_end: '2021-01-01'
          description: >
            <ul style="margin-left:0; padding-left:0; list-style-position: inside">
              <li>Undergraduate teaching assistant for the <a href="https://www.prograd.ufscar.br/pt-br/estudantes/bolsas/bolsa-programa-de-acompanhamento-academico-aos-alunos-de-graduacao-paaeg/tutoria-paaeg" target="_blank">Programa de Acompanhamento Acadêmico aos Estudantes de Graduação (PAAEG)</a></li>
              <li>Assisted first-year students of diverse majors in consolidating knowledge of Analytical Geometry and Linear Algebra classes, reinforcing problem-solving and theoretical understanding</li>
            </ul>
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'

  - block: experience
    content:
      title: Working Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many experience `items` below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
      - title: Summer Tech Intern
        company: BTG Pactual
        company_url: 'https://www.btgpactual.com/'
        company_logo: org-btg
        location: São Paulo, Brazil
        date_start: '2020-12-01'
        date_end: '2021-02-01'
        description: >
          <ul style="margin-left:0; padding-left:0; list-style-position: inside">
            <li>Worked as an undergraduate intern in BTG Pactual's Summer Tech vacation internship program</li>
            <li>Part of the automation team, developing Robotic Process Automation (RPA) programs using the UiPath tool</li>
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
  
  - block: accomplishments
    content:
      title: Awards & Scholarships
      subtitle: ''
      text: ''
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `items` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: MSc research fellowship
          certificate_url: 
          date_end: '2026-11-01'
          date_start: '2024-10-01'
          description: 'Grant 29271.02.01/2022.04-00'
          icon: org-fundep
          organization: Research Development Foundation (Fundep)
          organization_url: https://www.fundep.ufmg.br/
          url: ''
        - title: Honorable Mention - WebMedia'24 Undergraduate Research Track
          certificate_url: https://drive.google.com/file/d/1AS6vMlziYdOcP0tQEKwYPyyq0t7MbSjS/view?usp=drive_link
          date_end: ''
          date_start: '2024-10-01'
          description: ''
          icon: org-webmedia
          organization: WebMedia'24
          organization_url: https://webmedia.org.br/en/2024/
          url: ''
        - title: Undergraduate research fellowship
          certificate_url: 
          date_end: '2024-09-01'
          date_start: '2024-01-01'
          description: 'Grant 29271.02.01/2022.04-00'
          icon: org-fundep
          organization: Research Development Foundation (Fundep)
          organization_url: https://www.fundep.ufmg.br/
          url: ''
        - title: Undergraduate research internship abroad
          certificate_url: 'https://drive.google.com/file/d/1HFLjeCycuqbZ4ubrPRkg9ojXZo3_HHPz/view?usp=sharing'
          date_end: '2022-12-10'
          date_start: '2022-09-01'
          description: 'Grant 2022/07236-9'
          icon: org-fapesp
          organization: São Paulo Research Foundation (FAPESP)
          organization_url: https://fapesp.br/
          url: ''
        - title: Undergraduate research fellowship
          certificate_url: 'https://drive.google.com/file/d/1fn0eJqytczgGrMdsCWP7Y8tYsFJn_UHD/view?usp=sharing'
          date_end: '2023-04-01'
          date_start: '2022-01-01'
          description: 'Grant 2021/13054-8'
          icon: org-fapesp
          organization: São Paulo Research Foundation (FAPESP)
          organization_url: https://fapesp.br/
          url: ''
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'

  - block: accomplishments
    content:
      title: Extra-curricular Activities & Certificates
      subtitle: ''
      text: ''
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `items` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Training in Artificial Intelligence
          certificate_url: https://drive.google.com/file/d/1fYfMbGIRjWPrXpmo54T75iD0f1gbKHNJ/view?usp=sharing
          date_end: ''
          date_start: '2023-09-01'
          description: ''
          icon: org-unicamp
          organization: State University of Campinas (UNICAMP)
          organization_url: https://unicamp.br/
          url: ''
        - title: Introduction to Machine Learning
          certificate_url: https://www.coursera.org/account/accomplishments/certificate/RDSL56LM6W55
          date_end: ''
          date_start: '2021-05-10'
          description: ''
          icon: coursera
          organization: Duke University
          organization_url: https://duke.edu/
          url: ''
        - title: Natural Language Processing in Python Track
          certificate_url: https://www.datacamp.com/completed/statement-of-accomplishment/track/6948f59295ee24094b25f1f4bc438679f2309882
          date_end: ''
          date_start: '2021-01-01'
          description: ''
          icon: datacamp
          organization: DataCamp
          organization_url: https://app.datacamp.com/
          url: ''
        - title: Deep Learning Specialization
          certificate_url: https://www.coursera.org/account/accomplishments/certificate/HZADZURB82VM
          date_end: ''
          date_start: '2020-12-01'
          description: ''
          icon: coursera
          organization: DeepLearning.AI
          organization_url: https://www.deeplearning.ai/
          url: ''
        - title: Applied Machine Learning in Python
          certificate_url: https://www.coursera.org/account/accomplishments/certificate/8BT39H77KXSE
          date_end: ''
          date_start: '2020-10-01'
          description: ''
          icon: org-michigan
          organization: University of Michigan
          organization_url: https://umich.edu/
          url: ''
        - title: Machine Learning Foundations - A Case Study Approach
          certificate_url: https://www.coursera.org/account/accomplishments/certificate/98W7YZ4Q5GFE
          date_end: ''
          date_start: '2020-10-01'
          description: ''
          icon: coursera
          organization: Coursera
          organization_url: https://www.coursera.org
          url: ''
        - title: Mathematics for Machine Learning - Linear Algebra
          certificate_url: https://www.coursera.org/account/accomplishments/certificate/79L2JSH7AA43
          date_end: ''
          date_start: '2020-09-01'
          description: ''
          icon: coursera
          organization: Coursera
          organization_url: https://www.coursera.org
          url: ''
        - title: Introduction to R Programming Language
          certificate_url: https://drive.google.com/file/d/1SER820UvOPbPGIUxtRsS9jEBeqClfi4d/view?usp=sharing
          date_end: ''
          date_start: '2020-01-01'
          description: 
          icon: org-ufscar
          organization: Federal University of São Carlos (UFSCar)
          organization_url: https://cursos.poca.ufscar.br/
          url: 
        - title: Simplifying the Agile Scrum Method
          certificate_url: https://drive.google.com/file/d/1f1lXQHLvMo7X0jHkYTnNMomdJhBsx3gZ/view?usp=sharing
          date_end: ''
          date_start: '2020-03-01'
          description: ''
          icon: org-ufscar
          organization: Federal University of São Carlos (UFSCar)
          organization_url: https://cursos.poca.ufscar.br/
          url: ''
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
---
