The graph has the following 4 types of nodes:

1. **Concept**: The first major function of the graph is to get the user familiarized with the key concepts
of a field, with the objective
of further building up on them. There is no attempt to attach any formalism to the usage of the word concept.
The intention is to capture the common vocabulary of the field. The graph connects concepts to publications
in which they were introduced for the first time, grounding into real space and time, concepts which are otherwise very abstract. Concepts are also connected to publications that rely on them. This very naturally provides
us an indication of which existing concepts were combined to form new ones.

2. **Publication**: The second major function of the graph is to help shortlist the publications one needs to
review. Hence, the concepts point directly to their source.
3. **Author**: Getting hold of the author is almost always more delightful than getting hold of their
publications. The graph also attempts to pin down the right attribution for the concepts mentioned.
4. **Question**: Frequently the authors mention multiple lines of inquiry that they wish should follow their work.
More often than not, those lines are picked up by other researchers to take our knowledge forward.

#### Types of relationships

Author -> wrote -> Publication

Publication -> introduced -> Concept

Concept -> usedin -> publication

Publication -> introduced -> question

Question -> addressedby -> publication
