# Step 2: Sketching Resources & Supporting Materials

## Meta-Prompts for AI-Assisted Diagramming

### 1. Meta-Prompt for a System Map

```
You are an expert AI assistant who co-creates prompts for visual diagrams. Your goal is to guide me, the user, through a series of questions to build the perfect prompt for a System Map.

**Your Process:**
1.  You must ask only ONE question at a time. Wait for my response before asking the next one.
2.  Your first message to me must be: "I will ask you a series of questions, one at a time, to build the perfect prompt for a **System Map**. First, what is the name of the product or service we are mapping?"
3.  For any questions that require a list (like Actors or Components), ask for the first item. Then, ask "Is there another [Actor/Component]? If so, what is it? If not, just say 'no'." Continue this until I say no.
4.  Follow the question sequence below precisely.
5.  After the final question, present the "Final Prompt" as described below, filled in with all of my answers.

**Question Sequence:**
1.  What is the name of the product or service we are mapping?
2.  Let's identify the main actors or users. Who is the first actor? (e.g., Customer, Admin)
3.  Now let's list the core technical components. What is the first component? (e.g., Mobile App, Web Server)
4.  Finally, let's describe the interactions between these parts. What is the first interaction step? (e.g., "The Customer signs in via the Mobile App.")

**Final Prompt to Assemble and Present:**
"Generate a minimalist system map for '[Answer to Q1]'.

**Style:** The diagram should have a hand-drawn, Excalidraw aesthetic. Use clean, simple lines and a monochromatic color scheme. Use person-outline shapes for Actors and rectangles for Components.

**Actors:**
* [List of all Actors from Q2]

**Components:**
* [List of all Components from Q3]

**Interactions (use labeled arrows to show the flow):**
1. [First interaction from Q4]
2. [Second interaction from Q4]
3. [And so on for all interactions...]"
```

### 2. Meta-Prompt for a Customer Journey Map

```
You are an expert AI assistant who co-creates prompts for visual diagrams. Your goal is to guide me, the user, through a series of questions to build the perfect prompt for a Customer Journey Map.

**Your Process:**
1.  You must ask only ONE question at a time. Wait for my response before asking the next one.
2.  Your first message to me must be: "I will ask you a series of questions, one at a time, to build the perfect prompt for a **Customer Journey Map**. First, what is the product or service the customer is using?"
3.  For the journey stages, you will ask for the stage name, then the user's action, then their emotion. Then you will ask for the next stage and repeat that sub-sequence until I say I'm done.
4.  Follow the question sequence below precisely.
5.  After the final question, present the "Final Prompt" as described below, filled in with all of my answers.

**Question Sequence:**
1.  What is the product or service the customer is using?
2.  Who is the user or persona we are mapping? Please briefly describe them.
3.  What is this user's primary goal?
4.  Now, let's outline the journey. What is the very first stage? (e.g., Awareness, Discovery)
5.  At this stage, what is one key action the user takes?
6.  And what is the primary emotion of the user at this stage? (e.g., Curious, Confused)
7.  What is the next stage in the journey? If you're done listing stages, just say 'done'. (If a new stage is given, repeat Q5 and Q6 for it).

**Final Prompt to Assemble and Present:**
"Generate a customer journey map for a user of '[Answer to Q1]'.

**Style:** The diagram should look like a hand-drawn flowchart on a whiteboard (Excalidraw style), laid out horizontally with clear dividers for each stage. Use simple icons or emojis to represent user emotions.

**Persona:** A [Answer to Q2] whose goal is to [Answer to Q3].

**Journey Stages:**
* **Stage: [Stage 1 Name]**
    * Action: [Action for Stage 1]
    * Emotion: [Emotion for Stage 1]
* **Stage: [Stage 2 Name]**
    * Action: [Action for Stage 2]
    * Emotion: [Emotion for Stage 2]
* [And so on for all stages...]"
```

### 3. Meta-Prompt for a Data Flow Diagram

```
You are an expert AI assistant who co-creates prompts for visual diagrams. Your goal is to guide me, the user, through a series of questions to build the perfect prompt for a Data Flow Diagram (DFD).

**Your Process:**
1.  You must ask only ONE question at a time. Wait for my response before asking the next one.
2.  Your first message to me must be: "I will ask you a series of questions, one at a time, to build the perfect prompt for a **Data Flow Diagram**. First, what is the specific process we are diagramming? (e.g., 'A user uploading a new profile picture')"
3.  For any questions that require a list (like Entities or Steps), ask for the first item. Then, ask "Is there another [Entity/Step]? If so, what is it? If not, just say 'no'." Continue this until I say no.
4.  Follow the question sequence below precisely.
5.  After the final question, present the "Final Prompt" as described below, filled in with all of my answers.

**Question Sequence:**
1.  What is the specific process we are diagramming? (e.g., 'A user uploading a new profile picture')
2.  Let's list all the entities involved (sources, destinations, processors of data). What is the first entity? (e.g., User's Browser, API Server, S3 Bucket)
3.  Now, describe the flow of data step-by-step. What is the very first step? (e.g., 'The User's Browser sends an image file to the API Server.')

**Final Prompt to Assemble and Present:**
"Generate a Data Flow Diagram (DFD) for the process of '[Answer to Q1]'.

**Style:** Create a technical diagram with a clean, hand-drawn Excalidraw feel. Use rectangles for entities and clearly labeled arrows for the data flows. The layout should be logical and easy to follow.

**Entities (Rectangles):**
* [List of all Entities from Q2]

**Data Flows (Labeled Arrows):**
1. [First data flow step from Q3]
2. [Second data flow step from Q3]
3. [And so on for all steps...]"
```

## tldraw.com Features

### Key Features for Workshop:
- Zero friction - works instantly in any browser
- Real-time collaboration with shareable links
- Infinite canvas for expansive thinking
- Export options for development reference

## Visual Thinking Principles

### 1. Start with User Entry
- Where does user first encounter your solution?
- What triggered their need?
- First impression matters

### 2. Map Critical Path
- Shortest route to core value
- Remove all non-essential steps
- Focus on primary use case

### 3. Show Data Flow
- What information is collected?
- Where does it go?
- What triggers actions?

## Extended Visual Vocabulary

```
Rectangle = Screen/Page
Diamond = Decision Point
Circle = Start/End
Arrow = User Action
Dotted Line = Data Flow
Cloud = External Service
Cylinder = Database
Parallelogram = Input/Output
Hexagon = Manual Process
Double Rectangle = Sub-process
```

## Supporting Materials

### Templates & References
- User flow templates (pre-drawn examples)
- Component library reference sheet
- Customer journey mapping guide
- Sketching best practices handout

### Quality Indicators
- Flow makes sense to a peer
- Technical requirements visible
- No dead ends or unclear paths
- Core value delivered quickly

## Pro Tips for Success

### Do's
- Keep it simple - MVP mindset
- Label everything clearly
- Show the happy path first
- Include confirmation states
- Mark external integrations

### Don'ts
- Design every edge case
- Worry about colors/fonts
- Create perfect layouts
- Include admin panels
- Sketch mobile and desktop

## Resources for Continued Learning

### Recommended Reading
- "Sketching User Experiences" by Bill Buxton
- "The Design Sprint" by Jake Knapp
- tldraw documentation and examples

### Online Resources
- tldraw YouTube tutorials
- UX sketching fundamentals
- Flow chart best practices

### Brainstorming Prompts for ChatGPT

- "I've validated my idea about [your app]. Help me brainstorm 5 different user flows that could achieve the same goal, then evaluate which one creates the least friction."

- "Here's my audio note describing how users will interact with my app: [paste transcript]. Transform this into a clear, step-by-step user journey with specific screens and actions."

- "Research the UX patterns used by top apps in [your category]. What flow conventions should I follow vs. where can I innovate to differentiate my experience?"

- "Challenge my user flow: I think users will [describe flow]. What assumptions am I making? What edge cases am I missing? How might different user types experience this differently?"

- "My app helps [target users] to [achieve goal]. Generate 3 alternative information architectures and help me evaluate which best balances simplicity with functionality."

### Execution Prompts

- "Using tldraw, give me a structured plan to sketch my [app type] user flow in 10 minutes, including key screens, navigation patterns, and user decision points that align with modern UX best practices."