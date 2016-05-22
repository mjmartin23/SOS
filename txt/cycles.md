# Cycles Within Data Science Procceses

[Fayyad et al. (1996)](bib.md#fayyad96) offer the classic definition of data science, as applied to real-world activities:

+ KDD (knowledge discovery in databases) is the non- trivial process of identifying valid, novel, potentially useful, and ultimately understandable patterns in data.

The following figure summarizes their approach. 

![kdd cycle](https://www.researchgate.net/profile/Martin_Shepperd/publication/220277672/figure/fig1/AS:277448081068032@1443160185199/Fig-3-The-KDD-cycle-From-11.png)

Many aspects of this figure are insightful and worthy of careful study. For example, as shown in this figure,   data science is just a small part of the total process. Even just gaining permission to access data can be a long process requiring extensive interaction with business user groups. Copying large amounts of data from one source to another can also consume a large amount of time. Once data is accessed, then raw data typically requires extensive manipulation before it is suitable for mining. This is:

+ TIP:  _Most of “data science” is actually “data pre- processing._ Before any learner can execute, much effort must be expended in selecting and accessing the data to process, pre-processing, and transforming it some learnable form.

Figure 2 also clearly illustrates the cyclic nature of data science:

+ Usually, finding one pattern prompts new questions such as “why does that effect hold?” or “are we sure there is no bug in step X of the method?”. Each such question refines the goals of the data science process, which leads to another round of the whole process.
+ In the initial stages of a project, engineers try different methods to generate the feedback that let users refine and mature the goals of the project.
+ Real world data is highly “quirky” and inductive engineers often try different methods before they discover how to find patterns in the data.


The repetitive nature of data science implies:

+ TIP: _In any industrial application, the data science method is repeated multiples times_ to either answer an extra user question, make some enhancement and/or bug fix to the method, or to deploy it to a different set of user.

This, in turn, has implications on tool choice:

+  TIP: _Thou shall not click:_ For serious studies, to ensure repeatability, the entire analysis should be automated using some high level scripting language; e.g. R-script, Python, Matlab, or Bash [33]


