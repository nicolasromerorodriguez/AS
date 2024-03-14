**Workshop Inform - Systems Analysis Course**

**Introduction:**
In this workshop, we will explore a biological exercise that involves analyzing genomic data to identify patterns called motifs. The goal is to create a dummy database of genetic sequences, extract motifs of sizes 6 and 8, filter sequences based on Shannon Entropy, and then re-extract motifs, there wib be some conclusions and commentary on the procces



**Conclusions:**
- The initial dataset contained 50 genetic sequences, each with a length between 10 and 20 bases.

- After filtering the sequences based on Shannon Entropy with a threshold of 1.5, the dataset size decreased, indicating that some sequences were removed due to low variance.

- The motifs of sizes 6 and 8 were then extracted from the filtered dataset. The motifs were chosen based on their occurrence frequency in the dataset.

- The motifs of size 6 and 8 obtained after filtering showed different patterns compared to the motifs extracted from the original dataset. This suggests that the filtering process affected the composition of the motifs.

**Technical Concerns/Decisions/Difficulties:**

-The biggest limitation of this workshhop was time, because of this the code, and this inform does not contain the level of depth i would desire.

- One potential improvement could be to optimize the algorithm for motif extraction to handle larger datasets more efficiently.
- It's important to note that the Shannon Entropy threshold of 1.5 was arbitrarily chosen by a quick search in wikipedia and may not be the most optimal pick.

In conclusion, this workshop provided a hands-on experience in analyzing genomic data and extracting motifs using Shannon Entropy. It also highlighted the importance of data preprocessing and parameter tuning in bioinformatics analysis.