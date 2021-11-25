---
layout: post
title:  stabilizing and communicating symptoms
date:   2018-04-06 13:00:16
description: blog post on our new paper on the role of stabilizing and communicating symptoms
---
This blog post was originally written for the <a href="https://psych-networks.com/new-paper-on-the-role-of-stabilizing-and-communicating-symptoms/" target="blank">psych networks</a> blog together with <a href="https://mariekdeserno.github.io/" target="blank">Marie Deserno</a>. 

As two graduate students in the Psychological Methods department at the University of Amsterdam, we were familiarized with the work of Cramer and Borsboom on conceptualizing mental disorders as complex networks of interacting symptoms. This conceptualization signifies the role of symptoms and their interactions within and across disorders, and has inspired novel theoretical definitions of clinical concepts such as core symptoms and comorbidity1.

We often found ourselves discussing the potential of tools and metrics from other research areas using network analytic techniques. In the summer of 2016 we came across Santo Fortunato’s Community detection in graphs (2010) – an excellent paper on various applications and implications of network analytic techniques2. One specific sentence caught our attention:

<blockquote>
	“Identifying modules and their boundaries allows for a classification of vertices, according to their structural position in the modules. So, vertices with a central position in their clusters, i.e. sharing a large number of edges with the other group partners, may have an important function of control and stability within the group; vertices lying at the boundaries between modules play an important role of mediation and lead the relationships and exchanges between different communities.” (p. 3)
</blockquote>

Reading this passage immediately sparked a discussion on the numerous possibilities of utilizing the community detection toolbox to develop empirical definitions of these theoretical concepts. The notion of “vertices with a central position within their cluster […] may have an important function of control and stability within the group” can readily be translated to the idea of core symptoms. Similarly, the idea that “vertices lying at the boundaries between modules play an important role [… in] exchanges between different communities” can be mapped onto the theoretical definition of comorbidity within the network perspective on psychopathology.

In our paper, entitled “The role of stabilizing and communicating symptoms given overlapping communities in psychopathology”, we aspired to complement the statistical toolbox of the network approach to psychopathology by exploring what overlapping community detection analysis has to offer. Using community detection and inspecting the differential role of symptoms within and between communities offers a framework to study the clinical concepts of comorbidity, heterogeneity and hallmark symptoms. Symptoms with many and strong connections within a community, defined as stabilizing symptoms, could be thought of as the core of a community, whereas symptoms that belong to multiple communities, defined as communicating symptoms, facilitate the communication between problem areas.

We applied community detection to a large dataset (N=2089) assessing a variety of psychological problems using the Symptom Checklist 90. We identified 18 communities of closely related symptoms. Importantly, these communities are empirically derived instead of theoretically defined. In the paper we illustrate how the proposed definitions on the differential role of symptoms can inform us on the structure of the psychopathological landscape: both globally as well as locally. As such, we adopted established metrics in network science to accelerate our understanding of the psychopathological landscape.


<img src="/img/local_community.png" alt="drawing" width="600"/>

<div class="col three caption">
	Figure 1. Illustration of (a) the local structure of Feelings of Worthlessness community, (b) its connection to other communities; and (c) a symptom-level example of its connection to the community Worried about Sloppiness.
</div>

<br/>
<br/>

From our perspective, this endeavour highlights that diving into the world of network science across all kinds of research areas can inspire great advances for the toolbox we use to study psychopathology networks. Drawing inspiration from fields concerned with complex systems such as brain networks, economic networks and social networks, the options seem infinite – and we cannot wait to explore them.

<hr>
<br/>

[1] Cramer, A.O.J., Waldorp, L.J., van der Maas, H.L.J. & Borsboom, D. Comorbidity: a network perspective. *Behav. Brain. Sci. 33,* 137-150 (2010).

[2] Fortunato, S. Community detection in graphs. *Phys. Rep. 486,* 75-174 (2010).
