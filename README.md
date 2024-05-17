# EY-Challenge-2024
https://challenge.ey.com/challenges/tropical-cyclone-damage-assessment-lrrno2xm

Theme: Coastal Resillience
Phase 1: Storm Damage Assessment

With the opportunity to use AI for good, challenge participants will use high-resolution datasets to model coastal vulnerability and assess tropical storm damage.  These models will help communities develop strategies for mitigating and recovering from severe climate events.  The challenge consists of two phases.  Phase 1 is to develop machine learning and AI models using high-resolution satellite data to assess storm damage and support disaster response and recovery efforts in data-poor coastal environments. Phase 2 is to create a practical "business plan" describing how the Phase 1 model could be applied by local beneficiaries to assess coastal infrastructure damage, vulnerability, socioeconomic impact, and climate change risk for future storms.

Objective:

The goal of the challenge is to develop a machine learning model to identify and detect “damaged” and “un-damaged” coastal infrastructure (residential and commercial buildings), which have been impacted by natural calamities such as hurricanes, cyclones, etc.

Participants will be given pre- and post-cyclone satellite images of a site impacted by Hurricane Maria in 2017 and build a machine learning model, designed to detect four different objects in a satellite image of a cyclone impacted area:

·      Undamaged residential building

·      Damaged residential building

·      Undamaged commercial building

·      Damaged commercial building

Dataset Used: High-resolution panchromatic satellite images before and after a tropical cyclone, captured using Maxar GeoEye-1 (optical)

In this repository, I include all the codes to train YOLOv8 model (provided by EY) and scripts that our team used to streamline and unify our data annotation process (image seperated into 3 parts, each annotated by 1 team member from different machine, thus the script)
