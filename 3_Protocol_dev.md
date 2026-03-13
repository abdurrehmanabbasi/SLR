# Protocol Development
## Inclusion Exclusion Criteria

### Inclusion Criteria 

| Code | Inclusion Rule|
| -------- |------------------------------------------------------------------------------------------------------------------- |
| **IC-1** | The study proposes, uses, or evaluates **agent-based, autonomous, or multi-agent AI systems**                                                            |
| **IC-2** | The AI system is applied to at least one **software engineering task** (e.g. reequirements gathering, coding, testing, debugging, code review, refactoring, maintenance, DevOps) |
| **IC-3** | The paper presents a **technical approach, framework, architecture, or model** (not only opinion or commentary)                                          |
| **IC-4** | The study includes evaluation such as experiment, case study, prototype demonstration, or performance analysis.|                                                     
| **IC-5** | The paper is **peer-reviewed** (journal, conference, or workshop)                                                                                        |
| **IC-6** | The paper is written in **English**                                                                                                                      |
| **IC-7** | The study is published between **2022-2026** (to capture modern AI agents and deep learning era)                                                         |

### Exclusion Criteria
| Code     | Exclusion Rule                                                                                                          |
| -------- | ----------------------------------------------------------------------------------------------------------------------- |
| **EC-1** | The study focuses on **AI agents but not on software engineering** (e.g., robotics, games, IoT, economics)              |
| **EC-2** | The study focuses on **software engineering** but does **not** involve agent-based or autonomous AI                     |
| **EC-3** | The paper is a **tutorial, survey, editorial, poster, or opinion piece** without technical or experimental contribution |
| **EC-4** | The study does **not provide enough methodological detail** to understand or reproduce the approach.                     |
| **EC-5** | The paper is not peer-reviewed (e.g., blogs, GitHub posts, white papers, marketing content). Preprints are excluded unless a peer-reviewed version of the study is available.|
| **EC-6** | The full text is **not accessible**                                                                                     |
| **EC-7** | The paper is **not in English**                                                                                         |
| **EC-8** | The paper is a **duplicate or earlier version** of an already included study                                            |

## Selection of Database
### Core Database
1. Web of Science
2. Scopus
3. IEEE
4. ACM

### Supplementary Search
5. Google Scholar(Agentic ai is latest field emerge in previous 5 years so in hope to find missed relatable resouces like preprint we used it. so we it for snowballing and capturing latest resources or useful preprints)

### Selecting database reasons:
Google Scholar was additionally used as a supplementary source for identifying relevant papers and performing snowballing.
Google Scholar was used as a supplementary search source because agentic AI is an emerging research area. 
Some relevant studies may not yet be indexed in major digital libraries. Therefore, Google Scholar was used 
to support backward and forward snowballing and to identify recently published studies.



Search Strategy
General Query
("agent*" OR "intelligent agent*" OR "AI agent*"OR "artificial intelligence agent*" OR "autonomous agent*" OR "multi-agent system*") AND ("software engineering" OR "software development" OR "software architecture" OR "software testing" OR "requirements engineering" OR "devops" OR "program repair" OR "code generation" OR "bug fixing" OR "software maintenance")

Filter
Year:2022 to 2026
Language: English
Only: Journal Papers, Conference Paper, Early Access Articles
If Database have filterout option of review article then apply else we exclude in further title and abstract screening steps:
Note: 
Observe 1:After adding llm-based agent we only increase 1 result but adding quick keywords option add more 100 to 200 articles but quick keyword option generally not recommended in SLR so we do not add for but this create doubt in query So we add "llm-based agent" OR "large language model agent" OR "llm agent" keywords in first part of query but this not increase any result the reason is agent* cover all but quick keyword is hidden wos mechanism so it add keyword at end 

Do 1: We have screenshots of step apply query 1, filter out 2

WOS: Web of Science Core Collection we search above query on topic data fields
Total Result 3230 Result After filter out 639 we download in bibtex

Scopus: Title, Abstract, Keyword
Total Result 11206 Result After filter out 1390 we download in bibtex

ACM
We have 2 option we use adavance computing literature for broad collection 
result:2020 after filter:224

IEEE

we have result : after filterout: 2058 
now problem is ieee xplore we not able to download all result at once so we downloaded batch wise 100 size first 1000 downloaded in csv and convert to bibtex then 100 batch wise


# Reason of selecting this query
The search string was designed using a **concept-based strategy** combining two key concepts: agent-based artificial intelligence and software engineering. Broad domain terms such as “software engineering”, “software development”, “software architecture”, and “software testing” were used to ensure high recall and capture studies across different phases of the software lifecycle. Specific activities (e.g., bug fixing, code review, requirement analysis) were not included individually because they are typically described within the broader context of software engineering processes and would be captured during the screening stage.
