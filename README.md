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

###  Actionable Tasks:
- [ ] Define and finalize category schemas, such as "Topic," "Difficulty Level," or "Question Type."
- [ ] Develop a sorting algorithm that uses metadata tags to group questions into categories.
- [ ] Test the algorithm using three sample datasets with diverse question types (target: 95% accuracy).
- [ ] Document categorization workflows for developers to easily adapt and apply

### Requirements_2
### Description: 
The system shall allow developers to test their knowledge without immediately displaying answers, supporting self-assessment and reinforcement of learning.

### Assumptions:
- Delayed access to answers will encourage developers to actively engage in self-assessment.
- Developers prefer a self-paced testing experience.

### Validation Plan:
- Test whether answers are only displayed after user confirmation.
- Gather feedback from developers to confirm this improves their learning process.

### Actionable Tasks:
- [ ] Design a user interface component that hides answers by default.
- [ ] Implement a "Reveal Answer" confirmation button.
- [ ] Test the functionality with 5-10 users and gather feedback through surveys.
- [ ] Revise the interface based on testing results and developer feedback.

### Requirements_3
### Description: 
The system shall enable tagging of questions with metadata such as topics (e.g., "Machine Learning") and difficulty levels (e.g., "Beginner") for effective searching and filtering.

### Assumptions:
- Tagged questions will simplify search and filter processes for developers.
- Developers rely on predefined metadata to locate relevant questions efficiently.

### Validation Plan:
- Test the tagging system to ensure that all questions can be tagged appropriately.
- Verify that filters retrieve the correct set of tagged questions.

### Actionable Tasks:
- [ ] Create a metadata schema for tags (e.g., "Topic," "Difficulty Level").
- [ ] Build functionality to apply tags to questions, ensuring ease of use for developers.
- [ ] Implement search and filter features and test them with diverse question sets.
- [ ] Create a tagging and filtering user guide for developers.

### Requirements_4
### Description:
 The system shall analyze data for biases and automatically correct any imbalances to ensure fair and diverse training datasets.

### Assumptions:
- Biased data negatively impacts AI model fairness and accuracy.
- Developers will rely on the system’s automated corrections to produce balanced datasets.

### Validation Plan:
- Test whether the bias detection system correctly identifies and highlights biases in datasets.
- Verify the functionality of the automated correction process with imbalanced datasets.

### Actionable Tasks:
- [ ] Develop an algorithm to detect biases, including metrics like demographic representation and topic overrepresentation.
- [ ] Implement automatic corrections to adjust biases in datasets.
- [ ] Test bias correction with real-world datasets and record improvements (target: 90% accuracy).
- [ ] Create a developer report summarizing detection and correction processes.

### Requirements_5
### Description: 
The system shall immediately generate reports when biased data is detected, allowing developers to address and fix issues quickly.

### Assumptions:
- Prompt reporting of biased data helps developers respond to issues efficiently.
- Developers will use these reports to improve their datasets and address fairness concerns.

### Validation Plan:
- Verify that bias reports are generated in real-time when imbalances are detected.
- Test whether reports provide actionable insights to developers.

### Actionable Tasks:
- [ ] Develop a reporting system that includes metrics like bias percentage and diversity distribution.
- [ ] Ensure real-time integration of the reporting system with data analysis tools.
- [ ] Test generated reports for clarity, usability, and accuracy.
- [ ] Provide documentation on interpreting and using reports effectively.

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

### Actionable Tasks:
- [ ] Design and implement an indexed storage mechanism.
- [ ] Integrate indexing with tagging and filtering functionality.
- [ ] Test retrieval speed with a large sample dataset.
- [ ] Document indexing workflows and ensure scalability.

### Requirements_2
### Description:
The system shall only display answers after the user confirms their request, enabling self-testing.

### Assumptions:

- Developers benefit from delayed answer access for self-paced learning.
- This feature supports a more interactive learning process.


### Validation Plan:

- Test whether answers are only revealed when a user explicitly confirms.
- Gather user feedback to ensure this feature aligns with their needs.

### Actionable Tasks:
- [ ] Implement a mechanism that hides answers by default.
- [ ] Add a user confirmation button to reveal answers.
- [ ] Test the user experience with this feature, including surveys for feedback.
- [ ] Optimize the feature based on testing results.

### Requirements_3
### Description: 
The system shall allow tagging of questions by topics and difficulty levels to simplify searching and filtering.

### Assumptions:

- Developers need a tagging system to organize and retrieve data efficiently.
- Effective filters rely on accurate tagging of metadata.


### Validation Plan:

- Test whether the tagging and filtering system retrieves data accurately.
- Validate the functionality with diverse question sets.

### Actionable Tasks:
- [ ] Develop a metadata tagging schema.
- [ ] Implement tagging functionality and ensure user-friendly operation.
- [ ] Test filtering accuracy and usability with different datasets.
- [ ] Create documentation to guide developers in tagging and filtering.

### Requirements_4
### Description: 
The system shall generate regular reports summarizing biases in data, allowing developers to monitor and address them effectively.

### Assumptions:

- Developers require periodic updates on data quality and fairness.
- Reports must provide actionable insights for developers.

### Validation Plan:

- Test the report generation system for accuracy and completeness.
- Verify that reports provide useful data summaries and visualizations.

### Actionable Tasks:
- [ ] Develop functionality to generate reports at predefined intervals.
- [ ] Include metrics such as bias percentage and diversity distribution in reports.
- [ ] Test report generation with diverse datasets.
- [ ] Provide a user manual for interpreting reports.

### Requirements_5
### Description:
 The system shall notify developers immediately when biased or imbalanced data is detected.

### Assumptions:

- Real-time notifications allow developers to act on issues without delay.
- Developers require clear, concise alerts for data imbalances.

### Validation Plan:

- Test whether the notification system alerts users promptly after detecting biases.
- Verify the clarity and content of notification messages.

### Actionable Tasks:
- [ ] Develop a notification system for real-time alerts.
- [ ] Integrate the notification system with the bias detection module.
- [ ] Test notification accuracy, clarity, and delivery speed.
- [ ] Document usage guidelines for developers.

