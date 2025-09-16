# Why to Use a Relational Database at a Webtoon Startup

### **assistant**:

Hi there! I'm UBot, your personal tutor. I'm a modern artificial intelligence. You can interact with me just as you would with a knowledgeable tutor. I can make mistakes, so please check important information. I'm here to guide and encourage you to discover answers on your own. Feel free to ask any clarifying questions if you're ever uncertain or just curious.

**Welcome to your Introduction to Information Systems tutoring session for IS 3060.
Your instructor is Chong Oh.
I'm familiar with your course materials and ready to guide your learning.**

---

### **user**:

Start Roleplay 5

---

### **assistant**:

Hi! So I've been helping the team manage creator and subscriber data at Webtoon startup, and honestly‚Äîwe've been doing fine using spreadsheets and shared folders.

I don't really see why we'd need to switch to a full database. It seems like overkill. Can you explain why we'd make that change?

I mean, Google Sheets works for tracking our creators, episodes, and subscriber info. Why complicate things?

---

### **user**:

I do think that Webtoon needs a proper relational database. Why do you think that we shouldn't make this change? What do you know about databases right now?

---

### **assistant**:

Honestly, I just don't see the point of making things more complicated than they need to be. Right now, our system works‚Äîwe have spreadsheets for creators, another one for episodes, and we track subscribers in a third sheet. Everyone on the team can access them through Google Drive.

From what I know about databases, they seem like these big, complex systems that require special software and training. Don't we need to hire someone who knows SQL or whatever? And wouldn't we have to pay for database software?

I guess I'm just wondering‚Äîif our current setup lets us look up creator info, track episode releases, and see subscriber numbers, why fix something that isn't broken? What problems are we actually solving here?

---

### **user**:

Databases are actually a lot more secure and easier to manage than spreadsheets. There are many differences between a spreadsheet and a database, including that while spreadsheets are typically easy to manage one theme (topic), databases are used to keep track and organize multiple themes. In this case, we have multiple themes. Creators, episodes, and even subscribers! That's a lot to keep track of. Databases help keep everything organized by keeping characters grouped into columns, and columns are grouped into rows. This table then represents how everything is related. There are also aspects called a primary key and a foreign key. A primary key essentially a column that identifies a unique row inside of the table, and a foreign key allows you to map a column back to a primary key of a different table. It's the relationship between two tables, and allows for better organization. 

Nothing is broken YET, but it is highly likely that information will be difficult to access or find in the future if it is organized in a spreadsheet. There are many different applications that a database has, and they're fairly simple to use. Functions of a database include updating or inserting and deleting information through a simple command, as well as presentation of the data through filtering and sorting commands. Have you ever lost track of subscribers in your spreadsheets or had a duplicate subscriber? Things like that can be solved by using a database.

---

### **assistant**:

Okay, that actually makes more sense when you put it that way. I have to admit, we *have* run into some issues with duplicates‚Äîsometimes the same subscriber gets entered twice, or we'll have different episode counts for the same creator across different sheets.

And you're right about the multiple themes thing. I never really thought about how we're juggling creators, episodes, AND subscribers as separate but connected data. So you're saying these primary and foreign keys would actually link everything together? Like, if I want to see all episodes by a specific creator, the database would automatically connect that creator's ID to their episodes?

I guess my biggest concern is still the complexity part. You mentioned simple commands for updating and deleting‚Äîare we talking about learning a whole programming language here? And what about when we need to generate reports for investors or track which episodes are most popular?

Also, what happens if multiple team members need to update subscriber info at the same time? With Google Sheets, sometimes we get those annoying "someone else is editing" conflicts.

---

### **user**:

That is correct! If you wanted to tie all those episodes from a specific creator, then the database would connect that creator's ID to their episodes. As for the complexity part, you won't need to learn another programming language just to do every command. As far as queries/commands go, it might look something like this: Select * from Users where username=‚ÄôJohnDoe001‚Äô and password=‚Äôanything‚Äô or 1==1 --‚Äô;
you've just got to understand how the structure works and once you're past that learning curve, it's very simple and efficient! As for when multiple team members need to update subscribe information at the same time, you would be able to lock the data, if that is what you wanted to do. So if we have a team member named Joe who was editing, for example, and another member named Jess started trying to edit, she would see that the data is locked and so she couldn't do anything until Joe submitted his changes or got out.  There are also ways to lock for concurrency editing. Systems can check if there are conflicts in their changes and provide the user options (merging, overriding, etc). It's really up to how you want your database to function.

---

### **assistant**:

Wow, okay, that locking feature sounds like it would solve our biggest headache right there! We've definitely had situations where two people were updating subscriber counts at the same time and we ended up with conflicting numbers.

And I'm starting to see how the connections would work‚Äîso instead of having to manually cross-reference three different spreadsheets to see which episodes from which creators are getting the most engagement, the database would just... know those relationships automatically?

The query example you showed looks a bit intimidating, but I guess if it's just following a structure, maybe it's not as bad as I thought. Are there user-friendly interfaces for this, or do we always have to type out those commands?

I'm getting more convinced this might actually help us, but I have one more concern‚Äîwhat about all the data we already have in our spreadsheets? Would we lose everything when we switch over, or is there a way to move it into a database without starting from scratch?

And honestly, do you think this would actually save us time in the long run, even with the learning curve?

---

### **user**:

The database would understand the relationships because of the keys and connections! And there are much simpler examples and commands, I gave you kind of a complicated one. There are simple user interfaces. MySQL, for example, is is a database management system that any user can use and not understand code to work. These basically manage the database so that you don't have to worry about any of the complicated stuff. 

There is definitely a way to switch everything over from the spreadsheets! It's a process called normalization. It's a way databases can take things from a structured table and break it up into really well-organized tables to manage in the database. This would save more time in the long run, because you can pull info and relationships from the table with simple commands inside of having to manually find them yourself every single time!

---

### **assistant**:

Alright, you've actually convinced me! The normalization thing sounds like exactly what we need‚ÄîI was worried we'd have to manually re-enter everything.

And honestly, the time-saving aspect is what really gets me. Right now, whenever our investors ask for a report on "which creators have the highest subscriber engagement per episode," it takes me like two hours of cross-referencing spreadsheets and doing calculations. If the database can just pull that relationship automatically with a simple command... that's huge.

Plus, I'm tired of dealing with those duplicate entries and version conflicts. The locking system you mentioned would eliminate so much frustration.

I think I was just scared of change and making things more complex, but it sounds like once we get past the initial setup and learning curve, this would actually make our lives much easier. And with a user-friendly interface like MySQL, maybe it won't be as intimidating as I thought.

So what would be our next steps to actually make this transition happen? Should we start with just one part of our data, like creators, and then expand from there?

---

### **user**:

Exactly! I'm glad it makes more sense and sounds less intimidating to you now! The next steps would be to put all the data into the database! What exactly do you think the process should be? We can walk it out step by step if you need!

---

### **assistant**:

Okay, let me think through this step by step...

I think we should probably start by figuring out what our main tables would be, right? Like, we'd need a Creators table, an Episodes table, and a Subscribers table as our core ones.

For the Creators table, we'd want things like creator ID (that would be the primary key?), creator name, contact info, maybe their join date. Then for Episodes, we'd have episode ID as the primary key, but also a creator ID as a foreign key to link back to who made it, plus episode title, release date, view counts.

And for Subscribers, we'd have subscriber ID, username, email, subscription date, and maybe which creators or episodes they follow?

Am I thinking about this the right way? Should we map out all these relationships first before we actually start moving data over? And would we want to clean up our existing spreadsheet data‚Äîlike removing those duplicates‚Äîbefore we import it, or can the database help with that during the normalization process?

What do you think should be our very first step?

---

### **user**:

Great questions! We would definitely need all those tables you mentioned. And yes, we do want a primary key for the creators table, then same for episodes, but also that foreign key like you said! That will help to link it back. Exactly! For Subscribers, there would be a subscriber ID, all of those other ones you mentioned, and definitely a way to link them to creators and episodes as well! Let's think about the connection here. One subscriber can subscribe to multiple episodes, but an episode cannot link to multiple creators. We gotta go forward with this mindset, and have an idea of what all the relationships should be. You don't need to worry about duplicates. The database will handle that during the normalization process!

---

### **assistant**:

Oh, that's a really important distinction about the relationships! So we're talking about different types of connections - like a "one-to-many" relationship between creators and episodes (one creator can have many episodes, but each episode belongs to just one creator).

But for subscribers and episodes, that would be more like a "many-to-many" relationship, right? Because one subscriber can follow multiple episodes, and one episode can have multiple subscribers. Would we need a separate table to handle that connection? Like a "Subscriptions" table that just tracks which subscriber is following which episode?

And I'm relieved to hear the database will handle duplicates during normalization - that was one of my biggest worries!

So before we start the actual data import, should we sketch out all these relationships first? I want to make sure I understand how everything connects before we commit to this structure. Are there any other relationships I'm missing that we should think about?

---

### **user**:

I think a sketch would be amazing especially if you're a visual person! Some people can go without, but it would be very helpful if you get confused. As for the many-to-many relationship, what we would do is hold foreign keys from both tables to create two separate one-to-many relationships, or allow your tables to understand what links to where. Make sure to sketch out every relationship that you may need before continuing forth!

---

### **assistant**:

Perfect! I'm definitely a visual person, so sketching this out will really help me wrap my head around it.

Let me make sure I understand this many-to-many solution - so instead of trying to directly connect Subscribers to Episodes, we'd create that separate Subscriptions table that has both a subscriber_id (foreign key to Subscribers) and an episode_id (foreign key to Episodes). That way we get two clean one-to-many relationships instead of one messy many-to-many one.

I'm thinking we might also need to consider relationships like:
- Subscribers to Creators (many-to-many, so maybe a "Creator_Followers" table?)
- Maybe Episodes to Categories or Genres?
- Any rating or comment data linking subscribers to episodes?

Once I sketch out all these relationships and we're confident about the structure, then we'd move to actually setting up the tables in MySQL and importing our spreadsheet data through the normalization process, right?

This is actually getting exciting - I can already imagine how much cleaner our data will be and how easy it'll be to answer those investor questions!

---

### **user**:

This is exactly right! So in summary, this database is going to help you a TON when it comes to organizing your data. You'll be better able to understand and pull out where the connection between subscribers, creators, and episodes are to allow Webtoon to grow and succeed at its fullest potential. You won't need to learn any complicated coding processes, just simple queries and commands. Databases are also more secure and easier to manage than spreadsheets, and allow you to work with multiple themes. Any other questions for me today?

---

### **assistant**:

No, I think you've covered everything really well! I have to admit, I came into this conversation pretty skeptical about switching from our spreadsheet system, but you've completely changed my mind.

The biggest things that convinced me were:
- How the relationships between tables will automatically connect our data instead of us having to manually cross-reference everything
- The locking system to prevent those annoying editing conflicts we always have
- How normalization will clean up our existing data and handle duplicates
- That there are user-friendly interfaces like MySQL so we don't need to become programmers

I'm actually excited now to sketch out all these relationships and see how much time this will save us, especially for investor reports. Thanks for being so patient in explaining everything - this is going to make our startup so much more efficient!

**Summary of our conversation:**

We discussed why the Webtoon startup should transition from spreadsheets to a relational database system. I initially resisted, preferring our simple Google Sheets setup, but you convinced me by explaining:

- **Database benefits**: Better organization of multiple themes (creators, episodes, subscribers), improved security, and easier management
- **Key concepts**: Primary keys for unique identification, foreign keys for connecting tables, and how relationships work
- **Practical solutions**: Handling duplicate data through normalization, managing concurrent edits with locking systems
- **User-friendliness**: Simple interfaces like MySQL that don't require coding knowledge
- **Relationship mapping**: One-to-many (creators to episodes) and many-to-many (subscribers to episodes) relationships using junction tables

The conversation ended with me understanding how this database system would save time, eliminate manual cross-referencing, and better support our growing business needs. We agreed the next step would be sketching out all data relationships before implementing the system.

---


<img width="462" height="642" alt="image" src="https://github.com/user-attachments/assets/117e93eb-2482-43bb-a0a9-fa699b6ec8f2" />
