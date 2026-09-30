# How memory works: the pipeline, and which technique acts on which stage

**Level:** 101 · for anyone who wants to know why the study techniques work, not just that they do

**One line:** A memory passes through attention, working memory, consolidation and long-term storage, and each stage has a limit; every technique with strong evidence acts on one of those limits. The techniques are well established; the biology named under each stage is mostly good evidence in animals.

## The pipeline

```
attention / encoding  ──>  working memory  ──>  consolidation  ──>  long-term storage
        │                        │                     │                     │
  acetylcholine             bottleneck            sleep / rest           re-retrieval
  (a focused beam)       (3–5 chunks at once)    (LTP and BDNF)     (the trace strengthens)
```

The top row is a model every textbook uses, from Atkinson and Shiffrin's multi-store model (1968) through Baddeley and Hitch's working memory (1974). The bottom row is the biology usually given for each stage, graded on [brain chemistry](../brain_chemistry/README.md). What this page adds is the column that matters to a learner: what limits each stage, and what to do about it.

| Stage | What limits it | What to do | Grade | Lesson |
|---|---|---|---|---|
| attention / encoding | what you did not attend to was never encoded | remove extraneous load; know the goal before you read | well established | [cognitive load](../../02_Making_It_Stay/cognitive_load/README.md), [count the vowels](../../01_Knowing_What_You_Know/count_the_vowels/README.md) |
| working memory | about four chunks at once (Cowan, 2001) | make the foundations automatic, so each takes one place | well established | [cognitive load](../../02_Making_It_Stay/cognitive_load/README.md) |
| consolidation | a new trace is weak, and the next thing you learn can overwrite it | review within the day; sleep instead of cramming | well established | [spaced retrieval](../../02_Making_It_Stay/spaced_retrieval/README.md), [sleep](../sleep/README.md) |
| long-term storage | a trace fades unless it is used | retrieve it, spaced out and mixed with other topics | well established | [spaced retrieval](../../02_Making_It_Stay/spaced_retrieval/README.md), [interleaving](../../02_Making_It_Stay/interleaving/README.md) |

And beside every stage, [metacognition](../../01_Knowing_What_You_Know/metacognition/README.md): a test, not a feeling, says whether the trace is there.

## Three processes

Zakrajsek's *The New Science of Learning* (chapter 4) reduces the memory models to three processes, after Melton (1963):

- **Encoding** is taking the information in. There is a kind for every sense; most of what a course teaches is encoded *semantically*, as meaning, and *elaboratively*, by attaching it to what you already know.
- **Consolidation** stabilises the trace. It happens in two phases: within hours at the synapse, and over days to months as the memory is reorganised from the hippocampus to the cortex (Sun and colleagues, 2023, [doi:10.1038/s41593-023-01382-9 ↗](https://doi.org/10.1038/s41593-023-01382-9), model the second phase as *complementary learning systems*). Sleep does much of this work: [sleep](../sleep/README.md). A new trace is easily **interfered with**: meet Jordan and then Pablo seconds apart and you keep Pablo. Hence the advice to avoid back-to-back classes where you can, and to review a class before the next one starts. *Grade: well established for the effect, good evidence for the two-phase account.*
- **Retrieval** gets it back out, and is not neutral: each retrieval destabilises and restabilises the trace, *reconsolidation*, usually stronger (Nader and Hardt, 2009; in rats, Gonzalez and colleagues, 2021, [doi:10.1073/pnas.2025275118 ↗](https://doi.org/10.1073/pnas.2025275118), show dopamine gating whether new information updates the reactivated memory). This is why testing yourself is a study method and not just a measurement. *Grade: well established in people for the testing effect; the reconsolidation mechanism is good evidence, mostly in animals.*

## The forgetting curve

Ebbinghaus (1885) measured his own memory for nonsense syllables and found the shape every study since has confirmed: loss is fast at first and then slow. Roughly half of new material is gone within a day or two and most of it within a month, unless it is reviewed (DeSoto and Roediger, 2019, is one modern replication). Zakrajsek's own Calculus 1 story is the cost in one number: high Bs and low As on four unit exams studied all night, then 37% on the final. [Spaced retrieval](../../02_Making_It_Stay/spaced_retrieval/README.md) has the arithmetic of why reviews at growing intervals keep a fact for years at a cost that grows only with the logarithm of the time. *Grade: well established.*

## The big four, and how sure each claim is

Summaries of learning science, including AI-written ones, tend to name the same four techniques. Three have lessons here.

| Technique | What to do | Grade | Lesson |
|---|---|---|---|
| retrieval practice (active recall, the testing effect) | close the book and write down what you remember; answer questions before checking notes | **well established**: Agarwal, Nunes and Blunt's review of classroom studies (2021, [doi:10.1007/s10648-021-09595-9 ↗](https://doi.org/10.1007/s10648-021-09595-9)); Van Hoof and colleagues (2021, [doi:10.1097/CEH.0000000000000335 ↗](https://doi.org/10.1097/CEH.0000000000000335)) | [metacognition](../../01_Knowing_What_You_Know/metacognition/README.md), [spaced retrieval](../../02_Making_It_Stay/spaced_retrieval/README.md) |
| spaced (distributed) practice | review at growing intervals; let Anki schedule it | **well established**: Cepeda and colleagues (2006), 259 of 271 comparisons; Hintzman (1974) for the theory; Van Hoof and colleagues (2021, [doi:10.1097/CEH.0000000000000315 ↗](https://doi.org/10.1097/CEH.0000000000000315)) | [spaced retrieval](../../02_Making_It_Stay/spaced_retrieval/README.md) |
| interleaving | mix topics and problem types in one session | **well established** for problems that are easy to confuse; Chen, Paas and Sweller (2021, [doi:10.1007/s10648-021-09613-w ↗](https://doi.org/10.1007/s10648-021-09613-w)) argue it works by discriminative contrast, a different mechanism from spacing | [interleaving](../../02_Making_It_Stay/interleaving/README.md) |
| elaboration (elaborative interrogation, dual coding) | ask why; connect it to what you know, in your own words and in a drawing; explain it as if teaching | **good evidence**: Dunlosky's 2013 review rated elaborative interrogation moderate; Van Hoof and colleagues (2024, [doi:10.1097/ceh.0000000000000580 ↗](https://doi.org/10.1097/ceh.0000000000000580)) | [studying vs learning](../../01_Knowing_What_You_Know/studying_vs_learning/README.md): teach-the-material mode |

Donoghue and Hattie's meta-analysis of ten techniques (2021, [doi:10.3389/feduc.2021.581216 ↗](https://doi.org/10.3389/feduc.2021.581216)) and Karpicke and O'Day's handbook chapter (2024, [doi:10.1093/oxfordhb/9780190917982.013.70 ↗](https://doi.org/10.1093/oxfordhb/9780190917982.013.70)) reach the same ranking. Two caveats belong beside the top row. Retrieval practice is effortful: Zheng, Sun and Liu (2023, [doi:10.1038/s41539-023-00159-w ↗](https://doi.org/10.1038/s41539-023-00159-w)) found its benefit depends on having working-memory capacity to spare, which is a reason to test yourself rested and in a quiet room, not a reason to skip it. And students can mostly recognise the effective techniques and still not use them (Rea and colleagues, 2022, [doi:10.3390/jintelligence10040127 ↗](https://doi.org/10.3390/jintelligence10040127)); what moves them is self-efficacy and habit, which is [mindset and motivation](../mindset_and_motivation/README.md) and [goals and schedules](../../04_Planning_the_Work/goals_and_schedules/README.md).

## Desirable difficulties

Robert Bjork's phrase for what the big four have in common: conditions that make learning harder now and better later. Retrieval, spacing and interleaving all lower performance during practice and raise it on a later test, which is why learners misjudge them (Nelson and Eliasz, 2022, [doi:10.1111/medu.14916 ↗](https://doi.org/10.1111/medu.14916), for a review; Biwer and colleagues, 2020, [doi:10.1016/j.jarmac.2020.03.004 ↗](https://doi.org/10.1016/j.jarmac.2020.03.004), on teaching students to choose them anyway). Two related findings, often garbled in summaries:

- **Pretesting.** Guessing the answer before you study helps, even when the guess is wrong (Kornell, Hays and Bjork, 2009; Richland and colleagues, 2009). Errors are useful feedback, and larger errors, felt as well as measured, predict a larger testing effect (Shi and Liu, 2026, [doi:10.3758/s13423-026-03009-z ↗](https://doi.org/10.3758/s13423-026-03009-z)). Feedback after a hard retrieval matters: Kliegl, Bjork and Bäuml (2019, [doi:10.3389/fpsyg.2019.01863 ↗](https://doi.org/10.3389/fpsyg.2019.01863)) show it can reverse the usual cost of effortful retrieval, and hints can rescue a retrieval that would otherwise fail (McLane and Selmeczy, 2025, [doi:10.1080/09658211.2024.2406312 ↗](https://doi.org/10.1080/09658211.2024.2406312)). *Grade: good evidence.*
- **Hypercorrection** is a different finding: errors made with high confidence are the easiest to correct once feedback arrives (Butterfield and Metcalfe, 2001). Summaries that fuse the two and add "a burst of dopamine" are stating a speculation as if it were the mechanism. *Grade: good evidence for the effect; the dopamine story is speculative.*

The difficulty has to be *desirable*: above your level, it is just difficulty. Vygotsky's **zone of proximal development** is the band between bored and frustrated, and the advice that follows from it is plain: when you are over the top edge, ask.

## Po polsku, w skrócie

Wspomnienie przechodzi przez uwagę, pamięć roboczą, utrwalanie i przechowywanie, a każdy etap ma swoje ograniczenie: czego nie zauważyliśmy, tego nie zakodowaliśmy; pamięć robocza mieści około czterech porcji; świeży ślad łatwo nadpisać, a sen go utrwala; ślad blednie, jeśli się go nie używa. Cztery techniki o najmocniejszych dowodach działają każda na jedno z tych ograniczeń: sprawdzanie się z pamięci, powtórki rozłożone w czasie, przeplatanie i łączenie nowego ze znanym. Wszystkie są „pożądanymi trudnościami” (Bjork): w trakcie nauki idzie gorzej, na teście lepiej, dlatego uczniowie je niedoceniają. Krzywa zapominania Ebbinghausa mówi, że bez powtórki połowa znika w dzień lub dwa. Zgadywanie przed nauką pomaga nawet wtedy, gdy się mylimy; „hiperkorekcja” to co innego: błędy popełnione z dużą pewnością najłatwiej poprawić.

## See also

- [Spaced retrieval](../../02_Making_It_Stay/spaced_retrieval/README.md), [interleaving](../../02_Making_It_Stay/interleaving/README.md), [cognitive load](../../02_Making_It_Stay/cognitive_load/README.md) — the lessons behind the table
- [Sleep](../sleep/README.md) — consolidation's main worker
- [Brain chemistry](../brain_chemistry/README.md) — the bottom row of the diagram, graded
- [References](../../REFERENCES.md) — every source cited on this chapter's pages, with what kind of study it is
- Todd D. Zakrajsek, *The New Science of Learning*, 3rd ed. (2022), chapter 4, "Improving the Learning Process"
