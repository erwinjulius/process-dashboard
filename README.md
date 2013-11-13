process-dashboard
=================

This app should render a visual representation of a process activities and offer simple ways for the user to discover which instance is stoped where or under which role.

Scenario
--------

Information model:
Process Model/Activity - BPMS modeled processes  
Process/Activity Instance - Running instances representing models  


Activity Table (current state)
--------------
timestamp - process_id - process_name - process_instance_id - activity_id - activity_name - main_entity_name - main_entity_id


Sample process chain
--------------
Documents receiving -> Deliver Documents -> Evaluate Orientations -> Demand breakdown -> Demanda response preparation -> Response acceptance -> Document Answering

Tasks grouping
--------------

Documents receiving : register document -> validate document  
Deliver Documents : write orientations -> submit orientations  
Evaluate Orientations : analyse orientations -> validate orientations  
Demand breakdown : demand indentifying -> demand validation -> demand approval  
Demand response preparation : demand acceptance -> response writing -> response approval  
Response acceptance : response analisys -> response analisys approval  
Document Answering : ...  


KPI  
Quality / Delay / Time


