---
layout: post
title: Velodrome paper is out!
subtitle: Semi-supervised out-of-distribution generalization
tags: [Paper]
---

Velodrome is a method of drug response prediction that takes gene expression of cell lines (labeled) and patients (unlabeled) as input and predicts Area Above dose-response Curve as output. The model learns a predictive invariant representation using a standard supervised loss on cell lines, an alignment loss on cell lines and patients, and a consistency loss on patients. 

Our experimental results on cell lines, PDX samples, and clinical trial data suggest very promising performance. We demonstrated generalization to well- and under-represented tissue types as well as completely new tissue types w.r.t tissue types available in training domains. 

Draft: https://www.biorxiv.org/content/10.1101/2021.05.25.445658v3.abstract

Code and data: https://github.com/hosseinshn/Velodrome

November 2021 UPDATE! Velodrome is now published in Nature Machine Intelligence: https://www.nature.com/articles/s42256-021-00408-w
