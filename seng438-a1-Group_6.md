>   **SENG 438 - Software Testing, Reliability, and Quality**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group: 6      |
|-----------------|
| Mohamed Amara                |   
| Nour Ajami              |   
| Zuhaer Rahman               |   
| Krishna Shah                |   


**Table of Contents**

(When you finish writing, update the following list using right click, then
“Update Field”)

[1 Introduction	1](#_Toc439194677)

[2 High-level description of the exploratory testing plan	1](#_Toc439194678)

[3 Comparison of exploratory and manual functional testing	1](#_Toc439194679)

[4 Notes and discussion of the peer reviews of defect reports	1](#_Toc439194680)

[5 How the pair testing was managed and team work/effort was
divided	1](#_Toc439194681)

[6 Difficulties encountered, challenges overcome, and lessons
learned	1](#_Toc439194682)

[7 Comments/feedback on the lab and lab document itself	1](#_Toc439194683)

# Introduction

This following lab report provides a detailed summary of the exploratory testing, manual scripted testing, and regression testing done on an ATM simulation system. The issue tracking system used to manage the bugs found was Azure DevOps. Prior to this lab, we knew that exploratory testing is a testing approach that focuses on freedom and discovery. As a tester, this is the time for you to explore the system however you like without the guidance of a script or test plan. Moreover, our group had a high level of understanding of manual scripted testing due to prior internship experience in testing. This experience helped our group with designing a test suite/plan, writing test cases, and eventually running them manually through ADO's test editor. Overall, this lab was a great way to further solidify our understanding of software testing and promote collaboration and teamwork within our group.

# High-level description of the exploratory testing plan

Our exploratory test plan is intended to test the various services that an ATM must provide to a customer. The key functions that our test plan targets include but is not limited to processing multiple transactions, cash withdrawal from different accounts, deposits through cash and/or cheques, transfer money between two accounts, request a balance inquiry, and abort a transaction. The approach that is taken for this test plan is more of a behavioral testing strategy where the main focus will be on how our system acts rather than the mechanism behind its functions. This black-box approach makes our test plan centered more around the end-user's perspective rather than running the entirety of the system. We plan to come up with the test cases by covering multiple user profiles as well as usage scenarios. In summary, our exploratory test plan is designed to test a fully integrated ATM system rather than each of it's individual components.

# Comparison of exploratory and manual functional testing

The exploratory testing phase allowed the testers to use their creativity to see and discover how the SUT behaves by designing their tests. The effectiveness of these tests relied on the tester's ability to devise and execute them, showcasing the importance of their expertise in identifying potential issues. After completing our testing, we assessed our findings, which enabled a comprehensive and fresh outlook on our analysis. Our approach to the exploratory testing showed a lot of commonalities in the problems identified by our teams. For example, both teams aimed to examine the withdrawal function against the specified criteria, focusing on the transaction's effect on account balance, receipts, and the system’s responsiveness and button operations. This focus and attention to detail in every perspective greatly assisted us in uncovering a great range of software abnormalities and inconsistencies. 

The manual functional testing was a hands-on experience in which the testers manually interacted with the software, and observed the behavior to ensure that each function was working as intended. This particular way of testing guaranteed a complete evaluation of the software quality, which is backed up by our detailed test plan that displayed the scenarios aligned with the software requirements. During this phase, we carefully checked the functionality of the ATM system, splitting the work amongst each other into pairs to increase efficiency and pinpoint any system flaws. We were quite thorough with our manual testing examining each feature, and ensuring that all aspects of the application were tested from the user's perspective. The tradeoff between the two testing methods is that exploratory testing offers flexibility and insight without a fixed plan allowing the tester to leverage their intuition, experience, and creativity to examine the system in an unscripted way. However, without a specific plan, exploratory testing might overlook certain areas of functionality which can potentially lead to gaps in the testing coverage. On the other hand, manual testing ensures that each feature meets its intended outcome through a planned and systematic approach, which greatly helps in achieving a comprehensive coverage of the functionalities.  

# Notes and discussion of the peer reviews of defect reports

Text…

# How the pair testing was managed and team work/effort was divided 

To divide the work for this lab, our group split into two pairs (Mohamed and Nour & Krishna and Zuhaer) to perfrom the initial exploratory, manual scripted and regression testing. To manage the different findings of each pair, we created two test plans in Azure DevOps that had the same manual scripted and regresstion test suites but different exploratory test suites. Each pair was responsible for conducting the testing and analyzing the results. After both pairs were done testing their seperate test plans, we got into a call over discord to discuss each pairs findings. After careful discussion, we reached a consensus on any differences that may have arised from our testing. Lastly, two group members were then responsible for creating the defect report using excel while the other two were responsible for writing the lab report.

# Difficulties encountered, challenges overcome, and lessons learned

Our group faced many difficulties and challenges throughout the lab that were necessary to go through in order to reach the objectives of the lab. Some of the difficulties we encountered include choosing the right issue tracking system, not being to able to use certain services in Azure DevOps due to licensing requirements, and managing permissions/access levels of all group members. To overcome these challenges, we first experimented with both Jira and Azure DevOps and collectively agreed on ADO as the issue tracking system to use due to its comprehensive agile reporting and advanced traceability. Moreover, our group originally was under the basic plan for ADO which limited the individual services we could access. To upgrade our plan, we started a free basic + test plans trial which granted us access to all the services we needed to complete this assignment. Lastly, each one of our group members was added as a project administrator to ensure that everyone had the same permissions and access level. The most valuable lessons learned from the group include patience is key to testing, proper planning is vital to ensure the efficient workflow of a team, and team work makes the dream work.

# Comments/feedback on the lab and lab document itself

Overall, our group found the lab document easy to follow and work through. In addition, we found it as useful practice of testing a software sytem and helped us better understand the differences between the three different types of testing. However, we think the integration of pair testing in this lab made the testing process a bit repetitive and tedious. 
