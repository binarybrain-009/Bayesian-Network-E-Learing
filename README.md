# Bayesian-Network-E-Learing
Given a character of learner and e-learning platform determine the probability that the course will run successfully
Introduction- There are different ways in which students prefer to learn. In the last decade we have seen a boom in the space of Ed-Tech startups wanting to democratize learning. In the future we would find that a degree may no longer stand the same importance as it does today, Education and the same content would be accessible to everyone and available online. Among this the method to detect the optimal way in which the information can be delivered by making analogies through dependencies on each other is getting prominence and helping people to make better responsive decisions. There are a lot of different features provided by an E-Learning platform and different ways in which the teachers can make its maximum utilization to deliver content to students. The method of delivery of the teacher and compatibility of the student with that along with the student’s prior preparation and eagerness to learn in that subject stand of utmost importance. 
The learning sector possesses vast amounts of records of the student data. The usage of learning analytics by the educational institutions has gained prominence due to its effectiveness in helping the institute make well-informed decisions. The advent of Artificial Intelligence has provided humongous scope in improvement of E-Learning Platforms by providing intelligent and interactive environments to the students. It has made it possible to capture the data in real-time. This study aims to use machine learning algorithms on standardized data to predict the outcome of a course running successfully and helping the instructor to design the course in a better way.

Methods- We would be using a Bayesian Network “A type of probabilistic graphical model comprised of nodes and directed edges.” [1]. We first design a Bayesian Network given relationships in between different variables and calculate the probabilities given the occurrence of those events. The model is developed assuming random independent variables. We assume a fully independent model. Now we used Nodes as random variables and edges as relationships between the random variables while making the graphical model.
A lot of student data is present in the Institutional Learning Management System in the form of demographics, Performances up to date, login, and registration data. We would be using this data as sub attributes in an E-Learning System. 
	
 
Figure1-Graphical model for a Bayesian Network
Once prepared the graph is used for the reasoning purposes given the occurrence of certain instances within the model predict the probability for the further outcome.
For this study we picked 2 Electrical Electronics Department courses for the study to be conducted upon ADVD and Communication Systems. For the students the data was categorized and collected through floating a google form which had 4 main attributes as shown in the figure-1 followed by several sub-attributes on the basis of which the network was trained and the inferences were drawn. The E-Learning Platform data would be taken through the administrator logs, information available on the platform and System attributes collected from the developers.
The collected data from the students and the platform would be refined using methods such as data mining, machine learning, and big data analysis, since, the educational institutions, particularly colleges and universities, need to maintain high retention rates making the enrollment management important for the early detection of at-risk students prone to dropout. The study uses a practical method to model the learning states of students with the employment of a mathematical probabilistic graphical model.
 A Survey was circulated to assess the learning styles of different students consisting of certain questions that tested the learning styles of the students and his interest in that course. Further the sum and averages of all the questionnaire answers were computed to draw conclusions.

We analyze and collect data from user logs as to how the student interacts with the system to learn the student’s learning style. The algorithm then gives the probabilities providing useful assistance to the student and instructor through suggestion of more take Home assignment, reading exercises/problems according to his/her preferred learning styles









Citations-
1-https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/tr-95-06.pdf
2- Student Evaluation Model Using Bayesian Network in an Intelligent E-Learning System (Baisakhi Chakraborty and Meghamala Sinha)-Department of Information Technology, National Institute of Technology, Durgapur, INDIA
3-Estimation of Students’ Learning States using Bayesian Networks and Log Data of Learning Management System (Nobuhiko Kondo, Toshiharu Hatanaka)
4-Using Bayesian Networks to Detect Students’ Learning Styles in a Web-based education system (Patricio García, Analía Amandi1, Silvia Schiaffino1, Marcelo Campo1 )
