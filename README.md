# hello-world
Initialize this repository with a README.



Kesko Portability Pipeline System QA
1.	How many number of lambda functions we have used in this complete process?
32 serverless functions – importers, starting points, reports, enricher, pdf generator, transfer results to KNOW
Importers are fetching data from APIs
Enrichers can fill in missing data (e.g. same or other sources)
Most APIs return files in JSON format
CSV format used for 3 cases – shopping history related information
Events are way to pass data from one function to other
AWS SAM – can be used for debugging. Need Docker & SAM installed. Using Visual Studio Code.
Execute API – Loopback API (Digia) 

2.	Do we have any document regarding these lambda function?
Refer System Architecture document for high level summary. Ville, is there any other document or way to find this?

3.	I am not able to find some java scripts for step functions?
Every Javascript file has export.handler which are part of state machine and one step in the step function

4.	Do you have any document regarding the flow of step function?
AWS console & state machine & template.jaml file has step functions where we can find all functions

5.	How do you configure the GIT account with AWS and visual Code (GIT pull is not working in visual code)?

6.	How we configure  AWS account with visual code (When we running SAM command

7.	How to download code from GIT to Visual Code?


8.	How to upload code to GIT after change?

9.	Do we create different version of package  at GIT side?

10.	How to test code using Docker?

11.	How to update Cloud Formation template and how to migrate code to different environment?










