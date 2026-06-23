# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
It looked nice and simple, nothing seemed outwordly broken except the number of attempts was off by 1 on the rules and the settings.
- List at least two concrete bugs you noticed at the start  
  (for example: "the hints were backwards").
Yes the hints were backwards, and the ranges for easy and hard mode were not correct.

**Bug Reproduction Log**

Document at least 3 bugs you found. Add rows as needed.

| Input | Expected Behavior | Actual Behavior | Console Output / Error |
|-------|-------------------|-----------------|------------------------|
| playing on easy mode | the answer to be from 1-20  | answer was 1-100 | none |
| 5 attempts on easy | 6 attempts | locked after 5 attempts | none |
| clicked "new game" button | starts a new game | saves your attempts and throws a new secret number, not letting you guess | none |

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
- I used the Claude extension for VS code to help!
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
-  One example was it helped me figure out how to fix the hint bug (where it was showing the opposite hint), I changed it and ran the site again to check if it worked, and it did!
- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).
- Thankfully there were no incorrect suggestions given during my session.

---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
- By testing it and trying to recreate the issue.
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
- I manually tested all of the small bugs I found and once I fixed them I stress tested it to try and break it again. It showed me that even the smallest mistakes make a big difference.
- Did AI help you design or understand any tests? How?
- Yes, every single bug that I found, I made Claude explain why it is happening and helped me understand the code more.

---

## 4. What did you learn about Streamlit and state?

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?
- It's like a local host website.

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- I would probably want to reuse Claude as a teaching agent, asking it "why this?" rather than just "fix it".
- What is one thing you would do differently next time you work with AI on a coding task?
- Probably take more time to comb through bugs and try to rely less on AI.
- In one or two sentences, describe how this project changed the way you think about AI generated code.
- It definately has its perks for beginner coders, but from anecdotes from my father, it really doesn't have a place in the workspace for advanced coders.
