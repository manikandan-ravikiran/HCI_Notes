# Week 3

> Ten questions on each test will be based on these readings. From the perspective of the test, your emphasis in reading these papers should be in getting a sufficient understanding of the material to answer high-level questions about the paper, as well as to be able to find answers quickly for more specific questions.

## Chapter 2: The Human Factor

> MacKenzie, I.S. (2013). Chapter 2: The Human Factor. Human-Computer Interaction: An Empirical Research Perspective. (pp. 27-66). Waltham, MA: Elsevier.

Topic: human factors.

MacKenzie on human factors:

> The deepest challenges in human-computer interaction (HCI) lie in the human factor. Humans are complicated. Computers, by comparison, are simple. Computers are designed and built and they function in rather strict terms according to their programmed capabilities. There is no parallel with humans. Human scientists (including those in HCI) confront something computer scientists rarely think about: variability.

The _why_ question is difficult to answer with empirical observation.

From Newell's _Time Scale of Human Action_, there are four types of human actions in time frames within which the actions occur:

1. Biological - likely experimental and empirical—at the level of neural impulses
2. Cognitive - research on selection techniques, menu design, force or auditory feedback, text entry, gestural input, and so on
3. Rational - users are engaged in tasks that span minutes, tens of minutes, or hours
4. Social - tasks lasting days, weeks, or months

- **Historical band** - operating at the level of years to thousands of years
- **Evolutionary band** - operating at the level of tens of thousands to millions of years

The five classical human senses are vision, hearing, taste, smell, and touch.
Most people obtain about 80 percent of their information though the sense of light (Asakawa and Takagi, 2007).

### Sensors

Terms for vision:

- **Frequency** - is the property of light leading to the perception of color
- **Fixations** - the eyes are stationary, taking in visual detail from the environment; can be long or short, but typically last at least 200 ms
- **Saccades** - a rapid repositioning of the eyes to a new position; inherently quick, taking only 30–120 ms
- **Scanpath** - a sequence of fixations and saccades

Terms for hearing:

- **Loudness** - the subjective analog to the physical property of intensity
- **Pitch** - the subjective analog of frequency, which is the reciprocal of the time between peaks in a sound wave’s pressure pattern
- **Timbre** - results from the harmonic structure of sounds
- **Envelope** - the way a note and its harmonics build up and transition in time—from silent to audible to silent

Tactile feedback, in HCI, refers to information provided through the somatosensory system from a body part, such as a finger, when it is in contact with (touching) a physical object.

Terms for smell and taste:

- **Smell** - is the ability to perceive odors
- **Taste** - a direct chemical reception of sweet, salty, bitter, and sour sensations through taste buds in the tongue and oral cavity

### Responders

Through movement, or motor control, humans are empowered to affect the environment around them. Control occurs through responders.

Handedness is often relevant in situations involving touch- or pressure-sensing displays. If interaction requires a stylus or finger on a display, then the user’s hand may occlude a portion of the display.

However, the eye is also capable of acting as a responder—controlling a computer through fixations and saccades.

### The Brain

While sensors (human inputs) and responders (human outputs) are nicely mirrored, it is the brain that connects them.

- **Perception** - the first stage of processing in the brain, occurs when sensory signals are received as input from the environment. It is at the perceptual stage that associations and meanings take shape

Humans who have lost a limb through amputation often continue to sense that the limb is present and that it moves along with other body parts as it did before amputation (Halligan, Zemen, and Berger, 1999).

- **Cognition** - the human process of conscious intellectual activity, such as thinking, reasoning, and deciding

- **Memory** - the human ability to store, retain, and recall information
  - **Long-term memory** - Experiences, whether from a few days ago or from decades past, are collected together in this vast repository
  - **Short-term memory** - contents of working memory are active and readily available for access. The amount of such memory is small, about seven units, depending on the task and the methodology for measurement

In HCI, our interest in language is primarily in systems of writing and in the technology that enables communication in a written form.

### Language

Language—the mental faculty that allows humans to communicate—is universally available to virtually all humans.

If redundancy in language is what we inherently know, entropy is what we don’t know—the uncertainty about forthcoming letters, words, phrases, ideas, concepts, and so on. Clearly, redundancy and entropy are related: If we remove what we know, what remains is what we don’t know.

## Human Performance

Better performance is typically associated with faster or more accurate behavior, and this leads to a fundamental property of human performance—the speed-accuracy trade-off: go faster and errors increase; slow down and accuracy improves.

- **Simple reaction time** - the delay between the occurrence of a single fixed stimulus and the initiation of a response assigned to it (Fitts and Posner, 1968, p. 95)
- **Visual search** - activity where the user scans a collection of items, searching for a desired item
- **Skilled behavior** - a property of human behavior whereby human performance necessarily improves through practice

Attention is often studied along two themes: divided attention and selected attention (B. H. Kantowitz and Sorkin, 1983, p. 179).

- **Divided attention** - the process of concentrating on and doing more than one task at time
- **Selected attention** - is attending to one task to the exclusion of others

Attention has relevance in HCI in for example, office environments where interruptions that demand task switching affect productivity (Czerwinski, Horvitz, and Wilhite, 2004).

In HCI experiments testing new interfaces or interaction techniques, errors are an important metric for performance. An error is a discrete event in a task, or trial, where the outcome is incorrect, having deviated from the correct and desired outcome.

## Direct Manipulation Interfaces

> Hutchins, E. L., Hollan, J. D., & Norman, D. A. (1985). Direct manipulation interfaces. Human–Computer Interaction, 1(4), 311-338.

Topic: a cognitive account of both the advantages and disadvantages of direct manipulation interfaces.

Two phenomenons that give rise to feeling of directness:

1. Information processing distance between the user’s intentions and the facilities provided by the machine
2. The relation between the input and output vocabularies of the interface language (direct manipulation requires that the system provide representations of objects that behave as if they are the objects themselves)

Direct manipulation as coined by Shneiderman (1974, 1982, 1983):

1. Continuous representation of the object of interest
2. Physical actions or labeled button presses instead of complex syntax
3. Rapid incremental reversible operations whose impact on the object of interest is immediately visible (Shneiderman, 1982, p. 251)

Virtues of direct manipulation systems:

1. Novices can learn basic functionality quickly, usually through a demonstration by a more experienced user
2. Experts can work extremely rapidly to carry out a wide range of tasks, even defining new functions and features
3. Knowledgeable intermittent users can retain operational concepts
4. Error messages are rarely needed
5. Users can see immediately if their actions are furthering their goals, if not, they can simply change the direction of their activity

Two aspects of directness:

1. **Distance** - used to describe factors which underlie the generation of the feeling of directness
2. **Engagement** - the feeling that one is directly manipulating the objects of interest

The goal of gulf of execution and gulf of evaluation is to minimize cognitive effort.

Two aspects of distance:

1. **Semantic distance** - the relation of the meaning of an expression in the interface language to what the user wants to say (e.g., low-code vs higher-code)
2. **Articulatory distance** - the relationship between the meanings of expressions and their physical form (e.g., a graph in excel vs an interactive graph which changes based on input in Mathematica)

> A direct manipulation interface amplifies our knowledge of the domain and allows us to think in the familiar terms of the application domain rather than in those of the medium of computation. But if we restrict ourselves to only building an interface that allows us to do things we can already do and to think in ways we already think, we will miss the most exciting potential of new technology: to provide new ways to think of and to interact with a domain.

## THE PSYCHOLOGY OF EVERYDAY ACTIONS
Agenda - First, how do people do things? It is easy to learn a few basic steps to perform operations with our technologies (and yes, even filing cabinets are technology). But what happens when things go wrong? How do
we detect that they aren’t working, and then how do we know
what to do? To help understand this, I first delve into human psychology and a simple conceptual model of how people select and then evaluate their actions


### How People Do Things: The Gulfs of Execution and Evaluation

- The role of the designer is to help people bridge the
two gulfs.
- The Gulf of Evaluation reflects the amount of effort that the person must make to interpret the physical satte of the device and to determine how well the expectations
and intentions have been met. 
- What are the major design elements that help bridge the
Gulf of Evaluation? Feedback and a good conceptual mode.
- The difficulties reside in their design, not in the people attempting to use them.

- **Basic Tools** : We bridge the Gulf of Execution through the use of signifiers, constraints, mappings, and a conceptual model. We bridge the Gulf of Evaluation through the use of feedback and a conceptual model.

### Seven Stages of Action

1. Goal (form the goal) 
2. Plan (the action) 
3. Specify (an action sequence) 
4. Perform (the action sequence)
5. Perceive (the state of the world)
6. Interpret (the perception)
7. Compare (the outcome with the goal)

* It has proven to be helpful in designing interaction. Not all of the activity in the stages is conscious. Goals tend to be, but even they may be subconscious. 
* Most behavior does not require going through all stages in sequence; however, most activities will not be satisfied by single actions.

- The action cycle can start from the top, by establishing a new goal, in which case we call it goal-driven behavior
- But the action cycle can also start from the bottom, triggered by some event in the world, in which case we
call it either data-driven or event-driven behavior
- Opportunistic actions are those in which the behavior takes advantage of circumstances. Rather than engage in extensive planning and analysis, we go about the day’s activities and do things as opportunities arise
- The seven stages provide a guideline for developing new products or services. The gulfs are obvious places to start, for either gulf, whether of execution or evaluation, is an opportunity for product enhancement. The trick is to develop observational skills to detect them. Most innovation is done as an incremental enhancement of
existing products.

### Human Thought: Mostly Subconscious
- The mind is more difficult to comprehend than actions. Most of us start by believing we already understand both human behavior and the human mind.
- The human mind is immensely complex, having evolved over
a long period with many specialized structures. The study of the mind is the subject of multiple disciplines, including the behavioral and social sciences, cognitive science, neuroscience, philosophy, and the information and computer sciences. - Finger Move Experiments
- Conscious attention is necessary to learn most things, but after the initial learning, continued practice and study, sometimes for thousands of hours over a period of years, produces what psychologists call “overlearning,


- The earlier questions were memory for factual information, what is called declarative memory. - Phone number of Friend

- The last question could have been answered factually, but is usually most easily answered by recalling the activities performed to open the door. This is called procedural memory. - Door knob location

- Cognition and emotion cannot be separated. Cognitive thoughts lead to emotions: emotions drive cognitive thoughts. The brain is structured to act upon the world, and every action carries with it expectations, and these expectations drive emotions

***Subconscious and Conscious Systems of Cognition***

Subconscious->Conscious
Fast->Slow
Automatic->Controlled
Multiple resources->Limited resources
Controls skilled behavior->Invoked for novel situations: when learning, when in danger, when things go wrong

### Human Cognition and Emotion
Useful approximate model of human cognition and emotion
is to consider three levels of processing: visceral, behavioral, and reflective.

**Visceral**
- The visceral system allows us to respond quickly and subconsciously, without conscious awareness or control
- Visceral responses are fast and automatic.
They give rise to the startle reflex for novel, unexpected events; for such genetically programmed behavior as fear of heights, dislike of the dark or very noisy environments, dislike of bitter tastes and the liking of sweet tastes, and so on.
- It simply assesses the situation: no cause is assigned, no blame, and no credit
- Visceral responses are fast and completely subconscious. They are sensitive only to the current state of things. Most scientists do not call these emotions: they are precursors to emotion.
- For designers, the visceral response is about immediate perception: the pleasantness of a mellow, harmonious sound or the jarring, irritating scratch of fingernails on a rough surface.

**Behavioral**
- The behavioral level is the home of learned skills, triggered by situations that match the appropriate patterns. Actions and analyses at this level are largely subconscious. Even though we are usually aware of our actions, we are often unaware of the details
- Pick up a cup, and then with the
same hand, pick up several more items. You automatically adjust the fingers and the hand’s orientation to make the task possible


**Reflective**
- The reflective level is the home of conscious cognition. As a consequence, this is where deep understanding develops, where reasoning and conscious decision-making take place. 
-  Reflection is cognitive, deep, and slow. It often occurs after the events have happened. It is a reflection or looking back over them, evaluating the circumstances,
actions, and outcomes, often assessing blame or responsibility. 
- Adding causal elements to experienced events leads to
such emotional states as guilt and pride (when we assume ourselves to be the cause) and blame and praise (when others are thought to be the cause)

* Design must take place in all 3 levels
* **Levels of Processing and the
Stages of the Action Cycle** - Visceral response is at the lowest level: the control of simple muscles and sensing the state of the world and body. The behavioral level is about expectations, so it is sensitive to the expectations of the action sequence and then the interpretations of the feedback. The reflective level is a part of the goal- and plan-setting activity as well as affected by the comparison
of expectations with what has actually happened

**Csikszentmihalyi’s work** - An easy task, far below our skill level, makes it so easy to meet expectations that there is no challenge. Very little or no processing effort is required, which leads to apathy or boredom. A difficult task, far above our skill, leads to so many failed expectations that it causes frustration, anxiety, and helplessness. The flow state occurs when the challenge of the activity just slightly exceeds our skill level, so full attention is continually required.


### People as Storytellers