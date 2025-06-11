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
        url: uploads/202506-jmvanlit-resume.pdf
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
        I am a PhD candidate and lecturer at Radboud University. My PhD dissertation, Beautiful Spark of Democracy, is on the defence of democracy against incumbent-led autocratization, under the supervision of Prof. dr. Carolien van Ham and prof. dr. Maurits Meijers. The dissertation has been approved in May, and my defence is scheduled for 31 October.
        
        I have been a Visiting Researcher at the Varieties of Democracy Institute (V-Dem) at the University of Gothenburg in Sweden, and have previously worked at the Department of Public Administration at Leiden University. In addition to my research, I teach in the bachelor and master programmes Political Science at Radboud University, focusing mainly on methods. 

        Before starting my PhD, I worked as a Junior lecturer for the bachelor and pre-master Public Administration at Leiden University, where I received my University Teaching Qualification. I studied International Relations (BSc.), African Studies (BA., cum laude), and Political Science and Public Administration (MSc. res., cum laude) at Leiden University, with internships at the European Asylum Support Office, the International Institute of Social History, and the Netherlands National Commission for UNESCO.

        Outside of working hours (and occasionally during) I play cello, enjoy reading novels (with a preference for over-the-top and completely predictable spy novels), and running through the woods (training for marathons).
    design:
      columns: '1'
  - block: markdown
    id: research
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        My main research interests are autocratization, democratization, public opinion, and legitimacy. As such, I mainly work on topics within Comparative Politics and Political Behaviour, with a strong emphasis on advanced and rigorous methods. I have presented much of my research at international conferences in Europe and the USA. If you are interested to read some of it (while it is not yet published), feel free to reach out!

        ### PhD Project
        In my PhD dissertation, *Beautiful Spark of Democracy*, I ask when democratically elected leaders autocratize, and specifically when and by whom they are opposed. I call these opposition actors "democratic defenders", and research under what circumstances they stand up to defend democracy against these threats from the inside. In the dissertation, I use a multi-method approach to tackle this question from different angles, relying on in-depth casestudies, elite interviews, computational methods, and survey experiments. My dissertation has been approved in May 2025.
        
        ### Other projects
        Next to my PhD dissertation, I am working on several projects related to autocratization and democratization, citizen conceptions of democracy, and the normalization of political violence.
        
        #### Is Dutch Democracy in Decline?
        With a large and interdisciplinary group of academics, we are working on a joined publication to find an academic answer to the question if Dutch democracy is in decline. The start-meeting is in June 2025, at the Politicologen Etmaal (the Dutch annual political science workshop) in Groningen.

        #### DIY Deepfakes
        With an NWO SSH-XS Grant dr. Michal Mochtak and I are developing a replicable pipeline for researchers to construct their own deepfake videos as a research tool. As part of the project, we include a lab experiment to establish the effects of such deepfakes and create a framework for ethical and effective debriefing.

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
  - block: collection
    id: workingpapers
    content:
      title: Public working papers
      text: ""
      count: 5
      filters:
        folders:
          - workingpapers
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
