# Lexical diversity

Lexical diversity is a measurement of the richness of vocabulary of a language sample. It can be calculated in various ways, but most approaches focus on the ratio of types (unique words or word components) to tokens (non-unique instances of a type). Since diversity is thus constrained by sample size, it is common for samples to be normalized by resampling a text in segments of equal length.

ContentLab uses a technique called Measure of Textual Lexical Diversity (MTLD), which continuously resamples a text until an arbitrary threshold is reached. This threshold value is typically set at around 0.72 and represents the point at which diversity begins to level off.

$$
L_d = \frac{N_w}{N_s} 
$$

where:

- $L_d$ is the lexical diversity of the sample;
- $N_w$ is the total number of words;
- $N_s$ is the number of sample windows tested before the type-token ration falls below the threshold.


## Adding lexical diversity to an analysis job

1. In the ContentLab dashboard, click on **My analysis jobs**.
2. Select **New job**.
3. Select the **Language Properties** tab.
4. Using the **Select Language Properties** tree control, expand the **Complexity** branch and ensure that **Lexical diversity** is checked.

## Interpreting lexical diversity scores

MTLD measurements of lexical diversity have been shown to correlate well with common indices of reading proficiency, making them useful in assessing the relative difficulty of a sample text. However, the reliance of MTLD on arbitary samples sizes and thresholds has been criticised and it is susceptible to skewing caused by type repetition, outlying rarity, and other features. You should interpret lexical diversity scores with due regard for the context and subject matter of your content.