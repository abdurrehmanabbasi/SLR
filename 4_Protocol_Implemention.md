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

# 2 Stage

### Title+Abstract Screening Manual (1st pass)
Remove Obviously irrelevant papers using title and abstract, keywords using filter and irrelvant papers out like medical, iot, aose, blockchain and mention in Things to learn words.

after this 3262-2542= 720 Remaining

## Title+Abstract Strictly (2nd Pass)
Now we checking according more strictly towards I/E criteria

Creating relevance column and check strong Relevance according below:
- The study involves agent-based, autonomous, or multi-agent AI systems, explicitly excluding generic machine learning, deep learning, or standalone large language model (LLM) approaches
- The proposed system is applied to a software engineering task
- The paper presents a concrete technical contribution, such as a framework, architecture, or system
- The study includes explicit evaluation, such as experiments, case studies, or performance analysis

after this 720-385=335 Remaing for Full Text Screeing Process


### Full-text screening

QA and DE