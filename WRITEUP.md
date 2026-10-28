1. AI vs. Rules

I would mainly use AI for reading the proposal documents, extracting the key information from documents such as project experiences, pricing, timelines, and team details. Proposal documents may use different wording and formats, so AI may help us to interpret them and return the information in a consistent amd well structure manner. However, AI would not make the final eligibility or ranking decisions.

Additionally, I would like to use normal code for checking mandatory requirements, validating extracted data, calculating weighteed score, and sorting proposals.I chose this approach just because calculations and mandatory checks should follow clear, predictable rules rather than totally depend on AI judgment.


2. Consistency and Explainability

I would use the same prompt, output format, and scoring rules for every proposal. AI would extract the details, while the application calculates the scores using fixed criteria and weights. Each result would show the scores, evidence, and reasons for the ranking so reviewers can easily understand it.


3. Human in the Loop

A human reviewer will checks the extracted details, especially missing or unclear information and mandatory requirements. They could correct errors or change a result with a clear reason. The system would keep records of the extracted data, scores, criteria, prompt version, and any changes. So, the final decision would always be made by a human.


4. Changing Criteria

I would save each version of the evaluation criteria. If an administrator changes a criterion or its weight, the system would check that the total is still 100%. All of teh proposals could then be re-scored using the updated criteria while keeping the old results for comparison and auditing.


5. Risks

Content Extraction: AI may read details incorrectly so that important or unclear information should be checked by a human.

Manipulation: Proposal may contain the content which may manipulates the Prompt which we have setted for the text extraction 

Prompt injection: The AI should ignore instructions inside proposals that try to change the ranking.

Cost or failures: Limit document sizes, process files in smaller parts, and allow failed tasks to be retried.
