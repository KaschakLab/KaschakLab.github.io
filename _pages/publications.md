---
title: "LML Lab - Publications"
layout: gridlay
excerpt: "LML Lab -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

## Group highlights

**At the end of this page, you can find the [full list of publications](#full-list-of-publications). All papers are also available on [Google Scholar](https://scholar.google.com/citationsuser=4OkEqtMAAAAJ&hl=en).**

{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## Full List of publications

Morey, R. D., Kaschak, M. P.,...Zwaan, R. A. (2022). A pre-registered multi-lab non-replication of the Action-sentence Compatibility Effect (ACE). Psychonomic Bulletin and Review, 29, 613-626. https://doi.org/10.3758/s13423-021-01927-8

Chia, K., & Kaschak, M. P. (2022). Structural priming in question-answer dialogues. Psychonomic Bulletin and Review, 29, 262-267. https://doi.org/10.3758/s13423-021-01976-z

Eligio, R. B., & Kaschak, M. P. (2020). Gaming experience affects the interpretation of ambiguous words. PLoS One, 15, e0243512. https://doi.org/10.1371/journal.pone.0243512

Chia, K., Hetzel-Ebben, H., ..., & Kaschak, M. P. (2020). Examining the factors that affect structural repetition in question answering. Memory and Cognition, 48, 1046-1060. https://doi.org/10.3758/s13421-020-01036-2

Yazbec, A., Borovsky, A., & Kaschak, M. P. (2019). Examining the impact of text style and epistemic beliefs on conceptual change. PLoS One, 14, e0220766. https://doi.org/10.1371/journal.pone.0220766

Yazbec, A., Kaschak, M. P., & Borovsky, A. (2019). Developmental Timescale of Rapid Adaptation to Conflicting Cues in Real-Time Sentence Processing. Cognitive Science, 43, 1-41. https://doi.org/10.1111/cogs.12704 

Haeffel, G. J., & Kaschak, M. P. (2019). Rethinking How We Think About Cognitive Interventions for Depression: An Example from Research on Second Language Acquisition. Clinical Psychological Science, 7, 68-76. https://doi.org/10.1177/2167702618794157

Chia, K., Axelrod, C., Johnson, C., ... & Kaschak, M. P. (2019). Structural repetition in question answering: A replication and extension of Levelt and Kelter (1982). Discourse Processes, 56, 2 – 23. https://doi.org/10.1080/0163853X.2018.1515556

Connor, C. M., Phillips, B., Kim, Y. – S. Lonigan, C., Kaschak, M. P., Crowe, E., Dombek, J., Al Otaiba, S. (2018). Examining the efficacy of targeted component interventions on language and literacy for third and fourth graders who are at risk of comprehension difficulties. Scientific Studies of Reading, 22, 462-484. https://doi.org/10.1080/10888438.2018.1481409

Kutta, T. J., Kaschak, M. P., Porcellini, A., & Jones, J. L. (2017). Implicit and explicit memory factors in cumulative structural priming. Collabra, 3, 13. https://doi.org/10.1525/collabra.59

Kaschak, M. P., Connor, C. M., & Dombek, J. L. (2017). Enacted Reading Comprehension: Using bodily movement to aid the comprehension of abstract text content. PLoS One, 12, e0169711. https://doi.org/10.1371/journal.pone.0169711

Erickson, L. C., Kaschak, M. P., Thiessen, E. D., & Berry, C. A. S. (2016). Individual differences in statistical learning: Conceptual and measurement issues. Collabra, 2(1), p.14. DOI: https://doi.org.10.1525.collabra.41

Connor, C. M., Day, S. L., Phillips, B. P., Sparapani, N., McLean, N., Barrus, A., & Kaschak, M. P. (2016). Reciprocal effects of self-regulation, semantic knowledge, and reading comprehension in early elementary school. Child Development, 87, 1813-1824. https://doi.org/10.1111/cdev.12570            

Spencer, M., Kaschak, M. P., Jones, J. L., & Lonigan, C. J. (2015). Statistical learning is related to early literacy-related skills. Reading and Writing, 28, 467-490. https://doi.org/10.1007/s11145-014-9533-0

Connor, C. M., Phillips, B. M., Kaschak, M. P., Apel, K., Kim, Y-S., Al Otaiba, S., Crowe, E. C., Thomas-Tate, S., Johnson, L. C., & Lonigan, C. J. (2014). Comprehension tools for teachers: Reading for understanding from pre-kindergarten through fourth grade. Educational Psychology Review, 26, 379-401.  https://doi.org/10.1007/s10648-014-9267-1

Kaschak, M. P., Kutta, T. J., & Coyle, J. M. (2014). Long and short term cumulative structural priming effects. Language, Cognition and Neuroscience, 29, 728-743. https://doi.org/10.1080/01690965.2011.641387

Coyle, J. M., & Kaschak, M. P. (2012). Female fertility affects men's linguistic choices. PLoS One, 7, 1-7. https://doi.org/10.1371/journal.pone.0027971

Jones, J. L., & Kaschak, M. P. (2012). Global statistical learning in a visual search task. Journal of Experimental Psychology: Human Perception and Performance, 38, 152-160. https://doi.org/10.1037/a0026233

Kutta, T. J., & Kaschak, M. P. (2012). Changes in task extrinsic context do not affect the persistence of long-term cumulative structural priming. Acta Psychologica, 141, 408-414. https://doi.org/10.1016/j.actpsy.2012.09.007

Sell, A. J., & Kaschak, M. P. (2012). The comprehension of sentences involving quantity information affects responses on the up-down axis. Psychonomic Bulletin and Review, 19, 708-714. https://doi.org/10.3758/s13423-012-0263-5

Kaschak, M. P., Kutta, T. J., & Jones, J. L. (2011). Structural priming as implicit learning: Cumulative priming effects and individual differences. Psychonomic Bulletin and Review, 18, 1133-1139. https://doi.org/10.3758/s13423-011-0157-y

Kaschak, M. P., Kutta, T. J., & Schatschneider, C. (2011). Long-term cumulative structural priming persists for (at least) one week. Memory and Cognition, 39, 381-388. https://doi.org/10.3758/s13421-010-0042-3

Sell, A. J., & Kaschak, M. P. (2011). Processing time shifts affects the execution of motor responses. Brain and Language, 117, 39-44. https://doi.org/10.1016/j.bandl.2010.07.003

Coyle, J. M., & Kaschak, M. P. (2008). Patterns of experience with verbs affects long-term cumulative structural priming. Psychonomic Bulletin and Review, 15, 967-970. https://doi.org/10.3758/PBR.15.5.967

Kaschak, M. P., & Borreggine, K. L. (2008). Is long-term structural priming affected by patterns of experience with individual verbs? Journal of Memory and Language, 58, 862- 878. https://doi.org/10.1016/j.jml.2006.12.002

Kaschak, M. P., & Borreggine, K. L. (2008). Temporal dynamics of the action-sentence compatibility effect. Quarterly Journal of Experimental Psychology, 61, 883-895. https://doi.org/10/1080/17470210701623852

Dijkstra, K., Kaschak, M. P., & Zwaan, R. A. (2007). Body position facilitates retrieval of autobiographical memories. Cognition, 102, 139-149.  https://doi.org/10.1016/j.cognition.2005.12.009

Kaschak, M. P. (2007). Long-term structural priming affects subsequent patterns of language production. Memory and Cognition, 35, 925-937. https://doi.org/10.3758/BF03193466

Borreggine, K. L., & Kaschak, M. P. (2006). The action-sentence compatibility effect: It's all in the timing. Cognitive Science, 30, 1097-1112. https://doi.org/10.12007/s15516709cog0000_91

Kaschak, M. P. (2006). What this construction needs is generalized. Memory and Cognition, 34, 368-379. https://doi.org/10.3758/BF03193414

Kaschak, M. P., Loney, R. A., & Borreggine, K. L. (2006). Recent experience affects the strength of structural priming. Cognition, 99, B73-B82.  https://doi.org/10.1016/j.cognition.2005.07.002

Kaschak, M. P., & Saffran, J. R. (2006). Idiomatic syntactic constructions and language learning. Cognitive Science, 30, 43-63.  https://doi.org/10/1207/s15516709cog0000_44

Kaschak, M. P., Zwaan, R. A., Aveyard, M., & Yaxley, R. H. (2006). Perception of auditory motion affects sentence processing. Cognitive Science, 30, 733-744. https://doi.org/10.1207/s15516709cog0000_54

Kaschak, M. P., Madden, C. J., Therriault, D. J., Yaxley, R. H., Aveyard, M. E., Blanchard, A. A., & Zwaan, R. A. (2005). Perception of motion affects language processing. Cognition, 94, B79-B89. https://doi.org/10.1016/j.cognition.2004.06.005

Borghi, A. M., Glenberg, A. M., & Kaschak, M. P. (2004). Putting words in perspective. Memory and Cognition, 32, 863-873. https://doi.org/10.3758/BF03196865

de Vega, M., Robertson, D. A., Glenberg, A. M., Kaschak, M. P., & Rinck, M. (2004). On doing two things at once: Temporal constraints on actions in language comprehension. Memory and Cognition, 32, 1033-1043. https://doi.org/10.3758/BF03196879

Glenberg, A. M., Gutierrez, T., Levin, J., Japuntich, S., & Kaschak, M. P. (2004). Activity and imagined activity can enhance young children's reading comprehension. Journal of Educational Psychology, 96, 424-436. https://doi.org/10.1037/0022-0663.96.3.424

Kaschak, M. P., & Glenberg, A. M. (2004). This construction needs learned. Journal of Experimental Psychology: General, 133, 450-467. https://doi.org/10.1037/0096-3445.133.3.450

Gernsbacher, M. A. & Kaschak, M. P. (2003). Neuroimaging studies of language production and comprehension. Annual Review of Psychology, 54, 91-114.  https://doi.org/10.1146/annurev.psych.54.101601.145128

Glenberg, A. M., & Kaschak, M. P. (2002). Grounding language in action. Psychonomic Bulletin and Review, 9, 558-565. https://doi.org/10.3758/BF03196313

Kaschak, M. P., & Glenberg, A. M. (2000). Constructing meaning: The role of affordances and grammatical constructions in sentence comprehension. Journal of Memory and Language, 43, 508-529.  https://doi.org/10.1006/jmla.2000.2705  
