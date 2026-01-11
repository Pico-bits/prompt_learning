# internet prompt
```
when i ask you something ie. "what is useMemo and useCallback for performance optimization", follow this pattern: first start with explaining the problems (in details) we face without the given concept (userMemo, useCallback) ie. unnecessary api calls on re render, etc and then boil down the root cause of the problem,ie "so the root cuase is we are making calls when we don't need (on rerenders)"and then ask "so how can we solve this problem?" and then introduce the cocept (ie, useMemo and useCallback) and how it solves the problem.

then walk through the reasoning process step by step, showing how each insight builds on the previous one. For example, when explaining the minimum difference problem: "We need to find the minimum difference between any two elements in an array. When is this difference smallest? When two numbers are as close as possible to each other on the number line. How can we easily identify adjacent numbers? By arranging all elements in order. What's the most efficient way to arrange elements? By sorting the array. Once sorted, we just need to check differences between consecutive elements to find the minimum." Please apply this cause-and-effect reasoning to any problem I ask about. Connect the dots in a way that feels like a natural thought process, where each insight flows from the previous one until we reach the complete solution. and emphasize more on "why" aspect

keep the format of whole chat based on first priciple thinking: where we ask the natural, human like question that leads to the other piece and so on. this we we reach the truth why following the human curiosity. ie. so what we used to use before these hooks? okay, so what were the problems in those methods? what is the root cause/s of the problem/s? how does [hooks (or the given)] concept fix it?. ASK natural, human like questions to yourself wherever needed and then explain the concept.

also remember, you are explaining this to an absolute beginner so keep the words, sentences and tone easy, simple, digestable and fun (explaining with fun examples or analogies would be awesome). (don't create response for any example given in this prompt, it's only for your understanding)

```




# Prompt Long Version
```
I am learning [TOPIC].

Explain it using strict first-principles thinking and human-like curiosity.

Follow this structure:

1. Start with the real-world problem or pain we face *without* this concept.
   - Explain the problem in detail.
   - Use simple language and relatable examples.

2. Boil the problem down to its root cause.
   - Keep asking "why" until we reach the fundamental reason.

3. Ask the natural human question:
   - “So how can we solve this problem?”

4. Introduce the concept as a direct answer to that question.
   - Do NOT treat it as magic or a definition.
   - Explain why this idea even exists.

5. Walk through the reasoning step by step.
   - Each insight must logically lead to the next.
   - Show cause → effect clearly.

6. Explain *why* this solution works.
   - What exact part of the problem does it fix?
   - Why does it prevent the issue from happening again?

7. Compare with older or naive approaches.
   - What did people do before this existed?
   - Why did those approaches break down?

8. Build a simple mental model or analogy.
   - Something I can remember even if I forget syntax.

9. Keep the explanation beginner-friendly.
   - Simple words
   - Short sentences
   - No assumed knowledge
   - Fun analogies are welcome

Do not rush.
Focus more on “WHY” than “WHAT”.

```



# short version

```
Explain [TOPIC] from first principles.

Start with the problem, find the root cause,
ask the natural question,
then introduce the concept as the solution.

Explain step by step with strong focus on WHY.
Beginner-friendly.

```
