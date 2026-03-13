---
layout: pattern
title: "Control — Restoring Performance Under Pressure"
description: "When programmes are failing, capital is at risk, or leadership has lost operational command. The C³ Control pattern."
phase: control
question: "Can I stop the bleeding and regain command before the window closes?"
permalink: /control/
---

Restoring governance, decision clarity, and executive control when performance is deteriorating and the cost of delay is compounding.

## What This Pattern Looks Like

When you see these signals, you are likely in a Control situation:

- **A major programme is failing** — budgets are overrun, timelines have slipped repeatedly, and the internal narrative is "we need more resources" rather than "we need to change how decisions get made."
- **Capital is at risk** — a large investment has been committed based on assumptions that haven't survived contact with reality, but nobody has the authority or willingness to halt it.
- **Post-acquisition dysfunction** — two organizations have merged on paper but decision rights, governance, and reporting remain fragmented or duplicated.
- **Leadership paralysis** — escalations arrive too late to influence outcomes, and senior leaders receive status reports rather than decision-forcing information.

## What Changes When It Works

- **Executive control is restored** — decision rights are clear, escalations arrive in time, and governance forums produce decisions rather than updates.
- **Zero-value work is stopped** — scope creep is halted, initiatives that cannot justify their continued existence are cancelled, and the cost of "yes" becomes visible.
- **Decision quality improves** — the narrative shifts from "delivery failure" to "structural correction," unlocking future investment rather than discouraging it.
- **Trust is rebuilt** — between the board and management, between business and technology, between the organization and its stakeholders.

## Case Evidence

{% for cs in site.data.case_studies %}{% if cs.phase == "control" %}
{% include case-card.html title=cs.title client=cs.client phase=cs.phase situation=cs.situation outcome=cs.outcome url=cs.slug %}
{% endif %}{% endfor %}

{% include cta.html message="If you're facing a failing programme or capital at risk, let's talk about what restoring control would look like." %}
