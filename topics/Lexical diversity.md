# Lexical diversity

Lexical diversity is a measurement of the richness of vocabulary in a language sample. It is commonly expressed as the ratio of types (unique content words) to tokens (non-unique instances of a type). By definition, therefore, types cannot outnumber tokens and diversity and absolute diversity is constrained by sample size. For this reason, samples are typically normalized by "resampling" them into segments of equal length.

ContentLab uses a technique called Measure of Textual Lexical Diversity (MTLD), which continuously resamples a text until an arbitrary threshold is reached. By convention, this value is set at around 0.72 and represents the point at which diversity begins to level off. MTLD scores are given by:

$$
L_d = \frac{N_w}{N_s} 
$$

where:

- $L_d$ is the lexical diversity of the sample;
- $N_w$ is the number of sample windows tested before the type-token ration falls below the threshold.

## Considerations

MTLD measurements of lexical diversity have been shown to correlate well with common indices of reading proficiency, making them useful in assessing the relative difficulty of a sample text. However, the reliance of MTLD on arbitary samples sizes and thresholds has been criticised and it is susceptible to skewing caused by type repetition, outlying rarity, and other features.

## Adding lexical diversity to an analysis job

1. In the ContentLab dashboard, click **My analysis jobs**.
2. Click **New analysis job** or **Load analysis job**.
3. Select the **Language Properties** tab.
4. Using the **Select Language Properties** tree control, expand the **Language complexity** branch and ensure that **Lexical density** is checked.
5. Click **Save analysis job**.

