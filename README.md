# CSV reader

A gptscript tool that leverage duckdb to read csv and query data based on natural language. 

## Example

[Video example](https://www.loom.com/share/a1f704df5b5c4780b9bb330b72ec963b)

```
Tools: read-csv-schema duckdb install-duckdb from github.com/gptscript-ai/csv-reader

Perform the task one by one.

1. Read and understand Electric_Vehicle_Population_Data.csv schema
2. Based on schema, Tell me how many vehicle are made By TESLA in AZ.
```

## How it works

The tool leverages [duckdb](https://duckdb.org/) to read CSV file, and then using LLM to transform your natural language into sql to be able to find information you want.