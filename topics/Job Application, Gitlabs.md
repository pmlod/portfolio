---
tags:
  - work
  - jobs
date: 02.09.2024 at 12:22
---
# Job Application, Gitlabs

Please tell us about your experience with Git and docs as code. You can enter "NA" if you don't have experience in this area.

In my current role, one of the content categories I own is product documentation for a range of proprietary SaaS systems. As a longtime advocate of both the markdown format and the docs-as-code model, I'd like to say that I've managed to migrate and standardize all our workflows on Git. Sadly, the truth is a little messier -- decades of tech debt will do that -- but we're getting there.

As a side note, I've also managed to work Git into my side hustle as a novelist (I've published two widely acclaimed novels; see https://vspr.st/ for more details). All my research now lives in an Obsidian vault, and even my manuscript drafts are now iterated and branched in a personal repo.

Can you describe your participation in a major documentation effort?*

One of my current projects is a SaaS application used in the translation of content related to clinical trials. The workflow used is constrained to some degree by end-customer preferences, but we have adopted some elements of the documentation-first approach. For instance, new documentation topics are typically originated alongside user stories during daily stand-ups. Similarly, key top-level topics like Who Is This Product For get substantially drafted as part of persona definition, which can also require tweaks to the style guide. My role in the process is dynamic—as an overstretched SME, I end up reviewing my own work more often that I'd like—but I

Please share one or more writing samples. We'd like to understand their context, so please tell us about the toolchain used, the SME(s), other writer(s), editor(s), and an explanation of your role in the process. If you can't share work samples, please write two topics: a concept and a procedure. They do not have to be extensive. 250 words or less is fine.*

The sample that follows is from the documentation for an application used to perform language analysis on specialized forms of clinical content. The concepts involved are terms of art in computational linguistics. They are used in language services settings to assess both the readability the and the localization readiness of samples of content.

The documentation persona in this instance is an end-customer user or content owner.

## Lexical density


**Lexical density** - Lexical density is a measurement of the complexity of your content. It expresses the proportion of lexical items to the size of the text as a whole. It is given by:

$$
L_d = \frac{N_l}{N} \times 100
$$

where

$L_d$ is the lexical density of the text, expressed as a percentage;
$N_l$ is the number of lexical items. Lexical items are meaningful terms like nouns, verbs and adjectives;
$N$ is the total number of words, including both lexical and grammatical items. Grammatical items are words or lexemes (word components) that connect meaningful terms to form clauses or sentences.

### Adding lexical density to an analysis job

**Note**: As a core text property, lexical density is included by default in many analysis job templates.

1. In **Analysis Workbench**, open **My analysis jobs**.
2. Select **New job**.
3. Select the **Language Properties** tab.
4. Using the **Select Language Properties** tree control, expand the **Complexity** branch and ensure that **Lexical density** is checked.

### Interpreting lexical density scores

Language complexity is an active area of research, and many approaches are taken to defining and measuring it. 

Higher lexical density scores tend to correlate with higher reading difficulty, but you should bear the following


---
## References

