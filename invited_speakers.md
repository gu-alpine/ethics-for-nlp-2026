---
layout: default
title: Ethics4NLP-2026
---
{% if jekyll.environment  == "production" %}
        {% assign basepath = "." %}
{% else %}
        {% assign basepath = "" %}
{% endif %}

<hr>

<div>
    <div class="iblock headshot-invited-speaker">
        <img src="{{basepath}}/images/speakers/maria_barrett.jpg" class="headshot">
        <a href="https://" class="headshotaffiliation">Maria Barrett</a>
        <div class="headshotname">Industrial Researcher</div>
    </div>
</div>

**Bio**  
<div style="text-align: justify;">
<a href="https://mariabarrett.github.io">Maria Barrett</a> works as an industrial researcher on multilingual evaluation of large language models. She holds a PhD in NLP from the University of Copenhagen since 2018. Her work examines what it takes to know whether a model works across languages and cultures and she is particularly interested in topics that are hard to measure.
</div>

<b>Talk:</b>
<div style="text-align: justify;">
When we evaluate a language model, we are not just taking a measurement, we are making a series of choices. The benchmarks used during the development of models guide the modelling decisions and form the lens through which we see our model. Drawing on practical experience on building multilingual evaluation infrastructure within the team and as part of a larger EU collaboration and on building new evaluation sets, I will walk through the stakes embedded in the decisions that are too often treated as purely technical. 
</div>

<hr>

<div>
    <div class="iblock headshot-invited-speaker">
        <img src="{{basepath}}/images/speakers/elena_volodina.jpg" class="headshot">
        <a href="https://" class="headshotaffiliation">Elena Volodina</a>
        <div class="headshotname"> University of Gothenburg </div>
    </div>
</div>

**Bio**  
<div style="text-align: justify;">
<a href= "https://spraakbanken.gu.se/en/about/staff/elena">Elena Volodina</a> is Professor of Language Technology at the University of Gothenburg, Språkbanken. Her research focuses on NLP for second language learning, learner corpora and research infrastructure, with particular attention to ethical and privacy-related challenges of working with sensitive language data. Her recent work addresses automatic pseudonymization and privacy-preserving processing, aiming to enable responsible access to sensitive textual data for research.
</div>

<b>Talk:</b>
<div style="text-align: justify;">
<p>This talk will be devoted to the challenges of working with research data that contains personal information and the ethical considerations arising from that. I will describe a set of experiments with automatic pseudonymization that we have performed on learner essays within the [project "Mormor Karl](https://mormor-karl.github.io/ "https://mormor-karl.github.io/")". Among others, experiments with detection and labeling of personal categories using BERT models (Szawerna et al. 2024, 2025), attempts at using LLMs to "fill in the blanks" when substituting personal information with pseudonyms (Szawerna & Suchart,  2026), a study on whether pseudonyms can provoke biased automated classifications (Muñoz Sánchez et al. 2024), and a few more. I will finish with an outline of what we consider needs to be done to harmonize the field (Volodina et al., 2025).</p>

<p>References:</p>

<ul class="incremental">
<li>Ricardo Muñoz Sánchez, Simon Dobnik, Maria Irena Szawerna, Therese
Lindström Tiedemann and Elena Volodina. 2024. <a
href="https://aclanthology.org/2024.caldpseudo-1.10/"
title="https://aclanthology.org/2024.caldpseudo-1.10/">Did the Names I
Used within My Essay Affect My Score? Diagnosing Name Biases in
Automated Essay Scoring</a>. In Proceedings of the the EACL workshop
Computational Approaches to Language Data Pseudonymization
(CALD-pseudo-2024). EACL, Malta, 2024. Association for Language
Technology.</li>
<li>Maria Irena Szawerna, Simon Dobnik, Ricardo Muñoz Sánchez, Therese
Lindström Tiedemann and Elena Volodina. 2024.<a
href="https://aclanthology.org/2024.caldpseudo-1.7/"
title="https://aclanthology.org/2024.caldpseudo-1.7/">Detecting Personal
Identifiable Information in Swedish Learner Essays</a>. In Proceedings
of the the EACL workshop Computational Approaches to Language Data
Pseudonymization (CALD-pseudo-2024). EACL, Malta, 2024. Association for
Language Technology.</li>
<li>Maria Irena Szawerna, David Alfter, Elena Volodina. 2025. <a
href="https://acl-bg.org/proceedings/2025/LM4DH%202025/pdf/2025.lm4dh-1.15.pdf"
title="https://acl-bg.org/proceedings/2025/LM4DH%202025/pdf/2025.lm4dh-1.15.pdf">Annotating
Personal Information in Swedish Texts with SPARV</a>. In Proceedings of
the First Workshop on Natural Language Processing and Language Models
for Digital Humanities, pages 155-163</li>
<li>Maria Irena Szawerna, Jacob Lee Suchardt 2026. <a
href="https://doi.org/10.63317/42gh3j2hfmca"
title="https://doi.org/10.63317/42gh3j2hfmca">Fill-in-the-Blanks:
Automatic Generation and Evaluation of Language Models’ Pseudonyms for
English and Swedish Texts</a>, in Proceedings of the Fifteenth Language
Resources and Evaluation Conference (LREC 2026), pages 1155-1169. Palma
de Mallorca, Spain. ELRA.</li>
<li>Elena Volodina, Simon Dobnik, Therese Lindström Tiedemann, Ricardo
Muñoz Sánchez, Maria Irena Szawerna, Lisa Södergård, Xuan-Son Vu.
2025. <a
href="https://www.huminfra.se/resources/humevents/hic-2025_proceedings.pdf"
title="https://www.huminfra.se/resources/humevents/hic-2025_proceedings.pdf">Towards
shared standards for pseudonymization of research data</a>. In
Proceedings of the Huminfra Conference (HiC 2025), Stockholm, 12-13
November 2025</li>
</ul>

</div>
