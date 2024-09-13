# Lexical density

Lexical density is a measurement of the complexity of a language sample. It is commonly expressed as the proportion of lexical units (content words) either to functional units (grammatical words) or to higher-level structures such as sentences and clauses. The latter method is the one implemented by ContentLab.

## Considerations

As with all content characteristics, measurements of language complexity should be interpreted with due regard to the context and the intended audience for your content. 

Lexical density measurements do not discriminate between "easy" and "difficult" content words. In the same way, common grammatical units can be combined to constructions that may be challenging for some readers. Consider the following example:

>Hyaluronic acid is a carbohydrate polymer found in the extracellular matrices of animals.

>Never forget that all dogs are good dogs who deserve tasty treats.

The lexical density of the first example is 69%, whereas the second yields a score of 77%. However, the latter result would be misleading if interpreted in isolation, since the content words in the sample are all common vocabulary items. 

$$
L_d = \frac{N_lex}{N} \times 100
$$

where:

- $L_d$ is the lexical density of the text, expressed as a percentage;
- $N_l$ is the number of lexical items. Lexical items are meaningful terms like nouns, verbs and adjectives;
- $N$ is the total number of words, including both lexical and grammatical items. Grammatical items are words or lexemes (word components) that connect meaningful terms to form clauses or sentences.

### Adding lexical density to an analysis job

[!Note]: Languages encode complexity in many ways, and i

1. In **Analysis Workbench**, open **My analysis jobs**.
2. Select **New job**.
3. Select the **Language Properties** tab.
4. Using the **Select Language Properties** tree control, expand the **Complexity** branch and ensure that **Lexical density** is checked.

### Interpreting lexical density scores

Language complexity is an active area of research, and many approaches are taken to defining and measuring it. 

Higher lexical density scores tend to correlate with higher reading difficulty, but you should bear the following
