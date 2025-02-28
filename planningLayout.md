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
- "Assignment Element 010-1 Component Coursework Project Proposal"
- ARU logo
## document body and formatting (not a chapter)
>[!info] requirements:
> - [x] needs to be a PDF file formatted properly (ideally a $LaTeX$ file, but markdown will do just fine.)
> - [x] cover page.
> - [x] ARU logo
> - [x] watermark?
> - [x] table of contents.
> - [x] page numbering.
> - [x] reference page.

## task allocation list
>[!info] description
>A table containing the SID number of each student with an indication of which sections of the project design each student completed must be included.
#### final table format

| team member<br>*(delete this later)* | SID     | tasks                                                                                             | completed?                      |
| ------------------------------------ | ------- | ------------------------------------------------------------------------------------------------- | ------------------------------- |
| **Muhammad**                         | 2361648 | Navigation Maps<br>Pseudocode<br>Flow Charts                                                      | Yes<br>Yes<br>Yes               |
| **Micheal**                          | 2411228 | Prototype<br>Use Case Diagrams<br>Usability                                                       | <br>Yes<br>Yes                  |
| **Gedas**                            | 2410684 | Requirements Gathering<br>Report Compilation<br>Class Diagram<br>Wireframe Diagrams<br>Evaluation | Yes<br>Yes<br>Yes<br>Yes<br>Yes |
#### task allocation
-  **Muhammad (2361648)**
	- [x] Navigation Maps
	- [x] Pseudocode
	- [ ] Flow Charts
- **Micheal (2411228)**
	- [ ] Prototype
	- [x] Use Case Diagrams
	- [x] Usability
- **Gedas (2410684)**
	- [x] Cover Page
	- [ ] Document Body
	- [x] Requirements gathering
	- [x] Class Diagram
	- [x] Wireframe Diagram
#### task list
***highlighted*** entries are mandatory, **others** are optional.

| task                             | requirements / notes                                                                                                                                                                                          | member | status |
| -------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------ | ------ |
| ***cover page***                 | 1. has to contain SIDs **only** - no names included for anonymity.<br>2. file name contains SID.                                                                                                              | g      |        |
| ***document body / formatting*** | 1. ~~has to be a MS Word document.~~ can be a PDF document (~~markdown exported as PDF,~~ or LaTeX document).<br>2. introduction<br>3. table of contents and figures.<br>4. reference page.<br>5. evaluation. | g      |        |
| ***presentation slides***        |                                                                                                                                                                                                               |        |        |
| ***project requirements***       |                                                                                                                                                                                                               | g      |        |
| ***class diagram***              | 6                                                                                                                                                                                                             | g      |        |
| **wireframe diagram**            | 1                                                                                                                                                                                                             | g      |        |
| **prototype**                    | 8                                                                                                                                                                                                             | m      |        |
| **use case diagrams**            | 2                                                                                                                                                                                                             | m      |        |
| **usability**                    | 7                                                                                                                                                                                                             | m      |        |
| **navigation maps**              | 3                                                                                                                                                                                                             | u      |        |
| ***pseudocode***                 | 5                                                                                                                                                                                                             | u      |        |
| **flow charts**                  | 4                                                                                                                                                                                                             | u      |        |

## project requirements
>[!info] description
>A detailed description of the project requirements should be included based on the initial brief and later Q&A sessions. You should also include a clear indication of any assumptions you have made.

>[!question] comment by Gedas
>please read through these and think about what needs to be changed or added. I will constantly update the requirements over time to match our design. this is by no means how we *must* design the project, so let me know if you disagree or have ideas to implement.

Our client has requested us to design a software solution that simplifies and speeds up their recruitment process by automating CV review and sorting and providing a ranked list of CV summaries. Based on the Live Brief provided by TrackGenesis and the following presentation, we have decided on what we believe to be the essential requirements for this software. 
### functional requirements

The following list is the minimum and essential requirements needed for the system to function correctly:
1. **Job profile:** The program must allow the user to set up a job profile to use as a working environment for adding and keeping a job description and candidate resumes. The reason why we decided to implement profiles was to enable an easy way to save and resume work between multiple sessions, including adding resumes from new applicants to a previously generated ranking list without having to re-upload all of them. We have also made a reasonable assumption that the company might be hiring for multiple positions at the same time, and the user could benefit from having multiple saved job descriptions that they could later reuse without having to manage their storage themselves.
2. **Job description data input:** The user should be able to add a job description to a job profile either through a text field as plain text, or by uploading a PDF, DOCX, or TXT file.
3. **Job description parsing:** Because the client indicated optimisation and automation as their priorities, we have decided to use NLP to parse job descriptions to extract desired criteria for each job, instead of having the user set up their own criteria manually. This should simplify and hasten the setup of new job profiles. Parsing of job descriptions should result in a set of criteria which are then stored for each profile.
4. **Resume data input:** The user needs to be able to upload multiple CV files in different formats (PDF, DOCX, TXT) at the same time, which are then saved on the profile and assigned an candidate ID. The resumes should be stored in case the user wants to view them, and to avoid the need of uploading them multiple times in case they need to be parsed again (e.g. if a job description is updated).
5. **Resume data parsing:** CV files for each candidate need to have text extracted before it can be parsed into data that's usable by our data matching and ranking system. The workflow of handling resumes and job descriptions needs to include these steps to cover the file formats requested by our client: 
	1. **Plain text extraction from CV files:** - this can be achieved by reading TXT files natively in Java, using the *Apache PDFBox* library for PDF files, and the *Apache POI* library for DOCX files. However, the *Apache Tika* library acts as a wrapper for aforementioned libraries and can detect all 3 file types and extract text from all of them using just one function.
	2. **Natural Language Processing:** Extracted text is then passed on for processing via the *Stanford CoreNLP* library. Ultimately, processed data has to result in *entities* (e.g. `Name`, `Programming Languages`, `Company`) with assigned *attributes* (e.g. `John`, `Python`, `Google`) that are then put into *categories* (e.g. `Personal Info`, `Skills`, `Work Experience`).
6. **Data matching and ranking:** Parsed data needs to be stored in individual JSON files and then compared to the job description JSON file that has the same structure to hold entities and attributes. The CV files are assigned a *relevance score*, the value for each match is determined by it being an exact or partial match. 
7. **Result summary display and storage:** The program needs to be able to save data of each job profile and resume into JSON files that are encrypted using AES-256 encryption, and then accessed by the program and displayed in the GUI as a list that is ranked by the relevance score.
### non-functional requirements
> additional requirements that do not affect the basic functionality of the system, but provide additional benefits.

8. **Security:** Because TrackGenesis is a Scotland based company, and due to the nature of data being gathered and processed by the program, we have made the assumption that it should be compliant with the *UK GDPR 2023* and encrypt parsed data before it is stored. Therefore we decided to implement *AES-256* encryption using Java Cryptography Architecture (JCA) as it provides an easily accessible built-in way to encrypt the JSON data (Oracle, 2025).
9. **Usability:** The program should have an intuitive GUI that allows the user to easily set up job descriptions, upload CV files and view ranked summaries. We decided to implement a GUI is to avoid users having to familiarise and remember terminal commands, which is less intuitive and slower than a very basic GUI. This should improve the speed of resume screening further, which is one of the main stated goals of the client.
> [!warning] the live brief states that a GUI isn't mandatory, but I suggest we design it anyway - the whole idea of the software is to make the process easier and quicker for users, and typing out commands into a terminal is the opposite.
10. **Scalability and performance:** The user should be able to upload a large amount of complex CV files at the same time and not experience a major slowdown in data processing. Already processed data should be saved on the job profile and not processed repeatedly if additional CVs need to be uploaded. The data should be well organised and presented in a way that's intuitive and easy to navigate.
## project design solution

> [!info] description
> You should include appropriate tools such as Flow Charts, Use Case Diagrams, Wireframe Diagrams, class diagrams, Navigation Maps and other appropriate graphical tools used to design your solution.
>
>You **must** include appropriate pseudocode and class diagram to test your solution

### prototype
>[!tip] look into [Figma](https://www.figma.com) as an easy tool for designing the UI layout.

>[!tip] our program is pretty straight-forward and most complicated stuff happens in the back-end, we probably need only these screens:
> 1. main screen to select or create a new Job Profile.
> 2. job profile screen with "upload job description" and "upload CVs" buttons, then immediately below that we can have the ranked list of applicants.

### flow chart

## evaluation

> [!info] description
> Evaluate your design solution based on the principles covered in the lectures. 
> talk about any challenges you've faced and how you overcame them (e.g. time).

One part of designing the project, which presented a significant challenge, was selecting the correct tools for our purposes, primarily the Java libraries required for extracting raw text from resumes and then parsing the data via NLP. 

At first we were looking into the recommendations presented to us via the Live Brief, which included some Python libraries. After doing some research into those, we were informed that despite the Live Brief, we were required to use Java exclusively. This was a slight setback for us, but it simulated a very real possibility of requirements changing mid-project and shows the importance of careful requirements gathering.

Our Client emphasised efficiency and automation as a requirement, so we needed to pick Java libraries that were fast, accurate and able to process a large number of complex resumes. Plain text extraction from common file formats like PDF and DOCX is quite straightforward and fast, so we went with Apache Tika as recommended in the Live Brief. However, the NLP solution required more consideration. After doing some research, we have decided to use Stanford CoreNLP as recommended in the Live Brief. OpenNLP would offer easy integration with Tika (both developed by the Apache Software Foundation), however, multiple sources regard CoreNLP as the faster and more accurate libraries according to their benchmarks (Schmitt, et al., 2019; Nanavati and Ghodasara, 2015). Having gone through these considerations we are therefore confident in our choice of tools for the purposes of this program.
## references

> [!info] description
> References must be in the correct .[“ARU Harvard” referencing system](https://library.aru.ac.uk/referencing/harvard.htm).
> - [ ] sort all items alphabetically by author, then by date ascending.
> - [x] add references for Stanford CoreNLP

Oracle, 2025. *Java Platform, Standard Edition Security Developer’s Guide, Release 11.* [online] Available at:
<https://docs.oracle.com/en/java/javase/11/security/java-cryptography-architecture-jca-reference-guide.html> [Accessed 16 February 2025]

Apache Software Foundation, 2025. *Apache Tika 3.1.0 Documentation.* [online] Available at:
<https://tika.apache.org/3.1.0/index.html> [Accessed 16 February 2025]

*United Kingdom General Data Protection Regulation 2023 (Art. 32.1.a)* [online] Available at:
<https://www.legislation.gov.uk/eur/2016/679?view=plain> [Accessed 16 February 2025]

Nanavati, J. and Ghodasara, Y., 2015. *A Comparative Study of Stanford NLP and Apache Open NLP in the view of POS Tagging.* [pdf] Available at:
<https://www.ijsce.org/wp-content/uploads/papers/v5i5/E2744115515.pdf> [Accessed 14 February 2025]

Schmitt, X., Kubler, S., Robert, J., Papadakis, M. and LeTraon, Y., 2019. *A Replicable Comparison Study of NER Software: StanfordNLP, NLTK, OpenNLP, SpaCy, Gate.* [online] Available at:
<https://www.researchgate.net/publication/337977695_A_Replicable_Comparison_Study_of_NER_Software_StanfordNLP_NLTK_OpenNLP_SpaCy_Gate> [Accessed 14 February 2025]

## presentation / slides

> [!info] description
> There should be no more than 10 slides (e.g., Front slide mentioning project title, and group members name and ID, Presentation outline, individual contributions- at least 1 slide for the team member and finally a concluding slide- thank you! slide)

>[!warning] the slides need to be submitted to Canvas before 28/2, presentations will take place on 3/3 during the practice session.

> [!note] do not include the entire flow chart / class chart, only the minimum amount needed to explain the system and get the point across. do not overload the slides with images and text.


# group project additional info
## 010-1: group project - proposal
> [!warning] deadline is 28/2.
- word count actually doesn't matter as long as it's not overly short.
- 
## 010-2: solo project - implementation
> [!warning] deadline is 28/3.
- prof. Mahmud drop-in 1-to-1 sessions are on Fridays at 9AM. 
- can deviate from the proposal part drastically.
