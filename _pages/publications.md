---
layout: page
permalink: /publications/
title: publications
description: 
nav:  true
nav_order: 2
---

## Publications

{% bibliography --query @inproceedings[year=2024] || @book[year=2016] %}

## Working Papers

{% bibliography --query @unpublished %}
