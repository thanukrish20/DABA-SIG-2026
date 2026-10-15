# AI User Retention and Mood Analyzer

## Project Overview
The AI User Retention and Mood Analyzer is a Python-based project that analyzes app usage patterns and journal sentiment. It aims to understand user engagement, identify changes in journal sentiment, and provide supportive responses while applying basic safety guardrails.

## Objectives
- Analyze app usage patterns to understand user engagement.
- Explore factors related to user retention.
- Classify journal entries as Positive, Neutral, or Negative.
- Identify negative sentiment changes across journal entries.
- Apply safety checks before generating supportive responses.
- Integrate usage analysis, journal processing, and safety validation into one workflow.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Random Forest
- TextBlob
- Google Colab
- IPyWidgets
- GitHub

## Project Implementation

### Day 1: App Usage and Retention Analysis
Created a sample app usage dataset using login days, session duration, features used, and notifications opened. Developed an initial retention analysis workflow and defined the mood-journal process.

### Day 2: Usage and Journal Insights
Worked on connecting app usage patterns with journal insights while maintaining basic safety checks.

### Day 3: Safe-Support Knowledge Base
Created basic support categories and safety rules for handling different journal inputs.

### Day 4: Safety-Aware Prompt Design
Designed supportive prompts for positive, neutral, negative, empty, and safety-related inputs.

### Day 5: Guarded Mood-Journal Assistant
Developed a journal assistant that classifies text sentiment and provides supportive responses with basic safety screening.

### Day 6: Journal Safety Testing
Tested journal inputs under different safety conditions, including normal and safety-keyword entries.

### Day 7: Response Evaluation
Created checks to evaluate response relevance and basic safety compliance.

### Day 8: Response Quality Checks
Tested for unsafe, unsupported, and irrelevant responses using predefined checks.

### Day 9: Safety Prompt Improvement
Improved supportive prompts and reviewed the assistant's basic guardrails.

### Day 10: Enhanced Safety Filtering
Added keyword-based safety filtering and escalation guidance for selected safety-related inputs.

### Day 11: Guarded Journal Interface
Developed an interactive journal interface using IPyWidgets, including a text input area, an analysis button, and an output area.

### Day 12: Integrated Analysis
Combined sample app usage data, journal sentiment analysis, and safety status into an integrated dataset using Pandas.

### Day 13: Safety Scenario Validation
Created multiple test scenarios for positive, neutral, and negative journal entries, safety keywords, empty inputs, and whitespace-only inputs. Compared expected and actual safety statuses.

### Day 14: Guarded Assistant Demonstration
Demonstrated the combined workflow using sample app usage information and journal entries. Displayed sentiment results, safety status, and supportive responses.

## Key Features
- App usage data analysis.
- Initial user retention analysis.
- Text sentiment classification.
- Journal safety keyword screening.
- Supportive response generation.
- Interactive journal input interface.
- Multiple safety scenario tests.
- Integrated usage and journal report.
- Basic validation summaries.

## Workflow
1. Collect sample app usage data.
2. Analyze usage patterns.
3. Accept a journal entry.
4. Check for empty input and configured safety keywords.
5. If the safety check is triggered, show the configured support guidance.
6. Otherwise, analyze journal sentiment.
7. Display the sentiment result and an appropriate supportive response.
8. Combine usage and journal information for reporting.

## Limitations
- The project uses sample datasets for demonstration.
- Simple High Usage and Low Usage classification is a heuristic and is not equivalent to a trained retention prediction.
- Actual retention model performance must be evaluated using appropriate test data and metrics.
- TextBlob sentiment analysis may misclassify context, sarcasm, or complex emotions.
- Keyword-based safety screening may miss indirect or context-dependent concerns.
- The prototype does not replace professional support or a comprehensive safety assessment.
- An LLM-based component requires a configured model/API; the demonstrated rule-based responses do not by themselves establish that an LLM is integrated.

## Future Enhancements
- Use larger, realistic app usage datasets.
- Evaluate the retention model with suitable metrics.
- Improve detection of sentiment changes across journal history.
- Strengthen contextual safety screening and testing.
- Integrate an LLM through a securely configured API.
- Improve the interface and reporting dashboard.
- Evaluate response quality with broader test scenarios.

## Conclusion
The project demonstrates a prototype workflow for app usage analysis, journal sentiment classification, basic safety screening, and supportive response generation. The implementation provides a foundation for future improvements in retention modeling, contextual sentiment analysis, and safety validation.

## Project Status
Day 1–Day 14 implementation and demonstration activities documented. Further evaluation is needed before making claims about real-world retention accuracy or comprehensive safety performance.
