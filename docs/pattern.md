## O'Reilly Article on prompting

https://www.oreilly.com/radar/what-we-learned-from-a-year-of-building-with-llms-part-i/

## Evaluation links

- https://hamel.dev/blog/posts/evals/
- https://eugeneyan.com/writing/evals/

Think I need a page just on evaluation

## Prompting

- https://eugeneyan.com/writing/prompting/

## Goals

- https://www.loom.com/share/d0ff7c0b17b34aa7b46f9537c5b25785?start_download=true

I really like this idea of taking two companies and making the "Goals" [As I see it] relevant from one vendor to a potential client to help in sales calls

## Engineering

Hrishi Olickel's iterative loop of Chat, Play, Loop, and Nest<sup>[6](https://youtu.be/gsO5V30h-lU?si=pxQ0X-p9iUYHlYXs)</sup> <sup>[7](https://youtu.be/8w0hUcQSDy8?si=6eAb4SqLy3B015Jd)</sup> guides alot of my thinking on how to build agentic workflows. In general, the build principles I follow are:

- **Pipelines > Prompts**
- **Inputs > Outputs**
- **APIs > Abstractions**
- **Multimodal > Text**

The table below collects more specific technique tips and tricks - summarised from Hrishi's talks - across the build cycle.

| Stage                    | Techniques                                                                                                                                                                                                                                                                                                                                                                         |
| ------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Planning & Design**    | - **Iterative Loop:**<br> • Chat: Explore options<br> • Play: Edit in OpenAI playground (60% time)<br> • Loop: Add data and test cases<br> • Nest: Simplify with subtasks<br>- **Time Allocation:**<br> • Playing: 60%<br> • Prompt Tuning: 20%<br> • Input Massaging: 10%<br> • Coding: 10%<br> • Tooling: 1%                                                                     |
| **Development**          | - **Dos:**<br> • Use all modalities<br> • Code for input and output structure<br> • Leverage pretraining information<br> • Reduce search space upfront<br>- **Don'ts:**<br> • Add abstractions between yourself and the LLM<br> • Stick to one model<br> • Have too high an I/O ratio                                                                                              |
| **Testing & Debugging**  | - **Debugging:**<br> • Start at the prompt level or try a different model<br> • Transform input and add more structure to output<br> • Classify tasks and errors to identify where the failure is<br>- **Optimizing AI:**<br> • Break prompts to reduce complexity<br> • Use separate models for structure and long-form writing<br> • Implement state management and self-healing |
| **Deployment & Scaling** | - **Future Planning:**<br> • Assume everything will be 10x to 50x cheaper and faster in the future<br> • Build for at least 6 months ahead<br>- **AI Resources:**<br> • Be mindful of the exponential scaling of attention algorithms                                                                                                                                              |

## Andrew Ng

https://www.deeplearning.ai/the-batch/issue-249/

When building complex workflows, I see developers getting good results with this process:

Write quick, simple prompts and see how it does.
Based on where the output falls short, flesh out the prompt iteratively. This often leads to a longer, more detailed, prompt, perhaps even a mega-prompt.
If that’s still insufficient, consider few-shot or many-shot learning (if applicable) or, less frequently, fine-tuning.
If that still doesn’t yield the results you need, break down the task into subtasks and apply an agentic workflow.

prompting strategies : https://arxiv.org/abs/2311.16452?utm_campaign=The%20Batch&utm_source=hs_email&utm_medium=email&_hsenc=p2ANqtz-_PU4gmbfJN9_gBrzLMkZheDB1ROQnQWYv9cSxeMK53CO9ix0aYRLcabOd6v3xmmbHcM7HE

## Hrishi Budget

https://olickel.com/object-oriented-large-language-models

## Cameron Wolfe

Many useful ideas from his writings around prompt engineering and RAG https://cameronrwolfe.substack.com/

## Reflection

The reflection Tool at its simplest is about thinking about what was done and trying to improve it. Evaluation is a subset of reflection. or maybe the other way around. Here's a great list of evaluation/observability tooling available

- https://ianww.com/llm-tools
- tinyllm seems particularly interesting to me

I'd also want to consider and think about logfire from Pydantic :

- https://pydantic.dev/logfire
- https://python.useinstructor.com/blog/2024/05/01/instructor-logfire/

An evaluation paper

- https://arxiv.org/abs/2404.12272

## Instructor use cases I want to explore

- https://x.com/ddebowczyk/status/1792105564966662523
- https://x.com/jxnlco/status/1788558053094117691 [Some rag thing I need to review]

- In the docs there is a create iterable method instead of Iterable[T] - https://github.com/jxnl/instructor?tab=readme-ov-file#streaming-iterables-create_iterable

## Other librarires I 'm thinking through

- [Lumentis](https://github.com/hrishioa/lumentis)
- [Marker](https://github.com/VikParuchuri/marker)

## CSIRO links on Safety

- https://research.csiro.au/ss/team/se4ai/responsible-ai-engineering/
- https://research.csiro.au/ss/team/se4ai/

## Routing [Probably more urgent that I read the Leah Post]

- https://www.linkedin.com/pulse/how-create-good-ai-planner-agent-leah-bonser-mvrsf/?trackingId=nMqml7p%2BTVK2nhzyPLpsxQ%3D%3D

- Note Leah also wrote a second post.

## Jeremy Howard Stuff I need to read

- https://www.youtube.com/watch?v=jkrNMKz9pWU
- https://github.com/fastai/lm-hackers/blob/main/lm-hackers.ipynb
- https://x.com/HamelHusain/status/1793319488731107718

## LLama index router stuff

- https://medium.com/aimonks/agentic-rag-with-llama-index-router-query-engine-01-381e83a418af
- Have signed up to the course in deeplearning.ai

## AI Product Strategy for portfolio

- [AI Product Strategy](assets/AI_product_strategy.pdf)

## Ton of awesome AI speakers

https://x.com/HamelHusain/status/1792223793903276343

## Prompt book coming out

- https://www.oreilly.com/library/view/prompt-engineering-for/9781098156145/

## Agent collusion

https://arxiv.org/abs/2404.00806

## Hamel Husain

Consulting proposal from a meeting : https://gist.github.com/hamelsmu/ac72d18ee9d4cbd6a235a8e37a75f303

## Australian safety standards

- https://www.cyber.gov.au/resources-business-and-government/governance-and-user-education/artificial-intelligence/deploying-ai-systems-securely

## Education

https://towardsdatascience.com/ai-knocking-on-the-classrooms-door-87db39d00b94

## GPT - Researcher

- 1 : https://x.com/hu_yifei/status/1793751353308901394
- 2 : https://github.com/assafelovic/gpt-researcher

## Education

- Google Education Paper Worth reading. Long and dense : https://storage.googleapis.com/deepmind-media/LearnLM/LearnLM_paper.pdf

- Donald Clark Blog - https://donaldclarkplanb.blogspot.com/

- https://www.ai-supremacy.com/p/ai-in-education-googles-learnlm-product

## Shadow AI

- this keeps coming up as a thing

## Companies to watch

- https://www.studyfetch.com/

## Few shot tool use doesn't really work yet

- https://research.google/blog/few-shot-tool-use-doesnt-really-work-yet/

## Perplexity pages

- https://www.perplexity.ai/hub/faq/what-is-perplexity-pages

## Knowledge graphs

- https://gradientflow.com/graphrag-design-patterns-challenges-recommendations/
