# Day 14 - Demonstrate Guarded Journal Assistant

## Objective
Demonstrate the integrated app usage analysis and guarded mood-journal assistant with basic safety checks.

## Implementation
- Created a sample app usage dataset for multiple users.
- Classified app usage into High Usage and Low Usage.
- Analyzed journal entries using TextBlob sentiment analysis.
- Classified journal sentiment as Positive, Neutral, or Negative.
- Implemented keyword-based safety screening.
- Generated supportive responses based on detected sentiment.
- Handled empty journal inputs.
- Tested positive, neutral, negative, empty, and safety-keyword scenarios.
- Generated a final demonstration report.

## Tools Used
- Python
- Pandas
- TextBlob
- Google Colab

## Expected Output
- App usage information for the selected user.
- Detected journal sentiment and sentiment score.
- Safety status for the journal entry.
- A supportive response based on the detected sentiment.
- Appropriate handling of empty and safety-keyword inputs.

## Limitations
- Sample data is used for demonstration.
- High Usage and Low Usage are assigned using a simple heuristic, not a trained retention prediction model.
- Sentiment analysis may misclassify some journal entries.
- Keyword-based safety checks may miss indirect or context-dependent concerns.
- The prototype is not a substitute for professional support or a comprehensive safety assessment.

## Outcome
The prototype demonstrates app usage analysis, journal sentiment classification, safety screening, and supportive responses in a single workflow.

## Status
Day 14 - Guarded Journal Assistant Demonstration completed.
