# Learning to Learn — Learning Library

<!-- --8<-- [start:hero] -->

A learning library about learning itself, built the same way as its siblings [math-learning-library ↗](https://github.com/masiarek/math-learning-library) and [rust-learning-library ↗](https://github.com/masiarek/rust-learning-library): **one idea per page, and every claim backed by a program that actually runs.**

No page here hand-types what a program prints. Each lesson links a real `.py` file; a tool runs it, checks the output against a recorded answer key, and pastes that verified output into the page. CI fails if any of the three drift apart. So when a page says *"a student who reuses the last formula scores 75% on the blocked sheet and 25% on the exam"*, that is not a promise; it is a test result.

Some claims about learning no program can check: what sleep does to a memory, what a walk does to attention, whether a supplement does anything. Those pages do the next best thing. **Every claim on them carries a grade**, well established, good evidence, weak or speculative, with the source it rests on, and no page gives a dose or recommends anything to take.

The examples are **stdlib-only, on purpose**. If you have `python3`, you can run every page in this repo.

📖 **Read it as a site:** <https://masiarek.github.io/learning-to-learn-library/>

<!-- --8<-- [end:hero] -->

<!-- --8<-- [start:below-hero] -->

## Start here

[**01_Knowing_What_You_Know/**](01_Knowing_What_You_Know/README.md) — *How do you know that you know?*

| Lesson | What it teaches |
|---|---|
| [Metacognition: judging what you know](01_Knowing_What_You_Know/metacognition/README.md) | Flavell's four abilities, and the one a program can measure: confidence against results, the Brier score, and why honest confidence minimises it |
| [Count the vowels](01_Knowing_What_You_Know/count_the_vowels/README.md) | McGuire's exercise: 3 of 15 phrases remembered after counting vowels, 12 after knowing the goal and the principle |
| [Studying vs learning](01_Knowing_What_You_Know/studying_vs_learning/README.md) | Bloom's six levels climbed on the Pythagorean theorem, up to a formula that re-creates the facts a student would memorise |

[**02_Making_It_Stay/**](02_Making_It_Stay/README.md) — *How do you learn so that it lasts?*

| Lesson | What it teaches |
|---|---|
| [Spaced retrieval](02_Making_It_Stay/spaced_retrieval/README.md) | The forgetting curve, why testing beats rereading, the study cycle, and why a geometric review schedule makes remembering cost a logarithm |
| [Interleaving](02_Making_It_Stay/interleaving/README.md) | A blocked sheet of volume problems asks you to choose a formula 4 times in 12, a mixed exam 7 in 8; a student who reuses the last formula scores 75% on the sheet and 25% on the exam |
| [Cognitive load](02_Making_It_Stay/cognitive_load/README.md) | Working memory holds about four chunks, and a chunk is whatever practice made automatic: (a+b)² = a² + 2ab + b² is 19 items to a beginner and 1 to an expert |

[**03_Believing_You_Can/**](03_Believing_You_Can/README.md) — *What does a belief have to do with the evidence?*

| Lesson | What it teaches |
|---|---|
| [Learned helplessness](03_Believing_You_Can/learned_helplessness/README.md) | Honest counting, (s + 1)/(n + 2), leaves a learner who failed ten times never trying the lever that works; four small successes, or four watched ones, get them started |
| [Day or night: perspective taking](03_Believing_You_Can/day_or_night/README.md) | "When does night begin?" has four exact answers in Starbuck, WA, 20:49 to 23:39, one per cutoff; the sorites, and fuzzy logic's third way out |

[**04_Planning_the_Work/**](04_Planning_the_Work/README.md) — *Why does a good plan still fail, and what fixes it?*

| Page | What it teaches |
|---|---|
| [The buffer hour](04_Planning_the_Work/the_buffer_hour/README.md) | Task times are skewed, so five honestly estimated one-hour tasks fit in five hours one day in thirteen; a reserved hour gives 47%, and a recorded overrun ratio corrects the estimates |
| [Goals and schedules](04_Planning_the_Work/goals_and_schedules/README.md) | Specific goals just below your best, process goals, stretch goals, a written week with an hour in reserve, to-do rules, and which of the circulating "protocols" are findings |
| [Learning with AI](04_Planning_the_Work/learning_with_ai/README.md) | Answers are rereading made perfect; questions, hints, quizzes and a student to teach make every technique cheaper |

[**05_Body_and_Brain/**](05_Body_and_Brain/README.md) — *Which claims about sleep, exercise, food and the brain should a learner believe?*

| Page | What it grades |
|---|---|
| [How memory works](05_Body_and_Brain/how_memory_works/README.md) | The pipeline from attention to storage, the three processes, the forgetting curve, the big four techniques and desirable difficulties |
| [Sleep](05_Body_and_Brain/sleep/README.md) | Sleep after learning, sleep loss before it, naps, quiet rest, and what is mostly from rats |
| [Exercise](05_Body_and_Brain/exercise/README.md) | Long-term brain health, attention for the next hour, the small and inconsistent effect on a study session, and BDNF |
| [Food and supplements](05_Body_and_Brain/food_and_supplements/README.md) | Caffeine, deficiencies, diet over decades, and why the nootropic evidence is thin; no doses |
| [Brain chemistry](05_Body_and_Brain/brain_chemistry/README.md) | LTP, acetylcholine, dopamine, norepinephrine: good evidence in animals, and what does and does not follow |
| [Mindset and motivation](05_Body_and_Brain/mindset_and_motivation/README.md) | Self-regulation, self-efficacy, growth mindset's real size, two biases, imposter syndrome, stress, intrinsic motivation |

## Other ways in

- [Start here](00_Start_Here/README.md), [topic map](TOPICS.md), [glossary](GLOSSARY.md), [resources](RESOURCES.md) (books), [references](REFERENCES.md) (papers, with what kind of study each is), [roadmap](ROADMAP.md).
- Every lesson ships an Anki deck and ends with a short summary in Polish.

## Running the examples

```bash
python3 02_Making_It_Stay/interleaving/examples/interleaving.py   # any one page
python3 tools/run_examples.py --check                              # all of them, as CI does
```

## Contributing

House rules are in [CONTRIBUTING.md](CONTRIBUTING.md): one idea per folder, output generated never typed, stdlib only, evidence grades in place of a program where no program can check the claim, and a place in the topic map for every page.

<!-- --8<-- [end:below-hero] -->
