---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero-with-stats
    content:
      title: "Asiacrypt 2025 Tutorial"
      text: "<div style='text-align: center; font-size: 2.5rem; font-weight: bold; margin-bottom: 1rem; line-height: 1.4;'>Secure Post-Quantum Cryptography RISC-V IoT Platform Implementation and Demonstration on FPGA</div> <div style='text-align: center;'>Presented by <br> CityUHK Architecture Lab for Arithmetic and Security (CALAS) <br>Department of Electrical Engineering, City University of Hong Kong</div>"
      details: " <div style='text-align: center;'>December 8th, 2025</div>"
      primary_action:
        text: Register Now
        url: https://asiacrypt.iacr.org/2025/registration.php
        icon:
      items:
        - name: "Speakers"
          description: "TBD"
        - name: "Attendees"
          description: "TBD"
        - name: "Venue"
          description: "Woodside Building, Clayton Campus of Monash University"
        - name: "Location"
          description: "Melbourne, Australia"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "bg-gradient-to-r from-rose-100 to-teal-100"
#      background:
#        color: ""
#        image:
#          # Add your image background to `assets/media/`.
#          filename: ""
#          filters:
#            brightness: 1.0
  - block: countdown
    content:
      title: "Event Countdown"
      text: ""
      text_after: ""
      date: '2025-12-08T04:00:00'
    design:
      # Section background color (CSS class)
      css_class: "bg-primary-500"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: markdown
    id: about
    content:
      title: Introduction
      text: |
        The rapid progress of **quantum computing** threatens many classical cryptographic schemes—including RSA and ECC—making the shift to **post-quantum cryptography (PQC)** urgent.  
        This hands-on tutorial walks you through designing and implementing a secure **post-quantum RISC-V IoT platform** on an FPGA.

        Key features include:

        * **CRYSTALS-Dilithium 3** digital-signature acceleration via hardware–software co-design  
        * An open, extensible **RISC-V** architecture that easily embeds custom PQC accelerators  
        * Full **FPGA prototyping**, giving you practical experience in building and optimizing secure embedded systems for a post-quantum world  

        We begin with an overview of **lattice-based PQC**, focusing on CRYSTALS-Dilithium 3—its architecture, security properties, and the computational, memory, and power demands it places on IoT devices. You’ll see how offloading compute-intensive operations to dedicated hardware drastically improves performance while balancing flexibility, resource usage, and throughput.

        Following the theory, you’ll complete a step-by-step, live FPGA build:

        1. **RISC-V core** enhanced with a custom PQC accelerator  
        2. Integration with a **LoRa** module for low-power, long-range IoT connectivity  
        3. End-to-end FPGA workflow—HDL coding, block-design creation, synthesis, implementation, and bitstream generation  
        4. Real-time demonstration and evaluation of the finished system  

        To broaden your perspective, we will also briefly showcase our **GPU-based lattice-PQC prototypes**, outlining their design choices and performance metrics. Throughout the session, interactive discussions and live demos will give you deep insights into architectural design, hardware–software partitioning, and optimization techniques for resource-constrained, secure embedded platforms.

        > **Why this matters:** Bridging the gap between cutting-edge PQC algorithms and real-world IoT deployments equips you to build the secure systems tomorrow’s connected devices will rely on.

  - block: markdown
    content:
      title: Objectives
      text: |
        By the end of the tutorial you will be able to:

        - **Explain** the architecture and resource demands of **CRYSTALS-Dilithium 3**
        - **Apply** performance-tuning techniques for PQC on constrained embedded platforms
        - **Implement** hardware–software co-design flows on an **FPGA**
        - **Develop** secure embedded systems on **RISC-V**–based FPGAs
        - **Build** and evaluate a post-quantum-secure **IoT platform**
        - **Transfer** these skills to future post-quantum embedded and IoT projects
  # - block: cta-image-paragraph
  #   id: about
  #   content:
  #     items:
  #       - title: THE YEAR’S CAN’T-MISS EVENT FOR AI COLLABORATION
  #         text: AI Summit is coming home to San Francisco. Join us at AI Summit 2024 to explore all the cutting-edge innovation the data cloud has to offer.
  #         # Upload image to `assets/media/` and reference the filename here
  #         image: city-daniel-abadia.jpg
  #       - title: DISCOVER
  #         text: Discover the latest in AI, GenAI, application development and much more.
  #         # Upload image to `assets/media/` and reference the filename here
  #         image: conference-headway-F2KRf_QfCqw.jpg
  #       - title: HEAR FROM LEADERS REDEFINING THE AI LANDSCAPE
  #         text: Hear valuable insights from data and AI experts and business leaders, while discovering the limitless possibilities of data, AI and application collaboration for your organization.
  #         # Upload image to `assets/media/` and reference the filename here
  #         image: round-table-evangeline-shaw-xRlI-L-kvrw.jpg
  #         button:
  #           text: Get Tickets
  #           url: https://www.eventbrite.com/
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  # - block: people
  #   id: speakers
  #   content:
  #     title: Speakers
  #     text: ""
  #     user_groups: ['Speakers']
  #   design:
  #     show_role: true
  #     show_social: true
  #     show_interests: false
  - block: markdown
    id: speakers
    content:
      title: Speakers
      text: |
        ### Prof. Ray C. C. Cheung (Team Lead)
        **Professor**  
        Department of Electrical Engineering  
        City University of Hong Kong  
        
        ### Prof. Patrick S. Y. HUNG
        **Adjunct Professor**  
        Department of Electrical Engineering  
        City University of Hong Kong

        ### Dr. Abdurrashid Ibrahim SANKA
        **Post-doctoral Fellow**  
        Department of Electrical Engineering   
        City University of Hong Kong

        ### Dr. Hao YANG
        **Post-doctoral Fellow**  
        Department of Electrical Engineering   
        City University of Hong Kong

        ### Dr. Sherie Shiyu SHEN
        **Post-doctoral Fellow**  
        Department of Electrical Engineering   
        City University of Hong Kong

        ### Jeffrey HONG 
        Department of Electrical Engineering   
        City University of Hong Kong

        ### Alex ZHANG 
        Department of Electrical Engineering   
        City University of Hong Kong
  - block: markdown
    id: agenda
    content:
      title: Agenda (Proposed)
      text: |
        {style="padding-top: 2rem"}
        {{< table path="schedule.csv" header="true" >}}
  # - block: testimonials
  #   content:
  #     title: ""
  #     text: ""
  #     items:
  #       - name: "Alice Smith"
  #         role: "Researcher at X"
  #         # Upload image to `assets/media/` and reference the filename here
  #         image: "testimonial-1.jpg"
  #         text: "It has to be the most insightful conference I've ever attended!"
  #   design:
  #     spacing:
  #       # Reduce bottom spacing so the testimonial appears vertically centered between sections
  #       padding: ["6rem", 0, 0, 0]
  - block: logos
    content:
      title: "Organizers"
      text: ""
      # Image path relative to assets/media/ folder
      logo_folder: 'organizers/'
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""

  - block: logos
    content:
      title: "Sponsors"
      text: "TBA"
      # Image path relative to assets/media/ folder
      logo_folder: 'sponsors/'
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
  # - block: newsletter
  #   content:
  #     title: "Stay up to date"
  #     text: "Be the first to receive conference updates such as added speakers, deadlines, and ticket deals."
  #     text_cta: "Sign up to our newsletter 🔥"
  #     button:
  #       text: "Subscribe"
  #     convertkit:
  #       form_id: ''
  #       msg_subscribed: "Success! Please check your email to confirm your subscription."
  #   design:
  #     card:
  #       # Card background color (CSS class)
  #       css_class: "bg-primary-700"
  #       css_style: ""
---
