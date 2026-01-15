
# Log Classification With Hybrid Classification Framework

This project develops a hybrid log classification system that integrates three complementary techniques to address varying levels of log pattern complexity. By combining rule-based, machine learning, and LLM-driven approaches, the system ensures robust and flexible classification across predictable, complex, and sparsely labeled log data.

---

## Classification Approaches

1. **Regular Expression (Regex)**:
   - Designed for simple and predictable log patterns.
   - Effective for rule-based classification using predefined pattern matching.

3. **Sentence Transformer + Logistic Regression**:
   - Applied to complex log patterns when sufficient labeled data is available.
   - Leverages semantic embeddings from Sentence Transformers, with Logistic Regression serving as the classification model.

4. **LLM (Large Language Models)**:
   - Used for complex scenarios with limited or poorly labeled training data.
   - Acts as a fallback or complementary method to enhance overall classification coverage
