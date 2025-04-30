<Task>Analyze sales call transcriptions to identify recurring themes, and summarize the key customer phrases, questions, and concerns for each theme</Task>

 <Inputs> {$SALES_CALL_TRANSCRIPTS} </Inputs> <Instructions> You will be reviewing a set of sales call transcriptions to identify the major recurring themes expressed by potential customers. For each identified theme, you will summarize the essence of the customer language used, as well as the specific questions, objections, and concerns they voiced.

The output should be provided in a table format with the following columns:

Theme | Key Customer Phrases | Common Questions/Concerns

Here are the steps to follow:

1. <step>Carefully review the provided sales call transcripts, looking for common topics, pain points, or areas of focus that come up repeatedly across multiple conversations.</step>
2. <step>For each recurring theme you identify, note down the specific words, phrases, and language used by customers to express their thoughts, feelings, and perspectives on that theme.</step>
3. <step>Also identify the common questions, objections, or concerns that customers voiced related to each theme. These could be specific questions they asked, hesitations they expressed, or issues they wanted addressed.</step>
4. <step>Summarize the key customer language and common questions/concerns for each theme in the corresponding table cells. Aim to capture the essence of what customers are saying and feeling in a concise way.</step>
5. <step>If there are any themes that do not have a clear set of customer language or recurring questions/concerns, note that in the table as well.</step>
6. <step>Present your findings in the requested table format, with one row for each identified theme.</step>

BEGIN ANALYSIS {$SALES_CALL_TRANSCRIPTS} </Instructions>