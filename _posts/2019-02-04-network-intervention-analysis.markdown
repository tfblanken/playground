---
layout: post
title:  network intervention analysis
date:   2019-02-04 16:40:16
description: blog post on our new paper introducing Network Intervention Analysis
---
This blog post was originally written for the <a href="http://psychosystems.org/network-intervention-analysis/" target="blank">psychosystems blog</a>.

According to the <a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5269502/" target="blank">network theory of mental disorders</a>, mental disorders are developed and sustained through direct interactions between symptoms [1]. From this conceptualization it follows that treatment of mental disorders should involve changing the network of interrelated symptoms. While over the past years many studies have investigated the network structure of psychopathologies <a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5226976/" target="blank">[2]</a>, the effect of psychological treatment on the network of interrelated symptoms has rarely been assessed. Moreover, network analysis techniques provide a unique opportunity to investigate treatment effects at a more detailed symptom level. In <a href="https://www.karger.com/Article/FullText/495045" target="blank">this new study</a> we aspired to adopt and extent the network approach to investigate specific and sequential treatment effects—a technique we labelled Network Intervention Analysis (NIA) [3]. NIA involves estimating a network of interrelated symptoms and including an additional treatment indicator variable that encodes the treatment condition that a participants belongs to. Including such a variable into the network allows to see which symptoms are conditionally dependent on this treatment variable. Since the treatment can influence the symptoms but not vice versa, this dependency indicates the symptoms that are directly affected by treatment.

In our illustration of NIA we investigated the effect of cognitive behavioral therapy for insomnia (CBTI) on co-occurring insomnia and depression symptoms. More traditional analyses had showed that after completion, the treatment had relieved both insomnia and depression symptoms <a href="https://www.ncbi.nlm.nih.gov/pubmed/29747706" target="blank">[4]</a>. It remained unclear, however, whether the effect of treatment on the depression symptoms occurred via improving the sleep problems, or whether CBTI influenced the depression symptoms directly. Using NIA across 10 measurement weeks (2 prior to treatment, 5 during treatment, and 3 after treatment) we could identify that CBTI predominantly affected the sleep problems, indicating that the improvements in depression likely occur via CBTI-induced improvements in sleep.


<img src="/img/NIA_blog.jpg" alt="drawing" width="800"/>

<div class="col three caption">
	Figure. Network structure before, during, and after treatment. The networks include the Insomnia Severity Index and Patient Health Questionnaire items (circles) and treatment (square). The size of the node is proportional to the difference in symptom severity between the treatment and control group, where smaller node sizes represent greater differences in favor of the treatment group. All ten networks corresponding to each of the measurement weeks are shown in the paper. An animated version can be found online.
</div>

<br/>
<br/>

This paper is a first illustration of how NIA can be used to investigate sequential and symptom-specific treatment induced changes over time. We hope to further develop NIA into a more sophisticated technique to investigate treatment effects over time—to ultimately better understand treatment mechanisms and reveal clues to their optimization.

<hr>
<br/>

[1] Borsboom D. (2017). A network theory of mental disorders. World Psychiatry, 16, 5-13.

[2] Fried EI, Van Borkulo CD, Cramer AOJ, Boschloo L, Schoevers RA, Borsboom D. (2017). Mental disorders as networks of problems: A review of recent insights. Social Psychiatry and Psychiatric Epidemiology, doi.org/10.1007/s00127-016-1319-z.

[3] Blanken TF\*, Van der Zweerde T\*, Van Straten A, Van Someren EJW, Borsboom, D, Lancee J. (2019). Introducing Network Intervention Analysis to investigate sequential, symptom-specific treatment effects: A demonstration in co-occurring insomnia and depression. Psychotherapy and Psychosomatics, doi.org/10.1159/000495045.

[4] Van der Zweerde T, Van Straten A, Effting M, Kyle SD, Lancee J. (2018). Does online insomnia treatment reduce depressive symptoms? A randomized controlled trial in individuals with both insomnia and depressive symptoms. Psychological Medicine, 49, 501-599.

\*shared first authors