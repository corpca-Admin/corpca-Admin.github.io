---
title: "EntraOps Privileged EAM"
layout: splash
permalink: /entraops/
header:
  overlay_color: "#001B38"
  overlay_filter: "0.5"
  overlay_image: /assets/images/entraops/entraops_banner.png
  actions:
    - label: "Download"
      url: "https://github.com/Cloud-Architekt/EntraOps"
excerpt: "Community project to classify, identify and protect your privileges based on Enterprise Access Model (EAM)"
feature_row:
  - image_path: assets/images/entraops/1-ascode.png
    alt: "placeholder image 1"
    title: "Automated setup and tracking privileges as code"
    excerpt: "Automation for deployment in GitHub, support local execution or any platform which supports PowerShell Core"
  - image_path: /assets/images/entraops/2-identify.png
    alt: "placeholder image 2"
    title: "Identify and classify your privileged identities and access"
    excerpt: "Get privileges of user and workload identities with eligible, permanent, time-bounded and nested role assignments in Microsoft Entra. Identify your privileged identities and access based on automated and full customizable classification of Enterprise Access tiering” model"
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/entraops/3-hunting.png
    alt: "placeholder image 2"
    title: "Integration and hunting of privileged asset data"
    excerpt: 'Ingest classified privileges with detailed data to Log Analytics Workspace or Sentinel WatchList for hunting and enrichment"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/entraops/4-visualize.png
    alt: "placeholder image 2"
    title: "Analysis and visualization of privileged classification"
    excerpt: 'Using ingested data to Log Analytics-/Sentinel-Workspace or WatchLists for monitoring, hunting or entity enrichment of your privileged assets. Workbook to visualize results of all classified roles including charts to identify “tier breach”. Compare classification of privileged objects (based on custom security attribute) with their classified privileged access (identified by EntraOps)."`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

