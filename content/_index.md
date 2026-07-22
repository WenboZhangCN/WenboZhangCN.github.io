---
title: ''
summary: 'Wenbo Zhang is a PhD candidate at South China University of Technology and a visiting researcher at UCL, working on wearable sensing, body-state modelling, and closed-loop feedback for human movement and interaction.'
date: 2026-07-21
type: landing

seo:
  title: 'Wenbo Zhang | Body-State-Aware Wearable Intelligence'
  description: 'Wenbo Zhang is a PhD candidate at South China University of Technology and a visiting researcher at UCL, working on wearable sensing, body-state modelling, and closed-loop feedback for human movement and interaction.'

design:
  spacing: '0'

sections:
  - block: research-home
    id: home
    content:
      hero:
        name: Wenbo Zhang
        title: Body-State-Aware Wearable Intelligence
        role: PhD Candidate at South China University of Technology · Visiting Researcher at University College London
        text: I build wearable systems that move beyond recognising motion to infer hidden physical states - including muscle activation, loading, and force - and translate them into real-time support for human movement and interaction.
        image: home/wenbo-campus.jpg
        image_alt: Wenbo Zhang standing in front of a historic university building
        event:
          date: 22 Jul 2026 · 15:00 BST
          text: 'UCLIC seminar: Beyond Motion'
          url: https://www.ucl.ac.uk/uclic/events/2026/jul/beyond-motion-seminar-wenbo-zhang
        actions:
          - text: Publications
            url: /publications/
            style: primary
          - text: Google Scholar
            url: https://scholar.google.com/citations?hl=en&user=FuqXhXcAAAAJ&view_op=list_works
            style: secondary
            external: true
          - text: Download CV
            url: /uploads/resume.pdf
            style: secondary
          - text: Email Me
            url: mailto:zhangwenbo1225@gmail.com
            style: secondary

      agenda:
        title: Research Agenda
        subtitle: From observable movement to hidden body states and useful, real-time support.
        items:
          - title: Movement
            text: Recover observable body motion from sparse wearable sensors.
            projects: PressInPose
          - title: Evidence
            text: Infer muscle activation, pressure, loading, and force.
            projects: KineticsSense | Motion2Press | WatchForce
          - title: Body States
            text: Organise physical evidence into interpretable states.
            projects: HALO
          - title: Interaction
            text: Make hidden effort perceptible and adjustable in real time.
            projects: MuscleSense
          - title: Intelligence
            text: Reason over body states, memory, and personal context.
            projects: HALO-Agent
        summary: From recognising movement to understanding, communicating, and acting on hidden body states.

      featured:
        title: Featured Work
        subtitle: Four systems that define my current research direction across sensing, state inference, and closed-loop interaction.
        items:
          - title: MuscleSense
            image: research/musclesense.png
            alt: MuscleSense auditory biofeedback system overview
            status: Accepted
            tone: accepted
            venue: ACM IMWUT 2026
            text: Making muscle effort audible for eyes-free, in-the-loop regulation during lower-limb exercise.
            url: /publications/musclesense/
            links:
              - text: Publication
                url: /publications/musclesense/
              - text: Project
                url: /projects/musclesense/
          - title: HALO
            image: research/halo.png
            alt: HALO hidden activation-loading state inference overview
            status: Major revision
            tone: revision
            venue: ACM IMWUT 2026
            text: Organising muscle activation and biomechanical loading into interpretable body states.
            url: /publications/halo/
            links:
              - text: Project overview
                url: /projects/halo/
          - title: KineticsSense
            image: research/kineticssense.png
            alt: KineticsSense multimodal wearable sensing framework
            status: Published
            tone: published
            venue: ACM IMWUT 2025
            text: Estimating lower-limb muscle activation and movement kinetics from sparse wearables.
            url: /publications/kineticssense/
            links:
              - text: Publication
                url: /publications/kineticssense/
              - text: DOI
                url: https://doi.org/10.1145/3749462
                external: true
          - title: WatchForce
            image: research/watchforce.png
            alt: WatchForce wrist-worn PPG and IMU hand-force estimation framework
            status: Published
            tone: published
            venue: Computer Methods and Programs in Biomedicine, 2026
            text: Estimating hand force from wrist-worn PPG and IMU sensing.
            url: /publications/watchforce/
            links:
              - text: Publication
                url: /publications/watchforce/

      publications:
        title: Selected Publications
        items:
          - title: 'MuscleSense: Making Muscle Effort Audible for Eyes-Free In-the-Loop Regulation'
            authors: '**Wenbo Zhang**, Chenxu Zhang, Xingying Yan, Guanyu Xin, Yu He, Wenkang Zhang, Jagmohan Chauhan, Yang Gao, Zhanpeng Jin.'
            venue: Accepted, ACM IMWUT, 2026
            url: /publications/musclesense/
          - title: 'WatchForce: Wearables Can Tell How Strong You Grasp From Your Wrist'
            authors: 'Lingde Hu\*, **Wenbo Zhang**\*, Seokmin Choi, Yang Gao, Zhanpeng Jin.'
            venue: Computer Methods and Programs in Biomedicine, 2026
            url: /publications/watchforce/
          - title: 'KineticsSense: A Multimodal Wearable Sensor Framework for Modeling Lower-Limb Motion Kinetics'
            authors: '**Wenbo Zhang**, Chenxu Zhang, Yang Gao, Zhanpeng Jin.'
            venue: ACM IMWUT, 2025
            url: /publications/kineticssense/
          - title: 'Motion2Press: Cross-Modal Learning from IMU to Plantar Pressure for Gait Analysis'
            authors: 'Junbin Ren, Ruihao Zheng, **Wenbo Zhang**, Dong She, Yuting Bai, Zhanpeng Jin, Yang Gao.'
            venue: ACM IMWUT, 2025
            url: /publications/motion2press/
          - title: 'PressInPose: Integrating Pressure and Inertial Sensors for Full-Body Pose Estimation in Activities'
            authors: 'Yang Gao, **Wenbo Zhang**, Junbin Ren, Ruihao Zheng, Yincheng Jin, Di Wu, Lin Shu, Xiangmin Xu, Zhanpeng Jin.'
            venue: ACM IMWUT, 2024
            url: /publications/pressinpose/

      updates:
        title: Latest Updates
        items:
          - date: 22 Jul 2026
            datetime: 2026-07-22
            text: 'Invited seminar at UCLIC, University College London: "Beyond Motion: Body-State-Aware Wearable Intelligence for Human Movement and Interaction."'
            url: https://www.ucl.ac.uk/uclic/events/2026/jul/beyond-motion-seminar-wenbo-zhang
          - date: Jul 2026
            datetime: 2026-07
            text: MuscleSense was accepted by ACM IMWUT 2026.
          - date: Jul 2026
            datetime: 2026-07
            text: WatchForce was published in Computer Methods and Programs in Biomedicine.
          - date: Jul 2026
            datetime: 2026-07
            text: HALO received a major-revision decision from ACM IMWUT.
          - date: Jun 2026
            datetime: 2026-06
            text: Presented MuscleSense at MobiUK 2026, University of Cambridge.
          - date: Mar 2026
            datetime: 2026-03
            text: Started a visiting Ph.D. research stay at University College London.
          - date: Feb 2026
            datetime: 2026-02
            text: PPGSpeech was published in IEEE Internet of Things Journal.
          - date: Oct 2025
            datetime: 2025-10
            text: Invited as a panelist at ACM UbiComp/ISWC 2025 to discuss impact, risks, security, and privacy in ubiquitous computing research.
          - date: Oct 2025
            datetime: 2025-10
            text: Served as a Student Volunteer at ACM UbiComp/ISWC 2025.
          - date: '2025'
            datetime: 2025
            text: KineticsSense and Motion2Press were accepted by ACM IMWUT.
          - date: '2025'
            datetime: 2025
            text: Received the China Scholarship Council Joint Ph.D. Scholarship.
          - date: '2024'
            datetime: 2024
            text: PressInPose was accepted by ACM IMWUT.

      contact:
        title: Let's talk wearable intelligence.
        text: I welcome research discussions and collaborations on wearable sensing, body-state modelling, and closed-loop human-AI interaction.
        links:
          - text: zhangwenbo1225@gmail.com
            url: mailto:zhangwenbo1225@gmail.com
          - text: Google Scholar
            url: https://scholar.google.com/citations?hl=en&user=FuqXhXcAAAAJ&view_op=list_works
            external: true
          - text: LinkedIn
            url: https://www.linkedin.com/in/%E5%BC%A0%E6%96%87%E5%8D%9A/
            external: true
          - text: ORCID
            url: https://orcid.org/0000-0002-0387-6345
            external: true
    design:
      spacing:
        padding: ['0', '0', '0', '0']
---
