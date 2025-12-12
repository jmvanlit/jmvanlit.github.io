---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/202512-jmvanlit-resume.pdf
    design:
      css_class: dark
      background:
        color: '#495867'
        text_color_light: true
      #  image:
      #    # Add your image background to `assets/media/`.
      #    filename: stacked-peaks.svg
      #    filters:
      #      brightness: 1.0
      #    size: cover
      #    position: center
      #    parallax: false
  - block: markdown
    id: bio
    content:
      title: '🧐 Biography'
      subtitle: ''
      text: |-
        I am a postdoctoral researcher and lecturer in Comparative Political Science at Radboud University. My work asks a simple question with big consequences: how can democracies defend themselves when incumbents try to increase their power and weaken checks and balances? I study the roles of democratic elites and citizens using surveys, experiments, and interviews.
        
        I earned my PhD cum laude at Radboud University, Nijmegen (October 2025). My dissertation, Beautiful Spark of Democracy ([Open Access](https://doi.org/10.54195/9789465150840), Radboud University Press), feeds into articles in the European Journal of Political Research, West European Politics, European Political Science Review, and Democratization. I have been a Visiting Researcher at the V‑Dem Institute (University of Gothenburg) and I teach research methods in the BSc/MSc Political Science programmes. I regularly engage in the public debate about (Dutch) democracy with contributions to the Dutch Election Studies, public lectures, and advice to politicians and policy-makers.

        Outside of working hours (and occasionally during) I play cello, enjoy reading novels (with a preference for over-the-top and completely predictable spy novels), and running through the woods (training for marathons).
    design:
      columns: '1'
  - block: markdown
    id: research
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I study autocratization and democratic defence: when and how democratic elites and citizens resist incumbent-led democratic recession. Substantively, my work sits in Comparative Politics and Political Behaviour; methodologically, I use survey and field experiments, quantitative computational methods, and interviews (with a commitment to open and reproducible science).

        ### Current projects
        Currently, I am working on several individual projects, including survey experiments fielded in the Netherlands, the Czech Republic, the United States, United Kingdom, and Spain.
        
        ### DIY Deepfakes
        With an NWO SSH-XS Grant dr. Michal Mochtak and I are developing a replicable pipeline for researchers to construct their own deepfake videos as a research tool. As part of the project, we include a lab experiment to establish the effects of such deepfakes and create a framework for ethical and effective debriefing.

        ### PhD Project
        In my PhD dissertation, Beautiful Spark of Democracy, I ask when democratically elected leaders autocratize, and specifically when and by whom they are opposed. I call these opposition actors "democratic defenders", and research under what circumstances they stand up to defend democracy against these threats from the inside. In the dissertation, I use a multi-method approach to tackle this question from different angles, relying on in-depth casestudies, elite interviews, computational methods, and survey experiments. My dissertation is available Open Access [here](https://doi.org/10.54195/9789465150840).
    design:
      columns: '1'
  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: ""
      count: 5
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation    
  #- block: collection
  #  id: talks
  #  content:
  #    title: Outreach and Valorisation
  #    filters:
  #      folders:
  #        - outreach
  #  design:
  #    view: article-grid
  #    count: 3
---
