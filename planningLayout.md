# Option 1: Smart CV Analyser

**Background** 
Recruitment teams often manually screen hundreds of resumes, which is slow and error-prone. A **Smart CV Analyser** automates this using NLP to parse resumes, extract skills/experience, and match them to job requirements.

- **NLP Basics**: Start by learning how NLP identifies entities (e.g., "Python" as a skill). Use beginner-friendly tools like spaCy.
- **Problem Scope**: Focus on structured resumes first (e.g., PDFs with clear headings) to simplify parsing.

**Summary** 
Research and design a Smart Resume Analyser system capable of automating resume screening. Explore tools and techniques for extracting relevant information from resumes and matching them to job requirements. Clearly define the requirements, assumptions, and decisions involved in this process.

Design a system to automate resume screening. Extract key details (skills, education, experience) and rank candidates against job descriptions.

- **MVP Approach**: Build a minimal version first (e.g., keyword matching) before advancing to NLP models.
- **The system does not require to have a Graphical User Interface (GUI)**

**Objective** 
This project focuses on designing an automated system to solve real-world challenges in recruitment. It emphasises critical thinking, data processing, and optimisation to improve hiring workflows.
## Deliverables
### Artifact
A prototype application or wireframes demonstrating:
- **Prototype**: A simple app with features like:
	- Resume upload (PDF/DOCX).
	- Job description input (text field).
	- Ranked candidate list. 
- User interaction, such as uploading resumes and entering job descriptions.
- Key features, including:
    - Extracting resume details.
    - Matching candidates to requirements.
    - Ranking results.
## Requirements
### Data Input:
- Allow users to upload resumes in formats like PDF, DOCX, or TXT.
- Provide a text field or upload option for job descriptions.
### Resume Parsing:
- Extract structured information from resumes, such as:
- Name and contact details.
- Skills and technical proficiencies.
- Work experience and job titles.
- Education qualifications.
- **Tip**: Use regex for basic phone/email extraction.
### Matching & Ranking:
- Use NLP techniques to match extracted resume details to job requirements.
- Assign scores or ranks to resumes based on relevance.
### Result Display:
- Display a ranked list of resumes with key highlights, such as matched skills or experience.
- Include filtering options based on criteria like skills, experience, or education.
## Suggestions
### Tools Selection:
- Use spaCy or OpenNLP for named entity recognition and key phrase extraction.
- Libraries like PyPDF2 or Apache Tika can handle document parsing for PDFs and DOCX files.
### Dataset:
- Use publicly available resume datasets or generate synthetic resumes for testing.
- Collect example job descriptions for matching experiments.
### Scalability:
- Design the system to handle bulk resume uploads and job descriptions efficiently.
## Challenges
- Handling variations in resume formatting.
- Ensuring accurate matching of skills and experience to job descriptions.
- **Formatting Variations**: Start with resumes using standard headings (e.g., "Work Experience").
- **Ambiguous Terms**: Map synonyms (e.g., "ML" = "Machine Learning") using a glossary.
## Useful Resources / Research
- spaCy Documentation for NLP: [https://spacy.io/](https://spacy.io/ "https://spacy.io/")
- PyPDF2 for PDF Parsing: [https://pypi.org/project/PyPDF2/](https://pypi.org/project/PyPDF2/ "https://pypi.org/project/PyPDF2/")
- Stanford CoreNLP: [https://stanfordnlp.github.io/CoreNLP/](https://stanfordnlp.github.io/CoreNLP/ "https://stanfordnlp.github.io/CoreNLP/")
# Assessment Description

Based on one of the project descriptions provided below you are to work as a team to design a software-based solution for your chosen project. You must work together on the design of the solution, allocating each team member tasks as necessary. The structure of the team is left to you as are the working practices, but you must pick a team administrator who will be responsible for team contact with the module leader, module tutors and representatives of RedGate company.

Team membership will be allocated to you at the start of the module.

You are to submit a report before the submission deadline for this assignment element. Each member of the team should submit an identical copy of the report. The report must be well presented and written in a formal style.

As this is a group assignment each member of the team is expected to contribute work equivalent to 1500 written words. This may be made up of diagrams, pseudocode snippets, tables, wireframe diagrams, class navigation maps and prototypes as well as written work.

For example, if you are in a team of five students you should submit a report equivalent to 7,500 written words in detail.

>[!warning] **Submission Deadline: by  14:00 on Friday 28 February 2025.**
### Intended learning outcomes for the assessment

|     |                                                             |                                                                                                                                                                                                                                                                        |
| --- | ----------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | Knowledge and Understanding                                 | Use a range of techniques for problem decomposition, decision modelling and algorithm design such that, within a simple problem description, appropriate variables, decisions and repetitive actions can be identified and translated into appropriate code constructs |
| 3   | Intellectual, practical, affective and transferrable skills | To select appropriate tools and techniques to analyse and design solutions to specific simple scenarios                                                                                                                                                                |
| 5   | Intellectual, practical, affective and transferrable skills | To work effectively as a team player, understand different roles within a team and how to administrate effectively within that role                                                                                                                                    |

### Other skills and competencies

An understanding of referencing systems and appropriate writing styles will also be covered.

### Marking scheme, criteria or rubric

Requirements gathering 30%

Project solution design 45%

Evaluation and individual contribution 10%

Presentation 15%

References must be in the correct “ARU Harvard” referencing system. [Click here to learn ](https://library.aru.ac.uk/referencing/harvard.htm).

Your 010 assignment presentation has been scheduled for Week 7 at your tutorial sessions. 

Each group will get 10 to 12 minutes and 2-3 minutes for Q & A.

a. The presentation will be done based on your group's name (i.e., alphabetically).

b. There should be no more than 10 slides (e.g., Front slide mentioning project title, and group members name and ID, Presentation outline, individual contributions- at least 1 slide for the team member and finally a concluding slide- thank you! slide)

Wish you good luck for the 010 Assignment submission and the presentation.

### Links to Supporting Materials

Information relevant to the topics required for the report are provided in each of the lectures for the module. Specific links to each topic will be provided as they are covered in the delivery.

Please see the link to the module reading list in the left menu of this site.

### Assessment Literacy

This is, in part, a written assessment and you are expected to write your report using formal language that would be suitable for a professional report. If you have problems with your written work you should contact the ARU StudySkills+ Team for help and guidance.

Your work is to be submitted Via Canvas and it is your responsibility to ensure that you know how to access the Canvas system. As many students will be submitting their work at the same time you are encouraged to submit your work well before the deadline to avoid any system congestion.

Feedback will be provided on Canvas and you will be able to view this feedback after the marks are confirmed. This is typically 20 Working Days after the submission deadline.
# document outline

> [!warning] NOTE
> You are to submit a report before the submission deadline for this assignment element. Each member of the team should submit an identical copy of the report. The report must be well presented and written in a formal style. The report **must** include the following sections as a minimum **in the following order**.
## cover page

> [!info] description
> Cover Page with Your SID (Please make sure you upload the file with your SID-e.g., 203948.zip)

**should include:**
- course name
- module code
- SID (of one student, everyone should have their own identical copy with their SIDs)
- "Assignment Element 010"
- ARU logo
## tables of contents / figures etc as required
>[!info] description
>no description provided

## task allocation list
>[!info] description
>A table containing the SID number of each student with an indication of which sections of the project design each student completed must be included.
#### members

| team member  | SID     | email                    |
| ------------ | ------- | ------------------------ |
| **Muhammad** | 2361648 | mu319@student.aru.ac.uk  |
| **Micheal**  | 2411228 | omf115@student.aru.ac.uk |
| **Gedas**    | 2410684 | gk544@student.aru.ac.uk  |
#### task list
***highlighted*** entries are mandatory, **others** are optional.

| task                        | requirements / notes                                                                                                     | member | status |
| --------------------------- | :----------------------------------------------------------------------------------------------------------------------- | ------ | ------ |
| ***cover page***            | 1. has to contain SIDs.<br>2. file name contains SID.                                                                    |        |        |
| ***document / formatting*** | 1. ~~has to be a MS Word document.~~ unclear, ask prof. Mahmud. PDF is probably OK.<br>2. table of contents and figures. |        |        |
| ***presentation slides***   |                                                                                                                          |        |        |
| ***project requirements***  |                                                                                                                          | g      |        |
| ***class diagram***         |                                                                                                                          | g      |        |
| **wireframe diagram**       |                                                                                                                          | g      |        |
| **prototype**               |                                                                                                                          | m      |        |
| **use case diagrams**       |                                                                                                                          | m      |        |
| **usability**               |                                                                                                                          | m      |        |
| **navigation maps**         |                                                                                                                          | u      |        |
| ***pseudocode***            |                                                                                                                          | u      |        |
| **flow charts**             |                                                                                                                          | u      |        |

## project requirements
>[!info] description
>A detailed description of the project requirements should be included based on the initial brief and later Q&A sessions. You should also include a clear indication of any assumptions you have made.

>[!question] comment by Gedas
>please read through these and think about what needs to be changed or added. I will constantly update the requirements over time to match our design. this is by no means how we *must* design the project, so let me know if you disagree or have ideas to implement.

Our client has requested us to design a software solution which simplifies and speeds up their recruitment process by automating CV review and sorting and providing a ranked list of CV summaries. Based on the Live Brief provided by TrackGenesis and the following presentation, we have decided on what we believe to be the essential requirements for this software. 
### functional requirements

The following list is the minimum and essential requirements needed for the system to function correctly:
1. **Job profile:** The program must allow the user to set up a job profile to use as a working environment for adding and keeping a job description and candidate resumes. The reason why we decided to implement profiles was to enable an easy way to save and resume work between multiple sessions, including adding resumes from new applicants to a previously generated ranking list without having to re-upload all of them. We have also made a reasonable assumption that the company might be hiring for multiple positions at the same time, and the user could benefit from having multiple saved job descriptions that they could later reuse without having to manage their storage themselves.
2. **Job description data input:** The user should be able to add a job description to a job profile either through a text field as plain text, or by uploading a PDF, DOCX, or TXT file.
3. **Job description parsing:** Because the client indicated optimisation and automation as their priorities, we have decided to use NLP to parse job descriptions to extract desired criteria for each job, instead of having the user set up their own criteria manually. This should simplify and hasten the setup of new job profiles. Parsing of job descriptions should result in a set of criteria which are then stored for each profile.
4. **Resume data input:** The user needs to be able to upload multiple CV files in different formats (PDF, DOCX, TXT) at the same time, which are then saved on the profile and assigned an candidate ID. The resumes should be stored in case the user wants to view them, and to avoid the need of uploading them multiple times in case they need to be parsed again (e.g. if a job description is updated).
5. **Resume data parsing:** CV files for each candidate need to have text extracted before it can be parsed into data that's usable by our data matching and ranking system. The workflow of handling resumes and job descriptions needs to include these steps to cover the file formats requested by our client: 
	1. **Plain text extraction from CV files:**
		1. TXT files can be read directly using Python.
		2. PDF file extraction done via the *PyMuPDF* library - we decided to go with this choice over the PyPDF2 library which was recommended in the Live Brief because it's generally considered faster (important for scalability) and can parse data from tables (minimises data loss).
		3. DOCX file extraction done via the *python-docx* library.
	2. **Natural Language Processing** - Extracted text is then passed to *spaCy*, which we use for NLP processing. Processed data has to result into *entities* (e.g. `Name`, `Programming Languages`, `Company`) with assigned *attributes* (e.g. `John`, `Python`, `Google`) that are then put into *categories* (e.g. `Personal Info`, `Skills`, `Work Experience`).
> [!info] ^^^ I might have gone into more detail than necessary here for the requirements section, but this can be moved elsewhere.
6. **Data matching and ranking:**
7. **Result summary display and storage:**
### non-functional requirements
> additional requirements that do not affect the basic functionality of the system, but provide additional benefits.
1. **Security:** The program must comply with the UK Data Protection Act 2018 and encrypt parsed data using AES-256 encryption using Python's `encryption.fernet` module.
2. **Usability:** The program should have an intuitive GUI that allows the user to easily set up job descriptions, upload CV files and view ranked summaries. We decided to implement a GUI is to avoid users having to familiarise and remember terminal commands, which is less intuitive and slower than a very basic GUI. This should improve the speed of resume screening further, which is one of the main stated goals of the client.
> [!warning] the live brief states that a GUI isn't mandatory, but I suggest we design it anyway - the whole idea of the software is to make the process easier and quicker for users, and typing out commands into a terminal is the opposite.
3. **Scalability:** 
## project design solution

> [!info] description
> You should include appropriate tools such as Flow Charts, Use Case Diagrams, Wireframe Diagrams, class diagrams, Navigation Maps and other appropriate graphical tools used to design your solution.
>
>You **must** include appropriate pseudocode and class diagram to test your solution

## evaluation

> [!info] description
> Evaluate your design solution based on the principles covered in the lectures.

## references

> [!info] description
> References must be in the correct .[“ARU Harvard” referencing system](https://library.aru.ac.uk/referencing/harvard.htm).

## presentation / slides

> [!info] description
> There should be no more than 10 slides (e.g., Front slide mentioning project title, and group members name and ID, Presentation outline, individual contributions- at least 1 slide for the team member and finally a concluding slide- thank you! slide)
