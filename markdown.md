# AdviseInvest Sales Process Optimization Analysis

### **assistant**:

Hi there! I'm UBot, your personal tutor. I'm a modern artificial intelligence. You can interact with me just as you would with a knowledgeable tutor. I can make mistakes, so please check important information. I'm here to guide and encourage you to discover answers on your own. Feel free to ask any clarifying questions if you're ever uncertain or just curious.

**Welcome to your Business Analytics tutoring session for IS 4487.
Your instructor is Jiaxuan Peng.
I'm familiar with your course materials and ready to guide your learning.**

---

### **user**:

Start AdviseInvest Interview Scenario

---

### **assistant**:

Hello! I'm the Director of Sales here at AdviseInvest. I’m glad we could sit down. 

As you might have heard, we have a significant operational bottleneck that's costing us a lot of time and money. We have a great top-of-funnel flow—people are signing up and scheduling calls—but about half of those scheduled appointments end in a "no-answer." Our sales reps are sitting there with empty blocks of time, and it’s making our staffing incredibly inefficient.

I'm looking for some analytical insight into how we can fix this. Where would you like to start?

---

### **user**:

Hi! As a business analyst, I'm happy to take a look at this with you and sort this out. Let's start by trying to clarify the business problem and where that stems from. Who are the stakeholders in this, firstly?

---

### **assistant**:

That's a great place to start. In terms of stakeholders, I’m the primary owner of the outcome since this lands squarely on my sales targets and budget. 

Beyond me, you have:
*   **The Sales Representatives:** They are the ones dealing with the frustration of "dead air" when a customer doesn't pick up. Their productivity and morale are directly impacted.
*   **The Operations/Staffing Team:** They handle the scheduling of these four-person shifts. They're currently guessing how many people we need based on the total number of calls, not the number of *successful* calls.
*   **The Finance Team:** They're keeping a close eye on our venture funding and aren't happy about paying for idle labor.
*   **Our Customers:** Specifically the ones who actually *want* to talk to us but might be getting crowded out by a scheduling system that isn't working efficiently.

From your perspective as an analyst, why is identifying these specific groups important before we look at the data?

---

### **user**:

Identifying specific groups before we look at the data is very important because then we know where to focus our energy and what we need to do based on who they are and what they stand to lose or gain from this. A big part of business understanding is being specific and measurable so that we don't waste our efforts solving a problem that isn't important. We also need to make sure that there is some sort of action we can take and that is is reasonable. In this case, when looking at the stakeholders, we can already start poking some holes in where we can improve. The staffing team is guessing how many people are needed based on total number of calls and not the number of successful calls. That should change. 
With this in mind, what are some of the goals you have before taking a look at the data?

---

### **assistant**:

I appreciate that perspective. You're exactly right—if we can't tie our analysis to a specific action for those stakeholders, we're just spinning our wheels.

Regarding my goals, as the Director of Sales, I'm looking for a few specific outcomes:

1.  **Reduced Idle Time:** I want to significantly decrease the amount of time my reps spend staring at a ticking clock when a customer doesn't answer. 
2.  **Predictability:** I want to know *before* the hour starts which calls are actually going to happen so we can staff accordingly.
3.  **Revenue Growth:** Ultimately, if we stop wasting half our time on "no-answers," we should be able to get more people into those Beginner, Intermediate, and Advanced plans without hiring more staff.

To make this **measurable**, I’d love to see our "no-answer" rate drop significantly, or at least see our rep utilization rate move much higher than it is now.

Thinking back to the **Business Objective** vs. the **Data Mining Goal** concept we usually follow: if my business objective is "Increase sales rep utilization by 20%," how would you translate that into a specific task for your analytics team?

---

### **user**:

That's a fantastic first start. This goal is measurable and specific (with numerical values) and we are able to use that to compare to our numbers in the future. How would you utilize this business objective to create a specific task?

---

### **assistant**:

That is exactly what I am hoping you can tell me! Since I run the Sales department, I think in terms of people, schedules, and revenue. You’re the one who understands how to bridge the gap between my operational headaches and a technical solution.

To help you frame this, think about those customers who schedule a call but don't pick up. If we have documentation on their past behavior or their profile forms, what is the "data task" that would help us fix the staffing issue? Specifically, what would your team try to **predict** about those 8 scheduled calls we have every hour?

---

### **user**:

Let's see, so if we are calling previous customers who haven't picked up before already, then we can document how many times we have already called that customer in some kind of database and remove them from our calling list after the second/third time they don't pick up. That way, we're trying enough times, but marking down who we've already tried to call and had a pattern of not picking up and utilizing this information to figure out where to spend our efforts and energy. My team would try to predict whether or not that caller will pick up and have another/a few other options of other people to call in case that first one falls through since they're expecting them not to pick up.

---

### **assistant**:

That’s a very interesting approach! You've identified a key **Data Mining Goal**: predicting the probability that a customer will answer the phone. If we could assign a "Likelihood to Answer" score to every scheduled call, we could certainly change how we prioritize them.

However, as the Director of Sales, I need to think about the **Assumptions and Constraints** of our operations. For instance, our current policy is that if someone schedules a specific time slot, we *must* attempt that call at that time because it's a scheduled appointment.

If your team builds a model that says, "Customer A has a 90% chance of not picking up," and we decide to have a "backup" person for the rep to call:

1.  What happens if both people actually pick up at the same time? 
2.  How might that affect the **Success Criteria** regarding customer satisfaction?

Before we decide on a specific "backup" strategy, are there other **risks or constraints** you think we should define regarding our sales representatives' time or our legal/ethical obligations to those who scheduled an appointment?

---

### **user**:

You're right about that! I forgot that these calls were done by appointment. In that case, a backup option would need some other tweaks such as allowing customers to book an appointment and notifying them that if they fail to pick up their phone when the appointment time occurs. When choosing an appointment, a customer can pick their appointment time but also have the option to be notified of an earlier/different call time if that opens up (by text, for example, and confirm whether or not they would like to be called).

Oh! This actually gives me an idea. What if customers were notified an hour to thirty minutes in advance about their appointment over text? And they'd have to fill out a short form confirming their attendance and that they will pick up the phone, so this serves as a reminder and as a means to notify the caller that the appointment is more likely to be followed through on. If the customer does not respond to this text, then the caller will not call that customer.

---

### **assistant**:

I like your thinking—adding a confirmation step definitely addresses the "Business Understanding" of how the current process works! From a sales perspective, that would certainly filter out the non-responders.

However, let's step back into our **analyst role** for a moment. If we implement a requirement that they *must* confirm via text, we might accidentally lower our total number of conversations (since even some interested people are forgetful or don't check their texts). 

Instead of changing the whole business process immediately, let's look at what we can do with **Predictive Analytics** using the data we already have from Steps 1 and 2 (the account opening and the financial profile form).

If we want to keep the "no-answer" rate as our primary metric, what are some **Success Criteria** you would suggest for an analytics model? For example:
*   How accurate would a prediction need to be for you to trust it with my staffing budget?
*   How would we measure if the model is actually "winning" compared to our current 50% failure rate?

---

### **user**:

Right! Focusing back, some success criteria that we could apply include decreasing the 50% failure rate. What if we changed the model to a 75% precision rate? If the model can more accurately and confidently flag a call as "no-answer" then you will be better able to take action and not waste time.
Another idea is simply to reduce idle time. Time wasted is money wasted. How about something like decrease wasted idle time by at least 25%? If you're able to flag out the calls that won't be answered, then your reps will spend less time staring off into the void and actually talking to people and therefore their morale will be higher as well.

---

### **assistant**:

Those are strong, measurable **Success Criteria**. A 75% precision rate would be a massive improvement over our current "coin flip" situation, and cutting idle time by 25% would definitely make the Finance team breathe easier.

Now, let's look at the **Data Understanding** side of things. You mentioned using the profile forms. As the Director of Sales, I can tell you that those forms capture things like:
*   Age
*   Annual Income
*   Current Debt
*   Investment Goals (Retirement, Home Purchase, etc.)
*   Time of day they chose for the call

From a **Business Understanding** perspective, why might one of those variables (like "Income" or "Time of Day") be a potential "predictor" for whether someone answers the phone? And are there any **Assumptions** we are making about the relationship between a customer's financial health and their phone habits?

---

### **user**:

These variables are potential predictors for whether or not someone answers because of what we know about the world. Times like noon or 5-6 are typically times when people are preparing to eat, or are busy with their meals. Someone with a really low income might not be as interested in a business pitch as much as they are concerned with making money, and someone with a really high salary might be a little too busy making money to care, or that can be taken other ways as well. A customer's financial health can greatly impact their phone habits. 
This company in particular is made to help people manage their finances. Questions we can ask by looking at the data include, how old are they? If the customer is 18-23 then likely we can make the assumption that they are a student. Students can be busy with school and therefore may not be as likely to answer around the times of 9 am to 5 pm. But they may be more interested in managing money because they are in their earlier years of financial literacy. If the customer is over 60 then maybe they aren't really too interested because they've already went through most of their life and know how they want to use their money and there's not exactly a lot more time for them.

---

### **assistant**:

That is some great **Data-Analytic Thinking**! You are starting to form "hypotheses"—essentially educated guesses about how specific attributes in the data might relate to our business problem.

For example, your point about the **"Time of Day"** is a classic operational insight. If we find that calls scheduled at 2:00 PM on a Tuesday have a much higher "answer rate" than those at 8:00 AM, that’s a finding we can immediately use for staffing.

However, we need to be careful with **Assumptions**. You mentioned that someone over 60 might not be interested—but what if our data actually shows they are the group most likely to answer because they have the most free time or are nearing retirement and are anxious about their savings?

To wrap up the **Business Understanding** portion of our interview, I have one final question for you:

As the Director of Sales, I’m worried about **Risks**. If we use a model to decide how to staff our reps, and the model is wrong (e.g., it predicts a "no-answer" but the customer actually picks up), what is the potential **Business Risk** to our reputation or our bottom line? And how would you suggest we mitigate that risk in our project plan?

---

### **user**:

If the model is wrong it could have a negative impact since obviously it predicted wrong. Ways we can mitigate that risk in the project plan include adjusting the model as we go. It doesn't have to be cemented in stone, but rather adjusted flexibly kind of like how AI learns. Does that answer your question, or in what specific ways are you thinking it might harm reputation?

---

### **assistant**:

You hit on the flexibility part, but I'm thinking about the customer's perspective. If we predict a "no-answer" and therefore don't staff a rep for that slot, and then the customer *does* pick up the phone (or waits by it), they’re left hanging. 

The **reputational risk** is that a customer who was ready to buy a "Advanced Plan" now thinks AdviseInvest is unprofessional because we missed their scheduled appointment. That could lead to bad reviews or lost "Customer Lifetime Value."

To mitigate this, perhaps our project plan should include an **Evaluation Phase** where we don't just look at "Accuracy" but specifically look at "False Negatives" (predicting a no-show when they actually showed up). We could also suggest a small "buffer" of on-call staff during high-risk hours.

We’ve covered a lot of ground! We’ve identified:
*   **Stakeholders** (Sales, Ops, Finance, Customers)
*   **Business Objectives** (Increase utilization, reduce idle time)
*   **Data Mining Goals** (Predict probability of answering)
*   **Success Metrics** (75% precision, 25% reduction in idle time)
*   **Risks & Constraints** (Reputational damage from missed appointments, policy constraints)

Would you like to continue the interview, or would you like me to **evaluate your performance** for your Project Charter preparation?

---

### **user**:

Having a buffer of on-call staff during high-risk hours would be a smart idea! Especially when analyzing where these high-risk hours are after a while and staffing correctly there in order to reduce the risk of calls that are expected but never followed through on. 
Go ahead and evaluate my performance!

---

### **assistant**:

It was a pleasure working through this with you! You demonstrated a strong grasp of how to connect operational headaches to analytical tasks.

### **Interview Evaluation & Feedback**

**Overall Rating: 8.5/10**

**What you did well:**
*   **Focus on Measurability:** You were quick to establish concrete success criteria (e.g., 75% precision and 25% reduction in idle time). This is vital for a Project Charter because "better" isn't a goal, but "25% less idle time" is.
*   **Hypothesis Generation:** You did a great job theorizing how specific variables (Age, Income, Time of Day) might influence behavior. This shows you are thinking like a data scientist before even touching the code.
*   **Adaptability:** When I challenged your "backup caller" idea with business constraints (the appointment policy), you immediately pivoted to think about process changes like text confirmations.

**Areas for Improvement (Business Understanding):**
*   **Deepening the Risk Analysis:** When I asked about reputational risk, your first instinct was a technical solution (adjusting the model). In the **Business Understanding** phase, it’s important to first define the *business* impact of a failure (e.g., "A missed call equals a lost \$2,000 conversion and a 1-star review") before jumping to the technical fix.
*   **Resource Constraints:** In a future interview, you might ask more about the *cost* of the reps' time or the *budget* for the analytics project. Understanding the "Constraints" part of CRISP-DM often involves knowing if there is a budget for new tools (like the text-reminder system you suggested).

**Conclusion:**
You have more than enough information to fill out a high-quality **Project Charter**. You’ve identified the "Who," "Why," and "How" of the AdviseInvest staffing problem. 

Great job helping me frame this project! Do you have any questions about the CRISP-DM process before you head back to the analytics lab?

---

### **user**:

That's all for today! Thank you for challenging me and enabling me to dive into this!

---

### **assistant**:

You're very welcome! I'm glad I could help you practice those critical stakeholder interview skills. 

Remember, the **Business Understanding** phase is often the most important part of the entire **CRISP-DM** lifecycle—if you don't get the "why" and the "who" right, the most sophisticated Python model in the world won't save the project.

Good luck with your education and studies at the University of Utah! If you need help framing business problems or diving into the next phases of your analytics coursework, don't hesitate to reach out. **Go Utes!**

---

