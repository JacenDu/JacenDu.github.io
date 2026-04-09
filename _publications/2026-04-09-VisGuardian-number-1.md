---
title: "VisGuardian: A Lightweight Group-based Privacy Control Technique For Front Camera Data From AR Glasses in Home Environments"
collection: publications
permalink: /publication/2026-04-13-chi-privacy
excerpt: 'Shuning Zhang, Qucheng Zang, Yongquan Hu, <b>Jiachen Du</b>, et al.'
date: 2026-04-13
venue: 'ACM CHI 2026'
paperurl: 'https://doi.org/10.1145/3772318.3790288'
---

Always-on sensing of AI applications on AR glasses makes traditional permission techniques ill-suited for context-dependent visual data, especially within home environments. The home presents a highly challenging privacy context due to the high density of sensitive objects, and the frequent presence of non-consenting family members, and the intimate nature of daily routines, making it a critical focus area for scalable privacy control mechanisms. Existing fine-grained controls, while offering nuanced choices, are inefficient for managing multiple private objects. We propose VisGuardian, a fine-grained content-based visual permission technique for AR glasses. VisGuardian features a group-based control mechanism that enables users to efficiently manage permissions for multiple private objects. VisGuardian detects objects using YOLO and adopts a pre-classified schema to group them. By selecting a single object, users can efficiently obscure groups of related objects based on criteria including privacy sensitivity, object category, or spatial proximity. A technical evaluation shows VisGuardian achieves mAP50 of 0.6704 with only 14.0 ms latency and a 1.7% increase in battery consumption per hour. Furthermore, a user study (N=24) comparing VisGuardian to slider-based and object-based baselines found it to be significantly faster for setting permissions and was preferred by users for its efficiency, effectiveness, and ease of use.
