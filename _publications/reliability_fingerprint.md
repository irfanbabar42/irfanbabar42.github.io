---
title: "On the Reliability of Radio Frequency Fingerprinting"
collection: publications
category: manuscripts
permalink: /publication/reliability_fingerprint
excerpt: '**Irfan, Muhammad**, Savio Sciancalepore, and Gabriele Oligeri. "On the Reliability of Radio Frequency Fingerprinting." arXiv preprint arXiv:2408.09179, 2024.'
date: 2024-08-17
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2408.09179'
---
## Abstract
Radio Frequency Fingerprinting (RFF) offers a unique method for identifying devices at the physical (PHY) layer based on their RF emissions due to intrinsic hardware differences. Nevertheless, RFF techniques depend on the ability to extract information from the PHY layer of the radio spectrum by resorting to Software Defined Radios (SDR). Previous works have highlighted the so-called ``Day-After-Tomorrow'' effect, i.e., an intrinsic issue of SDRs leading to a fingerprint mutation following a radio power cycle. In this work, we extend such a study by demonstrating that fingerprint mutations appear every time a new FPGA image is reloaded, i.e., when the SDR initiates a new communication. In this context, we provide an in-depth analysis of the reliability of RFF over multiple FPGA image reloading operations, highlighting its ephemeral and mutational nature. We introduce a methodology for abstracting fingerprint mutations into a graph and provide a theoretical framework for assessing fingerprint reliability. Our results show that the common assumption of considering the RF fingerprint as unique and always persistent is incorrect. By combining real-world measurements, high-performance SDRs, and state-of-the-art deep learning techniques, we experimentally demonstrate that radio devices feature multiple fingerprints that can be clustered according to shared features. Moreover, we show that the RF fingerprint is a time-independent probabilistic phenomenon, which requires the collection of multiple samples to achieve the necessary reliability.