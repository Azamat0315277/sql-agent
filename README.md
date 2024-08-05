# sql-agent

## Build an AI agent that can answer questions about a SQL database.
**The agent will**
* Fetch the available tables from the database
* Decide which tables are relevant to the question
* Fetch the DDL for the relevant tables
* Generate a query based on the question and information from the DDL
* Double-check the query for common mistakes using an LLM
* Execute the query and return the results
* Correct mistakes surfaced by the database engine until the query is successful
* Formulate a response based on the results