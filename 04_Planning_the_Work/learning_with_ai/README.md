# Learning with AI: what gets worse and what gets better when an explanation is one click away

**Level:** 101 · for anyone who studies with a chatbot open

**One line:** Memory is still built by what you do, so an AI changes nothing about how learning works and everything about which mistakes are easiest. Asking it for answers is rereading made perfect; asking it for questions, hints, quizzes and a student to teach makes every technique in this library cheaper.

## What stays the same

McGuire's book was written in 2018, before a chatbot could explain any page on request. Almost nothing in this library changes because of that. McGuire's resident answered the drug question correctly from his phone and could not say why; "we can solve problems and do critical thinking only with information already stored in our brains." An AI is that phone, made fluent and patient. Every argument in the lessons is about what happens in the learner's head, and none of them is about where the explanation came from.

## What gets worse

Reading an AI's explanation is *rereading*, with every trap of [metacognition](../../01_Knowing_What_You_Know/metacognition/README.md): it is clear, confident and written for you, so it feels like knowing even more strongly than a textbook does. Asking it to solve the homework breaks McGuire's strategy 11, doing homework without examples, in the most complete way possible, and it is always one click away.

One field experiment in high-school mathematics (Bastani and colleagues, *PNAS*, 2025) gave students GPT-4 for practice problems. With plain access, practice scores rose, and on the exam taken without it those students scored about 17% lower than students who never had it. A version built to give hints instead of answers mostly avoided the loss. *Grade: good evidence, one large field experiment.*

## What gets better

Everything this library says to do, an AI can make cheaper, if you ask it for the right thing:

| Instead of asking for | Ask for | Why, here |
|---|---|---|
| the answer | a hint, and only after you have tried | [metacognition](../../01_Knowing_What_You_Know/metacognition/README.md): produce before you look |
| an explanation to read | a quiz on it; write a confidence before each answer | [metacognition](../../01_Knowing_What_You_Know/metacognition/README.md): calibration |
| a summary | flashcards, then review them spaced | [spaced retrieval](../../02_Making_It_Stay/spaced_retrieval/README.md) |
| more examples at the same level | questions at the level above: why, what if, find the flaw | [studying vs learning](../../01_Knowing_What_You_Know/studying_vs_learning/README.md) |
| a better explanation | to play a student while *you* explain, and ask the questions a class would | [teach-the-material mode](../../01_Knowing_What_You_Know/studying_vs_learning/README.md#make-an-a-mode-and-teach-the-material-mode) |
| the list of facts | the principle that produces them, then rebuild the list yourself | [count the vowels](../../01_Knowing_What_You_Know/count_the_vowels/README.md) |
| a problem set on one topic | a mixed set from the last three chapters | [interleaving](../../02_Making_It_Stay/interleaving/README.md) |

A tutor built on these rules can do well: in a Harvard physics course (Kestin and colleagues, *Scientific Reports*, 2025), students working with an AI tutor designed around them learned more, in less time, than in an active-learning class. Baillifard and colleagues (2023, [doi:10.48550/arxiv.2309.13060 ↗](https://doi.org/10.48550/arxiv.2309.13060)) report a personal AI tutor built to apply retrieval and spacing, and Karrar, Abdelrady and Ibrahim (2026, [doi:10.3389/feduc.2026.1862047 ↗](https://doi.org/10.3389/feduc.2026.1862047)) had an AI write context-rich Anki cards for language learners. *Grade: good evidence for the Harvard result; the other two are early studies.*

## One new skill

An AI can be wrong while sounding certain, so every answer it gives is a claim to check, and checking is Bloom's level 5, evaluating. This library has one rule for that, the same one it keeps for itself: a claim counts when a program that runs agrees with it, or, where no program can, when the evidence is graded honestly ([05_Body_and_Brain](../../05_Body_and_Brain/README.md) is the worked example). Ask the AI for the check, not just the claim, and run it.

## Tools

Spaced-repetition software, [Anki ↗](https://apps.ankiweb.net/) above all, is the one category of tool this library relies on: every lesson ships a deck. Note systems (Obsidian, Notion, OneNote), blockers (Freedom, Forest) and timers are matters of taste; the test of any of them is whether it makes you *answer* more often or *look* more often. McGuire's advice on study tools is the same: experiment until something works, and prefer a tool that makes you produce.

**The rule of thumb:** use AI *after* you have tried, and use it to be *asked* questions more than to be *told* answers.

## Po polsku, w skrócie

Pamięć buduje to, co robisz, więc sztuczna inteligencja nie zmienia nic w tym, jak działa uczenie się, i wszystko w tym, które błędy są najłatwiejsze. Czytanie wyjaśnienia od AI to ponowne czytanie w doskonałej postaci: jasne, pewne i napisane dla ciebie, więc daje złudzenie wiedzy mocniej niż podręcznik. W eksperymencie z GPT-4 uczniowie z pełnym dostępem mieli lepsze wyniki na ćwiczeniach i o 17% gorsze na egzaminie bez AI; wersja dająca tylko podpowiedzi prawie tego uniknęła. Proś więc o podpowiedź po własnej próbie, o quiz zamiast wyjaśnienia, o fiszki zamiast streszczenia, o pytania o poziom wyżej, o ucznia, któremu ty tłumaczysz. I sprawdzaj każdą odpowiedź: AI potrafi mylić się z pewnością siebie.

## See also

- [Metacognition](../../01_Knowing_What_You_Know/metacognition/README.md) — why a fluent explanation feels like knowing
- [Studying vs learning](../../01_Knowing_What_You_Know/studying_vs_learning/README.md) — the levels above "explain it to me"
- Hamsa Bastani and colleagues, "Generative AI without guardrails can harm learning: evidence from high school mathematics", *PNAS* (2025)
- Gregory Kestin and colleagues, "AI tutoring outperforms in-class active learning", *Scientific Reports* (2025)
