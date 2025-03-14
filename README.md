# Smart India Hackathon Workshop
# Date:
## Register Number: 212224230109
## Name: Jude Clement Jose G
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
The system provides a real-life virtual boardroom experience for both interviewers and candidates.
Candidates face AI-driven interview panels that generate questions based on their expertise.
The software ensures an unbiased, structured, and dynamic interview process.
Questions adapt in real-time, starting with ice-breaking queries and progressing to deep technical/managerial assessments.
Responses are evaluated using AI-powered relevance scoring, ensuring fair and objective assessments.
A live analytics dashboard helps interviewers track candidate performance instantly.
Experts receive quantifiable scores on their question relevance, ensuring high-quality assessments.
Candidates get instant feedback on their strengths and improvement areas.
The system helps streamline hiring and promotions, reducing human bias.
By enhancing accuracy and efficiency, the software ensures DRDO selects the best scientific talent.

## Proposed Solution / Architecture Diagram
![image](https://github.com/user-attachments/assets/b8758db8-2e54-49bd-910d-f45868c90d7c)


## Use Cases
![image](https://github.com/user-attachments/assets/85085f34-d218-4bcb-8e6b-d003175f4fa5)


## Technology Stack
1. Frontend:
React.js – For a dynamic, interactive, and fast UI
Tailwind CSS / Material-UI – For a clean and responsive design
WebSockets / Socket.io – For real-time updates
2. Backend:
Node.js with Express.js OR Django with Python – For handling requests and business logic
FastAPI – If a lightweight, high-performance backend is needed
TensorFlow / PyTorch – For AI-driven question assessment
3. Database:
PostgreSQL – For structured data storage
MongoDB – If flexibility with NoSQL is needed

## Dependencies
Here’s a **compact list** of essential dependencies:  

 **Frontend (React.js)**  
- `react`, `react-dom` – Core React framework  
- `react-router-dom` – Navigation  
- `@mui/material` OR `tailwindcss` – UI styling  
- `socket.io-client` – Real-time updates  

 **Backend (Node.js + Express.js)**  
- `express` – Web framework  
- `mongoose` OR `sequelize` – Database handling  
- `jsonwebtoken`, `bcryptjs` – Authentication  
- `socket.io` – Real-time communication  

 **AI/ML (Python-based)**  
- `nltk`, `transformers` – NLP processing  
- `speechrecognition` – Speech-to-text  

 **Deployment & Security**  
- `docker` – Containerization  
- `cors`, `helmet` – Security
