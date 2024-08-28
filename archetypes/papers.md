---
layout: papers
# specify the title of the paper
title:  "Eclares: Energy-Aware Clarity-Driven Ergodic Search"
# specify the date it was published
date: 2024-05-13
# list the authors. if a "/people/id" page exists for the person, it will be linked. If not, the author's name is printed exactly as you typed it. 
authors:
    - devanshagrawal
    - kalebbennaveed
    - Christopher Vermillion
    - dimitrapanagou 
# give the main figure location, relative to /static/
image: /images/2024-eclares.png
# specify the conference or journal that it was published in
venue: "IEEE ICRA 2024"
# specify the type  of the paper. choose from [conference, journal]
type: conference
# link to publisher site (optional)
link: https://doi.org/10.1109/ICRA57147.2024.10611286
# link to arxiv (optional)
arxiv: https://arxiv.org/abs/2310.06933
# link to github (optional)
code: https://github.com/kalebbennaveed/Eclares.git
# link to video (optional)
video: https://youtu.be/1ZCgxlHitzk
# link to pdf (optional)
pdf: /pdfs/2024-eclares.pdf
# abstract
abstract: "Planning informative trajectories while considering the spatial distribution of the information over the environment, as well as constraints such as the robot’s limited battery capacity, makes the long-time horizon persistent coverage problem complex. Ergodic search methods consider the spatial distribution of environmental information while optimizing robot trajectories; however, current methods lack the ability to construct the target information spatial distribution for environments that vary stochastically across space and time. Moreover, current coverage methods dealing with battery capacity constraints either assume simple robot and battery models or are computationally expensive. To address these problems, we propose a framework called Eclares, in which our contribution is two-fold. 1) First, we propose a method to construct the target information spatial distribution for ergodic trajectory optimization using clarity, an information measure bounded between [0, 1]. The clarity dynamics allow us to capture information decay due to a lack of measurements and to quantify the maximum attainable information in stochastic spatiotemporal environments. 2) Second, instead of directly tracking the ergodic trajectory, we introduce the energy-aware (eware) filter, which iteratively validates the ergodic trajectory to ensure that the robot has enough energy to return to the charging station when needed. The proposed eware filter is applicable to nonlinear robot models and is computationally lightweight. We demonstrate the working of the framework through a simulation case study."
# bib entry (optional). the |- is used to allow for multiline entry.
bib: |-
  @inproceedings{naveed2024eclares,
    title={Eclares: Energy-aware clarity-driven ergodic search},
    author={Naveed, Kaleb Ben and Agrawal, Devansh and Vermillion, Christopher and Panagou, Dimitra},
    booktitle={2024 IEEE International Conference on Robotics and Automation (ICRA)},
    pages={14326--14332},
    year={2024},
    organization={IEEE}
  }
---