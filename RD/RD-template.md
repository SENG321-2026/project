You may use this requirements document template to get your requirements document started for your designer team.

# Requirements Document - Project Name (date created)

# Revision History

| Name | Date | Reason for Changes | Version |
| ----------- | ----------- | ------------- | ---------- | 
|  |  | | |
|  |  | | |
|  |  | | |
|  |  | | |

1. **Overview**

      Provide an overview of the sections and contents of the document. Alternatively you may choose to provide a table of contents here instead. 
2. Business Requirements

   2.1. **Background**
   Summarize the rationale and context for the new product or for changes to be made to an existing one. 

   2.2. **Business Opportunity**
   Describe the business problem that is being solved or the process being improved. Describe the needs of typical customers or of the target market. Present customer problems that the new product will address. 

   2.3. **Business Objectives**
   Summarize the important business benefits the product will provide in a quantitative and measurable way. Organizations generally undertake a project to solve a problem or exploit an opportunity. Business objectives define ways to measure achievement of business goals. 

   2.4. **Success Metrics**
   Indicators that stakeholders will use to define and measure success on the project. What are the factors that will have the greatest impact on achieving success (i.e., could include aspects within and external to the organization).

   2.5. **Product Vision Statement**
   Write a vision statement that explains the long-term purpose and intent of the product.   Describe the context and origin of the product being specified in this RD. For example, state whether this product is a follow-on member of a product family, a replacement for certain existing systems, or a new, self-contained product. If the RD defines a component of a larger system, relate the requirements of the larger system to the functionality of this software and identify interfaces between the two. A simple diagram that shows the major components of the overall system, subsystem interconnections, and external interfaces can be helpful but not required.




3. **Scope and Limitations**
 
   3.1. **Major Features**
      Describe the major features the product contains or the significant functions that it performs or lets the user perform. Details will be provided in Section 5, so only a high level description is needed here. Organize the functions to make them understandable to any reader of the RD. Think about how users will use the features to ensure the list is complete. Also ensure that it does not include unnecessary features that sound interesting, but does not provide customer value.     

   3.2. **Project Scope**
   Provide a description of the software being specified and its purpose, including relevant benefits, objectives, and goals. Relate the software to corporate goals or business strategies. Address any goals that your software will not satisfy (i.e. what is outsie the scope?) 

   3.3. **Limitations and Exclusions**
   List any product capabilities or characteristics that a stakeholder might expect but that are not planned for inclusion in the product or in a specific release. List items that were cut from scope, so the scope decision is not forgotten.

5. **Context Description**


   4.1. **User Classes and Characteristics**

   Identify the various user classes that you anticipate will use this product. User classes may be differentiated based on frequency of use, subset of product functions used, technical expertise, security or privilege levels, educational level, or experience. Describe the characteristics of each user class. Certain requirements may pertain only to certain user classes. Distinguish the favored user classes from those who are less important to satisfy. If you have user classes that appear similar (e.g. 1st year students, 4th year students), be sure to explain how they are differentiated. 

   4.2. **Operating Environment**

   Describe the environment in which the software will operate, including the hardware platform, operating system and versions, and any other software components or applications with which it must peacefully coexist.


   4.3. **Design and Implmentation Constraints**

   Describe any items or issues that will limit the options available to the developers. These might include: corporate or regulatory policies; hardware limitations (timing requirements, memory requirements); interfaces to other applications; specific technologies, tools, and databases to be used; parallel operations; language requirements; communications protocols; security considerations; design conventions or programming standards (for example, if the customer’s organization will be responsible for maintaining the delivered software).


   4.4. **Assumptions and Dependencies**

   List any assumed factors (as opposed to known facts) that could affect the requirements stated in the RD. These could include third-party or commercial components that you plan to use, issues around the development or operating environment, or constraints. The project could be affected if these assumptions are incorrect, are not shared, or change. Also identify any dependencies the project has on external factors, such as software components that you intend to reuse from another project.
   4.5. **Glossary of Terms**

      Define all the terms necessary to properly interpret the RD, including acronyms and abbreviations.


   4.6. **References**

      List any other documents or Web addresses to which this RD refers. These may include user interface style guides, contracts, standards, system requirements specifications or use case documents. Provide enough information so that the reader could access a copy of each reference, including title, author, version number, date, and source or location.


6. **System Features** (Due Iteration 2 and beyond)

    This template illustrates organizing the functional requirements for the product by system features, the major services provided by the product. You may prefer to organize this section by use case, mode of operation, user class, object class, functional hierarchy, or combinations of these, whatever makes the most logical sense for your product.
   
   5.1. **System Feature 1**

      State the feature name in just a few words.

   5.2. **Description and Priority**

      Provide a short description of the feature and indicate whether it is high, medium, or low priority.
  
7. **Functional Requirements**

   Where applicable - Itemize the detailed functional requirements associated with this feature. These are the software capabilities that must be present in order for the user to carry out the services provided by the feature, or to execute related use case(s). Include how the product should respond to anticipated error conditions or invalid inputs. Requirements should be concise, complete, unambiguous, verifiable, and necessary. Use “TBD” as a placeholder to indicate when necessary information is not yet available.
      Each requirement should be uniquely identified with a sequence number or a meaningful tag of some kind. These could be requirements that the clients provided directly or were defined by the designer group as a result of rendering the feature.
      Each requirement should also include information a(1) bout Backward Traceability (the rationale for the requirements and the source – RFP and which section in it, client meeting and which notes from that meeting, etc.. and (2) Forward Traceability (how the requirement can be verified by the users.

   REQ-1:

   REQ-2:

8. **Use cases associated with the feature or functional requirement**

    This is the use case specification. For each Use Case, list the dialog elements in the use case that elaborates or is related to this feature or one of its functional requirements, i.e. sequences of user actions and system responses that stimulate the behavior defined for this feature/functional requirement.
         
| ID and Name | UC-2 View Recipe (Human Generated) | AI Generated (include link(s) to chat(s)) | Final Use Case |
| ----------- | ---------------- | ------------ | -------------- |
| Created By: | Nolan, Justin | | Nolan, Justin |
| Date Created: | 02/14/24 | | 02/14/24 |
| Primary Actor: | Kitchen Staff, Managers, Front of House Staff | As a kitchen manager, I want to include a "System Admin" role for recipe management. | Kitchen Staff, Managers, Front of House Staff |
| Description | The Actor selects a recipe from the list of all possible recipes. The system displays a view of the recipe based on the actor's level of access. | The Actor selects a recipe, and the system grants different levels of access to recipe details based on the role of the actor. | **Reflection:** I chose to keep the original description while incorporating the AI suggestion for role-based access control. This adds clarity without changing the core functionality. <br><br> The Actor selects a recipe from the list of all possible recipes. The system displays a view of the recipe based on the actor's level of access. |
| Trigger: | Actor opens recipe menu section of the system. | Actor accesses the recipe menu by clicking a “Recipes” button in the dashboard. | Actor opens recipe menu section of the system |
| Preconditions: | <ul><li>PRE-1: User is logged in.</li><li>PRE-2: User is authenticated.</li></ul> | <ul><li>PRE-1: User has access rights based on their role.</li><li>PRE-2: User is logged in and has internet access.</li></ul> | <ul><li>PRE-1: User is logged in.</li><li>PRE-2: User is authenticated.</li></ul> |
| Postconditions: | <ul><li>POST-1: Recipe is displayed.</li></ul> | <ul><li>POST-1: Recipe details are saved to user history for future reference.</li></ul> | <ul><li>POST-1: Recipe is displayed.</li></ul> |
| Normal Flow: | <ol>**2.0 View Detailed Recipe**<li>Kitchen Staff or Manager selects the recipe menu option.</li><li>Select active or inactive recipes to view.</li><li>Select desired recipe from list.</li><li>System displays the detailed recipe view.</li></ol> | <ol>**2.0 View Recipe with Access Control**<li>Kitchen Staff or Manager selects the recipe menu option.</li><li>Select the recipe of interest based on access level.</li><li>System displays full recipe details or only basic info based on actor's role.</li></ol> | <ol>**2.0 View Detailed Recipe**<li>Kitchen Staff or Manager selects the recipe menu option.</li><li>Select active or inactive recipes to view.</li><li>Select desired recipe from list.</li><li>System displays the detailed recipe view based on access level.</li></ol> (Blended with AI’s role-based access detail) |
| Alternate Flows: | <ol>**2.1 View Limited Recipe**<li>Front of House Staff selects the recipe menu option.</li><li>Select active or inactive recipes to view.</li><li>Select desired recipe from list.</li><li>System displays the limited recipe view.</li></ol> | <ol>**2.1 View Limited Recipe with Restrictions**<li>Front of House Staff selects the recipe menu option.</li><li>Select active or inactive recipes based on role.</li><li>System displays basic recipe details or redirect to manager for approval.</li></ol> | <ol>**2.1 View Limited Recipe**<li>Front of House Staff selects the recipe menu option.</li><li>Select active or inactive recipes to view.</li><li>Select desired recipe from list.</li><li>System displays the limited recipe view based on role.</li></ol> |
| Exceptions: | | The system may encounter a timeout error if the recipe details take too long to load. |  |
| Priority: | High | Medium (AI suggested that this be lowered for systems with multiple actors). | High |
| Frequency of Use: | 10 times per day by the Kitchen Staff, 1 time per day by the Manager, 20 times per day by the Front of House Staff. | 5-10 times per day for each actor, but varies based on the restaurant size. | 10 times per day by the Kitchen Staff, 1 time per day by the Manager, 20 times per day by the Front of House Staff. |
| Business Rules: | Must alert all customers of potential allergens. Only authorized ingredients may be in the ice cream. | Add a rule about updating recipes when allergen information changes. | Must alert all customers of potential allergens. Only authorized ingredients may be in the ice cream. |
| Other Information: | RSM-2, RSM-3, RSM-7 |  | RSM-2, RSM-3, RSM-7 |
| Assumptions: | Recipe already exists in the system. | Recipe exists, and the system can handle large recipe databases. | Recipe already exists in the system. |

8. User stories (per system feature):

- As a donor, I want to receive a personalized thank-you email so that I feel appreciated.
- As an organization, I want to track donor engagement so that I can improve retention.
- As a fundraiser, I want to create visually appealing campaign pages to attract more donors.



   **System Feature 2 (and so on)**

9. **Data Requirements**  
      
   9.1. Logical data model
      E.g., entity-relationship diagrams and UML class diagrams. You may provide a data model for the business operations or the data that the system modifies. Not the same thing as a database design data model. 
   9.2. Data dictionary
      Composition of data strucutres, meaning, data type, length, format, and allowed values. 
   9.3. Reports
      If your system will generate reports, then describe the attributes of those reports. You can detail the layout of the report.
   9.4. Data acquisition, integrity, retention, and diposal
      If possible, describe how data is acquired, retained, and later on disposed. Describe the requirements for protecting the integrity of the data.

   
10. **External Interface Requirements**
    
   10.1. User Interfaces

Describe the logical characteristics of each interface between the software product and the users. This may include sample screen images, any GUI standards or product family style guides that are to be followed, screen layout constraints, standard buttons and functions (e.g., help) that will appear on every screen, keyboard shortcuts, error message display standards, and so on. Define the software components for which a user interface is needed.
      
   10.2. Hardware Interfaces
   
 Describe the logical and physical characteristics of each interface between the software product and the hardware components of the system. This may include the supported device types, the nature of the data and control interactions between the software and the hardware, and communication protocols to be used.
   
   10.3. Software Interfaces

Describe the connections between this product and other specific software components (name and version), including databases, operating systems, tools, libraries, and integrated commercial components. Identify the data items or messages coming into the system and going out and describe the purpose of each. Describe the services needed and the nature of communications. Identify data that will be shared across software components.
       
   10.4. Communication Interfaces  

Describe the requirements associated with any communications functions required by this product, including e-mail, web browser, network server communications protocols, electronic forms, and so on.

11. **Software Quality Attributes**

    Specify requirements that include performance, security, reusability, maintainability, usability, availability, interoperability, etc.

12. **Analysis Models (Data Flow Diagrams, Sequence Diagrams, etc.)**

Context level DFD (minimum 1)
DFD level 1 (minimum 1)
DFD level 2 (where applicable)

Dialog Maps for 2 main features (select features where you did not also write a detailed use case)

Sequence Diagram (minimum 1)




13. **Appendix**   

14. **Reflection on the use of AI**

This section must be submitted as a separate document from the rest of the RD deliverable.

This is the only portion of the deliverable that cannot be written with AI.

In this section, reflect on how the use of AI impacted your submission of this deliverable. We have included questions here for you to answer as part of your reflection, but we encourage you to go above and beyond if the questions do not address the experience you have had. We urge you to reflect deeply on the use of AI as they contribute towards a significant portion on how your work is evaluated, and this section will largely inform how you work with requirements once you are out in the industry!

Remember that you must submit your chat logs, thus, we recommend collaborating around one computer in labs or via video chat when you are working on this outside of class time.

- Specify the model you are using (e.g. ChatGPT 4o)

- List all the ways that your team used generative AI in this deliverable. Please be specific.

- What context did you provide to the AI model to derive your desired outputs? How did you decide what context to provide?

- What aspects of the AI-generated artifact surprised you or that you hadn't considered? Provide examples from your deliverable.

- What are, if any, some areas where AI did not help you in writing your requirements document? Be specific about those areas. If AI was always helpful, why did you experience so much success? (e.g. perhaps your prompting behaviour)

- How confident were you in generative AI’s output?

- In your observations, what made prompts effective and what made prompts ineffective? Was it the types of prompt (question-based, instruction-based, etc.) How did you decide that a prompt was effective, or not? Please give examples of your prompts for both good and bad prompts, and your perceived good and bad responses from the AI model.

- If you had to repeatedly prompt the AI model, why did you keep updating your prompt? What changes were you making to your prompts? How did you know when you were satisfied with the output? Give examples of conversations requiring repeated or changing prompts.

- Was your GenAI model able to criticize its own output? Did you agree or disagree with its self-evaluation?

- Did you perceive that the AI model gained and maintained contextual understanding during the conversation? E.g. did you keep having to remind the model of something introduced early on? What context did it remember and what context did it forget?

- Based on your experience using AI to produce this portion of a requirements document, what challenges do you anticiapte in terms of using AI for requirements engineering in industry? What can you do as a software engineer to mitigate these challenges? 

