# How we judge

Four models from four companies, OpenAI Codex, Google Gemini, Anthropic Claude and Moonshot Kimi, read every repository, score a published rubric with quoted evidence, and rank the field. A human jury holds the other half of the score.

The mechanism in five lines. Each model reads your repository on its own and lists what the README claims. It checks every claim against the code and scores eight criteria, and every score must quote a line from your files or it does not count. The four then compare every project with every other project in pairs, in both orders, on one question: which is the better hackathon project. Your share of won comparisons is your score from the models. Judges never see each other's names or results, and where they disagree it stays visible on your scorecard.


The same text as a page: https://philipvollet.github.io/netbird-hackathon-judging/

## What is judged

Every project is scored from 1 to 5 on eight criteria. The anchors below say what the two ends of the scale mean.

| Criterion | 1 means | 5 means |
|---|---|---|
| Claims match code | README claims have no code behind them, or the code is a stub | Every claim traces to code that is wired in and tested, and the commit history shows it was built in the event window |
| Ambition realised in the time | Trivial scope, a one-shot prompt or API wrapper with no engineering judgement, or an ambitious plan with nothing finished | A hard thing attempted and finished; the constraint shows judgement, not just effort |
| Problem choice and product decisions | No identifiable user, or a concept of a plan | A real pain, visibly understood, with decisions a user would notice |
| Originality and astonishment | Generic, derivative, hard to care about; a wrapper around someone else's model or API with nothing added | Surprising, memorable, not seen before, and demonstrably difficult |
| Delight | No reaction imaginable | The room would remember it and want to play with it; movement, sound, humour, absurdity all count |
| Clarity of README and demo | The first paragraph does not say what the project is; no way to run it | A reader can repeat the project to someone else after one minute; limits are admitted |
| Value to NetBird users | No relation to NetBird, which costs nothing | Solves a pain NetBird users have and does something not previously possible with NetBird, or reaches the NetBird community |
| Built here, honestly | A bulk dump or work that predates the event, not declared | Clean incremental history inside the window, every outside piece declared and traceable, no large files committed |

### Two knockouts

- **Nothing.** No code implements any README claim, and no demo exists.
- **Not built here.** The work predates the event window and was not declared.

A knockout counts only when three judges other than the one who raised it confirm it with checked quotes.

### The overall question

> Which of the two is the better hackathon project, judged on the published criteria? One verified, astonishing thing, real fun, or real value to NetBird users can each carry a project; a well-rounded average beats none of them. Relevance to NetBird lifts a good project, it never replaces quality.



## How the council works

1. **Read in order.** Each judge first lists the claims the README makes, then reads every text file in the repository in the same fixed order.
2. **Trace every claim.** Each claim is followed to the code that implements it, or it is marked as missing or not wired in.
3. **Quote the evidence.** Every score comes with a quote from the files, and that quote is checked word for word against the files.
4. **Hide the names.** Judges see each other only as letters, and every pair of projects is shown to them in both orders.
5. **Ask one question.** Each judge compares every pair of projects on the overall question; the share of comparisons a project wins is its number.
6. **Keep disagreement.** Where judges disagree, the scorecard says so and shows the dissenting view with its quote.

## What teams submit

- **Repository.** The repository URL and the exact commit to judge. Nothing after that commit is read.
- **Demo video.** A short recording that shows the project doing its job.
- **Pitch.** A few lines on what the project is, who it is for and why it matters.

Declare any work that existed before the event in your README. Declared prior work is fine; undeclared prior work can lead to a knockout.

Large files are split and read in full, never dropped; binary files are listed but not read. Commits made outside the event window, very large commits and very large files are reported to the judges as evidence, and the judges decide what they mean.

## Fairness

- No weights and no sums: the ranking comes from head to head comparisons, not from adding up scores.
- A score without a checked quote from the repository carries no weight.
- Judges never see which model or company the other judges are.
- Every pair of projects is presented in both orders, so going first or second does not help.
- The human jury holds half of the score and holds the other half of the score.

## What teams get back

- A scorecard with every judge's scores and the quotes behind them.
- The full ranking of the field.
- The judge prompts, published after the event.

---

Built on the junta model council. Research behind the rubric: 25 published rubrics, 69 papers, 700 community threads.

Text licensed under CC BY 4.0, see `LICENSE`. The IBM Plex fonts are under the SIL Open Font License, see `fonts/IBM-Plex-LICENSE.txt`.
