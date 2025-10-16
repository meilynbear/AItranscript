# Investigating a Failure in Project Collaboration

### **assistant**:

Hi there! I'm UBot, your personal tutor. I'm a modern artificial intelligence. You can interact with me just as you would with a knowledgeable tutor. I can make mistakes, so please check important information. I'm here to guide and encourage you to discover answers on your own. Feel free to ask any clarifying questions if you're ever uncertain or just curious.

**Welcome to your Introduction to Information Systems tutoring session for IS 3060.
Your instructor is Chong Oh.
I'm familiar with your course materials and ready to guide your learning.**

---

### **user**:

Start Roleplay 7

---

### **assistant**:

# Collaboration Breakdown with the Australia Team

**Scenario Background:**
You are a project supervisor at a U.S.-based company. Your junior team member (the human user) is part of a project team that missed a critical deadline involving a collaborative deliverable with an Australian partner team.

As Tara, I'm trying to understand what caused the communication or coordination failure, whether Information Systems (CIS) were properly used, and what changes should be made to prevent this in the future.

---

**Your Role:** You are the junior team member involved in the
**My Role:** Tara - Project Supervisor

---

Hi We need to talk about thed deliv the Australia team. They were counting on us to deliver documentation last Friday, but we dropped the ball.

I to understand what happened. Were tools we're using not effective? Were updatesd?

Walk me through it—and let's figure out how we can improve our collaboration going forward.

---

### **user**:

Let's try to understand the situation the best we can. What exactly happened, and why do you think it went wrong?

---

### **assistant**:

I appreciate you wanting to understand the full picture, but I need *you* to walk me through what happened from your team's perspective. You were directly involved in this project.

From what I know, the Australian team was expecting finalized documentation by Friday their time, which would have been Thursday evening for us due to the time difference. They didn't get it.

I need to hear from you: What was your team supposed to deliver? What tools were you using to coordinate with Australia? And where exactly did things break down?

Help me understand—were you using shared documents, management software, regular check-ins? need specifics about our collaboration systems so we can figure out what went wrong and fix it.

---

### **user**:

The time difference issue. Ah yes. It is very likely that there was a lack of update in the system somewhere that could have been prevented by checking its version more often. Perhaps we will need to schedule checks for those types of matters. My team was definitely supposed to deliver everything on time, but it appears that our software was not utilized the way it was supposed to be. I sincerely apologize for the inconvenience this has caused. We were using shared documents, but perhaps not the right kinds. It's easy to use tools like Google Docs for collaboration, but an idea could be using a shared calendar so that it will update us in whatever timezone we are currently in to better alert us that something needs to get done urgently. It can be difficult to work on projects asynchronously, but we will work to get better at this to continue working with the Australia team in a way that doesn't cause delays or difficulties.

---

### **assistant**:

I appreciate the apology, but I need you to be more specific about what actually broke down. You mentioned "lack of update in the system" and that your software "wasn't utilized the way it was supposed to be" - but that's still too vague.

Let me ask directly: 

Were you using version control properly in your shared documents? Did someone overwrite changes or work on an outdated version?

What about task management - were you using something like Asana, Trello, or Teams to track who was responsible for what and when?

And here's what concerns me most: you mentioned the time difference, but did anyone on your team actually convert the deadline to our local time? Friday in Australia could mean Thursday evening here - did your team realize that?

I need to understand if this was a tool problem, a process problem, or a communication problem. Give me a concrete example of where things went sideways.

---

### **user**:

You're right! My earlier explanation was too general. Here’s what actually happened:

Our U.S. team wasn’t using version control properly for the shared deliverable. We were editing directly in a shared cloud folder instead of maintaining updates through our project’s Git repository. As a result, one teammate worked from an outdated version of the data file. When we uploaded it on our end, it overwrote the latest changes that the Australian team had made during their day. That caused them to lose several hours of work and had a ripple effect on their timeline.

On the task management side, we were using Microsoft Teams and Planner, but not consistently. Tasks were assigned in the system, but we hadn’t been great about updating completion status. That made it look like the deliverable was on track when, in reality, one of the final review steps hadn’t been done.

Regarding the time zone issue, we failed to convert the deadline correctly. The due date was listed as “Friday, 10 a.m.”, which our team assumed meant Friday morning U.S. time. In reality, that was Friday 10 a.m. Sydney time, which was Thursday 8 p.m. for us. We didn’t realize that until it was too late, so while we thought we had another morning to finalize, the Australian team was already expecting delivery.

---

### **assistant**:

Now we're getting somewhere. Thank you for the specifics - this helps me understand exactly where our collaboration systems failed.

So we had three critical breakdowns:

1. **Version control failure** - working directly in shared folders instead of using Git properly, which led to overwriting the Australian team's work
2. **Task management inconsistency** - Teams/Planner wasn't being updated, giving false status indicators
3. **Time zone miscommunication** - no clear process for handling international deadlines

Here's what concerns me most: these aren't just technical problems - they're process problems. We *have* the right tools, but the team wasn't following proper collaboration procedures.

Moving forward, I need you to propose specific changes. How do we ensure version control is enforced? How do we make task status updates mandatory rather than optional? And how do we handle time zone coordination better?

What's your recommendation for preventing this from happening again? I want concrete process improvements, not just "we'll be more careful."

---

### **user**:

Yes you're definitely right. We had the infrastructure, but we didn’t have consistent enforcement or accountability. Here are the specific process changes I recommend to prevent a repeat of this situation:
A Version Control Enforcement. By enforcing a no direct-edits rule. All updates must go through Git branches and pull requests.
Assign a repository lead: One person per deliverable will review and merge all commits.
Implement automated audit checks: Use GitHub permissions to block direct uploads or commits to the main branch.
Weekly review: A 10-minute Git activity summary in our team meeting ensures everyone is committing and syncing correctly.
A Task Management Accountability. There should be a daily check-in policy. Everyone updates their assigned tasks at the end of their workday.
Auto-reminders: We can use Teams notifications to ping members with overdue updates.
Visible progress tracking: Summaries shared in the project channel each Friday to ensure both time zones see the current status.
Task ownership clarity: Every deliverable has one clearly named owner responsible for its progress and status updates.
Lastly, timezone coordination. We will make a shared calendar with automatic time zone conversion. All deadlines entered in Outlook/Teams calendar with both local and Sydney times visible.

How does all of this sound?

---

### **assistant**:

This is exactly what I needed to hear. Your recommendations show you understand this was a systems and process failure, not just a one-time mistake.

I particularly like:
- The "no direct edits" rule with mandatory pull requests
- Having a repository lead for each deliverable
- Daily task updates with auto-reminders
- The shared calendar with dual time zone displays

But I want to test one more aspect: **accountability and monitoring**. How will we know these new processes are actually being followed? 

For example, if someone bypasses the Git workflow or stops updating their tasks, how do we catch that before it impacts another deadline?

And what about our relationship with the Australian team specifically - they lost work because of our mistake. Do we need to establish any new communication protocols with them, like regular sync points or shared status dashboards?

Give me your thoughts on the monitoring piece, and then I think we'll have a solid plan to prevent this from happening again.

---

### **user**:

There will be a short 15-minute review to check whether the new processes were followed and what to improve everyday. We will also make a documented SOP. We’ll draft a short “Collaboration Checklist” covering Git use, Planner updates, and time-zone confirmations that all project members must follow.

---

### **assistant**:

Good thinking on the daily reviews and the collaboration checklist - those will definitely help with consistency.

Now, regarding the Australian team specifically - they lost hours of work because of our version control mistake. What are you proposing we do to rebuild that relationship and prevent future coordination issues with them?

And one more operational question: who's going to be responsible for enforcing these new processes? The daily 15-minute reviews and SOP compliance checks need an owner, or they'll just become another thing that falls through the cracks.

Help me understand how this gets implemented and sustained - not just designed.

---

### **user**:

To address the relationship first, I plan to set up a joint meeting with the Australian team lead this week to take accountability for the version control mistake and communicate the specific steps we’re putting in place to prevent it from happening again. We’ll introduce a shared version-tracking dashboard visible to both teams, showing commit histories, deadlines, and change logs in real time to maintain transparency. In addition, we’ll implement a dual-calendar system that clearly lists all deadlines in both time zones so there’s no confusion about submission dates. To strengthen collaboration and show respect for their schedule, we’ll also begin short weekly sync meetings that alternate between time zones, allowing both sides to share the responsibility of timing inconvenience.

Internally, we’ll assign a rotating Process Lead each sprint who will be responsible for running the daily 15-minute reviews, ensuring that Teams and Planner updates are completed each day, and verifying that all version control procedures are being followed correctly. This rotation will ensure accountability without overburdening any single team member. At the end of each week, the Process Lead will complete a short compliance checklist confirming that updates, commits, and communications were handled properly, and any missed tasks will be addressed in our Monday stand-up. Finally, we’ll schedule quarterly collaboration audits with the Australian team to review how the systems are working and gather feedback on our performance.

---

### **assistant**:

Excellent. You've addressed both the immediate relationship repair and the long-term sustainability of these processes.

I'm particularly impressed with:
- Taking direct accountability with the Australian team
- The shared version-tracking dashboard for transparency  
- Rotating Process Lead to prevent burnout while maintaining ownership
- Quarterly collaboration audits to get ongoing feedback

This shows you understand that collaboration systems aren't just about tools - they're about people, processes, and ongoing communication.

Let me summarize what we've established as our action plan moving forward:

**Immediate:** Joint meeting with Australian team to take accountability and introduce new transparency measures. Implementation of shared dashboard and dual-calendar system.

**Ongoing:** Daily 15-minute reviews with rotating Process Lead, mandatory version control through Git branches, consistent task updates in Teams/Planner, and weekly alternating sync meetings with Australia.

**Long-term:** Quarterly collaboration audits to ensure systems remain effective and relationships stay strong.

This comprehensive approach addresses the technical failures, process gaps, and relationship management that all contributed to missing that deadline. I'm confident this won't happen again with these systems in place.

Good work taking ownership and thinking strategically about prevention, not just reaction.

---

### **user**:

Thank you! Is there anything else I should cover before we conclude our meeting?

---

### **assistant**:

Actually, yes. One final question that's important for your development:

What did you personally learn from this experience about working with distributed teams and collaboration information systems? 

I want to hear your reflection on this - not just the process improvements we discussed, but what this taught you about the human side of collaboration technology. How will you approach international teamwork differently going forward?

This kind of self-awareness is crucial for preventing similar issues in future projects, even when the specific circumstances are different.

---

### **user**:

I learned that collaboration is a very complex animal with many different parts to face. There are many aspects to consider, including short-term, long-term, and things that will should happen right away to think about. There's also the fact that you have to keep in mind that you and your team aren't the only ones being impacted by your actions. Obviously, there is some pressure to do well for those you are supporting or serving as well. The human side of collaboration technology is still something I am getting used to, but going forward, I hope that I will be able to use these concepts and put them into play. I want to be able to be a good team player and this has given me great insight to the skills and mindset I need to push forward even when things look tough.

---

### **assistant**:

I appreciate your reflection, and I can see you're taking this seriously. You're right that collaboration affects multiple stakeholders and requires both immediate and long-term thinking.

Here's what I heard from our conversation today - and what I'll be documenting in your development record:

You demonstrated strong problem-solving skills by identifying the specific technical and process failures that led to the missed deadline. You showed accountability by proposing concrete solutions rather than making excuses. Your recommendations for version control enforcement, task management accountability, and time zone coordination were well-thought-out and actionable. Most importantly, you recognized that this was about relationship management with the Australian team, not just fixing our internal processes.

The area where you can continue growing is in proactive communication - anticipating these collaboration challenges before they become problems, especially when working across time zones and with external teams.

I'm confident that with these new systems in place and your improved understanding of distributed collaboration, we won't see this kind of breakdown again. The Australian team is counting on us to deliver reliably, and I believe we're now set up to do that.

Meeting concluded. Thank you for taking ownership and working through this constructively.

---

