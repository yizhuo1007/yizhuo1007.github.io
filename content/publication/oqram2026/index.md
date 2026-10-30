---
title: "OQRAM: Oblivious Quantum Random Access Memory for Securing Delegated Quantum Queries"
authors: ["Shifan Xu", "admin", "Yongshan Ding", "Jakub Szefer"]
author_notes: ["Equal contribution", "Equal contribution", "", ""]
equal_contribution: true
date: "2026-07-29"
publication_types: ["3"]
publication: "arXiv:2607.27171, 2026"
publication_short: "arXiv preprint, arXiv:2607.27171"
publication_group: "preprints"
abstract: "Quantum query is a basic subroutine in many quantum algorithms, and Quantum Random Access Memory (QRAM) provides a natural way to realize such coherent query access. In delegated settings, however, a standard QRAM query interface can expose sensitive information to the server. This paper introduces oblivious QRAM, a cryptographic abstraction for privacy-preserving delegated coherent query access. The protocol consists of an offline refresh phase and an online protected query phase. The database is stored in an encrypted and shuffled layout, and each query is protected by coherent address masking using either a quantum-secure pseudorandom permutation (qPRP) based method or a quantum one-time pad (qOTP) based method. In the adopted client model, the online protection adds only modest quantum overhead beyond the query register, avoiding the exponential quantum resources that would otherwise be required by an equivalent local QRAM construction. The qPRP-based variant also supports multi-query use by distributing database refresh across multiple queries to reduce classical communication. To address malicious servers, decoy checks are further incorporated to strengthen privacy protection and enable probabilistic tampering detection. Compared with fully blind quantum computing, this framework provides a lighter abstraction tailored to private delegated QRAM access, significantly reducing quantum resource requirements on both the client and server sides and achieving an exponential reduction in quantum communication."
url_pdf: "https://arxiv.org/pdf/2607.27171"
links: [{"name": "arXiv", "url": "https://arxiv.org/abs/2607.27171"}]
tags: ["Quantum Computing", "Quantum Privacy"]
featured: false
---

*\* Equal contribution: Shifan Xu and Yizhuo Tan.*
