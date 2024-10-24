```
 ./gh-action-status -h
Usage: gh action-status [-n <number of workflows>] [-r <comma separated list of repos>  [-f <comma separated json fields>]
Example:
  gh action-status -n 2 -r "ULL-MII-SYTWS/ull-mii-sytws.github.io,ULL-MII-SYTWS-2425/ull-mii-sytws-2425.github.io" -f "createdAt,status" 
  
JSON FIELDS:
  attempt, conclusion, createdAt, databaseId, displayTitle, event, headBranch,
  headSha, name, number, startedAt, status, updatedAt, url, workflowDatabaseId,
  workflowName
```