# Explaining the Rationale Behind Agile Adoption in a Mid-Sized Technology Company

### **assistant**:

Hi there! I'm UBot, your personal tutor. I'm a modern artificial intelligence. You can interact with me just as you would with a knowledgeable tutor. I can make mistakes, so please check important information. I'm here to guide and encourage you to discover answers on your own. Feel free to ask any clarifying questions if you're ever uncertain or just curious.

**Welcome to your Introduction to Information Systems tutoring session for IS 3060.
Your instructor is Chong Oh.
I'm familiar with your course materials and ready to guide your learning.**

---

### **user**:

Start Roleplay 12

---

### **assistant**:

## Background: Information Systems Development Challenges

**Scenario:** You are a Chief Information Officer (CIO) at a mid-sized technology company that has recently transitioned from traditional Waterfall/SDLC development methods to Agile methodology. 

**Your Role:** CIO - You need to explain and defend this strategic shift to development team members.

**My Role:** I will play Riley, a senior software engineer who is frustrated with the new Agile approach and misses the structured nature of the previous development process.

**Expectations:** 
- Help me understand the business rationale behind Agile adoption
- Address my concerns about process changes and workflow disruptions  
- Explain how Agile benefits both the business and developers
- Use Chapter 12 concepts about systems development methodologies

Let's begin the roleplay!

---

Look, I'm trying to stay open-minded—but this Agile rollout has been frustrating.

Every week the scope changes, the stand-ups feel like a waste of time, and it's hard to know what's finished.

Honestly, I liked the structure of our old process better. Can you help me understand why we're doing this?

---

### **user**:

Agile is helpful in a number of ways. SDLC development can be good, but there are cons that determine the tradeoff. So we know the previous waterfall/SDLC method is a way to define the system, maintain the system, determine requirements, design system components, and implement the system. It's a very linear process for software development, and while it may be true that this can simplify things, it concludes with a big delivery at the end, which can make the process throughout more challenging and lengthy. Let's take a look at what Agile is. Agile is adaptive, and breaks parts down into pieces with continuous improvement throughout and delivering value through small increments. If we think about it, Agile is better for projects with changing requirements. You are free to test and design as you go. There is no need to be stressed about implementing a change or making everything "perfect" from the get-go because things don't need to be. Let me know exactly where in your concerns I should address now that you have a brief visualization of what the difference between the two are, which isn't exactly relevant to convincing you quite yet.

---

### **assistant**:

That's a helpful overview, but I'm still not seeing how this helps me day-to-day.

You say Agile handles changing requirements better—but that's exactly my problem. In the old system, once we locked in requirements during the analysis phase, I knew what I was building. Now it feels like we're constantly pivoting.

And you mention "continuous improvement" and "small increments," but honestly, it feels more like we're never actually finishing anything. We'll get halfway through a feature, then suddenly product owner wants to change direction based on some user feedback.

How is that more efficient than just getting solid requirements upfront and building it right first time?

---

### **user**:

Let me break down why this is happening and why, from a business and technical perspective, it’s actually designed to help you, not disrupt you.

First, the reason requirements felt so stable before is because Waterfall forces stability early, during the analysis phase. But the tradeoff is that we were often building against assumptions that were already outdated by the time development finished. Waterfall works well only when requirements are predictable and unchanging. But that’s not the environment we operate in anymore. In the old process, we gathered requirements upfront, locked them in, and delivered a big system months later. On paper, that felt organized. In reality, we usually discovered too late that: Users didn’t actually want certain features, requirements didn’t reflect real workflows, competitors had moved faster, or tech constraints changed.
Agile embraces the truth that we learn a lot only after we start building. So when the product owner shifts direction based on user feedback, that isn’t rework, it’s course correction. It prevents us from spending three months building something users ultimately reject.

Also "We never really finish anything" is an indicator of our slices being too big, not that Agile is flawed. If a feature is sitting half-done when new information arrives, that points to a planning issue, not an Agile problem. Agile only works when we break work into truly small, independently valuable increments. If we size stories better, you’ll experience: quick wins every sprint, clear definitions of done, less mid-sprint disruption, and a sense of real progress!
This is something we can adjust together. Agile is flexible by design, including how we structure our workflow.

---

### **assistant**:

Okay, I can see the logic there—especially about building against outdated assumptions. That does make sense.

But here's what's still bugging me: the constant meetings. Stand-ups every morning, sprint planning, retrospectives, demos... it feels like I'm spending more time talking about work than actually doing it.

In the old system, once we had our specs, I could just put my head down and code for weeks without interruption. Now I'm constantly context-switching between meetings and development work

And another thing—you mention "quick wins every sprint," but honestly, some of the stuff we're delivering feels half-baked. Like we're rushing things out just to hit sprint deadlines instead of taking the time to build them properly.

How is that better quality than when we had time to really think through and polish our work?

---

### **user**:

The issue with the number of meetings, for example, isn’t a sign that Agile is flawed. It’s a sign that we need to refine how we’re using it. Agile ceremonies aren’t meant to take over your day. Stand-ups should be quick check-ins to remove blockers, sprint planning happens only once per cycle instead of the huge planning phase we used to have, and retrospectives and demos are meant to give the team space to improve the process and validate work early. If these ceremonies are dragging or eating into your coding time, we need to tighten them up and protect larger blocks of uninterrupted development time. That is absolutely something we can adjust.

I also understand the appeal of being able to put your head down and code for long stretches. Deep focus is where engineers do their best work. But one of the biggest issues we learned from the old SDLC approach is that long periods of isolated development often meant we wouldn’t discover misalignment or missing requirements until late in the project, when changes became far more expensive and frustrating. Agile’s shorter, more frequent alignment points may feel like interruptions, but they’re actually there to prevent the kind of late-stage rework that used to derail projects. A small correction early on is far cheaper, and far less painful, than a large rewrite months later.

Regarding the feeling that our sprint outputs are “half-baked,” that is an important concern, and I want to emphasize that this is not what Agile is supposed to feel like. When work feels rushed or incomplete, the problem is usually in how the stories are being sized, estimated, or prioritized. Agile is designed for small, fully complete, high-quality increments. If we’re trying to cram too much into a sprint, or if acceptance criteria aren’t clear, or if the definition of “done” keeps shifting, then it’s absolutely fair for the work to feel rushed. That’s a breakdown in the process, not an expectation that speed should come before quality. In fact, Agile inherently supports higher quality because testing, refinement, and validation happen continuously rather than all at once at the end.

This means the slightly “messier” feeling you’re experiencing isn’t a sign that the final product will be lower quality. It’s simply the nature of exposing work in progress earlier rather than keeping everything hidden until a big reveal at the end, the way Waterfall projects do. The polish still happens, but it happens iteratively and with user feedback baked in, which ultimately reduces technical debt and increases confidence that we’re building the right thing.

Let me ask you directly, because this will help us fix the right problem: what part feels the most painful right now? Is it the number of meetings, the length of meetings, the pressure to complete too much in a sprint, or feeling like you don’t have enough influence over how the work gets sliced and estimated? Each of those has a different solution, and none of them require sacrificing code quality. Let’s pinpoint where the real friction is so we can adjust the process to work for you

---

### **assistant**:

You know what, that actually helps a lot. When you break it down like that, I can see the difference between Agile done right versus what we might be experiencing.

The most painful part right now is probably the sprint sizing issue you mentioned. We keep committing to stories that seem reasonable in planning, but then halfway through we realize they're way bigger than expected. So we're either rushing to finish or carrying things over, which makes it feel like we never really complete anything cleanly.

And honestly? I think part of my frustration is that I don't feel like I have much input on how work gets broken down. The product owner comes in with these big feature requests, and sometimes feels like we're just trying to cram them into two-week boxes instead of really thinking through what makes sense technically.

I guess my question is: how do we get better at this? Because if what're describing is how Agile should work—with proper story sizing and real definition of done—that sounds way better than what we're doing now.

Can we fix the process without scrapping it entirely?

---

### **user**:

If the product owner is bringing in large, vague features and the team feels pressured to fit them into a two-week sprint, that’s not Agile. That’s just Waterfall work being forced through Agile rituals. A big part of the correction involves shifting more ownership to the development team. You and the other engineers should be actively shaping how each feature gets broken down, what is technically feasible within a sprint, and what a true “done” increment looks like. The product owner defines the “what,” but the development team absolutely owns the “how,” the “how much,” and the “how long.”

When we do this properly, story sizing becomes far more accurate because it’s based on real technical insight rather than assumptions made in isolation. And you’re right, when a story is oversized, everything gets thrown off. You end up rushing, carrying work over, or feeling like nothing ever reaches a clean finish. That’s not a failure of Agile; it’s a signal that we’re slicing stories too large or too vaguely. 

As for improving the process, the fix is both simple and powerful: we need to involve the development team earlier and more deeply in backlog refinement. That time shouldn’t just be a meeting; it should be the forum where you challenge unclear requirements, push back on oversized work, break features into sensible increments, and ensure the acceptance criteria match what’s technically realistic. When that happens, two things improve immediately: the team commits to the right amount of work, and each sprint produces increments that actually feel finished. That’s the “quick wins” Agile promises, complete slices of value, not half-built features.

So yes, we can absolutely fix this without throwing the whole methodology away. In fact, what you’re experiencing is a sign we’re just a few adjustments away from Agile working the way it’s supposed to. And I’d like you to be part of shaping how we refine this. Your technical perspective is exactly what’s been missing in story breakdowns. If you’re willing, I’d like you to help lead the next round of backlog refinement and sprint planning so we can start building a process that actually supports you instead of getting in your way.

---

### **assistant**:

That... actually sounds really good. I think you've hit on exactly what's been missing.

When you put it that way—that the dev team should own the "how" and "how long"—that makes total sense. I've been feeling like decisions were being made about my work without input, which is probably why everything felt so chaotic.

And you're right about the backlog refinement. Right now it feels like we show up to sprint planning and just get handed a list of things to estimate, rather than actually being part of breaking them down properly

I'd definitely be interested in helping lead that process. Honestly, if I could help shape how stories get written and sized, that would probably solve most of my frustrations. Because're right—when the work is properly scoped and I understand exactly what "done" means, I can actually deliver something I'm proud of within the sprint.

I guess I was thinking Agile meant constant chaos, but what you're describing sounds more like... structured flexibility? Like we're being adaptive but in a way that actually respects the technical realities of building software.

Thanks for walking me through this. I feel a lot better about where we're headed now.

---

### **user**:

I want to take you up on your willingness to help lead backlog refinement and story breakdown. Having a senior engineer involved at that stage brings a level of technical grounding that product owners simply can’t provide on their own. It will also give you a stronger voice in how features are shaped before they reach sprint planning, which should eliminate the feeling of being handed oversized or unclear work. And honestly, your input will help us mature this Agile transition much faster.

Let’s start with a small but meaningful change: I’d like you to join me and the product owner in the next refinement session and walk through how you would break down one of the upcoming features. We’ll use that as a model for the rest of the team. This will give you the influence you’ve been missing and help establish the collaborative balance Agile depends on.

So yes! We’re absolutely on the right path, and your perspective is a big part of why. Thanks for being open about the frustrations, and even more importantly, for being willing to help shape the solution. Agile works best when developers have a voice, and I’m glad to see you stepping into that role.

---

### **assistant**:

Absolutely, I'm in. That sounds like exactly what we need.

I really appreciate you taking the time to explain all this instead of just telling me to "trust the process." Understanding the reasoning behind it makes the difference.

And honestly, I'm kind of excited about getting involved in the refinement sessions. It'll be nice to have some influence over the work before it gets to my desk, and I think I can bring some realistic technical perspective to keep us from overcommitting.

One last thing—I realize I was probably being pretty negative about this whole transition. I can see now that a lot of my frustration wasn't really with Agile itself, but with how we were implementing it. Thanks for being patient with that and for actually listening to what wasn't working.

I'm looking forward to helping make this process work better for everyone.

---

## Summary of Our Conversation

Riley, through our discussion, you demonstrated a clear evolution in understanding Agile development methodology. You initially expressed legitimate concerns about constant scope changes, excessive meetings, and perceived quality issues—all valid critiques that many developers experience during poorly implemented Agile transitions. However, you showed excellent openness to learning when I explained how proper Agile implementation addresses these exact problems through better story sizing, developer involvement in backlog refinement, and clearer definitions of "done." Your willingness to take on a leadership role in improving our process shows both professional maturity and genuine commitment to making our development practices more effective. You've transformed from a skeptical critic to an engaged collaborator who understands that the issues you experienced weren't inherent flaws in Agile, but rather symptoms of incomplete implementation that we can fix together.

---

