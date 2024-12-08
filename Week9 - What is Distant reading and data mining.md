## Definitions


## Week Overview
Ever since the concept was first devised by Franco Moretti, the term ‘distant reading’ has come to be associated with the differences between the digital humanities and its analogue predecessors.  This week we will dig into the analysis side of the distant reading paradigm, exploring a number of the approaches and technologies that form a part of the distant reading canon.  Key concepts include natural language processing (NLP),  advanced programming interfaces (APIs), named entity extraction (NER), statistical modelling, stylometry, open notebooks, machine learning, cultural informatics, neural networks, corpora.



## Sources
- ### Mandatory 
- **REQUIRED READING, RESEARCH ARTICLES:**

1. Moretti, F. (2000) Conjectures on World Literature.  New Left Review 1. [https://newleftreview.org/issues/II1/articles/franco-moretti-conjectures-on-world-literature](https://newleftreview.org/issues/II1/articles/franco-moretti-conjectures-on-world-literature)
2. Blanke et. al. (2020) Understanding memories of the Holocaust – A new approach to neural networks in the digital humanities.  Digital Scholarship in the Humanities 35.1 (see PDF linked above)

**REQUIRED MATERIALS TO PREPARE:**

1. Above you will find a link to this book: Jockers, M. (2014) Text Analysis with R for Students of Literature. Springer.  Jockers worked closely with Franco Moretti at Stanford throughout the 2000s, and would have delivered a lot of the coded realities behind Moretti's big ideas. This book is one of two published out of that time, the other (Macroanalysis: Digital Methods and Literary History) is much more focus on literary insights than methods.  **Don't try to read this**, but skim through the chapters to get a sense of what Jockers does with R, the kinds of questions he can answer, the methods he uses.
2. For a good computational project, you need three things: a HOW (=methods, such as Jockers describes in his book); a WHAT (= some sort of research corpus, like historical newspapers, parliamentary debates, or any other dataset) and a WHY (=your research question).  Take a look at this blog post to see if you can start to develop an understanding of this last element: Underwood, T. (2015) Seven ways humanists are using computers to understand texts, Ted Underwood, [http://sites.nd.edu/digitalhistory/files/2017/02/Underwood_Seven-Ways-Humanists_.pdf](http://sites.nd.edu/digitalhistory/files/2017/02/Underwood_Seven-Ways-Humanists_.pdf)
		
- ### Further 



### Discussion Questions
What makes for a good digital humanities research question? How do the various approaches to distant reading differ?  What preconditions do we need to meet to make distant reading a productive and robust approach?  What does Moretti think the problems are inherent in big literary questions, and what solutions does he propose?  What conclusions does he come to about the question of world literature?  What kind of approach do Blanke, Bryant and Hedges use, and why?  What do you make of their results?

## Notes

**Franco Moretti** argues against the limitations of comparative literature's focus on Western Europe and advocates for a "distant reading" approach that analyzes large datasets to identify patterns and systems across diverse literatures. He uses the diffusion of the novel as a case study, demonstrating how Western forms interacted with local materials in different ways depending on the global literary system's power dynamics. The second source details a study using neural networks to analyze Holocaust survivor testimonies. **Blanke, Bryant, and Hedges** address the scarcity of labeled data in digital humanities by employing "distant supervision," combining supervised and unsupervised sentiment analysis to classify memories as positive or negative. They utilize various computational semantics techniques to interpret the neural network's findings and explore the complex interplay of sentiments within the testimonies. The final source is a PDF document with an unclear title and contents; only instructions on printing the file are present.

### Seven ways humanists are using computers to understand text. - Ted Underwood

The blog post discusses how **humanists are using computers to understand text** in a way that bridges connections to social science through computational methods. This interdisciplinary approach allows for the exploration of **research questions** that may not have been possible before due to the limitations of traditional methods.

- The post outlines **seven ways humanists are using computers to understand text**, including identifying distinctive vocabulary, finding and organizing works, modeling literary forms and genres, modeling social boundaries, and unsupervised modeling.
- Each of these methods presents opportunities for **framing research questions**. For instance, one could investigate how word frequencies change over time, how literary forms evolve, or how social boundaries are reflected in text.
- The post emphasizes the importance of **modeling** in computational text analysis. Models can help researchers identify patterns, explain concepts, and make predictions about text.
- The choice of **research question** will often determine the type of model used.

For example, if the **research question** involves understanding the difference between two genres, a supervised model could be used to identify the features that distinguish them. On the other hand, if the **research question** is more exploratory, an unsupervised model like topic modeling could be used to discover patterns in a collection of texts.

The blog post highlights the potential of computational methods to **transform the humanities** by providing new ways to understand text and answer research questions. The post also emphasizes that these methods require careful consideration of the assumptions underpinning them and the potential for overfitting data. By understanding these issues, researchers can use computational methods to generate insightful and meaningful results.

Computational methods bridge humanities and social sciences by facilitating the application of quantitative models, traditionally used in social sciences, to the analysis of textual data prevalent in the humanities. This bridge is built upon the increasing ability to represent unstructured text, such as written documents, in a statistical model.

- Historically, the quantitative models employed by social scientists to understand social phenomena did not contribute significantly to the humanities. This was due to the difficulty in connecting these models to the nuanced and less structured evidence provided by written texts.
- However, with the advent of new methods that enable the representation of unstructured text within statistical models, both social scientists and humanists can now explore shared research questions. For instance, questions about authorship, theme, genre, and intended audience, which are traditionally humanistic concerns, can now be addressed using quantitative methods informed by social science.
- The blog post emphasizes the concept of **modeling** as a central aspect of this interdisciplinary bridge. Models, often expressed as equations in social science, help describe the likelihood of an association between variables. In the context of text analysis, these variables can represent features extracted from the text, such as word frequencies or syntactic patterns.
- The purpose of modeling can be twofold: **explanation** and **prediction**. Models can help explain concepts by identifying the features that distinguish them. For example, a model could be built to identify the defining characteristics of a specific literary genre.
- Alternatively, models can be used for prediction, such as identifying instances of a genre within a large collection of texts. The choice between explaining and predicting depends on the specific research question.
- The blog post also highlights the potential of computational methods to go beyond traditional humanistic inquiries. Statistical models can be applied to understand social boundaries reflected in text. For example, by training models to distinguish between texts published in different social contexts, researchers can investigate the evolution of social norms and distinctions.
- The application of computational methods in the humanities presents both opportunities and challenges. Researchers need to carefully consider the assumptions underlying the chosen methods and address the potential for overfitting data. Additionally, the use of these methods may require a level of technical expertise in data analysis and programming that is not traditionally part of humanities training.

In conclusion, computational methods are bridging the gap between humanities and social sciences by providing tools to analyze textual data in a quantitative manner. This interdisciplinary approach allows researchers to address shared questions and explore new avenues of inquiry, enriching our understanding of both the human experience and the social world.

### Limitations of "Bags of Words" Models

While "bags of words" models can be useful for tasks like identifying distinctive vocabulary or modeling literary genres, they have inherent limitations stemming from their simplified representation of text.

- **Ignoring Word Order and Syntax**: As the name suggests, "bags of words" models treat text as a collection of individual words, disregarding the order in which they appear and the grammatical relationships between them. This approach overlooks the crucial role that syntax plays in conveying meaning. For example, the sentences "The dog bit the man" and "The man bit the dog" would be considered identical by a "bags of words" model, even though their meanings are completely different.
    
- **Lack of Semantic Understanding**: "Bags of words" models focus on word frequencies, neglecting the deeper semantic relationships between words. They cannot capture the nuances of meaning conveyed by synonyms, metaphors, or irony. For instance, the model would not understand that "happy" and "joyful" convey similar sentiments, or that "fire" can have both literal and metaphorical meanings.
    
- **Inability to Capture Context**: By treating words in isolation, "bags of words" models fail to consider the broader context in which they appear. The meaning of a word can change drastically depending on the surrounding words and the overall topic of the text. For example, the word "bank" can refer to a financial institution or a riverbank, and the model would not be able to distinguish between these two meanings without considering the context.
    
- **Limited Understanding of Literary Devices**: Many literary devices, such as metaphors, similes, and allusions, rely on the interplay between word meaning and context. "Bags of words" models, with their focus on individual word frequencies, are ill-equipped to analyze the complexities of these devices.
    

Because of these limitations, "bags of words" models are better suited for tasks that focus on surface-level features of text, such as identifying distinctive vocabulary or broadly categorizing texts into genres. For research questions that require a deeper understanding of meaning, context, and literary devices, more sophisticated computational methods that incorporate syntactic and semantic information are necessary.

### Distant Reading in the Sources

Franco Moretti, in source, advocates for **distant reading** as a necessary approach to tackle the vast and complex problem of **world literature**. He argues that traditional methods of close reading, while valuable, are inadequate for addressing the sheer volume and diversity of texts in a global literary system.

Moretti proposes a **"pact with the devil,"** urging scholars to **"learn how not to read"** in the conventional sense. Instead, he suggests focusing on units of analysis that are either much smaller (devices, themes, tropes) or much larger (genres, systems) than the individual text. This shift in perspective, enabled by computational methods, allows researchers to identify patterns and connections that would otherwise remain hidden.

The article on "Neural Networks Holocaust" in source provides a concrete example of distant reading applied to oral history testimonies of Holocaust survivors. The researchers use **Recurrent Neural Networks (RNNs)** to analyze sentiments in these testimonies, developing a model that outperforms traditional dictionary-based sentiment analysis methods. This study demonstrates how distant reading can be used to gain insights into complex historical experiences and uncover patterns in large collections of personal narratives.

The blog post in source outlines various ways in which humanists are using computers to understand text. The author emphasizes the role of **modeling** in bridging the gap between humanities and social sciences. By representing textual data in statistical models, researchers can apply quantitative methods to explore traditionally humanistic concerns, such as genre, authorship, and social boundaries.

### Limitations of Distant Reading

While distant reading offers exciting new possibilities for literary analysis, it is important to acknowledge its limitations, some of which we have discussed. For instance, the reliance on **"bags of words"** models, which disregard word order and syntax, can lead to misinterpretations. As noted in our conversation history, these models lack semantic understanding and fail to capture the nuances of meaning conveyed by literary devices or contextual variations.

Furthermore, distant reading should not be seen as a replacement for close reading. Rather, the two approaches can complement each other, providing different but valuable perspectives on literary texts and their contexts. Distant reading can help identify broad trends and patterns, guiding closer examination of specific works or passages. Close reading, in turn, can provide nuanced interpretations that inform the development and refinement of computational models.
### Distant Reading vs. Close Reading: A Summary

**Distant reading**, as discussed in the sources, is a computational approach to literary analysis that uses computer algorithms to process large amounts of textual data and identify patterns that may not be easily discernible through traditional methods of close reading. This approach relies on **modeling** techniques, which involve creating simplified representations of complex phenomena using statistical methods.

**Close reading**, on the other hand, is a more traditional method of literary analysis that involves meticulous examination of individual texts, focusing on elements like language, imagery, and structure to develop nuanced interpretations.

#### Key Differences:

- **Scope**: Distant reading operates on a larger scale, examining patterns across extensive collections of texts. Close reading, in contrast, is typically limited to the detailed analysis of individual works or passages.
- **Methods**: Distant reading employs computational tools and statistical models to process textual data, while close reading relies on the interpretive skills and close attention of the human reader.
- **Focus**: Distant reading seeks to uncover large-scale trends and patterns in literary history, genre, or social contexts, while close reading aims to develop deep and nuanced interpretations of individual texts.
- **Objectives**: Distant reading often aims to test hypotheses or build predictive models, while close reading typically focuses on generating interpretive insights.

### Generating Additional Training Data: A Distant Supervision Approach

The researchers in the source "Neural Networks Holocaust" faced a common challenge in the digital humanities: a lack of large, annotated training datasets for supervised machine learning. To overcome this obstacle, they employed a technique called **distant supervision** to generate additional training data for their sentiment analysis model, which focused on Holocaust testimonies.

Here's a step-by-step breakdown of their process:

1. **Initial Sentiment Scoring Using a Dictionary-Based Method**:
    
    - They began by applying a standard **dictionary-based sentiment analysis** to a corpus of Holocaust testimonies. This method relies on a pre-existing lexicon of words tagged with their associated positive or negative sentiment.
    - To create manageable units of analysis, the researchers split the testimonies into segments of 500 words each.
    - By analyzing the presence and frequency of positive and negative words within each segment, they derived an initial sentiment score.
2. **Selecting the Most Extreme Examples**:
    
    - Recognizing that the Holocaust testimonies would inherently lean towards negative sentiment, the researchers focused on identifying the most extreme examples to create a balanced training dataset.
    - They selected the **25% of segments with the most negative scores** and the **25% of segments with the most positive scores**, based on the dictionary-based analysis. This resulted in a training set with roughly equal numbers of positive and negative examples.
3. **Generating New Text Using RNNs**:
    
    - This is where the **"distant supervision"** aspect comes in. Instead of relying solely on human-annotated data, which is time-consuming and expensive to produce, the researchers used **Recurrent Neural Networks (RNNs)** to generate additional training data.
    - RNNs are particularly adept at learning patterns in sequential data, such as text. By training an RNN on the existing positive and negative segments, the researchers were able to generate **new text fragments** that exhibited similar linguistic characteristics.
    - They generated **8,000 new segments for each sentiment class** (positive and negative), resulting in a total of 16,000 artificially generated segments.
4. **Combining the Generated Data with the Original Training Set**:
    
    - The final step was to **combine these 16,000 generated segments** with the **original training set** derived from the dictionary-based analysis. This significantly expanded the training dataset, providing the RNN with more data to learn from and improve its accuracy.

The researchers note that this process of generating training data using RNNs was computationally expensive, taking approximately 10 hours on their hardware even for 16,000 segments. However, they believe that the benefits of having a larger, more diverse training set outweighed the computational costs.

By using this **"distant supervision"** approach, the researchers were able to leverage the power of RNNs to create a more robust and accurate sentiment analysis model, even in the absence of extensive human-annotated data. This method holds promise for future research in the digital humanities, particularly for analyzing large collections of texts where manual annotation is not feasible.

## Analyzing Sentiment in Holocaust Testimonies: A Blend of Distant and Close Reading

The sources offer valuable insights into the methods used to analyze sentiment in Holocaust testimonies, highlighting a combination of **distant reading techniques**, particularly those powered by artificial intelligence, and the importance of **qualitative interpretation**.

Source focuses specifically on a **new approach to using neural networks** for sentiment analysis in Holocaust testimonies. The authors address the challenge of limited annotated training collections in the digital humanities, proposing a method called **"distant supervision"**. This involves using a **dictionary-based sentiment analysis** to create a categorized corpus of testimonies, then selecting the most positive and negative examples to train a **Recurrent Neural Network (RNN)**.

**Key Steps in their methodology**:

1. **Initial Sentiment Analysis**: Applying a dictionary-based method to a corpus of Holocaust testimonies, split into 500-word segments, to get a preliminary sentiment score for each segment.
2. **Creating a Training Dataset**: Selecting the 25% most negative and 25% most positive segments based on the dictionary scores to create a training dataset for the RNN.
3. **Enhancing the Training Dataset**: Using RNNs to generate additional text fragments that exhibit either positive or negative sentiment, thus expanding the training dataset.
4. **Training the RNN**: Training the RNN on this enhanced dataset to learn the language patterns associated with positive and negative sentiment in Holocaust testimonies.
5. **Predictive Modeling**: Applying the trained RNN to the entire corpus of testimonies to predict the sentiment of each segment.
6. **Analyzing the Results**: Using computational semantic methods like chi-square analysis, word2vec, and topic modeling to understand the RNN's decisions and identify the key themes and word associations related to positive and negative sentiment.

The researchers found that this approach significantly outperformed the baseline dictionary-based method, achieving an accuracy of 97% in identifying the sentiment of manually labeled test segments. This demonstrates the potential of distant reading techniques, particularly RNNs, for analyzing sentiment in Holocaust testimonies.

### Combining Computational Analysis with Qualitative Understanding

While the computational analysis provides valuable insights, the authors emphasize the importance of combining these findings with **qualitative interpretation**. For example, they note that:

- The RNN tended to associate **family relations** with positive sentiment, even when these relations appeared in the context of negative experiences. This suggests that the model may have oversimplified the complexities of sentiment in these testimonies.
- Many **"positive" experiences** identified by the model were actually **"neutral"** in the context of the Holocaust. These were often memories of post-war life or experiences that, while difficult, paled in comparison to the atrocities of the Nazi regime.

These findings highlight the need for careful consideration of the context and nuances of individual testimonies when interpreting the results of computational sentiment analysis.

### The Role of Close Reading in Refining Sentiment Analysis

The limitations of purely computational approaches, as highlighted in our conversation history, underscore the continuing relevance of **close reading**. The researchers acknowledge that distant reading methods like "bags of words" models can overlook the crucial roles of **word order, syntax, and context in conveying meaning**.

Therefore, a comprehensive understanding of sentiment in Holocaust testimonies requires a **combination of distant and close reading**. Distant reading can identify broad patterns and trends, while close reading can provide the nuanced interpretation necessary to understand the complex emotions and individual experiences conveyed in these testimonies.

### Beyond Simple Positive/Negative Classification

Furthermore, the researchers' observation about the prevalence of "neutral" or "normal" experiences classified as positive by the RNN raises an important point: **sentiment analysis in Holocaust testimonies may need to move beyond a simple binary classification of positive/negative**. A more nuanced approach that considers the specific context and the spectrum of human emotions during and after the Holocaust is needed to fully capture the complexities of these narratives.

This study exemplifies how computational methods can be powerful tools for analyzing large collections of texts, particularly those dealing with sensitive and emotionally charged topics like the Holocaust. However, the study also emphasizes the importance of combining computational analysis with qualitative interpretation and the continued relevance of close reading for a complete understanding of sentiment and meaning.

