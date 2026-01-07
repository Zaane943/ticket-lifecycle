<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution </h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket. Configuring ticket categories and priorities, verifying system functionality through test ticket submissions, and testing the system to ensure tickets were submitted and routed correctly. Part 3 of 3
<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)



<h2> Ticket Lifecycle Stages: 
</p>
<p>
Intake-Tickets are submitted into osTicket through the end-user web portal. The system records the request, assigns a ticket number, and places the ticket in an open state for review.
</p>
<p>
Assignment and Communication- Tickets are reviewd and assigned to the appropriate agent or team based on category and priority. Communication with the user is handled through osTicket's intgernal messaging system, ensuring updates are logged within the ticket.
</p>
<p>
Working the Issue- Assigned agents investigate and troubleshoot the issue, document actions taken, and provide updates to the user through the ticket thread until a resolution is identified.
</p>
<p>
Resolution- The issue is resolved by implementing the appropriate fix, confirming functionality with the user, documenting the final solution, and updating the ticket status toresolved or closed.
</p>
<p>
Lifecycle Stages
</p>
<p>
<img width="734" height="307" alt="screenshot 61" src="https://github.com/user-attachments/assets/4afd244b-5b94-419e-9fde-45ccd0427f22" />
</p>
<p>
Step 1: Welcome back! In this section we're going to be creating tickets as end users. But first, start by deleting the "Maintenance" department
</p>
<p>
<img width="639" height="373" alt="screenshot 62" src="https://github.com/user-attachments/assets/04af44d6-f10a-4ecb-8d9a-4e27ed4012ad" />
</p>
<p>
Step 2: And now jumping straight into it, we're going to use the link that takes us to the ticket creating page http://localhost/osTicket and create our very first ticket.
</p>
<p>
<img width="633" height="677" alt="screenshot 63" src="https://github.com/user-attachments/assets/117cf064-74ae-4247-88b4-cba89a5bdd75" />
</p>
<p>
Step 3: Having Karen create the first ticket, fill out her name and email section. In the help desk section, set it to "Report A Problem/Business Critical Outage" because for this scenario, the entire mobile/online bankikng system is down. Be sure to put that in the "Issue Summary" section. For the actual ticket, come up with a breif story that fits the issue like the one pictured above in the example image.
</p>
<p>
<img width="339" height="299" alt="screenshot 65" src="https://github.com/user-attachments/assets/2e94e407-6e9d-49ed-b811-32a435896caf" />
</p>
<p>
<img width="722" height="682" alt="screenshot 66" src="https://github.com/user-attachments/assets/39e1af88-49d5-4cfd-b5a8-5096a74fb17d" />
</p>
<p>
<img width="704" height="562" alt="screenshot 67" src="https://github.com/user-attachments/assets/a74cbd20-4a8f-458d-9c8e-f97a8400b6f4" />
</p>
<p>
Step 4: Log into the osTicket system as John and take a minute to observe that because we set him to "Read Only," he is not allowed to make any changes to the ticket at the moment. So testing this out, insert a note briefly explaining that so we can make sure we see it after logging in as someone else.
</p>
<p>
<img width="728" height="321" alt="screenshot 68" src="https://github.com/user-attachments/assets/d93cde18-438d-4124-ba32-0b3b9815728c" />
</p>
<p>
<img width="724" height="426" alt="screenshot 69" src="https://github.com/user-attachments/assets/8d66dd93-f486-48d4-b9b3-ea6915a606e8" />
</p>
<p>
Step 5: Logging back into the admin panel, we are going to give John full access to the ticket
</p>
<p>
<img width="491" height="193" alt="screenshot 70" src="https://github.com/user-attachments/assets/46c11702-60ec-4afc-bbb8-cb75cc91a93e" />
</p>
<p>
Step 6: Now that John has access to make changes to the ticket, we are first going to set the priority to "emergency." Briefly detail in the section below it
</p>
<p>
<img width="483" height="192" alt="screenshot 71" src="https://github.com/user-attachments/assets/472ae18f-5f45-4c64-b8bd-889d0737723f" />
</p>
<p>
Step 7: Next, set the SLA plan to "Sev-A" to mirror the severity of the scenario
</p>
<p>
<img width="487" height="191" alt="screenshot 72" src="https://github.com/user-attachments/assets/4728ce3d-042c-4f8e-a8ce-5b6b5e802fdb" />
</p>
<p>
Step 8: Molving to the help topic section, set it to "Report A Problem/Business Critical Outage" and insert a brief description of what's going on.
</p>
<p>
<img width="702" height="472" alt="screenshot 73" src="https://github.com/user-attachments/assets/96ac5836-cf07-42d4-a667-a86a263b4000" />
</p>
<p>
Step 9: Have John add a note stating that he will be escalating the ticket to the "SysAdmin" department to triage the ticket
</p>
<p>
<img width="486" height="217" alt="screenshot 74" src="https://github.com/user-attachments/assets/695ec7fa-976e-4331-87e2-bd8fd5878ae2" />
</p>
<p>
Step 10: We will be assigning the ticket to Jane specifically
</p>
<p>
<img width="491" height="208" alt="screenshot 75" src="https://github.com/user-attachments/assets/dca67eff-ac59-4001-962b-d4e6f5a7a155" />
</p>
<p>
Step 11: Set the department to "SysAdmins" and click "transfer."
</p>
<p>
<img width="303" height="227" alt="screenshot 76" src="https://github.com/user-attachments/assets/ef0bf9ba-5cf1-4ed9-a432-db659e748fc5" />
</p>
<p>
Step 12: Log out of the admin panel and log back in as Jane to configure and resolve the ticket.
</p>
<p>
<img width="724" height="273" alt="screenshot 77" src="https://github.com/user-attachments/assets/18c8c5db-c571-4bfe-979c-eebe00ad92f0" />
</p>
<p>
<img width="730" height="566" alt="screenshot 78" src="https://github.com/user-attachments/assets/655543bb-27ef-4f0a-96fc-42b12d37e5fb" />
</p>
<p>
Step 13: Click on the ticket and get updated to the situation by reading over the notes between Karen and John.
</p>
<p>
<img width="719" height="638" alt="screenshot 79" src="https://github.com/user-attachments/assets/25297ac3-1eff-4a33-b8cb-6cde49661f1c" />
</p>
<p>
Step 14: Update the team as Jane in the notes section, letting them know that you are trying to esolve the issue.
</p>
<p>
<img width="711" height="589" alt="screenshot 80" src="https://github.com/user-attachments/assets/726a3dfa-ee53-4ee4-aeba-0677967b45de" />
</p>
<p>
Step 15: Now that the issue is "resolved," add another note letting the team know that they're all set! :-)
</p>
<p>
<img width="710" height="277" alt="screenshot 81" src="https://github.com/user-attachments/assets/f5d8e9f7-d18d-4771-bc84-1a8b264b6284" />
</p>
<p>
Step 16: Change the ticket status to "resolved."
</p>
<p>
<img width="630" height="680" alt="screenshot 82" src="https://github.com/user-attachments/assets/e8f6b8ed-d4ad-4bf2-bd4e-3c3bf51f926d" />
</p>
<p>
Step 17: Going back to the link to create a ticket, we are going to have Ken start this one so fill out his name, email section, and start adding the details of the next ticket. In this scenario, the adobe reader will be down so in the summary, put it under "Report A Problem/Personal Computer Issues." Briefly detail the issue in the neccessary section and remember to click "create ticket."
</p>
<p>
<img width="313" height="235" alt="screenshot 83" src="https://github.com/user-attachments/assets/d84cbe33-8a64-4465-b63b-1c2a426a039c" />
</p>
<p>
Step 18: Log in as John as he will be closing out this ticket.
</p>
<p>
<img width="715" height="586" alt="screenshot 84" src="https://github.com/user-attachments/assets/1aebaff1-0a4e-4133-a652-389e8b091bae" />
</p>
<p>
Step 19: Add in a note stating that you spoke with Ken and he confirmed that adobe is indeed not working. Feel free to use the note in the example pictured above for reference if you are unsure of what to put.
</p>
<p>
<img width="496" height="196" alt="screenshot 85" src="https://github.com/user-attachments/assets/09fef944-4479-483c-9ae3-fa8175fa205b" />
</p>
<p>
Step 20: Set the priority level to "High."
</p>
<p>
<img width="493" height="192" alt="screenshot 86" src="https://github.com/user-attachments/assets/91f3eb06-5119-498c-be8c-c8b80934cdbf" />
</p>
<p>
Step 21: For the SLA level, set it to a 'Sev-B" with a brief note explaining that audit is taking place today.
</p>
<p>
<img width="701" height="397" alt="screenshot 87" src="https://github.com/user-attachments/assets/72f90cf4-fbf9-40a2-b2fd-4aba2e178316" />
</p>
<p>
Step 22: Add a note that you spoke with the desktop admins group to get more info and state what was said (see image above for example).
</p>
<p>
<img width="705" height="317" alt="screenshot 88" src="https://github.com/user-attachments/assets/b5e0828e-47e5-4f34-be0a-c38d1d2b0d5a" />
</p>
<p>
Step 23: Note that the issue was resolved and adobe is back up and running.
</p>
<p>
<img width="709" height="201" alt="screenshot 89" src="https://github.com/user-attachments/assets/a8c1e965-3af1-4d45-ba79-d2415d2172cf" />
</p>
<p>
<img width="490" height="173" alt="screenshot 90" src="https://github.com/user-attachments/assets/f8788cdc-ed23-4978-b2fd-75880925ec79" />
</p>
<p>
Step 24: Now set the ticket status to "Closed" as this wraps up the project on installing and configuring the osTicketing system! :-)
























