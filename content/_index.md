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
        - title: Undergraduate Academic Visitor
          company: University of Sheffield
          company_url: 'https://www.sheffield.ac.uk/'
          company_logo: org-uos
          location: Sheffield (United Kingdom)
          date_start: '2022-09-01'
          date_end: '2022-12-10'
          description: Undergraduate research internship at the University of Sheffield, funded by the brazilian agency Fundação de Amparo à Pesquisa do Estado de São Paulo (FAPESP).
        - title: Summer Tech Intern
          company: BTG Pactual
          company_url: 'https://www.btgpactual.com/'
          company_logo: org-btg
          location: São Paulo (Brazil)
          date_start: '2020-12-01'
          date_end: '2021-02-01'
          description: I worked as an intern in BTG Pactual's Summer Tech vacation internship program. I was part of the automation team, developing Robotic Process Automation (RPA) programs using the UiPath tool.
        - title: Undergraduate Academic Tutor
          company: Federal University of São Carlos (UFSCar)
          company_url: 'https://www.ufscar.br/'
          company_logo: org-ufscar
          location: Sorocaba (Brazil)
          date_start: '2020-09-01'
          date_end: '2021-01-01'
          description: I was a tutor for the "Programa de Acompanhamento Acadêmico aos Estudantes de Graduação" (PAAEG) at UFSCar, helping students from various courses at the university in their studies and deepening in the disciplines of Analytic Geometry and Linear Algebra.
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'

  - block: accomplishments
    content:
      title: Accomplishments & Awards
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
        - title: Neural Networks and Deep Learning
          certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2021-01-25'
          description: ''
          icon: coursera
          organization: Coursera
          organization_url: https://www.coursera.org
          url: ''
        - title: Blockchain Fundamentals
          certificate_url: https://www.edx.org
          date_end: ''
          date_start: '2021-01-01'
          description: Formulated informed blockchain models, hypotheses, and use cases.
          icon: edx
          organization: edX
          organization_url: https://www.edx.org
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - title: 'Object-Oriented Programming in R'
          certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          icon: datacamp
          organization: DataCamp
          organization_url: https://www.datacamp.com
          url: ''
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
---
