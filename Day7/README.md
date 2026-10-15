# Day 7 - Journal Safety Testing

## Objective
Test the mood-journal assistant using different journal inputs and safety conditions.

## Test Cases
- **Positive mood:** Tests positive journal entries.
- **Neutral mood:** Tests ordinary journal entries.
- **Negative mood:** Tests entries expressing difficult feelings.
- **Safety keyword:** Checks whether predefined safety keywords trigger a supportive response.
- **Empty input:** Checks whether blank journal entries are handled correctly.

## Implementation
- Used Python and Pandas to create the test dataset.
- Used TextBlob to analyze text sentiment.
- Tested the `guarded_mood_assistant()` function.
- Checked the results using passed and failed test counts.

## Expected Result
The assistant should respond appropriately to each test condition and handle empty inputs without errors.

## Limitation
The safety check uses predefined keywords and may miss other expressions of distress. Sentiment analysis is not a clinical assessment, and the assistant should not replace professional support.

## Status
Day 7 journal safety testing completed.
