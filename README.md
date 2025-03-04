# ds_project
Data Science project, Zemskova Sofia and Alekseeva Polina

Problem

During the educational process, many students face problems with learning the material. Often, they do not have time to ask questions during a lecture or are embarrassed to ask the teacher. As a result, they waste time searching for information on the Internet, where exact answers are not always found.
On the other hand, teachers are overloaded: they receive hundreds of questions and cannot promptly answer each student. In addition, educational materials are scattered across different files, which makes searching for information difficult and ineffective.
On both sides, problems can slow down the learning process and reduce the quality of education.

Solution

We propose the development of a RAG system – an intelligent assistant that will help students quickly receive accurate answers to questions based solely on the materials of their course.
Teachers upload lectures and other educational materials to the system. Students ask questions via a chatbot. AI processes the request, finds the most relevant information in the materials and formulates an accurate answer.
Thus, the system provides information 24/7, helping students better understand the subject without the participation of the teacher.

Technologies

The core of our system is the Retrieval-Augmented Generation (RAG) method. It combines two powerful approaches: algorithms for extracting the most relevant parts of the lecture material and LLM, which forms a meaningful answer based on the data found. 
To improve accuracy, we will also implement filtering and ranking of answers to select the most relevant one and Feedback loop – analysis of students’ interactions with the system to gradually improve its performance. In the end, we will have an AI solution that minimizes errors and does not go beyond the loaded materials.

Business value

For students, this is a convenient tool that allows them to quickly get clarification on complex topics without having to contact a teacher. For teachers, it reduces the workload and saves time. For universities, it is an opportunity to improve the level of education and introduce innovative technologies. Moreover, the university can offer the system as an additional educational service or license it to other universities, creating a source of income.

Development potential

The system can be equipped with a voice assistant so that students can interact with the system in ways other than text.
Integration with various learning management systems (LMS), such as Moodle, is possible to simplify access to materials.
It would be useful to implement multilingual support for international students.
Analytics of student questions will allow teachers to identify problematic topics and adapt the course.
