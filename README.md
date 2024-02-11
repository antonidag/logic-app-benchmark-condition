# Logic App Benchmark Condition vs Inline vs Expression
## Description
Benchmark project to compare the difference between Condition, Inline and Expressions implementing if statement. Generated input files used in benchmark can be viewed under the folder `benchmark_files`.

See my full blog post [here](https://www.antonbjorkman.com/posts/benchmark-condition/)!
## Installation
Let's gather our tools:

- Vs Code Extension Logic App Standard 🧙
- Azure Function Core Tools 🖳

Set up local.settings.json
```
{
  "IsEncrypted": false,
  "Values": {
    "AzureWebJobsStorage": "UseDevelopmentStorage=true",
    "APP_KIND": "workflowapp",
    "ProjectDirectoryPath": "C:\\Users\\YourUser\\projectfolder",
    "FUNCTIONS_WORKER_RUNTIME": "node",
    "WORKFLOWS_SUBSCRIPTION_ID": "",
  }
}

```
## Running locally
Run project with the `F5` command.
Right click the "Orchestration" and press `Overview`, get the trigger url and start posting.