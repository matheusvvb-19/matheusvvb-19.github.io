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
    id: education
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
            _Current GPA: 3.84 / 4.0_
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
            _Final score: 9.03 / 10.0_
            <ul style="margin-left:0; padding-left:0; list-style-position: inside">
              <li>Received broad training in Computer Science, including topics such as artificial intelligence, data science, deep learning, and machine learning</li>
              <li>Conducted a funded research internship abroad, which resulted in the publication of a peer-reviewed article in an international journal</li>
              <li>Worked as undergraduate teaching assistant in mathematics-related disciplines and organized student-led events</li>
            </ul>
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'

  - block: experience
    id: research_experience
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
              <li>Collaborated with the <a href="https://sheffield.ac.uk/cs/research/groups/natural-language-processing" target="_blank">Natural Language Processing (NLP) Research Group</a> at the <a href="https://www.sheffield.ac.uk/cs" target="_blank">School of Computer Science</a>, investigating the use of deep bidirectional transformers to uncover latent knowledge from unstructured biomedical cancer literature</li>
            </ul>
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'

  - block: experience
    id: teaching_experience
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
              <li>Facilitated the learning experience for BSc Computer Science students in a NLP course</li>
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
    id: working_experience
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
          </ul>
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
  
  - block: portfolio
    id: awards_scholarships
    content:
      title: Awards & Scholarships
      subtitle: 
      text: 
      # Display content from the `content/extracurricular/` folder
      filters:
        folders:
          - extracurricular
        tags: 
          - award
          - scholarship
        #exclude_tags:
          #- award
          #- scholarship
      # Field to sort by, such as Date or Title
      sort_by: 'date_start'
      sort_ascending: false
      # Default portfolio filter button
      # 0 corresponds to the first button below and so on
      # For example, 0 will default to showing all content as the first button below shows content with *any* tag
      default_button_index: 0
      # Filter button toolbar (optional).
      # Add or remove as many buttons as you like.
      # To show all content, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the button toolbar, delete the entire `buttons` block.
      #buttons:
        #- name: All
          #tag: '*'
        
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose your content listing view - here we use the `showcase` view
      view: community/awards_scholarships_acomplishments
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: true
  
  - block: portfolio
    id: extracurricular
    content:
      title: Extracurricular Activities & Certificates
      subtitle: 
      text: 
      # Display content from the `content/extracurricular/` folder
      filters:
        folders:
          - extracurricular
        #tags: 
          #- tag
        exclude_tags:
          - award
          - scholarship
      # Field to sort by, such as Date or Title
      sort_by: 'date_start'
      sort_ascending: false
      # Default portfolio filter button
      # 0 corresponds to the first button below and so on
      # For example, 0 will default to showing all content as the first button below shows content with *any* tag
      default_button_index: 0
      # Filter button toolbar (optional).
      # Add or remove as many buttons as you like.
      # To show all content, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the button toolbar, delete the entire `buttons` block.
      buttons:
        - name: All
          tag: '*'
        - name: Enterpreunership
          tag: extracurricular_enterpreunership
        - name: Events & Community
          tag: extracurricular_eventsCommunity
        - name: Professional Development
          tag: extracurricular_professionalDevelopment
        
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose your content listing view - here we use the `showcase` view
      view: community/awards_scholarships_acomplishments
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: true
---
