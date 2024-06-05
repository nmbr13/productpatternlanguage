by Alex Gregorie, UX Researcher
# What is research?

In her book Just Enough Research, Erika Hall provides the most concise definition for research as “systematic inquiry”. That’s it. There are many styles of research and many outcomes but the key concepts that make research effective are that it is systematic and that it is inquisitive. In order to be research an activity must have both components. Asking strangers questions pulled from a hat isn’t systematic. Shouting rote Confucian proverbs at stray cats isn’t inquisitive. Both elements must be present in an activity for it to constitute research.

The good and bad news of this simple definition is that research can take on many different forms. This is good because it means that you have many options and tools to help you. It is bad because that means there are a lot of different techniques and methods to understand and work through which can be intimidating and overwhelming. How do I know what to do next? How do you know if you’re doing it right? The purpose of this document is to help you answer those questions.

# What is a Playbook?

The idea of a playbook comes from sports. It is a document that helps orchestrate the activities of a team around achieving a desired outcome. These “plays” tell each member of a team where to be, what to look out for and what their objective is. In this document you will find “plays” that will help you make the decisions and take action in the moment. Each play will tell you:

- When it applies
- Who should be involved and what their role will be
- What to do to apply this play
- What the objective is.

Each play can be leveraged in many different ways and it is up to you to apply them appropriately.

## Common principles

1. Be collaborative
2. Be curious
3. Be thoughtful

## What makes good research

As discussed above research has two components.

There is good research and there is bad research but what they all have in common is that they are about

# Why does research matter?

# How do I do research?

# Who should do research?

# Intro to the double diamond


The double diamond is a standardized model for product development. It goes by many names including Divergent/Convergent thinking, Discovery and Framing, Design Thinking. Regardless of what you call it the double diamond process is a systematic way of uncovering and understanding problems as well as finding the best solutions.
![[00 -Blank.jpg]]

The name double diamond comes from the diagram that is commonly used to explain it which is comprised of two diamonds. Each diamond represents a portion of the product development lifecycle and the type of mindset that is appropriate in that half. 



![[C - Discovery.jpg]]
The first is Discovery or Research. In this half you are seeking to understand and learn. This may sound simple but is incredibly difficult for those not used to it. This isn’t the part of the project where you go off and begin sketching ideas or building prototypes. The goal in discovery is to uncover as much information as you can about your customers and your problem.

![[D - Solutioning.jpg]]

The second diamond is Ideation or solutioning. This half is all about identifying how to solve the problems that your team uncovered in the Discovery phase. Key concepts in this half are to work quickly and to work together. Building software is an incredibly complex task and each member of your team is there to provide some level of expertise. Additionally, bringing your team along on the discovery and ideation journey will ensure that when it comes time to build, they don’t need a large ramp up. When the whole team is included each member becomes well equipped to make informed decisions that add value to the user’s experience and drive the product towards successfully accomplishing its goals for the business.

Next let’s dive into each diamond in more detail.

## Why diamonds?

Each diamond in the double diamond process is made of two symmetrical triangles. One that starts small and gets large and one that starts wide and goes narrow. These two triangles represent two ways of thinking about each phase of your project. Each half shares a common paradigm with is pair in the other diamond.

### Divergent Thinking

![[A - Divergent.jpg]]
The first triangle or phase is Divergent thinking. Divergent thinking is when the team goes wide and deep looking in many different directions for information or possible solutions (depending on which half of the process you are in). When in the discovery phase this half is called research. In the solutioning phase it is called brainstorming.

This half is all about creating momentum. Have you ever noticed that one of the hardest parts of a project is getting over your own internal critic? This half is all about getting out of the way and letting the information and ideas come to you.

### Convergent Thinking

![[B - Convergent.jpg]]
The second diamond is convergent thinking. This name comes from the idea that from all of these various bits of information you are going to look at it all and then find a way to converge upon a small number of useful tidbits. Taking the best of what you’ve uncovered and reducing it into something that can propel you into your next phase. What we are looking for coming out of convergent phases is something like espresso. We want to take all of our divergent and disparate ideas and insights and pack them into a small, digestable but incredibly potent form.

In the discovery phase this half is called synthesis and in the solutioning half its called design.

## Each phase in detail

Now that we have an overview we are going to look at each phase in detail. In this section we are going to identify the goals of each phase and potential solutions you can use to help you cross each milestone.

### Research
![[02 - Research.jpg]]
Research is the phase in which you are learning and uncovering data. 
Related patterns are:
```dataview
LIST
WHERE phase = "1 - Research"
```

### Synthesis
![[03 -Synthesize.jpg]]
Synthesis is the phase of the process where you are converging your research findings into a coherent set of problems themes or ideas. 
Patterns for Synthesis are:
```dataview
LIST
WHERE phase = "2 - Synthesis" 
```
### Brainstorming
![[05 - Brainstorm.jpg]]
Common ways of Brainstorming are:
```dataview
LIST
WHERE phase = "3 - Brainstorming"
```
### Design

![[06 - Design.jpg]]
Common Iteration Patterns are:
```dataview
LIST
WHERE phase = "Iteration"
```

## What are those other bits?

On either end of the Double diamond are sets of meetings that help define what you will be doing. These help scope your work and give accountability to your actions while in the creative process.

### Prioritization
![[04 - Prioritize.jpg]]
Some will include this in Synthesis others as an alignment. It can go either way. This is an opportunity to involve your leadership if they desire in understanding the synthesized research and allow their input into the direction of the solutioning phase.

Some patterns you can use to Prioritize your work are:
```dataview
LIST
WHERE phase = "3 - Prioritization"
```

### Alignments

On each end of the diamonds are opportunities for alignment with your stakeholders. Kickoff and Report.
![[F - Alignments.jpg]]
Some patterns to help you get alignment include:
```dataview
LIST
WHERE phase = "Alignment"
```
# Now what?
Take some time to think about where you are in your project. From here you can explore some patterns that can help you move forward. 
```dataview
TABLE Phase
WHERE phase
SORT phase asc
```
