| | |
| -- | -- |
| Score range | Float [0-1]: higher means better quality. |
| What is this metric? | METEOR score measures the similarity by shared n-grams between the generated text and the ground truth, similar to the BLEU score, focusing on precision and recall. But it addresses limitations of other metrics like the BLEU score by considering synonyms, stemming, and paraphrasing for content alignment. |
| How does it work? | The METEOR score is calculated based on the harmonic mean of unigram precision and recall, with higher weight given to recall. It also incorporates additional features such as stemming (matching word roots), synonym matching, and a penalty for incorrect word order. The final score ranges from 0 to 1, where 1 indicates a perfect match. |
| When to use it? | The recommended scenario is Natural Language Processing (NLP) tasks. It addresses limitations of other metrics like BLEU by considering synonyms, stemming, and paraphrasing. METEOR score considers synonyms and word stems to more accurately capture meaning and language variations. In addition to machine translation and text summarization, paraphrase detection is a recommended use case for the METEOR score.  |
| What does it need as input? | Response, Ground Truth |
