---
layout: splash
title: "Hi, I'm Your Name"
header:
  overlay_color: "#000"
  overlay_filter: 0.35
  overlay_image: "https://images.unsplash.com/photo-1518779578993-ec3579fee39f?q=80&w=2400&auto=format&fit=crop"
  actions:
    - label: "View Projects"
      url: /projects/
      class: "btn btn--primary"
    - label: "Resume"
      url: /assets/resume.pdf
      class: "btn btn--light-outline"
excerpt: "Data Scientist ➜ AI Engineer. I ship useful ML & LLM systems."
intro: 
  - excerpt: 'I specialize in end‑to‑end ML: data, training, evals, and deployment. Below are a few highlights — see **Projects** for more.'
feature_row:
  - image_path: https://images.unsplash.com/photo-1526378722484-bd91ca387e72?q=80&w=1200&auto=format&fit=crop
    alt: "LLM Evaluator"
    title: "LLM Evaluator"
    excerpt: "Automatic evals for RAG and agents with rubric & behavioral tests."
    url: /projects/llm-evaluator/
    btn_label: "Read more"
    btn_class: "btn--primary"
  - image_path: https://images.unsplash.com/photo-1515879218367-8466d910aaa4?q=80&w=1200&auto=format&fit=crop
    alt: "MLOps Pipeline"
    title: "MLOps Pipeline"
    excerpt: "Data to deployment with CI/CD, feature store, and model registry."
    url: /projects/mlops-pipeline/
    btn_label: "Read more"
    btn_class: "btn--primary"
  - image_path: https://images.unsplash.com/photo-1534759846116-57970f717f3b?q=80&w=1200&auto=format&fit=crop
    alt: "Computer Vision"
    title: "Computer Vision"
    excerpt: "Real-time detection with model distillation for edge devices."
    url: /projects/edge-detection/
    btn_label: "Read more"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}
{% include feature_row %}
