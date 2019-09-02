---
venue: MiniMetricon 3.5
venueurl: http://www.securitymetrics.org/
name: Attack Resistance Score
date: 2009/04/20
description: Brenda's April 2009 discussion of an aggregate measure for a system's effectiveness at thwarting attacks.
---

# Summary

Brenda will present a candidate scale to use for direct measurement 
of the security of a product: direct as opposed to indirect indicators 
like security defect count, percentage of developers who have received
secure coding training, or code complexity; measurement as opposed to
qualitative analysis; product as opposed to operation or organization. 

The units of attack resistance score are seconds (sort of) required to
get from one set of privileges to another using the system, not including
exploit development or system discovery time.  Interesting starting & ending
privileges would presumably come from the system's security objectives.

The system is analogous to a resistor network, with the connection points
being privileges and the resistance unit being time.  The time to
traverse each resistor (intentional or not) can be estimated at design
time, then measured in deployment.  Graph traversal algorithms and
standard electrical engineering equations can be used to compute the
attack resistance score for any given security goal.

Brenda will cover how an attack resistance score is calculated and why
this could be a reasonable way to calculate it, prerequisites for widespread
use and usefulness of this metric, known limitations, and anticipated uses.
She will also list a few of the many other related metrics that are possible
using this analogy.

The attack resistance score concept is under active development by the
Trike team and will be part of the v2 release.

# Slides

[Attack Resistance Score](attack_resistance_score.pdf)
