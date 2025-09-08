---
title: Securing HHL Quantum Algorithm against Quantum Computer Attacks

event: Joint March Meeting and April Meeting - Global Physics Summit 2025
event_url: https://www.aps.org/events/2025/joint-meeting

location: Joint March Meeting and April Meeting - Global Physics Summit 2025
address:
  street: 
  city: Anaheim
  region: CA
  postcode: ''
  country: sUnited States

summary: 
abstract: 'As the quantum research community expands and new quantum algorithms are created and implemented, it is essential to consider the security implications and potential threats that could lead to the compromise the information processed by them. This work focuses on securing the HHL quantum algorithm against attacks while it executes on a quantum computer. Specifically, two types of potential attacks could be deployed on a cloud-based quantum computer by an attacker circuit attempting to interfere with the victim HHL circuit: the Improper Initialization Attack (IIA) and the Higher Energy Attack (HEA). To protect the HHL algorithm from IIA and HEA, this work proposes first-of-a-kind defense strategies against these attacks on the HHL quantum algorithm. Next, this work demonstrates an implementation of a new quantum circuit for the HHL quantum algorithm that incorporates these defenses. The redesigned quantum circuit is necessary to successfully apply and realize all proposed defense strategies. Finally, this work illustrates how these defense strategies function in practice in the redesigned circuit, specifically how they can protect the HHL quantum algorithm from both IIA and HEA across multiple qubits involving all three types of qubits used in the HHL algorithms: ancilla, clock, and b. The defense requires minimal modification to the circuit, and has only a very small effect on the fidelity of the circuits. The circuits have been tested and validated in both simulation, and also on real IBM quantum computer hardware. The work further analyzes how the modified HHL circuit with the defenses is affected by noise during quantum computation. This work in the end demonstrates that it is practical to add protections to quantum circuits so that they not only perform correct computation, but also self-detect if an attack has occured during the execution.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-03-19T00:00:00Z'
date_end: ''
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: '2024-10-09T00:00:00Z'

authors: ['Yizhuo Tan']
tags: ['Quantum Computing Security']

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point: 

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
#   - example

# <!-- 
# {{% callout note %}}
# Click on the **Slides** button above to view the built-in slides feature.
# {{% /callout %}}

# Slides can be added in a few ways:

# - **Create** slides using Wowchemy's [_Slides_](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
# - **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
# - **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

# Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page. -->
---
