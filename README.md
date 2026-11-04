# Data Science Interview Questions 2026: 10 Free Practice Questions

Ten practice questions for data scientist interviews, picked from the 100-question Valenx Press Data Science Interview Question Bank. They cover the five areas DS interview loops tend to test: statistics and probability, A/B testing and experimentation, product metrics, SQL, and machine learning. They are a mix of Entry, Mid and Senior levels.

**Weekly drill packs:** [Valenx Pass](https://valenx.org/go/pass-y?utm_source=github&utm_campaign=data-science-interview-questions-2026&utm_content=readme), $79/yr, a new drill pack every Monday, cancel anytime.

Each question comes with a short hint, not a full answer. Try your own answer first, then use the hint to see if you covered the key idea.

**Contents:** [How to practice](#how-to-practice) · [The 10 questions](#the-10-questions) · [Get the full bank](#want-the-full-answers) · [License](#license)

## How to practice
1. **Set a timer.** Give yourself 3-5 minutes per question and answer out loud or in writing, as if you were in the interview.
2. **Answer before you read the hint.** The hint names what a strong answer has to include. It is not the full answer.
3. **Score yourself from 1 to 5.** 1 = can't define it; 3 = can explain it with one example; 5 = can draw it, compare alternatives and discuss edge cases.
4. **Redo anything you scored 3 or lower** two days later, without notes.
5. **Check one written answer for free** with the [answer-check tool](https://johnnnmai.github.io/ai-engineer-interview-questions/answer-check/?utm_source=github&utm_medium=repo&utm_campaign=ds_sample).

## The 10 questions

| # | Area | Level |
|---|---|---|
| 1 | Statistics & probability | Entry |
| 2 | Statistics & probability | Senior |
| 3 | A/B testing | Mid |
| 4 | A/B testing | Senior |
| 5 | Product metrics | Mid |
| 6 | Product metrics & business case | Senior |
| 7 | SQL | Entry |
| 8 | SQL | Mid |
| 9 | Machine learning | Entry |
| 10 | ML system design | Senior |

### Statistics and probability interview questions

**1. [Entry] What does a p-value actually mean?**
*Hint:* Define it under the assumption that the null hypothesis is true. Then say what it is *not*, and what you report alongside it.

**2. [Senior] A trial reports p = 0.03 with n = 50. What follow-up checks matter before you trust it?**
*Hint:* A p-value alone settles little. Ask about effect size and its interval, how the hypothesis and test were set up in advance, power, how many endpoints were tested, and replication.

### A/B testing interview questions

**3. [Mid] An experiment shows no significant result after two weeks. What do you do?**
*Hint:* First check whether the planned sample size and power were actually reached. Then use the confidence interval to tell "precisely near zero" apart from "too noisy to tell".

**4. [Senior] How would you test a pricing change in a two-sided marketplace?**
*Hint:* Ask whether one user's treatment can affect another user's outcome. If it can, think about which unit you randomize and how you keep the groups comparable over time.

### Product metrics interview questions

**5. [Mid] Story sharing dropped week over week. How do you investigate?**
*Hint:* Pin down the exact metric definition first. Then slice by time and segment, and walk the sharing funnel step by step before you guess at causes.

**6. [Senior] A test lifts conversion, but refunds rise too. Would you ship it?**
*Hint:* Put both effects in the same unit (money) before you decide. Then ask what kind of purchases the treatment is adding and what you would change and retest.

### SQL interview questions for data scientists

**7. [Entry] How do you define a signup cohort in SQL?**
*Hint:* Each user gets exactly one cohort period, based on a fixed start event. Join later activity back to that assignment and report by cohort and by time since signup.

**8. [Mid] Compare ROW_NUMBER, RANK and DENSE_RANK.**
*Hint:* The difference is what happens to ties and to the number that comes after a tie. Know which one to use for "top N distinct values".

### Machine learning interview questions

**9. [Entry] Explain the precision-recall tradeoff.**
*Hint:* Define each as a share of something different. Then tie the choice to which mistake costs the business more.

**10. [Senior] How would you design a fraud model when the fraud labels arrive late?**
*Hint:* Think about what is known at transaction time versus weeks later. Cover how the delay changes training, evaluation and monitoring, and what you would watch besides accuracy.

## Want the full answers?
The full Data Science Interview Question Bank has 100 graded questions with model answers, 20 deep-dives on what the interviewer is really testing, 20 rapid-fire one-liners, seven answer frameworks and a 7-day drill plan. It is part of **Valenx Interview Pass**.

- **A new drill pack every Monday:** questions, scoring rubrics and a practice plan. Week 0 arrives as soon as you join.
- **Data science track:** data science and product manager blocks start in Week 2 of the Pass calendar (Monday, Nov 16, 2026). Until then, the weekly drops cover AI engineering and MCP topics.
- **Written answers to your questions:** reply to your receipt email and we answer in writing. No live calls.
- **$19/month or $79/year.** Cancel anytime.

**[Join Valenx Interview Pass](https://valenx.org/pass?utm_source=github&utm_medium=repo&utm_campaign=ds_sample&utm_content=data-science-interview-questions-2026_L81)**

## License
© 2026 Valenx Press. This work is licensed under [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)](https://creativecommons.org/licenses/by-nc-nd/4.0/). You may share it unchanged, with credit to The Valenx Press team, for non-commercial use. You may not sell it or publish modified versions.

*The Valenx Press team*
