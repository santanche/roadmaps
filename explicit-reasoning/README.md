# Learning Analytics for Explicit Reasoning Roadmap
*updated at February 6th, 2023*

This roadmap comprises several initiatives we did not find a proper term for yet and we call *explicit rationale*. They encompass mechanisms to make explicit a learner's reasoning when solving a problem through a digital platform. Explicit here means machine interpretable. Learning analytics tools then help to analyze this reasoning, finding patters and related outcomes.

## 1. Teaching an Agent with an Executable Concept Map

**Betty's Brain** is the only initiative we know now that applies what we call an executable concept map. A special kind of conceptual map representing causality among phenomena (causal map) formalizes the way of teaching a bot (Betty) to answer questions.

> Segedy, J. R., Kinnebrew, J. S., & Biswas, G. (2015). **Using Coherence Analysis to Characterize Self-Regulated Learning Behaviours in Open-Ended Learning Environments**. *Journal of Learning Analytics*, 2(1), 13–48. [online](https://doi.org/10.18608/jla.2015.21.3).

This paper offers the broadest view of the research (model, experiments, and analysis). You can start here or in the subsequent reference.

Important points to note in this article:
* The mechanism to build and process the executable concept maps.
* The learning analytics approach to evaluate the maps produced by students.

> Leelawong, K., & Biswas, G. (2008). **Designing Learning by Teaching Agents: The Betty’s Brain System**. *International Journal of Artificial Intelligence in Education*, 18(3), 181–208.

An open version is available [here](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=0b1eb872ae143ffb9f36b90b1243dfd28bbbd731).

This is the first article, which presents related work and details of the conception and implementation.

Important points to note in this article:
* Related work can point to relevant initiatives in open reflection.
* It unveils the rationale to conceive the model behind Betty's Brain.

## 2. Learning Analytics in Open-Ended/Exploratory Learning Environments

Learning analytics is a core element for analyzing actions in open-ended and exploratory learning environments. A frequent approach is mining recurring sequences of actions to relate them to outcomes.

### User Modeling

An approach exploited by Betty's Brain is what Conati & Kardan call User-Modeling Framework, which involves three steps:
1. Feature Vector Calculation
2. Classification via Clustering Algorithm
3. Users' behavior patterns of clusters

> Conati, C., & Kardan, S. (2013). **Student modeling: Supporting personalized instruction, from problem solving to exploratory open-ended activities**. *AI Magazine*, 34(3), 13–26. https://doi.org/10.1609/AIMAG.V34I3.2483

An open version is available [here](https://web.archive.org/web/20190429/http://www.aaai.org/ojs/index.php/aimagazine/article/download/2483/2376).

### Class Association Rules

> Bernardini, A., & Conati, C. (2010). Discovering and recognizing student interaction patterns in exploratory learning environments. Intelligent Tutoring Systems - ITS 2010 - Lecture Notes in Computer Science, Vol 6094, 6094 LNCS(PART 1), 125–134. https://doi.org/10.1007/978-3-642-13388-6_17/COVER

This paper shows a mining approach based on Class Association Rules.

## 3. Knowledge Components in Open-ended Environments

**TRESTE** is an approach to model discovery that enables tracking concept formation.

> Harpstead, E., Maclellan, C. J., & Aleven, V. (2015). **Discovering knowledge models in an open-ended educational game using concept formation**. *Proc. of the Workshops at the 17th International Conf. on Artificial Intelligence in Education AIED 2015*. https://ceur-ws.org/Vol-1432/iseole_pap2.pdf

This first paper is a short overview of the proposal.

> Maclellan, C. J., Harpstead, E., Aleven, V., & Koedinger, K. R. (2016). **TRESTLE: A Model of Concept Formation in Structured Domains**. *Advances in Cognitive Systems*, 4, 131–150. http://www.cogsys.org/journal/volume4/article-4-10.pdf

This second paper presents a more detailed analysis.

Important points to note in this article:

* How to combine the notion of an open-ended environment with a controlled set of primitives+combinations, which can be related to concept formation.
* How the TRESTLE approach analysis the results.

The authors provide a [Github page](https://github.com/cmaclell/concept_formation).

It is relevant to watch the game videos to understand how it works at [RumbleBlocks Videos](https://www.etc.cmu.edu/engage/?page_id=509).
