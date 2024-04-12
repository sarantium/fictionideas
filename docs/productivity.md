![Hero](assets/hero_1.png)

Where product managers end up is not where they start. _Build-measure-learn_ and _design thinking_ are two powerful ways to accelerate value creation and capture. I use these concepts - framed as loops and documents respectively - as foundational schemas in implementation.

## Loops

![Step](assets/hero_4.png)

GIST is a modern approach to learning loops in product management; it stands for **G**oals, **I**deas, **S**teps and **T**asks. The underlying theory advocates rapid experimentation to increase confidence that ideas deliver measurable value.

> goals define what we wish to achieve, ideas are hypothetical ways to achieve the goals, steps are mini-projects that implement an idea in parts while validating it, and tasks are the day-to-day activities that implement a step<sup>[1](https://itamargilad.com/book-evidence-guided/)<sup>

GIST has a variety of tools available - quantitative metrics, idea banks and ICE scores - to structure loops and is often depicted as a sequential whiteboard with sticky notes.

![GIST](assets/gist_1.jpg)

## Documents

Design thinking is a convenient way to categorise different stages of product planning and execution. I use a specific flavour of design thinking, assigning a single output document to each stage.

![designthinking](assets/designthinking_2.png)

These documents are live and persistent artifacts with a dual purpose; they help product managers think better by themselves and communicate their thoughts more clearly to others throughout a loop.

![Modified GIST](assets/designthinking_3.png)

The distinction between loops and documents is the difference between execution routes and planning maps. I position design thinking documents as a parallel step stage and persistent set of artifacts in the GIST loop.

!!! tip

    **Act quickly** with GIST loops and **plan persistently** with design thinking documents

My version of GIST is also a specific instance of the generic workflow class. Workflows combine loops and documents to guide action from concept to execution.

## Workflows

![Agents](assets/clones_1.jpg)

The near-term promise of AI agents is that, given minimal input and supervision they can:

- decide what to do by stringing together workflow components, sequences and schedules
- get things done by implementing automations, accessing tools and parallelising activity
- semi-autonomously know when to start, when to keep going and when to stop
- help architect and orchestrate workflows for faster, cheaper and better outcomes

Taking the goal of writing a fiction novel, the table below distinguishes between four types of agentic workflows.

| Workflow      | Description                                                                                                                                                         | Example                                                                                                                                                                        |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Operational   | These are the basic tasks that the AI agent handles, like fixing grammar, suggesting better words, or keeping track of character details in a story.                | Imagine the AI agent is like a helpful assistant who takes care of the small but important jobs, such as making sure the writing is polished and consistent.                   |
| Strategic     | These are the bigger plans and decisions the AI agent helps with, like figuring out the main steps of a story or setting goals for what the writing should achieve. | Think of the AI agent as a co-author who helps map out the story's journey and ensures that each chapter moves the plot forward.                                               |
| Cognitive     | These are the smart, thinking tasks where the AI agent analyses the writing, spots areas for improvement, and learns from feedback to make better suggestions.      | The AI agent acts like a wise editor who not only finds issues but also learns what works best for your writing style and preferences.                                         |
| Metacognitive | This is where the AI agent manages and improves its own tasks, strategies, and thinking processes to become more effective over time.                               | Imagine the AI agent is like a self-improving app that gets better at helping you the more you use it, constantly fine-tuning its assistance based on your needs and feedback. |

These workflows can also be applied to the goal of a product manager delivering an admissions module within a student management system.

| Workflow      | Description                                                                                                                                                                                      | Example                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Operational   | These are the basic tasks that the AI agent handles, such as automating data entry for student applications, generating reports on application status, or sending notifications to applicants.   | Imagine the AI agent as a meticulous assistant who streamlines the admissions process by automatically entering student application data, generating real-time reports on the status of applications, and sending timely notifications to applicants about their application status.                                                                                                                                                                                                                                                    |
| Strategic     | These are the larger plans and decisions the AI agent assists with, using frameworks like GIST to set goals, generate ideas, plan steps, and execute tasks for developing the admissions module. | Think of the AI agent as a strategic partner who uses the GIST framework to help the development team set clear goals for the admissions module, brainstorm features that enhance the admissions process, outline development steps, and guide the execution of the module development.                                                                                                                                                                                                                                                 |
| Cognitive     | These are the intelligent analysis and decision-making tasks where the AI agent identifies patterns in application data, plan module enhancements, and solve usability challenges.               | The AI agent acts like a smart analyst who examines application data, plans improvements based on applicant feedback, and addresses usability challenges to enhance the module's effectiveness and user experience.                                                                                                                                                                                                                                                                                                                     |
| Metacognitive | This is where the AI agent oversees and refines its own operational, strategic, and cognitive workflows to optimize the development and implementation of the admissions module over time.       | Visualise the AI agent as a self-regulating system that continually optimises its performance within the admissions module. It assesses its own effectiveness in handling application workflows, identifies areas for improvement in data analysis, and adapts its strategies for engaging with applicants. This self-assessment and adaptation are driven by ongoing feedback from the admissions team and shifts in application patterns, ensuring the module remains aligned with the evolving objectives of the admissions process. |

??? danger "Caution"

    Not every workflow or outcome needs to be agentic, especially operationally. Many of the items above may just be app features with no agent input or output.

    Right now, agents are buzzy and fuzzy; we are all figuring out where they fit and sometimes use them as hammers even when there aren't any nails.

Agent workflows evolve from operational to metacognitive, each serving a distinct purpose. Operational workflows focus on routine tasks, like tracking project milestones or managing customer feedback. Strategic workflows, such as GIST, are broader, targeting larger goals within specific domains like product management. While these workflows are optimised for certain contexts, they can be adapted to other areas, although their effectiveness may vary.

The transition to cognitive workflows introduces a move toward dynamic and adaptive approaches. Examples of cognitive workflows for agents include:

- Hrishi Olickel's iterative loop of Chat, Play, Loop, and Nest
- Marvin Minsky's sequence of Search, Pattern-Recognition, Learning, Planning, and Induction
- Andrew Ng's progression with Reflection, Tool Use, Planning, and Multi-Agent Collaboration

These models emphasise continuous learning and iteration, employing abstract problem-solving techniques that are applicable across various fields.

At the metacognitive level, the focus is on understanding and improving how agents think and work. This involves monitoring their own processes, recognizing when it's time to adjust their approach, and making those changes. For example, in AI systems, this could mean an algorithm that learns from its mistakes and gets better over time. In teams, it might involve regularly checking how agents work together and finding ways to be more efficient. This kind of self-awareness and adaptability is key in many areas, helping agents solve problems more effectively and come up with better ideas.

## Manifesto

An early shadow inspired by Agile, I'm proposing my rule of thumb AI manifesto for working with LLMs that is focused on build techniques

- **Pipelines > Prompts**
- **Inputs > Outputs**
- **APIs > Abstractions**
- **Multimodal > Text**

The table below collects technique tips and tricks across the build cycle.

| Stage                    | Techniques                                                                                                                                                                                                                                                                                                                                                                         |
| ------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Planning & Design**    | - **Iterative Loop:**<br> • Chat: Explore options<br> • Play: Edit in OpenAI playground (60% time)<br> • Loop: Add data and test cases<br> • Nest: Simplify with subtasks<br>- **Time Allocation:**<br> • Playing: 60%<br> • Prompt Tuning: 20%<br> • Input Massaging: 10%<br> • Coding: 10%<br> • Tooling: 1%                                                                     |
| **Development**          | - **Dos:**<br> • Use all modalities<br> • Code for input and output structure<br> • Leverage pretraining information<br> • Reduce search space upfront<br>- **Don'ts:**<br> • Add abstractions between yourself and the LLM<br> • Stick to one model<br> • Have too high an I/O ratio                                                                                              |
| **Testing & Debugging**  | - **Debugging:**<br> • Start at the prompt level or try a different model<br> • Transform input and add more structure to output<br> • Classify tasks and errors to identify where the failure is<br>- **Optimizing AI:**<br> • Break prompts to reduce complexity<br> • Use separate models for structure and long-form writing<br> • Implement state management and self-healing |
| **Deployment & Scaling** | - **Future Planning:**<br> • Assume everything will be 10x to 50x cheaper and faster in the future<br> • Build for at least 6 months ahead<br>- **AI Resources:**<br> • Be mindful of the exponential scaling of attention algorithms                                                                                                                                              |

## Hypothesis

My hypothesis is that agents and pipelines built to accelerate productivity can also be repurposed or adjusted to accelerate creativity. The core insight is that creative and productive processes and patterns both rely on overlapping agentic workflows. This is particlarly true when focusing - as I am - on the **intersection of AI-generated science fiction and fantasy microworlds and product ideas**.

!!! tip "Hypothesis 1"

    Productivity and creativity agents enhance each other through shared workflows

I believe the speed, cost and quality improvements offered by agents provides a step change in resources, opportunities and leverage for product managers; in an enviornment of abundance rather than scarcity, they can say say yes more often<sup>[2](https://x.com/clairevo/status/1774451083622191400)<sup>.

!!! tip "Hypothesis 2"

    Agents help product managers ship faster, cheaper and better at every stage of value capture and creation
