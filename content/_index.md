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
      title: Experience
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
          description: Funded postgraduate international research internship at the [Center of Automotive Research on Integrated Safety Systems and Measurement Area (CARISSMA)](https://www.thi.de/en/research/carissma/) research institute from the Technische Hochschule Ingolstadt (THI) as part of my Master's (MSc) program.
        - title: Graduate Teaching Assistant
          company: Federal University of São Carlos (UFSCar)
          company_url: 'https://www.ufscar.br/'
          company_logo: org-ufscar
          location: Sorocaba, Brazil
          date_start: '2025-03-31'
          date_end: '2025-07-31'
          description: Facilitated the learning experience for BSc Computer Science students in a Natural Language Processing (NLP) course. Responsibilities included developing and proposing assignments, delivering detailed, constructive feedback on submitted work, and conducting lectures on key course topics.
        - title: Undergraduate Academic Visitor
          company: University of Sheffield
          company_url: 'https://www.sheffield.ac.uk/'
          company_logo: org-uos
          location: Sheffield, United Kingdom
          date_start: '2022-09-01'
          date_end: '2022-12-10'
          description: Undergraduate international research internship at [School of Computer Science](https://www.sheffield.ac.uk/cs) from the University of Sheffield, funded by the brazilian agency [Fundação de Amparo à Pesquisa do Estado de São Paulo (FAPESP)](https://fapesp.br/).
        - title: Summer Tech Intern
          company: BTG Pactual
          company_url: 'https://www.btgpactual.com/'
          company_logo: org-btg
          location: São Paulo, Brazil
          date_start: '2020-12-01'
          date_end: '2021-02-01'
          description: I worked as an intern in BTG Pactual's Summer Tech vacation internship program. I was part of the automation team, developing Robotic Process Automation (RPA) programs using the UiPath tool.
        - title: Undergraduate Teaching Assistant
          company: Federal University of São Carlos (UFSCar)
          company_url: 'https://www.ufscar.br/'
          company_logo: org-ufscar
          location: Sorocaba, Brazil
          date_start: '2020-09-01'
          date_end: '2021-01-01'
          description: I was an undergraduate teaching assistant for the [Programa de Acompanhamento Acadêmico aos Estudantes de Graduação (PAAEG)](https://www.prograd.ufscar.br/pt-br/estudantes/bolsas/bolsa-programa-de-acompanhamento-academico-aos-alunos-de-graduacao-paaeg/tutoria-paaeg) at UFSCar, helping students from various courses at the university in their studies and deepening in the disciplines of Analytic Geometry and Linear Algebra.
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'

  - block: accomplishments
    content:
      title: Accomplishments, Awards & Certificates
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
        - title: Honorable Mention - WebMedia'24 Undergraduate Research Track
          certificate_url: https://drive.google.com/file/d/1AS6vMlziYdOcP0tQEKwYPyyq0t7MbSjS/view?usp=drive_link
          date_end: ''
          date_start: '2024-10-17'
          description: ''
          icon: org-webmedia
          organization: WebMedia'24
          organization_url: https://webmedia.org.br/en/2024/
          url: ''
        - title: Introduction to Machine Learning
          certificate_url: https://www.coursera.org/account/accomplishments/certificate/RDSL56LM6W55
          date_end: ''
          date_start: '2021-01-01'
          description: ''
          icon: coursera
          organization: Duke University
          organization_url: https://duke.edu/
          url: ''
        - title: Natural Language Processing in Python Track
          certificate_url: https://www.datacamp.com/certificate/track/6948f59295ee24094b25f1f4bc438679f2309882
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
