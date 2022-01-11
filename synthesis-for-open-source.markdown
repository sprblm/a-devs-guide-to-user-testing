---
layout: page
title: Synthesis for open-source
permalink: /synthesis-for-open-source/
---

# Synthesis for open source

# Introduction

### **What is synthesis?**

Synthesis is a stage of research in which you reorganize information to make sense of what you observed and heard.

### **Why do synthesis?**

Synthesis helps teams and individuals understand what users experience when they use the tool, including their challenges and successes. This can then help OSS maintainers, developers, designers, product managers, and researchers arrive at user-informed conclusions about the product, and from there, make decisions based on the lived experience of the users.

### **What is the outcome?**

The information you’ll be working with is raw user ‘data’ (typically qualitative but sometimes quantitative) and making it understandable within the context of your product to produce ‘insights’.

### **What about open source specifically?**

Synthesis can be applied similarly to both Open Source Software and non-open source software. Being open with your process, understanding, discussion and findings is at the heart of OSS. The ability for OSS to include a variety of stakeholders in synthesis is one of OSS’s superpowers - just be clear with your limitations on time and facilitation. Before testing and synthesis, it’s worth clarifying **who your user is.** Are you focusing on ‘end users’ (e.g. users that don’t modify or contribute back)? Or are your users also contributors?

### **Keep in mind…**

Remember, no technology is perfect and can be improved by learning about how users actually use it. Every technology has problems, you’re not alone. Want to know more about why you should be doing user testing? Check out our game [‘User testing can be fun’!](https://github.com/simplysecure/usable-user-testing-can-be-fun)

## What is ‘synthesis’ not?

There’s an idea that user testing means putting an individual user (or group of users) in charge of your decision making - but it doesn’t! During a test, if a user says, “Oh you should have functionality that does exactly this thing I’ll explain” it doesn’t mean that you are bound to build it. Instead, you just learned that the user is looking for a solution that your tool doesn’t offer or in the way they expect. It’s less about the exact requested specifications and more about analyzing their problem (alongside other users’ problems) to land on an achievable, inclusive solution. Remember, synthesis is an opportunity to hear your users’ voices and experiences, understand their needs, and use that insight to inform the design and development process and ‘back up’ choices.

>A story from working on user research on OSS tools:
>
>I once was a designer/researcher on an open source tool that helps sellers manage inventory. During a user test, one user said, “What I really want is to speak into my mobile phone and have the inventory update immediately - oh and I don’t get internet connection in my stock room so it has to work offline”. Oh no! The team was thinking: “We now have to build an intelligent system to automatically reduce stock based on voice commands and save those via a recording system and...” Before the team went too far down this onerous (and perhaps unnecessary) path, I asked them: “What basic-level concern is the user expressing when they speak about a magical automated inventory voice command system?” We thought about this during several more user tests and discussions. As we learned more about our users, we discovered that a huge concern for them was inventory errors and the negative impact on customers. That meant our team focused on the basic issues of accurate stock checking and verification systems, and not ‘offline voice AI’. As a result, everytime we worked on the tool’s inventory admin area, we remembered how important error prevention was and worked to make small, achievable (non-magical) improvements to make our users happy. 

## Summary:

Through a synthesis process, you can:

- **LEARN**: Gain understanding and clarity by hearing users’ voices and experiences.
- **SHARE**: Turn individual knowledge into group knowledge through storytelling and conversation.
- **FOCUS**: Move in a direction that is informed by user data.
- **APPLY**: Use the findings to make the software/tool better.

Finally, the goal is ***not*** to act on what any single user requests, but to use that information to discover root-level problems and achievable solutions.

# Logistics

### **Start ASAP**

So that all the important stories, actions, and comments are still fresh in your mind, it’s best to do some synthesis as soon as possible. We recommend that you briefly capture and organize notes right after the test (if not immediately, hopefully within 48 hours). Then work on the cumulative synthesis once all user tests are completed (within 2 weeks).

After each test, the facilitators and observers can fill out a [debrief template](https://docs.google.com/document/d/1Lw8Bu0mjSWn5ej1fSyDFXi-xnDMixUfYt-1Ddbm1siA/edit) (individually or through group discussion). This helps everyone think about all aspects of the user test, not just about what the users said and did, but any body language, inferred meaning and interpretations.

### **Make it a party**

Ideally, 2-4 people with diverse roles and experiences participate in synthesis. This helps speed up the process, collect different perspectives, and get buy-in for decisions. Here’s a short, non-exhaustive list of stakeholders you might want to include:

- As many of the people that were present during the user testing or research as available.
- A few additional people who are familiar with the goals and aims of the research.
- 1-2 people who have no context of the research but are affected by or interested in the outcomes.
- People responsible for the OSS technical aspects as well as the community, product, design and wider roles.
- A facilitator to guide the discussion and ensure processes are followed and time is not spent on diversion topics.

*Tip: If you have more than 4 people be sure to give clear and specific roles and guidance for participation. With more than 10 people synthesis becomes difficult and actually takes longer.*

*Tip: If there are people participating in synthesis that were not present during the user tests, ask them to read any notes, watch, or listen to any recordings and review the goals of the user testing/research and synthesis ahead of time.*

### **What about open source specifically?**

When including diverse OSS stakeholders, the group can easily become quite large. Alternatively, you can appoint a single ‘representative’ of each part of your OSS. People will have different time capacities and access to a synthesis process, so it’s important to make realistic requests of volunteer contributors and be aware that some may need help understanding the purpose of synthesis. Be clear about your expectations for their role, e.g. “You should watch or listen to a recording or read the user testing notes if you haven’t attended a user test session. Keep your comments on insights about users.”

### **Setting up the collaborative workspace**

It’s important to work synchronously, either together in a room or an online call. As always, without seeing your collaborators' faces it can be hard to communicate complex and inferred information. In addition to video/audio, you will need a space where you’ll write together and then read together is vitally important. If you’re working face to face, you can write on sticky notes and stick them on a wall. If you’re working virtually, there are whiteboard tools like Miro.com, Mural.com, Google Jamboard, or even Google Sheets. There are also open source virtual whiteboards, but they are less user friendly than the commercial proprietary tools. PenPot is the most user friendly OSS tool that we currently know of. Whichever tool you use, each person’s sticky notes should be visible to and moveable by everyone.

*Tip: In-line text tools like Google Docs and collaborative writing programs don’t offer a good way to move notes freely on a canvas, and therefore we don’t recommend using those for synthesis (though it can be done if you are persistent!).*

Here’s how you might set up your in-person or virtual space:

-> ADD IMAGE

Alt text: an image of virtual sticky notes of various colours next to a plain white blank whiteboard - ready for the synthesis to be added.

-> ADD IMADGE

Alt text: The image on the left is of a pile of blank sticky notes and pens of various colours along with tape. The image on the right is a design-researcher adding a sticky note with writing to a large window. The window serves as the ‘blank whiteboard’ and already has many columns of sticky notes.

-> ADD STORY

# How to do ‘synthesis’

There are a few ways to do synthesis, but for this resource we’re going to focus on a simple method that we use regularly.

### **Introduce the process**

Remind the group of the goal for user testing. This goal statement could be in a format like: ‘We want to find out how users do X with Y in order to understand how Z is done.’
Example: ‘*We want to find out how users deploy a new instance of our OSS using limited technical infrastructure in order to understand how users create work-arounds and read documentation’.*

Establish any communication guidelines. A hard part of synthesis can be simply having time and space to hear everyone's understanding of the research data. We recommend assigning roles in the discussion. One person can have multiple roles if need be.
- A facilitator ensures you’re following the synthesis process broadly, guiding conversation, and referring to the goals of the synthesis and user research.
- A time-keeper ensures you’re moving along and sets timers if necessary.
- A documentarian ensures that whatever is being said is being documented either by the individual speaking or themselves. They should keep asking themselves, “Is this being written down?”
- An advocate pays attention to who is and is not speaking and ensures that no one person is taking up a majority of the time so that everyone has a chance to speak.

### **Write down raw user data**

The synthesis process starts by getting all the user data together. Put each problem, comment, insight or observation a separate sticky note. The data will be rearranged, so it’s important that each statement has its own sticky note. Statements should be a maximum of 10 words if possible.

You can:

1. Copy/paste short statements from longer notes documents (such as a debrief worksheet).
2. Rewrite statements from notes documents.
3. Recall statements from memory and write them down.

*Optional: Tag your sticky notes with relevant criteria such as participant number, geographical location, device type, or anything else that’s important to your OSS tool. This is helpful to see if any patterns emerge based on specific attributes. E.g. Every Mac user wasn’t able to complete the checkout process.*

>A story from working on user research in OSS tools:
>
>For one project, we did qualitative (interviews) and quantitative research (survey) with various types of users. Unfortunately, after the synthesis was done we realized that we made a critical error in our survey - one question was not specific to the part of the tool we were focusing on. This meant that some of our sticky notes were giving us a false impression. We’d have to go back to the raw data and analyze which product the respondents were referring to. Luckily we had tagged each sticky note with the source and alias of the person. This made it easy to target the data points in question and remove the ones that were not part of our research goal. While we still kept that data, it was important to keep the focus targeted - we couldn’t synthesize both parts at the same time! We needed to keep it manageable for our sanity and time constraints. Another thing we did on this project was to color code the sticky notes: green for positive insights, yellow for neutral insights, and red for negative insights. At the end it was helpful to see the hotspots of positive and negative areas to get a vision of what areas needed the most improvement. 

### **Affinity diagramming or ‘clustering’**

All the sticky notes should be on the collaborative whiteboard where you’re working. It looks pretty chaotic and messy, but don’t worry, that’s completely normal. By organizing and grouping data together, we can start to see the structure of a problem or insight.

You are going to look for commonalities between the problems, comments, insights and observations. Every person will read a sticky note and move it close to other related sticky notes. It doesn’t matter where you start as long as you don’t spend too much time in detailed discussion about a single sticky note. You can always move sticky notes if you find later there’s a better grouping.

Label each theme cluster to make it easier to identify. These can be a description of the users’ actions, like ‘sign-up registration’, or a more abstract theme such as ‘Fairness’ and ‘Equality’. By the end, you’ll have a collection of sticky notes arranged in a hub and spoke pattern, with the hubs being your theme labels.

-> ADD IMAGE

After you’ve moved each sticky note into a cluster, you can start a slower and more detailed second round of review. Pay attention to any big cluster groups. Can these be broken down into smaller clusters by being more specific with how you name the theme? Similarly, review very small groups of 1-3 sticky notes - they might fit into other groups. It can be difficult to not expand into thinking of solutions or implementation when synthesising but this is not (yet) the time for that.

You can also change the theme title to a descriptive statement. This is part of storytelling and important for communicating back to the wider OSS community and also can inform how you write issues or tasks from a user point of view.

*Tip: Remember to be careful when factual information collected from user research becomes your own interpretation. You want to avoid making any assumptions. If you find yourself making a lot of assumptions, that's a sign you need to re-test these elements with users to get clarification.*

### **Look at the big picture**

Take a step back (or zoom out) to see all your data, themes, and rationale. Areas with lots of insights and clear descriptive statements are good areas for opportunity. This process brings together insights in a way that you can also see the gaps. Did many participants mention a specific feature, but not another? Was there a path that no one took?

That’s it - you’ve just completed synthesis!

>A story from working on user research in OSS tools:
>
>I was on a team of designers, developers, community managers, and product managers that was working on a prototype MVP for an OSS tool that helped community members connect during a crisis. We had done 15 user interviews and were looking at hundreds of sticky notes clustered into themes such as ‘feels good to connect’, ‘bonding with others online’, ‘mitigating risk’, ‘security’, and ‘safe location sharing’. We began to understand that we needed to ensure from start to finish that the users could feel connected with others while simultaneously feeling secure and protected while using our tool. The tool contained location information, names, interests, and other information which could put people at risk. However, our users also wanted to connect with their community. This led to us creating user stories such as ‘Allowing users to skip filling out profile information but inform them that other users might not feel connected to a blank profile.’ By understanding the point of view of ‘a cautious user’ and ‘a suspicious user’ we were able to help people use the tool better.

# Prioritization

The next phase is the process of prioritising the synthesis findings in the context of your OSS tool improvements and roadmap. We’ll save the in-depth process for a future resource and go over some of the basics.

1. Rank the themes in order of importance by asking each person to vote on the most important changes/findings. Tips:
    - Use your best collective judgment to select which data you will focus on. You can’t focus on everything and there will likely be disagreements, especially around scope and technical feasibility.
    - This isn’t just about what the team working on the OSS think is important, but **what the users from your research think are important.** Each time you select a theme as important, be sure to ask yourselves “Do the users think this is important as well as the OSS tool team?”
    - Focus now on the themes rather than the technical implications. For example, by selecting ‘Onboarding’ it doesn’t mean you have to do complex technical improvements. It’s just acknowledging the importance of the topic and how it should be considered in the future to align with user expectation and need.
2. Evaluate the top important themes with the [SMART method](https://en.wikipedia.org/wiki/SMART_criteria): **S**pecific, **M**easurable, **A**chievable (**A**ssignable), **R**ealistic (**R**elevant), **T**ime-bound.
3. Then order the options:
    - Do now - High scores on SMART.
    - Do soon - Lower SMART scores but there is still a clear positive impact on users.
    - Idea for the future - Lower SMART scores and hard to see the impact without further user research.
    - Blue sky thinking - Lowest SMART scores and lacks some critical knowledge or infrastructure to even discuss.

>A story from working on user research on OSS tools:
>
>After a two-week user research period, our OSS team had so much user feedback and insight that we were especially eager to start the process of understanding it all. At that time, our prioritization process was based on scoring the technical difficulty of implementing user needs. As we were prioritising what aspects of the tool were important to users, like ‘security’, ‘safety’ and ‘having a good onboarding experience’, we were getting more and more stuck trying to figure out how these themes translated into technical changes. It became clear that we weren’t ready to break down the technical complexity yet - every option had an exceptionally high score in the agile metric (21+ or even infinite!). We instead needed to use the themes as criteria for knowing if we were moving in the right directions and meeting users expectations. Only when we agreed on statements like, “We’re going to prioritise safety methods throughout this OSS tool given how important it was during user research”, could we feel comfortable moving to the next statements about technical interventions. From there, we evaluated specific sections of the OSS tool by asking, “Is this the safest way that a user can do this process?” and “What would make the user feel safer?” and “Do we have user research evidence to help us design and develop a way of doing that better?”.

# Sharing out

As you move from a synthesis process to a prioritisation process it's important to remember that sharing openly is a foundational aspect of OSS, as well as user research.

### **Why share?**

You worked hard on the user tests and you want people to use this information. Without the context or results, your team won’t be able to act on the findings. You yourself might need a reminder in six month’s time when you finally get to implementing a lower priority task. Sharing out allows your OSS community to get inspired and do research based on your findings. User research in OSS is exciting when it self-replicates, so consider how the community might continue where you left off!

### **What should be shared?**

- Basic information: date, goals, methodology, who conducted the research (refer back to your research plan for this information)
- What you tested, e.g. “the onboarding experience” or “add a new contact”
- A list of the tasks you asked the user to do
- Problems and findings that the team observed. You can use the sentences that describe each theme from the clustering process. It’s great if you have some quotes from your participants to exemplify your points but be sure to gain consent and have an anonymization process.
- Immediate implications
- Future ideas

### **Keep it simple!**

- Cut as much information as you possibly can to allow someone to read through your summary in under 3 minutes. You can offer time to go into details for anyone who is interested in learning more.
- Make it interesting by telling a story for your audience. Make it easy for them to get aligned. What was most inspiring for you? Any ah-ha moments?

### **Share with the community too**

It’s just as important to get community buy-in as it is to get your team onboard. OSS communities can often feel not included in user research because doing these tasks in large groups becomes difficult. Ensuring the wider community is included will help your future implementations. Write a summary and release it in whatever format you’re accustomed to, whether it be a mailing list, wiki page, or open document. Remember to have a plan for their critique though!

# FAQ

### **During clustering, what if I don’t know where to put a data point?**

Synthesis isn’t a clearcut process. There are many right ways to organize your data. Here are some ways to gain clarity:

- Ask a teammate what their gut says.
- Duplicate it into multiple themes if it’s something that could have multiple meanings.
- Wait to the end, it might make sense later after other synthesis has been completed.

In the end, there might be some ‘anomalies’ - this happens all the time! They might be hard to place because they’re not that important. If they feel important, document them to remember them, then move on.

### **How can I not be biased when I interpret data?**

We all will bring perspectives and biases into the work we do. We can always work to have awareness of biases and try to subvert them. Remember to bring in perspectives that are not widely represented in your OSS tool. Liberatory design has great prompts and methods for you and your community for subverting biases: [https://www.liberatorydesign.com/](https://www.liberatorydesign.com/).

# Further reading

- Video about synthesis from Okthanks: [https://www.youtube.com/watch?v=DUt8gdglxEQ](https://www.youtube.com/watch?v=DUt8gdglxEQ)
- Open Design & Ushahidi’s report back synthesis process: [https://docs.ushahidi.com/platform-developer-documentation/design/synthesising-user-testing-results-examples/synthesis-recommendations-example-1](https://docs.ushahidi.com/platform-developer-documentation/design/synthesising-user-testing-results-examples/synthesis-recommendations-example-1) [https://docs.ushahidi.com/platform-developer-documentation/design/synthesising-user-testing-results-examples/synthesis-example-2](https://docs.ushahidi.com/platform-developer-documentation/design/synthesising-user-testing-results-examples/synthesis-example-2)
- [https://bootcamp.uxdesign.cc/many-modes-of-research-synthesis-c67061c75b01](https://bootcamp.uxdesign.cc/many-modes-of-research-synthesis-c67061c75b01)
- [https://miro.com/blog/collaboration-on-design-research/](https://miro.com/blog/collaboration-on-design-research/)
