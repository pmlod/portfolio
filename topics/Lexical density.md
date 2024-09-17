# Lexical density

Lexical density is a measurement of the complexity of a language sample. It is commonly expressed as the proportion of lexical units (content words) either to functional units (grammatical words) or to higher-level structures such as sentences and clauses.

The latter method is the one implemented by ContentLab, with lexical density given by:

$$
L_d = \frac{N_l}{N_h} \times 100
$$

where:

- $L_d$ is the lexical density of the text, expressed as a percentage;
- $N_l$ is the number of lexical items or content words;
- $N_h$ is the number of clauses or sentences.


## Considerations

As with all content characteristics, measurements of language complexity should be interpreted with due regard to the context and the intended audience for your content. 

Lexical density measurements do not discriminate between "easy" and "difficult" content words. In the same way, common grammatical units can be combined to constructions that may be challenging for some readers. Consider the following examples:

>Occasional administration of dopaminergic nutrients is indicated in all domesticated canines.

>All dogs are good dogs who deserve tasty treats.

The second sample has a higher lexical density (78%) than the first (72%), though the content words it contains are all common items of vocubulary.


### Adding lexical density to an analysis job

1. In **Analysis Workbench**, open **My analysis jobs**.
2. Select **New job**.
3. Select the **Language Properties** tab.
4. Using the **Select Language Properties** tree control, expand the **Complexity** branch and ensure that **Lexical density** is checked.

