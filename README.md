Named Entity Disambiguation (NED) refers to the process of resolving ambiguity in entity recognition, specifically when multiple entities share the same name. The goal is to correctly identify and link the named entity (person, location, organization, etc.) to its unique identifier in a knowledge base or database, avoiding confusion between similarly named entities.

For example, if "Apple" is mentioned, NED ensures the system knows whether "Apple" refers to the fruit or the technology company.

### Key Steps in NED:
1. Named Entity Recognition (NER): Identify potential entities within a text (e.g., "Apple", "Paris").
2. Candidate Generation: List all possible entities that match the ambiguous name (e.g., "Apple Inc.", "apple fruit").
3. Contextual Analysis: Use surrounding text and domain knowledge to determine which entity is most likely intended (e.g., "Apple's latest iPhone" refers to the company, not the fruit).
4. Disambiguation: Select the correct entity based on context, similarity, or other criteria.
