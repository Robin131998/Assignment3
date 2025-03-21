## Name:Robinjit kaur  

## Student ID:8867197
 
# AI Training Data Project Documentation

Functional Requirements
--
### Requirements_1
### Description: 
The system shall automatically sort questions into distinct categories to help developers quickly locate relevant training data.

### Assumptions:

- Categorizing questions will save developers time in finding specific training data.
- Developers rely on automated categorization for faster workflow.


### Validation Plan:

- Verify that the system categorizes questions based on predefined tags.
- Conduct tests to ensure the categorization process is accurate and complete.

###  Tasks:

- [ ]  Define and finalize category schemas (e.g., by topic or type).
- [ ]  Develop an algorithm to sort questions into categories automatically.
- [ ] Test the algorithm using sample datasets to ensure accuracy.


### Requirements_2
### Description: 
The system shall allow developers to test their knowledge without immediately displaying answers, supporting self-assessment and reinforcement of learning.

### Assumptions:

- Delayed access to answers will encourage developers to actively engage in self-assessment.
- Developers prefer a self-paced testing experience.

### Validation Plan:

- Test whether answers are only displayed after user confirmation.
- Gather feedback from developers to confirm this improves their learning process.

### Tasks:

- [ ]  Develop a user interface that hides answers initially.
- [ ] Implement a confirmation mechanism to reveal answers when requested.
- [ ] Test the self-testing functionality with a user sample.

### Requirements_3
### Description: 
The system shall enable tagging of questions with metadata such as topics (e.g., "Machine Learning") and difficulty levels (e.g., "Beginner") for effective searching and filtering.

### Assumptions:

- Tagged questions will simplify search and filter processes for developers.
- Developers rely on predefined metadata to locate relevant questions efficiently.

### Validation Plan:

- Test the tagging system to ensure that all questions can be tagged appropriately.
- Verify that filters retrieve the correct set of tagged questions.

### Tasks:

- [ ]  Create a tagging framework to define tags such as "topic" and "difficulty level."
- [ ]  Develop functionality to apply tags to questions.
- [ ]  Implement a search and filter feature based on tags.

### Requirements_4
### Description:
 The system shall analyze data for biases and automatically correct any imbalances to ensure fair and diverse training datasets.

### Assumptions:

- Biased data negatively impacts AI model fairness and accuracy.
- Developers will rely on the system’s automated corrections to produce balanced datasets.

### Validation Plan:

- Test whether the bias detection system correctly identifies and highlights biases in datasets.
- Verify the functionality of the automated correction process with imbalanced datasets.

### Tasks:

- [ ]  Develop algorithms to detect bias metrics (e.g., demographic representation, topic overrepresentation).
- [ ]  Implement functionality to apply automatic corrections to biased data.
- [ ] Test the bias correction system using real-world datasets.
