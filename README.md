# Cause Connect - Code for Good
<img width="270" alt="cconnect" src="https://github.com/user-attachments/assets/0b6d5b6d-c3a2-426a-80cc-92fdfa74964b">


Cause Connect is a web application that automates and accelerates the process of matching nonprofit organizations with emerging leaders. It aims to reduce the time spent manually screening and contacting nonprofits, provide a more personalized experience, and improve the overall matching process by aligning candidates’ interests with nonprofit missions.

Table of Contents

	•	Overview
	•	Features
	•	Tech Stack
	•	Installation
	•	Usage
	•	Future Enhancements
	•	Contributors
	•	License

Overview

Nonprofit organizations and emerging leaders often face challenges in finding meaningful matches due to manual processes, high mismatches, and lack of personalization. Cause Connect solves this by:

	•	Automating and personalizing the matching process using a combination of surveys and a matching algorithm.
	•	Utilizing a Cosine Similarity matching model combined with LLMs to provide contextually aware matches.
	•	Enabling next-generation leaders to drive meaningful change through skill development, leadership, and volunteering.

Features

	•	Matching Algorithm: Uses Cosine Similarity with TF-IDF to find matching nonprofits based on user input and profile.
	•	Surveys: Collects information on users’ passions, skills, availability, and leadership experience to enhance matching accuracy.
	•	Real-time Feedback: Provides feedback to users and nonprofits about their matches and volunteering experiences.
	•	Skill Development: Allows users to track their progress, earn skill badges, and get certifications.
	•	Leader and Nonprofit Role Selection: Users can sign up as a nonprofit or leader and engage in a smooth onboarding process.

Tech Stack

	•	Frontend: React.js
	•	Backend: Node.js, Express.js (to be implemented)
	•	Database: MongoDB (future integration)
	•	APIs: Integration with LinkedIn for user authentication.
	•	LLM Matching: Uses LLM and NLP tools for improved semantic understanding and matching based on context.

Installation

	1.	Clone the repository:

git clone https://github.com/mori6mori/cause-connect.git


	2.	Navigate to the project directory:

cd cause-connect


	3.	Install the required dependencies:

npm install


	4.	Run the application:

npm start



Usage

	1.	Sign Up or Login: Users can sign up as a nonprofit or a leader. LinkedIn sign-up is also available for quick authentication.
	2.	Fill out a Survey: Users provide information such as causes they’re passionate about, skills they offer, and availability.
	3.	Get Matched: The app generates a list of nonprofits that align with the user’s profile, with a detailed breakdown of why each match was made.
	4.	View Match Details: Users can view detailed information about their top matches and why they were paired with specific nonprofits.
	5.	Dashboard: Track your profile, volunteer hours, and feedback from nonprofits.

Future Enhancements

	•	Machine Learning: Further refinement of matching algorithms using machine learning to better assess personality traits and skills.
	•	Data Collection: Gather data from past successful matches to improve future recommendations.
	•	Feedback System: Implement real-time feedback loops for nonprofits and volunteers to enhance the user experience.
	•	Skill Badging: Introduce a system for users to earn badges and certifications based on their volunteering experience and skill development.

Contributors

	•	Mori Liu
	•	Tejas Iyer
	•	Shreya Gavarapattu
	•	Pablo Vicencio
	•	Ayooluwa Adeleye
	•	Saipavan Perepa
	•	Isoudine Daher

License

This project is licensed under the MIT License - see the LICENSE file for details.

Let me know if you’d like to modify or expand any sections!
