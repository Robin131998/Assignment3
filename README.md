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

### Requirements_5
### Description: 
The system shall immediately generate reports when biased data is detected, allowing developers to address and fix issues quickly.

### Assumptions:
- Prompt reporting of biased data helps developers respond to issues efficiently.
- Developers will use these reports to improve their datasets and address fairness concerns.

### Validation Plan:
- Verify that bias reports are generated in real-time when imbalances are detected.
- Test whether reports provide actionable insights to developers.

### Tasks:
- [ ]  Create a reporting system for bias metrics and imbalances.
- [ ]  Ensure real-time integration of the reporting system with data analysis tools.
- [ ]  Test the clarity and usability of generated reports.

System Requirements
--
### Requirements_1
Description: The system shall maintain an indexed structure to ensure quick and efficient retrieval of information.

### Assumptions:
Indexed structures will improve the speed of search and categorization processes.
Developers require instantaneous data retrieval for efficiency.

### Validation Plan:
Test the system’s search time for retrieving indexed information.
Verify that the indexed structure integrates well with search and filtering features.

### Tasks:

- [ ] Design and implement an indexed storage mechanism.
- [ ] Integrate the index with search and tagging functionality.
- [ ] Test the retrieval speed of the indexed data.

### Requirements_2
### Description:
The system shall only display answers after the user confirms their request, enabling self-testing.

### Assumptions:

- Developers benefit from delayed answer access for self-paced learning.
- This feature supports a more interactive learning process.


### Validation Plan:

- Test whether answers are only revealed when a user explicitly confirms.
- Gather user feedback to ensure this feature aligns with their needs.

### Tasks:

- [ ]  Implement a mechanism that hides answers by default.
- [ ]  Add a user confirmation button to reveal answers.
- [ ] Test the user experience with this functionality.

### Requirements_3
### Description: 
The system shall allow tagging of questions by topics and difficulty levels to simplify searching and filtering.

### Assumptions:

- Developers need a tagging system to organize and retrieve data efficiently.
- Effective filters rely on accurate tagging of metadata.


### Validation Plan:

- Test whether the tagging and filtering system retrieves data accurately.
- Validate the functionality with diverse question sets.

### Tasks:

- [ ] Develop a metadata schema for tags (e.g., topics, difficulty levels).
- [ ] Implement a tagging feature for developers to label questions.
- [ ] Create and test the search and filter functionality.

### Requirements_4
### Description: 
The system shall generate regular reports summarizing biases in data, allowing developers to monitor and address them effectively.

### Assumptions:

- Developers require periodic updates on data quality and fairness.
- Reports must provide actionable insights for developers.

### Validation Plan:

- Test the report generation system for accuracy and completeness.
- Verify that reports provide useful data summaries and visualizations.

### Tasks:

- [ ] Develop functionality to generate reports at predefined intervals.
- [ ] Include metrics like bias percentages and diversity distributions in reports.
- [ ] Test the report generation system using real-world datasets.

### Requirements_5
### Description:
 The system shall notify developers immediately when biased or imbalanced data is detected.

### Assumptions:

- Real-time notifications allow developers to act on issues without delay.
- Developers require clear, concise alerts for data imbalances.

### Validation Plan:

- Test whether the notification system alerts users promptly after detecting biases.
- Verify the clarity and content of notification messages.

### Tasks:

- [ ] Develop a notification system for real-time alerts.
- [ ] Integrate the notification system with the bias detection module.
- [ ] Test notifications for accuracy and delivery speed.
