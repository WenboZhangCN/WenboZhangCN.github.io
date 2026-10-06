---
title: ''
summary: 'Wenbo Zhang (张文博) is a PhD candidate at South China University of Technology working on human-centered wearable and ubiquitous intelligence, multimodal human sensing, and interactive systems for movement and health.'
date: 2026-10-06
type: landing

seo:
  title: 'Wenbo Zhang | Human-Centered Wearable and Ubiquitous Intelligence'
  description: 'Wenbo Zhang (张文博) is a PhD candidate at South China University of Technology working on human-centered wearable and ubiquitous intelligence, multimodal human sensing, and interactive systems for movement and health.'

design:
  spacing: '0'

sections:
  - block: research-home
    id: home
    content:
      hero:
        name: Wenbo Zhang · 张文博
        title: Human-Centered Wearable and Ubiquitous Intelligence
        role: PhD Candidate at SCUT · Visiting Researcher at UCL (Mar-Aug 2026)
        text: Wearable sensing has become good at recognising movement, but health and interaction often depend on states we cannot observe directly - muscle activation, loading, and force. I develop multimodal systems that recover these states from practical sensors and turn them into interpretable feedback and context for human-centered wearable agents.
        image: home/wenbo-campus.jpg
        image_alt: Wenbo Zhang standing in front of a historic university building
        event:
          date: '12 & 14 Oct 2026 · Shanghai'
          text: Presenting HALO-Agent and MuscleSense at UbiComp/ISWC
          url: https://www.ubicomp.org/ubicomp-iswc-2026/
        actions:
          - text: Publications
            url: /publications/
            style: primary
          - text: Google Scholar
            url: https://scholar.google.com/citations?hl=en&user=FuqXhXcAAAAJ&view_op=list_works
            style: secondary
            external: true
          - text: Email Me
            url: mailto:zhangwenbo1225@gmail.com
            style: secondary

      talks:
        title: Two Presentations at UbiComp/ISWC 2026
        subtitle: From body-state representation for wearable agents to real-time feedback for muscle-effort regulation.
        items:
          - kind: Workshop paper
            date: 12 Oct 2026 · 16:46-16:54
            title: 'Beyond Sensor Streams: HALO-Agent as a Body-State Representation Layer for Wearable Agents'
            venue: WearAgent 2026 · Shanghai
            text: A body-state representation layer that connects continuous wearable sensing with context-aware agent reasoning.
            url: https://wearagent.github.io/
          - kind: IMWUT paper
            date: 14 Oct 2026 · 16:00-17:30
            title: 'MuscleSense: Making Muscle Effort Audible for Eyes-Free In-the-Loop Regulation'
            venue: 'Session D5: Sports Injury and Performance · Yangtze Hall'
            text: A real-time auditory biofeedback system for perceiving and regulating lower-limb muscle effort during exercise.
            url: https://www.ubicomp.org/ubicomp-iswc-2026/accepted-papers/

      agenda:
        title: Research Questions
        subtitle: I study how everyday sensors can recover consequential human states and support timely, reliable interaction.
        items:
          - title: Sense
            text: How can sparse wearables capture movement, physiology, and physical interaction outside controlled laboratories?
            projects: PressInPose · Motion2Press · PPGSpeech
          - title: Infer
            text: How can multimodal models recover muscle activation, loading, pressure, and force that cannot be observed directly?
            projects: KineticsSense · HALO · WatchForce
          - title: Interact
            text: How can inferred body states become low-burden feedback and useful context for personalized wearable agents?
            projects: MuscleSense · HALO-Agent
        summary: The central challenge is to learn from expensive lab-grade ground truth while keeping sensing sparse, calibration practical, and feedback useful in everyday settings.

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
              - text: DOI
                url: https://doi.org/10.1145/3831987
                external: true
              - text: Project
                url: /projects/musclesense/
          - title: HALO
            image: research/halo.png
            alt: HALO hidden activation-loading state inference overview
            status: Accepted
            tone: accepted
            venue: ACM IMWUT 2026
            text: Organising muscle activation and biomechanical loading into interpretable body states.
            url: /publications/halo/
            links:
              - text: Publication
                url: /publications/halo/
              - text: Project
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
          - title: 'HALO: Inferring Hidden Activation-Loading Organization from Sparse Wearables'
            authors: '**Wenbo Zhang**, Xingying Yan, Chenxu Zhang, Dong Huitian, Haoyang Li, Chenxu Zhu, Yang Gao, Jagmohan Chauhan, Zhanpeng Jin.'
            venue: Accepted, ACM IMWUT, 2026
            url: /publications/halo/
          - title: 'MuscleSense: Making Muscle Effort Audible for Eyes-Free In-the-Loop Regulation'
            authors: '**Wenbo Zhang**, Chenxu Zhang, Xingying Yan, Guanyu Xin, Yu He, Wenkang Zhang, Jagmohan Chauhan, Yang Gao, Zhanpeng Jin.'
            venue: Accepted, ACM IMWUT, 2026
            url: /publications/musclesense/
          - title: 'Beyond Sensor Streams: HALO-Agent as a Body-State Representation Layer for Wearable Agents'
            authors: '**Wenbo Zhang**, Yuan Gao, Dong Huitian, Chenxu Zhu, Chenxu Zhang, Wenkang Zhang, Yang Gao, Jagmohan Chauhan, Zhanpeng Jin.'
            venue: WearAgent Workshop, ACM UbiComp/ISWC, 2026
            url: /publications/halo-agent/
          - title: 'WatchForce: Wearables Can Tell How Strong You Grasp From Your Wrist'
            authors: 'Lingde Hu\*, **Wenbo Zhang**\*, Seokmin Choi, Yang Gao, Zhanpeng Jin.'
            venue: Computer Methods and Programs in Biomedicine, 2026
            url: /publications/watchforce/
          - title: 'PPGSpeech: A Wearable Silent Speech Interface Leveraging Neck-Worn Photoplethysmography'
            authors: 'Lingde Hu\*, **Wenbo Zhang**\*, Wenkang Zhang, Yu He, Seokmin Choi, Yang Gao, Jagmohan Chauhan, Zhanpeng Jin.'
            venue: IEEE Internet of Things Journal, 2026
            url: /publications/ppgspeech/
          - title: 'KineticsSense: A Multimodal Wearable Sensor Framework for Modeling Lower-Limb Motion Kinetics'
            authors: '**Wenbo Zhang**, Chenxu Zhang, Yang Gao, Zhanpeng Jin.'
            venue: ACM IMWUT, 2025
            url: /publications/kineticssense/

      updates:
        title: Latest Updates
        items:
          - date: 14 Oct 2026
            datetime: 2026-10-14
            text: Presenting MuscleSense in the Sports Injury and Performance session at ACM UbiComp/ISWC 2026 in Shanghai.
            url: https://www.ubicomp.org/ubicomp-iswc-2026/accepted-papers/
          - date: 12 Oct 2026
            datetime: 2026-10-12
            text: Presenting HALO-Agent at the WearAgent 2026 workshop, co-located with ACM UbiComp/ISWC 2026.
            url: https://wearagent.github.io/
          - date: Oct 2026
            datetime: 2026-10
            text: HALO was accepted by ACM IMWUT 2026.
          - date: Aug 2026
            datetime: 2026-08
            text: Completed a six-month visiting research stay at University College London with Prof. Jagmohan Chauhan.
          - date: 22 Jul 2026
            datetime: 2026-07-22
            text: 'Gave an invited seminar at UCLIC, University College London: "Beyond Motion: Body-State-Aware Wearable Intelligence for Human Movement and Interaction."'
            url: https://www.ucl.ac.uk/uclic/events/2026/jul/beyond-motion-seminar-wenbo-zhang
          - date: Jul 2026
            datetime: 2026-07
            text: MuscleSense was accepted by ACM IMWUT 2026.
          - date: Jul 2026
            datetime: 2026-07
            text: WatchForce was published in Computer Methods and Programs in Biomedicine.
          - date: Jun 2026
            datetime: 2026-06
            text: Presented MuscleSense at MobiUK 2026, University of Cambridge.
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
        text: I welcome research discussions and collaborations on multimodal human sensing, wearable intelligence, mobile health, and human-centered AI.
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
