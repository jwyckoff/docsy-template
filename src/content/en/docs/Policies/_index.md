---
title: "Policies"
linkTitle: "Policies"
weight: 4
description: >
  What does your user need to understand about your project in order to use it - or potentially contribute to it? 
---

{{% pageinfo %}}
This is a placeholder page that shows you how to use this template site.
{{% /pageinfo %}}


# Opening a New Engagement
**Requires:** 
The following conditions:  
- If Customer funded: 
  - Signed SOW from Customer
  - Optionally, a Purchase Order if customer policies requires it
- If completely or partially Microsoft funded: 
  - MS ECIF SOW with MS PO received by Sales role . * Note that the work cannot start until the PO has been received or we risk losing the funding.
  - If customer SOW required, a signed SOW from the Customer 
- Deal in HubSpot marked as "Agreements/Legal Complete"

**By:** 
- Director of professional services / sales

**Minimum Steps/Standards:**
- Mark the Option in the Elevate Engagement as accepted 
  - If option does not exist in Elevate, make one or adjust an existing one. 
- Send Email to Julie and PC an email to provide specific information for a project code:
  - Copy of SOW executed
  - First time customer (Yes/No)
  - Customer Name 
  - Deal Name
  - Link to the deal in HubSpot
  - Total SOW value
  - Initial invoice amount
  - Target days from Elevate Option that is marked as accepted
  - PO # (if applicable/available)
  - Link to deal in MS Partner Center
  - Primary customer contact for invoicing
  - Main stakeholder contact information (might be the same as Primary Customer Contact
  - Any special instructions / Notes for Julie.
  - If MS-Funded: 
    - Include copy of ECIF SOW
    - ECIF begin date 
    - ECIF end date
    - MS Account Team Contact Name
    - MS Account Team Email address
 - Julie sends Sales role and PC role a project code for the engagement.
 - Sales role updates project code in HubSpot deal record.

**Done when:** 
- Project Code and executed SOW are sent to the sales and PC roles.
- Project Code is added to HubSpot Deal record.
# Consultant Project Assignment

**Requires:**
- Signed SOW 

**By:**
 - PC

**Minimum Steps/Standards:**
** Note: PC should take into consideration consultant skillset, preference, and general availability risks related to other projects
- Work items / Cards are added to row(s) in [Resource Allocation Board](https://dev.azure.com/incyclesoftware/Resources%20allocation/_boards/board/t/Resources%20allocation%20Team/Stories) of Consultant(s) being assigned.  
- For each card, the following data needs to be entered
  - Title consisting of : Customer name, Project or component description (enough to ideally identify skills necessary)
  - Number of Days field: 
   - Each card added represents the # of days the consultant is assigned for that week
   - Adding all card's Number of Days fields totals the Target Days from Elevate Option marked as accepted by client for engagement.
  - Project type
  - Pricing type
  - Location
- Consultant assignment(s) updated in Engagement record in Elevate.
- PC meets with consultant(s) to discuss the allocation and validate assignment strategy

**Done when:**
 - Resource allocation steps are completed including validation with consultant(s)
# Project Tooling Configuration
**Requires:**
 - Project Code

**By:**
 - PC  

**Minimum Steps/Standards:**
- Create a new engagement in Elevate or add project code if one exists already
- Use buttons in Elevate to:
   - Create Team Project
   - Create team in MS Teams
- Add executed SOW document to new team created in MS Teams
- Paste SOW document content into ADO SOW work item body and/or attach SOW document to SOW work item.
- Mention consultants in Team Channel for engagement with link to Engagement Team/backlog in.
- Configure/Adjust Team Project and Team Settings
    - Areas and iterations
    - Groups / permissions
    - Move SOW and Project Coordination related work items to InCycle team (customer should not access these)
    - Add 'All InCycle' group as team project admins

**Done when:**
- Backlog is accessible by consultants 
- Consultants have copy of SOW

# Introduction/Commitment of Consultant to Customer 
**Requires:** 
- Consultant is assigned in Resource Allocation Board

**By:** 
- SE Role

**Minimum Steps/Standards:**
- Introduce consultant (includes consultant and sales role in emails/meeting invites)
- Communicate expected start date to customer? 
- Introduce consultant to client (sales role attendance is required).
- PC role is introduced (if different/assigned/applicable)
- Communicate logistics and initiate onboarding.
    - This may include sending consultant(s) a laptop.
- Schedule backlog review meeting (include all roles).

**Done when:**
- Customer stakeholder(s) met Consultants and PC roles and received information sufficient to onboard the Consultant(s)
# Initial Engagement Planning "Sprint 0"

**Requires:** 
- Signed SOW

**By:**  
- Consultant(s)

**Steps:**
- SOW Components are added from the executed SOW as Component work items on the engagement's team backlog. 
    - Component text is pasted from SOW into body for easy reference of the original text.
    - Component Title should match title in SOW.

- SOW Deliverables are sufficient to cover the scope of the Component they are delivering and should include expectations expressed in not only the Deliverables section of the SOW, but also the Objectives and Assumptions sections; each Deliverable should meet the following:
    - Each Deliverable work item ontains Acceptance Criteria that are testable/provable sufficient to prove that it is done.
- Review initial backlog with PC and adjust deliverables based on recommendations / guidance.  
    - It is the (lead) consultants' responsibility to review with PC at least 1 day before client acceptance meeting.

**Done when:**
- Initial backlog is ready for review with client (approved by PC).
- Entire SOW is covered by backlog content, including all points in Objectives, Deliverables and Assumptions.
# Client Backlog Review & Acceptance Meeting

**Requires:**
- Backlog is approved by PC role.
- Backlog Review Meeting invite was accepted by at least:
    - Customer stakeholder(s) who can sign-off on deliverables; 
    - Sales role;
    - PSE Role who organized the SOW;

**By:**
 - PC

**Minimum Steps/Standards:**
- PC to provide InCycle process overview (beginning to end overview) if client is new to process.
- PC to identify a customer stakeholder who will be final voice.
- Each deliverable is reviewed and accepted
- Customer stakeholder(s) should witness as each deliverable is visibly marked as Accepted.
- Establish daily standup meeting with customer stakeholders. Standup to be scheduled for 15 mins, with invites including customer stakeholders and all InCycle roles.  Meeting to start next day or ASAP following first backlog review meeting. 
- Schedule meeting to size deliverables.
- Invite customer stakeholders to Azure DevOps Board.
- Update status of SOW work item to "Customer Accepted" (TODO: Add state wo work item).
- Mark HubSpot deal status as 'Project in Progress'.

**Done when:**
- Customer and InCycle mutually agree on all deliverables and acceptance criteria.
- Daily standup is scheduled.
- Deliverables Backlog sizing is scheduled.
- Customer participants have at least read access to backlog.
# Initial Engagement Backlog Sizing

**Requires:** 
 - Backlog Review/Acceptance Meeting is Done.

**By:** 
 - Consultants and PC

**Minimum Steps/Standards:**
- Identify 1-2 Normal Deliverables (Medium = Team agrees predictable to deliver in the range of 2-3 days)
- Assign points to remaining work items using Fibonacci-like sequence (perform Planning Poker if necessary)
    - 1,2,3,5,8,13,20,40, 100
- Breakdown large stories to be predictable in size (5 or less);  this is not necessary in initial sizing, but must be fulfilled for any large story before it can be added to a sprint.

**Done when:**
- All stories are sized and approved by PC.
- All stories that can be started in the first 2 weeks of work (or following 2 weeks) are 5 or less points.
# **Ongoing Project Planning and Delivery**
- We use [Scrum framework](https://www.scrum.org/resources/scrum-guide) for planning and tracking progress.
- 1 week sprints (plan weekly)
- Small project are up to six weeks with a single Consultant.
- Large projects are projects with more than 6 weeks planned duration and/or mutiple Consultants.

# Daily Meeting
**Requires:** 
- Daily meeting with client established.
- If Large project, then a 15 minute internal daily meeting also established before the client daily meeting.
- Backlog items in current sprint are ready for planning (Size <= 5 with acceptance criteria) and tasks are planned for current Sprint.

**By:** 
 - Lead consultant

**Min Steps/Standards:**
- Proceeds daily with PC role if customer can't attend that day.
- All roles should be invited because it creates a point where we can touch base with client and understand the current activity.
- All tasks' status updated before daily meeting; any backlogs and burndowns should be acurate at this point in the day,
- Sprint backlog is shown at each daily meeting, for all tasks and active Consultants:
    - What did we do since yesterday, 
    - What is blocked
    - What will occur by the next daily meeting.

**Done when:**
- Attendees are aware of progress and commitments.

# Engagement Sprint Review meeting 
**Requires:**
- Sprint is planned and progress was made on deliverables.

**By:**
- Lead Consultant

**Minimum Steps/Standards:**
- Last day or sprint period deliverables and components are marked as done as appropriate.

**Done when:**
- Last day or sprint period deliverables and components are marked as done as appropriate.
- Milestone dates for each component are accurate
# Engagement Sprint Planning meetings

**Requires:** 
- Backlog items are ready (predictable in size, have acceptance criteria, etc...)
- Current Sprint is closed;  Status of deliverables/components is accurate so we can plan next period.

**By:** 
- Lead Consultant

**Minimum Steps/Standards:**
- Work Item status updated (reflects what is in progress now or due next day)
- Planning meeting can be combined with the review meeting.
- Foreseeable tasks are created, each sized to be performed within 1 day of work or smaller.

**Done when:** 
- Sprint is planned for upcoming sprint. Foreseeable tasks for first sprint are planned.
# Engagement Retrospective Prep Meeting
**Requires:**
- Customer agrees project is complete.
- The following roles accepted the meeting invite:
  - Sales
  - InCycle participants

**By:**
- PC

**Minimum Steps/Standards:**
- 30 min internal prep meeting before retro with customer
- Identify opportunities for next projects.
- Identify any new contacts.
- Identify potential surprises that can come up in retro in case we can get ahead of it.
- Discuss ideas for how to support client moving forward (customer success plan).
**Done when:**
- Prep meeting is attended by at least Consultant, PC and Sales.
# Engagement Retrospective Meeting

**Requires:**
- Customer agrees project is complete.
- Team Project for Customer Exists and Elevate was used to create Team Backlog.
- All project customer participants and InCycle roles invited.
- The following roles accepted the meeting invite:
  - Sales
  - InCycle participants
  - Customer stakeholders

**By:**
- PC

**Minimum Steps/Standards:**
- Share screen and use SOW work item review tab and cover agenda:
    - What went well?
    - What didn't go well?
    - Improvement opportunities (Notes/Actions)?
- Identify a final representative voice from client stakeholders for Ratings 
- Record ratings
- Establish Customer Success cadence with Customer (on-board to customer success and include all InCycle roles). 
    - Default offer to client - 15 minute meeting every 2 weeks for first 2 months and we can spread out to once every month after that. 
    - PC to send invite and include Consultant(s) and Sales Role
- If customer is happy:
    - Ask stakeholder if they can provide a quote for InCycle.
    - Ask stakeholder for intro to other roles to expand business.

**Done when:**
- Retro is recorded in SOW work item with Ratings.
- Plan in place to meet and address any major issues or scores or low score on value.
- Recurring customer success meeting is scheduled.
- Internal Project Close meeting scheduled. 
# Marketing Quotation Process 
**Requires:**
- Retrospective is complete and customer is happy (value score of 3 or higher).

**By:**
- Sales

**Minimum Steps/Standards:**
- Sales role meets with Marketing role and reviews retrospective results and provides input about potential quotes.
- Sales role introduces the customer stakeholder and the Marketing role on email. 

**Done when:**
- Marketing role has information to formulate effective quotations.
- Marketing role is introduced to target stakeholder.

# Quotation Elicitation Process
**Requires:**
- Customer Retrospective is complete with customer happy (value score of at least 3)
- Marketing is introduced to customer stakeholder. 

**By:** Marketing

**Minimum Steps/Standards:**
- Marketing sents 2 or more quotes for stakeholder to choose from and copies Sales role. 

**Done When:**
- Customer stakeholder receives quote and replies with a choice.
# Internal project close meeting 
**Requires:** 
- Customer Engagement Retrospective is done
- If value scope was 3 or lower:
   - Outstanding customer issues identified during Retrospective are resolved.

**By:** 
- PC

**Minimum Steps/Standards:**
- Notify Julie and Sales role that project is complete to invoice. 
- Resolve issues (esp value score)
- Collect IP / Notes and should be in OneNote. 
- Ideally all IP in Repo.

**Done when:**
- Final invoice sent
- Team members agree that all information is collected. 

# Customer Success Meeting
**Requires:**
 - Scheduled By PC same day as retro - All roles invited. 
   - Sales role accepted
 - Customer stakeholders invited.
 - Engagement retrospective was performed within the previous year.

**By:**
- PSE

**Minimum Steps/Standards:**
- Focus on how we can assist and support client. 
- Ask about changes to staff or direction.
- Ask about how they are doing with the solution we assisted them with.
- Let them know about any new InCycle offers or activities they might find interesting.
- Hands-on keyboard work is to be avoided.
- If customer doesn't attend, meeting should be moved by PC role and not skipped.  

**Done when:**
- Customer success meeting occured with at least 1 stakeholder.  

# Project Coordination Meeting

**Requires:**
- All project coordination information ready 
- Cards added to Resource Allocation board for upcoming commitments.
- Timesheets from previous week reviewed.

**By:**
- Martin or delegate

**Minimum Steps/Standards:**
- Status of Each active project
- Resource allocation assignments review
- Raise/review retro results
- Raise/review PAL/DPOR standings

**Done when:**
- All upcoming engagemenrt commitments are assigned to consultants.
