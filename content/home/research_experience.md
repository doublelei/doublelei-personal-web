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
    company_logo: Delight
    location: Pittsburgh, PA
    date_start: '2021-06-01'
    date_end: '2022-12-02'
    description: >-
        * Proposed a simple pipeline to directly transfer representation and knowledge between modalities instead of redesigning or adapting the whole model. The calibration networks for Lidar, WiFi, and infrared achieve comparable results on computer vision tasks with image inputs;  

  - title: Full-Range Monocular Detection of Human Body Meshes
    company: DeLight Lab, Carnegie Mellon University
    company_url: 'https://www.ri.cmu.edu/robotics-groups/delight/'
    company_logo: Delight
    location: Pittsburgh, PA
    date_start: '2021-03-01'
    date_end: '2022-12-01'
    description: >-
        * Addressed challenges in body mesh detection with monocular RGB cameras by introducing Aligned Dense Supervision (ADS), which leverages locally body-aligned ROIs and globally augmented locations;
        
        * Successfully implemented ADS within multiple state-of-the-art (SOTA) mesh detection architectures, resulting in a 8.9\% improvement in detection metrics in average;
  
  - title: Person-in-WiFi&#58; Fine-grained Person Perception using WiFi
    company: RISS Program, Carnegie Mellon University
    company_url: 'https://riss.ri.cmu.edu/'
    company_logo: riss
    location: Pittsburgh, PA
    date_start: '2019-06-01'
    date_end: '2019-10-01'
    description: >-
        * Developed a novel algorithm to increase the robustness of WiFi data perception, reducing its sensitivity to the positioning of antennas and environmental noise, leading to the construction of a real-time, portable WiFi perception system;
  
  - title: Calligraphy Robot
    company: RAIL, The Chinese University of Hong Kong, Shenzhen
    company_url: 'https://rail.cuhk.edu.cn/'
    company_logo: CUHKSZ
    location: Shenzhen, China
    date_start: '2018-06-01'
    date_end: '2020-06-01'
    description: >-
        * Pioneered a GAN-based algorithm capable of generating unique Chinese fonts, achieving 93\% accuracy in style imitation, enabling the robot to emulate diverse handwriting styles;

        * Fine-tuned the control parameters of the robot to ensure smooth, human-like movements during the writing process, leading to a more authentic calligraphy experience;
  


design:
  columns: '2'
---
