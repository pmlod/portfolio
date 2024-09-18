# Lexical density

Lexical density is a measurement of the complexity of a language sample, expressed as the proportion of lexical units (content words) either to functional units (grammatical words) or to higher-level structures such as sentences and clauses. It is given by:

$$
L_d = \frac{N_l}{N_h} \times 100
$$

where:

- $L_d$ is the lexical density of the text, expressed as a percentage;
- $N_l$ is the number of lexical items or content words;
- $N_h$ is the number of clauses or sentences.

## Considerations

Lexical density scores have been shown to correlate well with widely used reading proficiency measures, making them useful in assessing the relative difficulty of a text. However, they represent only one dimension of complexity and make no distinction between "easy" and "difficult" content words. Consider the following examples.

> The occasional administration of dopaminergic nutrients is indicated in all domesticated canines.

> All dogs are good dogs who deserve tasty treats.

The second sentence has a higher lexical density (69%) than the first (62%), even though the content words it contains are all common vocabulary items.


## Adding lexical density to an analysis job

1. In **Analysis Workbench**, open **My analysis jobs**.
2. Click **New analysis job** or **Load analysis job**.
3. Select the **Language Properties** tab.
4. Using the **Select Language Properties** tree control, expand the **Complexity** branch and ensure that **Lexical density** is checked.
5. Click **Save analysis job**.

## See also

- [Lexical diversity](Lexical%20diversity.md)

