[prod_name]: ContentLab
# Lexical density

Lexical density is a measurement of the complexity of a language sample. It is commonly expressed as the proportion of lexical units (content words) either to functional units (grammatical words) or to higher-level structures such as sentences and clauses. The latter method is the one implemented by [prod_name].

$$
L_d = \frac{N_l}{N_h} \times 100
$$

where:

- $L_d$ is the lexical density of the text, expressed as a percentage;
- $N_l$ is the number of lexical items or content words;
- $N_h$ is the number of clauses or sentences.




### Adding lexical density to an analysis job

[!Note]: Languages encode complexity in many ways, and i

1. In **Analysis Workbench**, open **My analysis jobs**.
2. Select **New job**.
3. Select the **Language Properties** tab.
4. Using the **Select Language Properties** tree control, expand the **Complexity** branch and ensure that **Lexical density** is checked.

### Interpreting lexical density scores

Language complexity is an active area of research, and many approaches are taken to defining and measuring it. 

Higher lexical density scores tend to correlate with higher reading difficulty, but you should bear the following
