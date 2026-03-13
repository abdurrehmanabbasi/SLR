# Protocol Implementation
## Execute Stringa and Export results in bibtex
here define all results of every database
and total number
We colledted total 4311 Paper

## Remove duplicates 
Autmated Same type removal 685
Manual Type conversion removal 364 means we have 609 duplicate records some are 2 and some are 3 so we carry one and its 609->245

So 4311-1049=3262
Now we have total 3262 papers remaining for title and abstract reading

## Study selection using prisma 

2 Stage

### Title+Abstract Screening

Remove Obviously irrelevant papers using title and abstract for Apply inclusion/exclusion rules more strictly.

### Full-text screening 
Verify:
Methodological clarity
Agentic AI implementation
SE task relevance
Record exclusion reasons.
drop papers and also do QA, Data extraction along this
record every reason