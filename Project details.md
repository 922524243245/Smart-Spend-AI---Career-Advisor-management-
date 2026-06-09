SMARTSPEND AI – Career Advisor

1. Project Title

SMARTSPEND AI – Career Advisor

---

2. Abstract

SMARTSPEND AI – Career Advisor is an intelligent career guidance system that helps students and job seekers choose suitable career paths based on their interests, skills, qualifications, and career goals. The system analyzes user inputs and provides personalized career recommendations along with learning resources and career development guidance.

The main objective of the project is to reduce confusion in career selection and help users make informed decisions regarding their future profession.

---

3. Problem Statement

Many students and job seekers face difficulties in selecting the right career path due to lack of guidance, awareness, and understanding of available opportunities. Traditional career counseling methods are often expensive, time-consuming, and not easily accessible.

The proposed SMARTSPEND AI – Career Advisor system aims to provide an intelligent and user-friendly platform that recommends suitable career options based on user profiles and preferences.

---

4. Objectives

- To provide personalized career recommendations.
- To analyze user interests and skills.
- To guide users towards suitable career opportunities.
- To suggest learning resources and skill development programs.
- To reduce career selection uncertainty.

---

5. Scope of the Project

The system can be used by:

- School students
- College students
- Fresh graduates
- Job seekers
- Career changers

The project focuses on career recommendation and guidance rather than job placement.

---

6. Modules

Module 1: User Registration

Users create an account and provide basic information.

Module 2: Profile Management

Users enter educational qualifications, skills, and interests.

Module 3: Career Assessment

The system evaluates user data and career preferences.

Module 4: Career Recommendation

Suitable career options are generated based on assessment results.

Module 5: Learning Resource Suggestion

Relevant courses and learning materials are recommended.

---

7. System Requirements

Hardware Requirements

- Processor: Intel i3 or above
- RAM: 4 GB Minimum
- Storage: 20 GB Free Space

Software Requirements

- Operating System: Windows 10/11
- Programming Language: Python
- Database: MySQL
- Frontend: HTML, CSS, JavaScript
- IDE: VS Code

---

8. ER Diagram

Entities

USER

- User_ID (PK)
- Name
- Email
- Password
- Qualification
- Skills

CAREER_ASSESSMENT

- Assessment_ID (PK)
- User_ID (FK)
- Interests
- Strengths
- Score

CAREER_SUGGESTION

- Suggestion_ID (PK)
- Assessment_ID (FK)
- Career_Name
- Description
- Salary_Range

LEARNING_RESOURCE

- Resource_ID (PK)
- Suggestion_ID (FK)
- Course_Name
- Platform
- Link

Relationships

- One User can have many Assessments.
- One Assessment can generate many Career Suggestions.
- One Career Suggestion can have many Learning Resources.

---

9. Working of the System

Step 1

User registers and logs into the system.

Step 2

User enters educational details, skills, and interests.

Step 3

The system analyzes the provided information.

Step 4

Career assessment is performed.

Step 5

Suitable career options are recommended.

Step 6

Learning resources and courses are suggested.

Step 7

User reviews recommendations and plans career growth.

---

10. Advantages

- Easy to use
- Personalized recommendations
- Time-saving
- Accessible anytime
- Helps in career planning

---

11. Future Enhancements

- AI chatbot integration
- Resume analysis
- Job market trend prediction
- Interview preparation assistance
- Skill gap analysis

---

12. Conclusion

SMARTSPEND AI – Career Advisor provides an intelligent solution for career guidance. The system assists users in identifying suitable career paths based on their interests, qualifications, and skills. It improves career decision-making and supports continuous learning and professional growth.
