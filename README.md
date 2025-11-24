# Experiment 3 – Scenario-Based Report Development Utilizing Diverse Prompting Techniques

Name: SHIVAKUMAR K V 

Date: 03.11.2025

---

## Aim
To design an AI-based Smart Campus Assistant that helps students with academic-related queries such as timetable updates, faculty availability, and event notifications. The system should efficiently respond to student questions using Straightforward Prompts, Tabular Format Prompting, and Preceding Question Prompting techniques.

---

## Tools Required
- AI-based text generation platforms (ChatGPT, Google Gemini, Claude, etc.)
- Microsoft Word / Excel for documentation
- Internet connectivity for query testing

---

## Theory
Prompt engineering is a crucial skill in developing AI chatbots. It focuses on crafting effective prompts that yield relevant, accurate, and context-aware outputs from large language models (LLMs).

### 1. Straightforward Prompting
- Direct questions or commands.
- Ideal for short, factual responses.

### 2. Tabular Format Prompting
- Requests AI to organize information in a table.
- Useful for schedules, lists, or comparisons.

### 3. Preceding Question Prompting
- Builds conversation flow using previous responses.
- Makes interactions more natural and human-like.

These techniques improve the chatbot’s versatility and efficiency when handling real-world student interactions.

---

## Experiment Procedure
The experiment simulates three student-support scenarios:

1. Timetable Assistance  
2. Faculty Availability Check  
3. Campus Event Information  

Each scenario was tested using all three prompting techniques, and responses were analyzed for clarity, accuracy, and engagement.

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/849edfd7-e100-4c63-a617-e258cab77cd4" />


---

## Scenario 1: Timetable Assistance

### Straightforward Prompt
Prompt: What are the class timings for ECE final year students on Monday?  
Response: ECE final year classes on Monday are from 8:45 AM to 3:30 PM with a lunch break from 12:30 PM to 1:15 PM.

### Tabular Format Prompting
| Time          | Subject              | Faculty Name  | Room No. |
|----------------|----------------------|----------------|-----------|
| 8:45 – 9:35 AM | VLSI Design          | Mr. Karthik R  | E-203     |
| 9:35 – 10:25 AM| Wireless Networks    | Mrs. Nithya P  | E-204     |
| 10:40 – 11:30 AM| Machine Learning    | Mr. Anand R    | E-205     |
| 11:30 – 12:30 PM| Project Work        | Guide Allotted | Lab       |
| 1:15 – 3:30 PM | Embedded Systems Lab | Mr. Ravi Kumar | Lab-1     |

### Preceding Question Prompting
Prompt 1: Can you show me the ECE Monday timetable?  
Prompt 2: Which subject is handled after lunch?  
Response: After lunch, the Embedded Systems Lab is conducted from 1:15 PM to 3:30 PM by Mr. Ravi Kumar.

---

## Scenario 2: Faculty Availability

### Straightforward Prompt
Prompt: Is Professor Anand available today?  
Response: Yes, Professor Anand is available in the AI Lab from 10:00 AM to 12:30 PM.

### Tabular Format Prompting
| Faculty Name  | Availability Time | Location       | Status    |
|----------------|------------------|----------------|-----------|
| Mr. Karthik R | 9:00 – 11:00 AM  | Room E-203     | Available |
| Mrs. Nithya P | 11:00 – 1:00 PM  | Room E-204     | Available |
| Mr. Anand R   | 10:00 – 12:30 PM | AI Lab         | Available |
| Mr. Ravi Kumar| 1:00 – 3:00 PM   | Embedded Lab   | Available |

### Preceding Question Prompting
Prompt 1: Is Mrs. Nithya available today?  
Prompt 2: Can I meet her after lunch?  
Response: No, Mrs. Nithya is available only till 1:00 PM, so meetings after lunch are not possible.

---

## Scenario 3: Campus Event Information

### Straightforward Prompt
Prompt: When is the next technical symposium scheduled?  
Response: The next technical symposium, TechSpark 2025, is scheduled for March 20th at the Central Auditorium.

### Tabular Format Prompting
| Event Name        | Date        | Venue               | Organized By   |
|--------------------|-------------|---------------------|----------------|
| TechSpark 2025     | 20-Mar-2025 | Central Auditorium  | ECE Department |
| Saveetha Innovate  | 05-Apr-2025 | Research Block      | AI Division    |
| Sports Fest        | 18-Apr-2025 | College Ground      | Sports Club    |

### Preceding Question Prompting
Prompt 1: When is TechSpark 2025 happening?  
Prompt 2: Who can participate in that event?  
Response: TechSpark 2025 is on March 20th, and participation is open to all final-year students across departments.

---

## Analysis
- Straightforward Prompting is best for factual, one-line answers.  
- Tabular Format Prompting provides clear and structured information suitable for timetables and lists.  
- Preceding Question Prompting gives a conversational and context-aware experience.

---

## Evaluation and Observations
| Prompt Type | Strengths | Weaknesses | Best Use Case |
|--------------|------------|-------------|----------------|
| Straightforward | Quick, precise | Limited detail | Simple queries |
| Tabular | Organized output | Less conversational | Timetables, lists |
| Preceding Question | Interactive, natural flow | Needs context memory | Ongoing chat sessions |

---

## Conclusion
By applying Straightforward, Tabular, and Preceding Question Prompting techniques, the Smart Campus Assistant efficiently resolved student queries about timetables, faculty availability, and events. Each technique excelled in different areas, enhancing the chatbot’s clarity, engagement, and usability.

---

## Result
Thus, the prompts were successfully designed and executed. The AI-powered Smart Campus Assistant demonstrated strong performance in handling multiple student support queries using diverse prompting strategies.
