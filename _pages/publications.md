---
layout: page
permalink: /research/
title: research
description: Links to working papers will be uploaded in due course. Till then, please reach out out via e-mail and I will be happy to share research drafts.
nav: true
nav_order: 2
---

<div class="publications">
  <h2>Working Papers</h2>
  {% bibliography --group_by none --query @*[category=working_paper]* %}

  <h2>Work in Progress</h2>
  {% bibliography --group_by none --query @*[category=work_in_progress]* %}
</div>

