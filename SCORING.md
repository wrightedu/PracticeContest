
# Scoring

The algorithm used in PC2 to compute Rank and “Score” (Penalty Points) is the one used in
the ICPC World Finals, which is as follows:

1.  Teams are ranked according to the number of problems solved; a team solving more
problems is always ranked higher than a team solving fewer problems.

3.  Within a group of teams solving the same number of problems, teams are ranked by
increasing “Penalty Points” (that is, the team with the lowest number of Penalty Points
is ranked highest within the group). Teams only accrue Penalty Points for problems
which the team has solved; unsolved problems do not affect the scoring in any way.
Teams accrue Penalty Points for solved problems in two ways:
  - Some number of penalty points for each minute elapsed from the start of the
  contest until the problem was solved (the time of SUBMISSION is counted as
  the “time solved”; it does not matter how long it took the Judges to judge it).
  - Some number of penalty points for each INCORRECT submission submitted to
  the Judges prior to a correct solution for the problem (runs submitted after a
  correct solution are not counted in the scoring).

3. If two or more teams have the same number of solved problems and exactly the same
number of Penalty Points, ties are broken in favor of the team with the earliest time of
the last correct submission (that being the time when the team “finished” the contest).

5. If two or more teams remain tied for a given rank after all the above criteria have been
applied, the teams are listed in alphabetical order within their rank by the team’s
“display name”.

\- Per [PC2 Admin Guide](https://pc2ccs.github.io/docs/pc2v9AdminGuide.pdf) 
