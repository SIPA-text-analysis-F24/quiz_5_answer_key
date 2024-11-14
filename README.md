### TF-IDF 

1. **What does TF-IDF stand for?**
   - A) Term Factor - Information Density Factor
   - B) Term Frequency - Inverse Document Frequency
   - C) Text Frequency - Inverse Density Factor
   - D) Term Formation - Inner Density Factor  
   *Answer: B*

2. **In TF-IDF, "Term Frequency" (TF) measures:**
   - A) The length of a document
   - B) How many documents contain the term
   - C) How often a term appears in a document
   - D) The importance of a term across all documents  
   *Answer: C*

3. **What does a high IDF score indicate about a term in a policy document dataset?**
   - A) It appears frequently in many documents
   - B) It has no special significance
   - C) It is rare across all documents
   - D) It is common across all documents  
   *Answer: C*

4. **Why might common words like "government" or "policy" have low TF-IDF scores in a public policy dataset?**
   - A) They only appear in one document
   - B) They have low IDF scores because they appear in many documents
   - C) They are removed during text processing
   - D) They have high IDF scores but low TF scores  
   *Answer: B*

5. **If a word appears in nearly every policy document, its TF-IDF score will likely be:**
   - A) Very low
   - B) Very high
   - C) Unaffected by IDF
   - D) Exactly 1  
   *Answer: A*

6. **Which of the following best describes a potential use of TF-IDF in policy analysis?**
   - A) Summarizing policy documents
   - B) Calculating document length
   - C) Translating policy documents into multiple languages
   - D) Identifying the most relevant topics in a set of policy documents  
   *Answer: D*

7. **A word with a high TF but low IDF score in a public policy corpus implies that:**
   - A) The word is common across documents and may not reveal unique information
   - B) The word is important across all documents
   - C) The word is rare and significant for specific policies
   - D) The word does not appear in any other document  
   *Answer: A*

8. **TF-IDF helps in identifying:**
   - A) Only the longest words in a document
   - B) Sentiment in policy documents
   - C) The most relevant terms across documents by weighing their uniqueness
   - D) Only uncommon terms across policy documents  
   *Answer: C*

9. **If a word appears only once in one document and nowhere else in the dataset, its TF-IDF score is likely:**
   - A) Zero
   - B) High
   - C) Low
   - D) Negative  
   *Answer: B*

10. **TF-IDF could assist public policy researchers by:**
    - A) Filtering out common terms to focus on unique terminology
    - B) Highlighting only governmental organizations mentioned in policies
    - C) Counting all nouns in the document
    - D) Creating translations for policy terminology  
   *Answer: A*

### Named Entity Recognition (NER) 

11. **What is Named Entity Recognition (NER) primarily used for in policy analysis?**
    - A) Identifying specific names, places, organizations, and dates in policy text
    - B) Calculating the frequency of terms in policy documents
    - C) Recognizing abstract ideas in a policy
    - D) Summarizing policy documents  
   *Answer: A*

12. **Which of these would be recognized as a named entity by an NER system in policy analysis?**
    - A) Emotions
    - B) Organizations, Locations, Key Individuals
    - C) Adjectives
    - D) Article words like "a" and "the"  
   *Answer: B*

13. **What’s the main difference between a named entity and a regular noun in policy text?**
    - A) Named entities are always capitalized
    - B) Named entities represent specific names, places, or organizations relevant to the policy
    - C) Named entities only include locations
    - D) Regular nouns are used exclusively in technical writing  
   *Answer: B*

14. **How can NER be applied in analyzing policy documents?**
    - A) By summarizing policy sentiment
    - B) By translating documents into different languages
    - C) By identifying key stakeholders, locations, and dates mentioned in policy texts
    - D) By identifying only legal terms  
   *Answer: C*

15. **If an NER system mistakenly labels the name of a legislative body as a location, this is an example of:**
    - A) Misclassification
    - B) Overfitting
    - C) Clustering
    - D) Proper classification  
   *Answer: A*

16. **A major challenge in using NER on government policy documents is:**
    - A) Only people’s names are considered entities
    - B) Names of organizations and locations can be similar and require contextual understanding
    - C) It is impossible to distinguish organizations from general nouns
    - D) NER systems ignore titles by default  
   *Answer: B*

17. **NER can improve the analysis of policy documents by:**
    - A) Ignoring all pronouns and common nouns
    - B) Reducing document length for analysis
    - C) Categorizing names of institutions, people, and places for more targeted analysis
    - D) Removing all irrelevant data from documents  
   *Answer: C*

18. **Why might distinguishing between "Washington" as a location versus as a person or institution be challenging for NER in policy texts?**
    - A) Only names of organizations are detected
    - B) "Washington" can represent multiple types of entities depending on context
    - C) "Washington" is only a location in policy documents
    - D) NER systems ignore all place names  
   *Answer: B*

19. **Why is context crucial for NER when analyzing policy documents?**
    - A) It helps NER determine the type of each entity correctly
    - B) It translates entities into multiple languages
    - C) It only affects punctuation detection
    - D) It allows NER to calculate document length  
   *Answer: A*

20. **NER may struggle with newly introduced entities in policy documents (e.g., new agencies) because:**
    - A) They are spelled incorrectly
    - B) They might not be part of the system’s training data
    - C) They are too similar to pronouns
    - D) They are always ignored by NER  
   *Answer: B*
