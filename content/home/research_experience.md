---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Research Experience
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
  - title: Adversarial Calibration between Modalities
    company: DeLight Lab, Carnegie Mellon University
    company_url: 'https://www.ri.cmu.edu/robotics-groups/delight/'
    company_logo: delight
    location: Pittsburgh, PA
    date_start: '2021-06-01'
    date_end: ''
    description: >-
        * Proposed a simple pipeline to directly transfer representation and knowledge between modalities instead of redesigning or adapting the whole model. The calibration networks for Lidar, WiFi, and infrared achieve comparable results on computer vision tasks with image inputs;  

  - title: Full-Range Monocular Detection of Human Body Meshes
    company: DeLight Lab, Carnegie Mellon University
    company_url: 'https://www.ri.cmu.edu/robotics-groups/delight/'
    company_logo: delight
    location: Pittsburgh, PA
    date_start: '2021-03-01'
    date_end: ''
    description: >-
        * Proposed Aligned Dense Supervision (ADS) that aggregates supervision among body meshes and between local-global regression towards a full-range mesh detection solution;
        
        * Reached comparable performances on local metrics and much better performances on our proposed global metrics for multi-person 3D mesh estimation;
  
  - title: Person-in-WiFi&#58; Fine-grained Person Perception using WiFi
    company: RISS Program, Carnegie Mellon University
    company_url: 'https://riss.ri.cmu.edu/'
    company_logo: riss
    location: Pittsburgh, PA
    date_start: '2019-06-01'
    date_end: '2019-10-01'
    description: >-
        * Proposed a novel algorithm based on MUSIC to make the WiFi Data less sensitive to the location and orientation of the antennas as well as free from variance of random noise from the environments;
        
        * Built a real-time and highly portable WiFi perception system;
  
  - title: Calligraphy Robot
    company: RAIL, The Chinese University of Hong Kong, Shenzhen
    company_url: 'https://rail.cuhk.edu.cn/'
    company_logo: CUHKSZ
    location: Shenzhen, China
    date_start: '2018-06-01'
    date_end: '2020-06-01'
    description: >-
        * Developed a GAN-based algorithm to generate Chinese fonts, which can imitate anyone’s style;

        * Developed an algorithm using deep Q-learning with LSTM that allows the robot to write calligraphy based on any inputted Chinese characters;
  


design:
  columns: '2'
---
