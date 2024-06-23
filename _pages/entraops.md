---
title: "EntraOps"
layout: splash
permalink: /entraops/
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#001B38"
  overlay_filter: "0.5"
  overlay_image: /assets/images/entraops/entraops_banner.png
  actions:
    - label: "Download"
      url: "https://github.com/Cloud-Architekt/EntraOps"
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "Community project to classify, identify and protect your privileges based on Enterprise Access Model (EAM)"
intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
feature_row:
  - image_path: assets/images/entraops/1-ascode.jpg
    alt: "placeholder image 2"  
    title: "Automated setup and tracking privileges <as Code>"
    excerpt: "Automation for deployment in GitHub, support local execution or any platform which supports PowerShell Core" 
  - image_path: /assets/images/entraops/2-identify.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Identify and classify your privileged identities and access"
    excerpt: "Get privileges of user and workload identities with eligible, permanent, time-bounded and nested role assignments in Microsoft Entra. Identify your privileged identities and access based on automated and full customizable classification of Enterprise Access “tiering” model""
    url: "https://github.com/Cloud-Architekt/EntraOps?tab=readme-ov-file#entraops-integration-in-microsoft-sentinel"
    btn_label: "Configure ingestion"
    btn_class: "btn--primary"    
feature_row2:    
  - image_path: /assets/images/entraops/3-hunting.jpg
    title: "Integration and hunting of privileged asset data"
    alt: "placeholder image 2"    
    excerpt: "Ingest classified privileges with detailed data to Log Analytics Workspace or Sentinel WatchList for hunting and enrichment."
    url: "https://github.com/Cloud-Architekt/EntraOps?tab=readme-ov-file#entraops-integration-in-microsoft-sentinel"
    btn_label: "Configure ingestion"
    btn_class: "btn--primary"
  - image_path: /assets/images/entraops/4-visualize.jpg
    title: "Analysis and visualization of privileged classification"
    alt: "placeholder image 2"    
    excerpt: "Using ingested data to Log Analytics-/Sentinel-Workspace or WatchLists for monitoring, hunting or entity enrichment of your privileged assets. 
    Workbook to visualize results of all classified roles including charts to identify “tier breach”. Compare classification of privileged objects (based on custom security attribute) with their classified privileged access (identified by EntraOps)."
    url: "https://github.com/Cloud-Architekt/EntraOps?tab=readme-ov-file#entraops-integration-in-microsoft-sentinel"
    btn_label: "Configure ingestion"
    btn_class: "btn--primary"    
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Identify and classify your privileged identities and access"
    excerpt: 'Analyzing privileges of user and workload identities with eligible, permanent, time-bounded and nested role assignments in Microsoft Entra.Identify your privileged identities and access based on automated and full customizable classification of Enterprise Access “tiering” model"'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}