---
layout: page
title: "Case Studies"
description: "Anonymized, outcome-focused case studies organized by C³ impact pattern: Control, Coherence, and Compounding."
permalink: /case-studies/
---

Each case follows a consistent structure: the problem as the organization framed it, the real constraint I identified, the key interventions at the decision level, and the measured outcomes — with conservative attribution.

All client names are anonymized. Full case details are available in confidential conversation.

<div class="case-grid">
{% for cs in site.data.case_studies %}
{% include case-card.html title=cs.title client=cs.client phase=cs.phase situation=cs.situation outcome=cs.outcome url=cs.slug %}
{% endfor %}
</div>
