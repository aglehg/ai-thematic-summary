# ai-thematic-summary
An AI pipeline that ingests a list of documents, grounds them against a configurable JSON list of themes (using few-shot prompting), 
summarizes the relevant content per theme, and outputs a structured HTML report organized by theme.

## pipeline 
( theme.json , data ) → classify → summarize → html structure  
