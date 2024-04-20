This initiative was developed as part of the "HackHerHealth" hackathon, which aimed to address the gender health gap.

Globally, women's health often does not receive the necessary priority, especially in low-income and developing regions. There are areas where educational deficits or limited access to gynecological services prevail. As a result, women may postpone seeking medical care, thus compromising their health. Our objective is to mitigate this inequity by concentrating on one of the most common symptoms across various gynecological diseases and syndromes: menstruation. Changes in menstruation or its absence are frequently early indicators of potential health issues, yet these signs are frequently disregarded due to inadequate education and other barriers.

Our application utilizes a machine learning algorithm as an “anomaly detector” to prompt women to seek medical attention. This solution employs a unique ID for each response, which simplifies question interpretation since the algorithm does not depend on specific terminologies. We opted against using a large language model (LLM) due to the potential for inaccurate generation of information and the absence of a “human-in-the-loop,” which could compromise user safety.

Initially, responses will be compared against a baseline derived from healthy individuals. After six months, the algorithm will transition to a personalized model, assessing responses against an individual’s historical data. If an anomaly is identified, users will be recommended to consult professional healthcare providers. The platform is designed to enable straightforward sharing of data with healthcare professionals.

Initially, we will release a complimentary version of this service in underdeveloped countries to maximize accessibility. Plans are in place to refine the service by incorporating follow-up questions for detected anomalies, thereby optimizing the efficiency of medical consultations. Furthermore, we will expand the scope to include additional multimodal data points, such as abdominal pain symptoms. Our long-term vision involves providing this service free of charge in regions with low socioeconomic status before introducing an enhanced, paid version in more developed health systems.

The models requires further validation since they during the hackathon been evaluated on generated patient data.


Plan:

* UX Design: Develop a user interface that is intuitive and easy to navigate for all users.
* Questionnaire Development: Formalize and design the questions in the questionnaire to ensure clarity and effectiveness
* Data Collection and Validation: Gather real-life data to validate the effectiveness of the models.
* Adjust for local/cultural differences

Future Plans:

* Multimodality: Expand the app's capabilities to include multiple modes of interaction and data integration.
