# **Option 1: Smart CV Analyser**

**Background** Recruitment teams often manually screen hundreds of resumes, which is slow and error-prone. A **Smart CV Analyser** automates this using NLP to parse resumes, extract skills/experience, and match them to job requirements.

- **NLP Basics**: Start by learning how NLP identifies entities (e.g., "Python" as a skill). Use beginner-friendly tools like spaCy.
    
- **Problem Scope**: Focus on structured resumes first (e.g., PDFs with clear headings) to simplify parsing.
    

**Summary** Research and design a Smart Resume Analyser system capable of automating resume screening. Explore tools and techniques for extracting relevant information from resumes and matching them to job requirements. Clearly define the requirements, assumptions, and decisions involved in this process.

Design a system to automate resume screening. Extract key details (skills, education, experience) and rank candidates against job descriptions.

- **MVP Approach**: Build a minimal version first (e.g., keyword matching) before advancing to NLP models.
    
- **The system does not require to have a Graphical User Interface (GUI)**


**Objective** This project focuses on designing an automated system to solve real-world challenges in recruitment. It emphasises critical thinking, data processing, and optimisation to improve hiring workflows.

## **Deliverables**

### **Artifact**

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
    

## **Requirements**

### **Data Input:**

- Allow users to upload resumes in formats like PDF, DOCX, or TXT.
    
- Provide a text field or upload option for job descriptions.
    

### **Resume Parsing:**

- Extract structured information from resumes, such as:
    
- Name and contact details.
    
- Skills and technical proficiencies.
    
- Work experience and job titles.
    
- Education qualifications.
    
- **Tip**: Use regex for basic phone/email extraction.
    

### **Matching & Ranking:**

- Use NLP techniques to match extracted resume details to job requirements.
    
- Assign scores or ranks to resumes based on relevance.
    

### **Result Display:**

- Display a ranked list of resumes with key highlights, such as matched skills or experience.
    
- Include filtering options based on criteria like skills, experience, or education.
    

## **Suggestions**

### **Tools** **Selection:**

- Use spaCy or OpenNLP for named entity recognition and key phrase extraction.
    
- Libraries like PyPDF2 or Apache Tika can handle document parsing for PDFs and DOCX files.
    

### **Dataset:**

- Use publicly available resume datasets or generate synthetic resumes for testing.
    
- Collect example job descriptions for matching experiments.
    

### **Scalability:**

- Design the system to handle bulk resume uploads and job descriptions efficiently.
    

## **Challenges**

- Handling variations in resume formatting.
    
- Ensuring accurate matching of skills and experience to job descriptions.
    
- **Formatting Variations**: Start with resumes using standard headings (e.g., "Work Experience").
    
- **Ambiguous Terms**: Map synonyms (e.g., "ML" = "Machine Learning") using a glossary.
    

## **Useful Resources / Research**

- spaCy Documentation for NLP: [https://spacy.io/](https://spacy.io/ "https://spacy.io/")
    
- PyPDF2 for PDF Parsing: [https://pypi.org/project/PyPDF2/](https://pypi.org/project/PyPDF2/ "https://pypi.org/project/PyPDF2/")
    
- Stanford CoreNLP: [https://stanfordnlp.github.io/CoreNLP/](https://stanfordnlp.github.io/CoreNLP/ "https://stanfordnlp.github.io/CoreNLP/")
    

# **Option 2: AI-Based News Summariser and Risks Monitoring**

**Background** In the age of information overload, readers often struggle to consume lengthy news articles in their entirety. An AI-Based News Summariser addresses this problem by leveraging Natural Language Processing (NLP) techniques to extract the key points of news articles and create concise summaries. The system ensures that the core message of the articles is retained, making it easier for users to stay informed without investing significant time.

By utilising Java-based NLP libraries such as Stanford CoreNLP, OpenNLP, or libraries like Sumy and JSoup for web scraping, the News Summariser can automatically break down articles into summaries while maintaining their context and relevance.

This can be a very

Readers struggle with information overload. An **AI-Based News Summariser** uses NLP to condense articles into key points.

- **Summarisation** **Types**: Start with extractive methods (select key sentences) before tackling abstractive (generative) models.
    

**Summary** Research and design an AI-Based News Summariser capable of automating the summarisation process for news articles. Explore tools and techniques for extracting and summarising relevant information while retaining the core message. Clearly define the system’s requirements, assumptions, and decisions involved in its development.

Design a system to generate concise summaries from news articles. Use NLP to extract main points and retain context.

- Begin with single-article summarisation before scaling to bulk processing.
    

**Objective** This project focuses on designing an intelligent system that addresses real-world challenges of information overload. It emphasises critical thinking, effective data processing, and optimisation techniques for delivering high-quality summaries.

## **Deliverables**

### **Artifact**

A prototype application or wireframes demonstrating:

- **Prototype**: A web/mobile app with:
    
- Input for URLs/text.
    
- Summary output with key phrases highlighted.
    
- User interaction, such as inputting news article URLs or pasting raw text.
    
- Key features, including:
    
- Extracting and preprocessing article text.
    
- Generating concise summaries.
    
- Highlighting the main points and topics.
    
- Any risks associated with the news [misinformation, fake news]
    

## **Requirements**

### **Data Input:**

- Allow users to provide news articles via:
    
- URLs.
    
- Pasted raw text.
    
- Uploaded text or PDF files.
    

### **Text Extraction and Preprocessing:**

- Parse and clean the text from input sources using:
    
- Libraries like JSoup for web scraping and HTML parsing.
    
- NLP techniques for:
    
- Tokenization.
    
- Sentence segmentation.
    
- Stopword removal.
    

### **Summarisation:**

- Generate summaries using:
    
- Extractive summarisation techniques to highlight key sentences.
    
- Libraries like Sumy or custom algorithms for identifying key points.
    
- NLP models (e.g., BERT or GPT-based models) for abstractive summarisation.
    

### **Result Display:**

- Present the summarised text in a user-friendly interface.
    
- Highlight key phrases or topics within the summary.
    
- Provide options to:
    
- Download the summary as a text or PDF file.
    
- View the original article for context.
    

## **Suggestions**

### **Tool Selection:**

- Use Java libraries like:
    
- Stanford CoreNLP for NLP processing.
    
- Apache OpenNLP for language models.
    
- Sumy for extractive summarisation.
    
- Optional: Integrate pre-trained transformer models (e.g., BERT) using Java frameworks like Deep Java Library (DJL).
    

### **Dataset:**

- Collect publicly available news articles from:
    
- RSS feeds.
    
- OpenNews datasets.
    
- Kaggle’s news dataset.
    

### **Scalability:**

- Design the system to handle bulk article submissions efficiently.
    
- Use multi-threading for concurrent summarisation.
    

## **Challenges**

- Handling ambiguous or poorly formatted text.
    
- Maintaining the contextual meaning in abstractive summaries.
    
- Processing large documents efficiently within resource constraints.
    
- **Context Loss**: Test summaries on short, structured articles (e.g., news with clear headings).
    
- **Speed vs. Accuracy**: Prefer rule-based methods (e.g., Sumy) over heavy models like BERT initially.
    

## **Useful Resources / Research**

- Stanford CoreNLP: [https://stanfordnlp.github.io/CoreNLP/](https://stanfordnlp.github.io/CoreNLP/ "https://stanfordnlp.github.io/CoreNLP/")
    
- OpenNLP Documentation: [https://opennlp.apache.org/docs.html](https://opennlp.apache.org/docs.html "https://opennlp.apache.org/docs.html")
    
- ROUGE Metric: [https://pypi.org/project/py-rouge/](https://pypi.org/project/py-rouge/ "https://pypi.org/project/py-rouge/")
    

The system does not require any Graphical User Interface based solution.

# Assessment Description

Based on one of the project descriptions provided below you are to work as a team to design a software-based solution for your chosen project. You must work together on the design of the solution, allocating each team member tasks as necessary. The structure of the team is left to you as are the working practices, but you must pick a team administrator who will be responsible for team contact with the module leader, module tutors and representatives of RedGate company.

Team membership will be allocated to you at the start of the module.

You are to submit a report before the submission deadline for this assignment element. Each member of the team should submit an identical copy of the report. The report must be well presented and written in a formal style.

As this is a group assignment each member of the team is expected to contribute work equivalent to 1500 written words. This may be made up of diagrams, pseudocode snippets, tables, wireframe diagrams, class navigation maps and prototypes as well as written work.

For example, if you are in a team of five students you should submit a report equivalent to 7,500 written words in detail.

**Submission Deadline: by  14:00 on Friday 28 February 2025.**
### Intended learning outcomes for the assessment

|     ||     |
| --- | ---- | ----- |
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

> [!NOTE] NOTE
> You are to submit a report before the submission deadline for this assignment element. Each member of the team should submit an identical copy of the report. The report must be well presented and written in a formal style. The report **must** include the following sections as a minimum **in the following order**.
## cover page

> [!NOTE] description
> Cover Page with Your SID (Please make sure you upload the file with your SID-e.g., 203948.zip)

## tables of contents / figures etc as required
>[!NOTE] description
>no description provided

## task allocation list
>[!NOTE] description
>A table containing the SID number of each student with an indication of which sections of the project design each student completed must be included.
#### allocation

| team member  | SID | email |
| ------------ | --- | ---- | 
| **Mohammad** |     |mu319@student.aru.ac.uk|
| **Michael**  |     |omf115@student.aru.ac.uk|
| **Gedas**    | 2410684 |gk544@student.aru.ac.uk|
#### task list

| task                      | requirements                                                          |     | notes |
| ------------------------- |:--------------------------------------------------------------------- | --- | ----- |
| **cover page**            | 1. has to contain SIDs.<br>2. file name contains SID.                 |     |       |
| **wireframe**             |                                                                       |     |       |
| **prototype**             |                                                                       |     |       |
| **use case diagrams**     |                                                                       |     |       |
| **usability**             |                                                                       |     |       |
| **navigation maps**       |                                                                       |     |       |
| **pseudocode**            |                                                                       |     |       |
| **flowcharts**            |                                                                       |     |       |
| **document / formatting** | 1. has to be a MS Word document.<br>2. table of contents and figures. |     |       |
| **presentation slides** | 

## project requirements
>[!NOTE] description
>A detailed description of the project requirements should be included based on the initial brief and later Q&A sessions. You should also include a clear indication of any assumptions you have made.

## project design solution

> [!NOTE] description
> You should include appropriate tools such as Flow Charts, Use Case Diagrams, Wireframe Diagrams, class diagrams, Navigation Maps and other appropriate graphical tools used to design your solution.
>
>You **must** include appropriate pseudocode and class diagram to test your solution

## evaluation

> [!NOTE] description
> Evaluate your design solution based on the principles covered in the lectures.

## references

> [!NOTE] description
> References must be in the correct .[“ARU Harvard” referencing system](https://library.aru.ac.uk/referencing/harvard.htm).

## presentation / slides

> [!NOTE] description
> There should be no more than 10 slides (e.g., Front slide mentioning project title, and group members name and ID, Presentation outline, individual contributions- at least 1 slide for the team member and finally a concluding slide- thank you! slide)
