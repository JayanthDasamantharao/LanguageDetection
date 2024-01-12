# LanguageDetection

The project focuses on Language Identification (LI), categorizing text snippets into various languages.
A structured methodology covers data collection, preprocessing, feature extraction, model development, training, and evaluation.

The project categorizes into three distinct language cases based on similarities: diverse languages, European languages, and languages with shared dialects.

## Challenges and Shifts:
Initial aims included working on varied languages, but complexities led to a focus on similar languages.
Shifts occurred due to data availability challenges, leading to a focus on languages with akin dialects.

## Three Distinct Cases:
First case: Identifying diverse languages crucial for global communication.
Second case: Differentiating languages sharing the Roman script (mainly European languages).
Third case: Identifying languages with similar dialects, emphasizing subtle linguistic variations.

## Baseline Models:
Multinomial Naive Bayes and Logistic Regression served as foundational models.
DistilBERT, a transformer-based model, was integrated for advanced analysis.

## Methodology Highlights:
Systematic data preprocessing included noise removal, lowercasing, and tokenization.
Text vectorization involved generating N-grams and applying TF-IDF for nuanced feature representation.

## Model Selection:
Multinomial Naive Bayes and Logistic Regression were chosen for their effectiveness with categorical data.
DistilBERT was integrated for its advanced transformer-based architecture.

## Performance Evaluation:
Baseline models (Naive Bayes and Logistic Regression) demonstrated effectiveness in language identification.
Logistic Regression consistently outperformed Naive Bayes in precision, recall, and accuracy.
DistilBERT surpassed baseline models in terms of precision, recall, and accuracy.

## Challenges and Insights:
Challenges in differentiating languages with shared scripts and linguistic roots.
Importance of character-level N-grams over word-level N-grams for accurate language differentiation.

## Project Structure:
Three distinct cases showcased the effectiveness of models across diverse language attributes.
Integration of advanced models like DistilBERT demonstrated improved accuracy.

## Conclusion:
The project illuminated diverse challenges associated with different language sets.
The addition of DistilBERT emphasized the dynamic nature of language processing.
