# ds-5230-final-prigect
## Unsupervised Word-level Association and Text Clustering
Zhewen Zhang, Hongyang Wang, Zhengyan Shi. 
### Description
Using Apriori to build Association Rules

Using kmeans to do Clustering Analysis

Building Latent Semantic Indexing model

Building Hierarchical Dirichlet Process model

Building Latent Dirichlet Allocation model
### Data
Our dataset is Lee Background Corpus. The text corpus evaluated by human judges contained 50 documents selected from the Australian Broadcasting Corporation’s news mail service, which provides text emails of headline stories. The documents varied in length from 51 to 126 words and covered several broad topics.
### Association Rules
In this step we decided to use R to calculate association rules. Because using R to calculate the society rules is much simpler than using Python. In R, we use the "read.transactions" function to read a text file exported from Python. Separate each sentence with a space to get each word. for example, “[1] {bushfire, forced, highlands, hill, homes, huge, hundreds, new, people, pushed, south, southern, strong, today, top, towards, town, vacation, wales, winds}”.
### K-means
In this section, we first utilize the Silhouette Scores to make estimation on the best clustering numbers. As shown in the outcomes, the final appropriate cluster number turn out to be 2. After setting the cluster numbers in the K-means clustering models, we finally obtained the specific figure demonstrating the performance of the Clustering methods.
### LSI
LSI is a mathematical implementation which helps classify and retrieve information on key phrases and concepts. The method to decompose the original matrix is to find out the eigenvector and use singular vector decomposition to simplify the representation by number of dimensions.
### LDA
Latent Dirichlet allocation (LDA) is a generative statistical model that allows observations to be explained by unobserved groups.
### HDP
HDP (short for Hierarchical Dirichlet Process) is actually an extension to the normal Latent Dirichlet Allocation according to its so-called hierarchical attributes. Specifically, it is a nonparametric Bayesian approach to clustering grouped data.
