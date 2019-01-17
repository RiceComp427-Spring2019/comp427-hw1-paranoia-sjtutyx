# <img src="http://www.rice.edu/_images/rice-logo.jpg" width=180> Comp427, Spring 2018, Homework 1
## Rational Paranoia
The homework specifications, as well as the corresponding course slide decks,
can be found on the [Comp427 Piazza](https://piazza.com/class/jqifhp864b37ju).
This assignment is due **Thursday, January 17 at 6 p.m.**

You will do this homework by editing the _README.md_ file. It's in
[MarkDown format](https://guides.github.com/features/mastering-markdown/)
and will be rendered to beautiful HTML when you visit your GitHub repo.

## Student Information
Please also edit _README.md_ and replace your instructor's name and NetID with your own:

_Student name_: Yuxin Tang

_Student NetID_: yt33

Your NetID is typically your initials and a numeric digit. That's
what we need here.

_If you contacted us in advance and we approved a late submission,
please cut-and-paste the text from that email here._

What assets are important for you to protect?

What security threats will you choose to defend against?

What countermeasures can you justify, in terms of costs and benefits?

## Problem 1
- Scenario: As head of the TSA, you set the rules for screening passengers at airport checkpoints.

Christmas is coming soon. Many people are hurrying to take flights back home and gather with their family. So the airport is super crowded at this time. Due to the limited number of screening machines, people need to wait at the checkpoints for a long time.
- Assumptions:
  - Every passenger's ID (passport Number), name, birthday, nationality and other information are needed for checking.
  - Every passenger will carry some personal belongings containing some personal information.
  - Every passenger needs to send all personal baggages to the screening machines and go through body scanner.
  - To save the time, some special quick-pass channels should be opened when the checkpoint is very crowded. 
  - Screening machine cannot check all the potential threats. If necessary, TSA needs to check the passenger's personal belongs manually.  
- Assets:
  - Safety for the public environment of airport including public facilities, airport property, aircraft. No acts of terrorism, sabotage and threat to life should be allowed.
  - Safety of passenger body and personal belongings. The screen machine should do no damage to passenger's baggage. The body scanner should pose no threat to the health of the passenger.
  - Privacy of the passenger including the content in passenger's personal baggage, passenger-specific images, flight number etc. 
  - Precious time of passenger. The TSA should ensure the checking time won't be too long, otherwise passenger may miss the flight.
  
- Threats:
  - Metallic and non-metallic threats, including weapons and explosives carried by passengers which could pose threat to infrastructure of the airport.
  - Passenger's information(ID, name, birthday, nationality) may be collected at checkpoint. Those information should not be leaked or stolen.
  - Body scanner should do no harm to the health of the passenger. Screening machines should do no damage to passenger's baggage.
  - The time of passenger should not be wasted at the checkpoint. Make sure passengers can catch up on the flight.
  - Someone could use the quick-pass channel to escape the tedious checking procedures. 
- Countermeasures:
  - Buy screening machines with high precision. If anything abnormal happens, check the belongings of the passenger manually. Cost: high, Benefits: check the passenger's baggage more carefully.
  - Purchase body scanner with good quality to protect the health of the passenger. Cost: high, Benefits: protect the body for passengers.
  - Arrange enough staff around the checkpoint for manually checking passenger's baggages. Cost: medium, Benefits: check the belongings of passenger manually.
  - Make a good plan to handle emergency (e.g. To handle the weapons and explosives, we may arrange some policeman at the airport). Cost: high, Benefits: can handle the emergencies.
  - Make a good plan to let people use the quick-pass channel.(e.g., only passengers who do not have baggages can go through the quick-pass channel.) Cost: low, Benefits: save passenger's time and make checkpoint less crowded. 
  - Delete those personal information collected from passengers. Cost: low, Benefits: can provide security guarantee for passenger personal information.
## Problem 2
- Scenario: As head of IT for an international law firm, you are responsible for a document management system; some documents stored there are about sensitive legal, financial, or political matters.

The servers of the document management system are out-of-date. The international law firm is trying to get some new servers for storage. We need to migrate the data from the old servers to the new servers. 
- Assumptions:
  - The documents are stored distributedly through multiple servers.
  - All the documents stored at the document management system contain highly confidential information
  - All the requests to the documents should be approved by the manager. Anyone who tries to get the information from the system without approval is illegitimate.
  - All the servers for storing the documents are reliable. In short time, there should be no data loss.
  - The software document management system can run reliably.
- Assets:
  - The confidentality of the documents should be preserved by document management system.
  - The integrity of the documents during data migration from old servers to new servers.
  - The reliability of servers. Make sure the servers won't be attacked easily by hackers
- Threats:
  - Hackers could attack the servers and obtain information
  - Document could be lost during the migration of the documents
  - Docuemnts could be printed out and information may leak
  - The document management operating staff could do illegal operations to the document management system 
- Countermeasures:
  - We can build some backup servers for the information stored in our system. Cost:high, Benefits: perserve the data more securely
  - Add password for each document and the password can only be get through the permission of system manager. Cost: low, Benefits: perserve the data more securely
  - Build the Local Area Network(LAN) for servers in our system and isolate our system from outside.Cost: medium, Benefits: servers won't be attacked easily. 
 

## Problem 3
- Scenario: Assume I am the organizer of one campus event, I have made a survey to collect the information of the attendees of the event.
- Assumptions:
  - Every student who attend the event must complete the survey and submit
  - The information submitted by every student is correct and accurate.
  - This is a private event. Other student should not know the exact time and place the event will take place. 
  - Every student do the survey online.
- Assets:
  - The personal information of the attendees, including the IDs, Names, Birthday 
  - When and Where the event will happen
  - The number of student who attend the event
  - The purpose of the event
- Threats:
  - Other students who do not attend the event could submit the wrong information 
  - Other students could also attend the event if he/she knows the place and time event will take place
  - The information collected by our survey can be obtained by hackers.
- Countermeasures:
  - Use a URL for the survey that could not find easily by other people. Cost: Low, Benefits: other student may not find the survey
  - Set the expiration time for the survey. Cost: low, Benefits:other student could not submit their information after expiration. Cost:low, Benefits: we may get fewer wrong information
  - Delete all the personal information collected by the survey after the event. Cost:low, Benefits: maintain the confidentiality of the personal information of the students.
  

