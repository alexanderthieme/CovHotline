# CovHotline
An automatic hotline service where users can dial-in and answer SARS-CoV-2 related questionnaires, get a recommendation and generation of a code to speed up processes at the hospital.

Requirements for version 1.0:

MUST:
- Scalable solution for dial-in of users
- Uses API of CovQuestions
- Text-to-speech for questions and possible answers
- User feedback with telephone keypad or voice

IMPORTANT:
- Detection of users who are not able to use the service
- Forward of call to human operator
- multi lingual
- Generation of a short code which contains the answers of the patient and which is feasible to be written on a piece of paper

NICE TO HAVE:
- Fault tolerance of code (e.g. reed solomon encoding)

