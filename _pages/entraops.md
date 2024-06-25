---
title: "EntraOps Privileged EAM"
layout: splash
permalink: /entraops/
header:
  overlay_color: "#001B38"
  overlay_filter: "0.5"
  overlay_image: /assets/images/entraops/entraops_banner.png
  actions:
    - label: "Get it on GitHub"
      url: "https://github.com/Cloud-Architekt/EntraOps"
excerpt: "Community project to classify, identify and protect your privileges based on Enterprise Access Model (EAM)"
feature_row1:
  - image_path: assets/images/entraops/1-ascode.png
    title: "Automated setup and built for DevOps platforms"
    excerpt: "The core of EntraOps is a PowerShell module and works on any platform which supports PowerShell Core. It can be also executed locally within an interactive session. It's optimized for being used in a DevOps environment and includes an automated setup for GitHub and Federated Credentials. This also allows to take benefit of Git, to compare changes of your privileged assets."
    url: "https://github.com/Cloud-Architekt/EntraOps?tab=readme-ov-file#using-entraops-with-github"
    btn_label: "Using EntraOps with GitHub"
    btn_class: "btn--primary"    
feature_row2:    
  - image_path: /assets/images/entraops/2-identify.png
    title: "Identify and classify your privileged assets"
    excerpt: "Get privileges of user and workload identities with eligible, permanent, time-bounded and nested role assignments in Microsoft Entra. Identify your privileged identities and access based on automated and full customizable classification of Enterprise Access tiering” model"
    url: "https://github.com/Cloud-Architekt/EntraOps?tab=readme-ov-file#classify-privileged-objects-by-custom-security-attributes"
    btn_label: "Classify privileged assets"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/entraops/3-hunting.png
    title: "Integration and hunting of privileged asset data"
    excerpt: 'Ingest classified privileges with detailed data to Log Analytics Workspace or Sentinel WatchList for hunting and enrichment"`'
    url: "https://github.com/Cloud-Architekt/EntraOps?tab=readme-ov-file#entraops-integration-in-microsoft-sentinel"
    btn_label: "Setup Integration to Microsoft Sentinel"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/entraops/4-visualize.png
    title: "Analysis and visualization of privileged classification"
    excerpt: 'Using ingested data to Log Analytics-/Sentinel-Workspace or WatchLists for monitoring, hunting or entity enrichment of your privileged assets. Workbook to visualize results of all classified roles including charts to identify “tier breach”. Compare classification of privileged objects (based on custom security attribute) with their classified privileged access (identified by EntraOps)."`'
    url: "https://github.com/Cloud-Architekt/EntraOps?tab=readme-ov-file#workbook-for-visualization-of-entraops-classification-data"
    btn_label: "Deploy EntraOps Workbook"
    btn_class: "btn--primary"
---

{% include feature_row id="feature_row1" type="left" %}

{% include feature_row id="feature_row2" type="right" %}

{% include feature_row id="feature_row3" type="left" %}

{% include feature_row id="feature_row4" type="right" %}

