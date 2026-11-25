# CS50 Runoff
A command-line election simulation written in the C programming language that implements a ranked-choice voting system, allowing voters to rank candidates in order of preference.

## Features:
- Candidate Management: Stores candidate names, vote counts, and elimination status using a custom `candidate` structure.
- Ranked Voting: Allows voters to rank candidates in order of preference.
- Vote Validation: Uses `strcmp()` to verify that submitted candidate names are valid.
- Preference Storage: Stores voter rankings in a two-dimensional array.
- Vote Tabulation: Counts votes for each candidate based on the highest-ranked candidate who has not been eliminated.
- Majority Detection: Identifies a winner when a candidate receives more than 50% of the votes.
- Candidate Elimination: Eliminates candidates with the lowest vote count between rounds.
- Automatic Runoffs: Recalculates vote totals after each elimination round.
- Tie Detection: Identifies when all remaining candidates are tied and declares them joint winners.

#

Developed as apart of the curriculum for [Harvard University's CS50X: Introduction to Computer Science](https://cs50.harvard.edu/x/2025/psets/3/runoff/)
