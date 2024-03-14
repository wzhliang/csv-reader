# CSV reader

A gptscript tool that leverage duckdb to read csv and query data based on natural language. 

## Pre-requisite

You have to install duckdb first. Following this [link](https://duckdb.org/docs/installation/index?version=stable&environment=cli&platform=macos&download_method=package_manager)

## Example

[Video example](https://www.loom.com/share/a1f704df5b5c4780b9bb330b72ec963b)

```
Tools: github.com/gptscript-ai/csv-reader

Perform the task one by one.

1. Read and understand Electric_Vehicle_Population_Data.csv schema
2. Based on schema, Tell me how many vehicle are made By TESLA in AZ.
```

Note: Make sure you download the [csv](./examples/Electric_Vehicle_Population_Data.csv) file and put it into the current dir if you are copying and paste the example.

## How it works

The tool leverages [duckdb](https://duckdb.org/) to read CSV file, and then using LLM to transform your natural language into sql to be able to find information you want.