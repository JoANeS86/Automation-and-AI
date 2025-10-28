## Prompt Engineering for ChatGPT

  - Document a new pattern to prevent an AI assistant from generating negative outputs to the user.
  - Persona Pattern: Act as Persona X and perform task Y (e.g., Act as a nutritionist, I am going to tell you what I am eating and you will tell me about my eating choices.
  - Question Refinement Pattern. To use this pattern, your prompt should make the following fundamental contextual statements:

        - From now on, whenever I ask a question, suggest a better version of the question to use instead.
        - (Optional) Prompt me if I would like to use the better version instead.

  - Cognitive Verifier Pattern. To use this pattern, your prompt should make the following fundamental contextual statements:

        - When you are asked a question, follow these rules.
        - Generate a number of additional questions that would help more accurately answer the question.
        - Combine the answers to the individual questions to produce the final answer to the overall question.

  - Audience Persona Pattern. To use this pattern, your prompt should make the following fundamental contextual statements:

        - Explain X to me. 
        - Assume that I am Persona Y.

  - Flipped Interaction Pattern. To use this pattern, your prompt should make the following fundamental contextual statements:

        - I would like you to ask me questions to achieve X.
        - You should ask questions until condition Y is met or to achieve this goal (alternatively, forever).
        - (Optional) ask me the questions one at a time, two at a time, ask me the first question, etc.

"Few-shot" refers to a machine learning approach called few-shot learning, which enables AI models to learn to perform a new task by training on a very small number of labeled examples, sometimes just one or five per category.

Chain of thought (CoT) prompting is a technique used to improve the reasoning abilities of large language models (LLMs) by encouraging them to break down a problem into a series of intermediate steps before providing a final answer.
This method makes the LLM's thought process more explicit, transparent, and accurate, which is particularly useful for complex tasks like math problems and logic puzzles.

ReAct prompting is a technique for large language models (LLMs) that combines Reasoning and Acting to solve complex problems step-by-step. Instead of providing a single answer, the LLM generates a chain of "Thought," "Action,"
and "Observation" steps, allowing it to interact with external tools, refine its reasoning, and produce more accurate and transparent results.

  - Game Play Pattern. To use this pattern, your prompt should make the following fundamental contextual statements:

        - Create a game for me around X OR we are going to play an X game.
        - One or more fundamental rules of the game.

  - Template Pattern. To use this pattern, your prompt should make the following fundamental contextual statements:

        - I am going to provide a template for your output.
        - X is my placeholder for content.
        - Try to fit the output into one or more of the placeholders that I list.
        - Please preserve the formatting and overall template that I provide.
        - This is the template: PATTERN with PLACEHOLDER.

 - Meta Language Creation Pattern. To use this pattern, your prompt should make the following fundamental contextual statements:

        - When I say X, I mean Y (or would like you to do Y).

  - Recipe Pattern. To use this pattern, your prompt should make the following fundamental contextual statements:

        - I would like to achieve X.
        - I know that I need to perform steps A,B,C.
        - Provide a complete sequence of steps for me.
        - Fill in any missing steps.
        - (Optional) Identify any unnecessary steps.

  - Alternative Approaches Pattern. To use this pattern, your prompt should make the following fundamental contextual statements:

        - If there are alternative ways to accomplish a task X that I give you, list the best alternate approaches.
        - (Optional) compare/contrast the pros and cons of each approach.
        - (Optional) include the original way that I asked.
        - (Optional) prompt me for which approach I would like to use.

  - Ask for Input Pattern. To use this pattern, your prompt should make the following fundamental contextual statements:

        - Ask me for input X.

  - Outline Expansion Pattern. To use this pattern, your prompt should make the following fundamental contextual statements:

        - Act as an outline expander. 
        - Generate a bullet point outline based on the input that I give you and then ask me for which bullet point you should expand on. 
        - Create a new outline for the bullet point that I select. 
        - At the end, ask me for what bullet point to expand next.   
        - Ask me for what to outline.

  - Menu Actions Pattern. To use this pattern, your prompt should make the following fundamental contextual statements:

        - Whenever I type: X, you will do Y.
        - (Optional, provide additional menu items) Whenever I type Z, you will do Q.
        - At the end, you will ask me for the next action.

  - Fact Check List Pattern. To use this pattern, your prompt should make the following fundamental contextual statements:

        - Generate a set of facts that are contained in the output.
        - The set of facts should be inserted at POSITION in the output.
        - The set of facts should be the fundamental facts that could undermine the veracity of the output if any of them are incorrect.

  - Tail Generation Pattern. To use this pattern, your prompt should make the following fundamental contextual statements:

        - At the end, repeat Y and/or ask me for X. 

  - Semantic Filter Pattern. To use this pattern, your prompt should make the following fundamental contextual statements:

        - Filter this information to remove X.























