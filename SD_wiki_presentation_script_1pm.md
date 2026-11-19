# South Dakota Election Analysis Wiki: 1 PM Presentation Script

*About 10–12 minutes. Plain spoken script. South Dakota figures throughout; the only Nebraska numbers are in the section labeled "Nebraska comparison." 2026 governor votes are certified; 2026 ballots cast are still labeled unofficial on the Secretary of State results site.*

## 1. Opening (about 1 minute)

Good afternoon. Today I'm walking you through the South Dakota Election Analysis wiki. It's built the same way as the Nebraska wiki, with the same method, applied to South Dakota's own numbers.

Everything you'll see comes from the South Dakota Secretary of State: the official 2022 canvass, the 2026 State Canvass that was certified on November 10, the results-site turnout files, and the voter registration reports by county. Population comes from the Census Bureau.

One thing up front: these pages measure a pattern. They don't claim anyone did anything. Where I talk about "implied extra votes," that reading is my hypothesis, and I'll say so each time.

## 2. Home page (about 1 minute)

The Home page has four links: Reverse Math, the Locked South Dakota Formula, Floor and Ceiling, and Graphs.

Two differences from Nebraska. First, South Dakota has no Cedar-County-style audit page. We use the same reverse-factoring method from the Cedar work, but there's no county manual-audit record here. Second, South Dakota has no all-mail counties. People vote at precinct polling places or, in 12 counties, at vote centers, and anyone can vote absentee.

The statewide picture: active registered Democrats fell from 151,415 to 135,275. That's a drop of 16,140, about 10.7 percent. Democratic governor votes fell from 123,148 to 111,161. Total ballots fell from 354,670 to 310,298.

So both Democratic votes and Democratic registration went down. The question is how the two moved against each other, county by county.

## 3. The Locked South Dakota Formula (about 1.5 minutes)

Here's the equation, word for word:

**Gap equals Democratic votes divided by total ballots cast, minus Democratic registered voters divided by total registered voters.**

A positive gap means Democrats got a bigger share of the ballots than their share of registration. A negative gap means a smaller share. In South Dakota, "registered voters" means active registered voters.

Delta-G is simply the 2026 gap minus the 2022 gap.

The page has a blank twelve-line template anyone can fill in for a county, and a worked example for Moody County. Moody's gap went from plus 0.70 to plus 11.98, so its delta-G is plus 11.28, the highest in the state.

One rule: Lincoln County is the only county that gained active registered Democrats, up 150. So Lincoln skips the residual step and is reported as raw numbers only.

## 4. Reverse Math (about 2.5 minutes)

This page takes the formula step by step.

**Step one, the gap.** Across all 66 counties, delta-G averaged plus 4.82 points, and the median was plus 4.78. It ranged from minus 0.99 in Hughes to plus 11.28 in Moody. Delta-G was positive in 62 of 66 counties.

**Step two, the reverse-factoring step.** We take out the part of delta-G that comes from the drop in Democratic registration share. What's left is the residual. Mathematically, that residual is just the change in Democratic vote share, 2026 minus 2022. It's a benchmark, not proof. Then we multiply the residual by 2026 ballots and divide by 100. That gives what I call implied extra votes, or offset votes. Again, that's my hypothesis, not a finding.

**Step three, South Dakota's own constant.** Fit delta-G against the registration-share drop across all 66 counties and you get: delta-G equals 0.10 plus 1.07 times the registration-share drop. Put simply, each point of lost registration share goes with about one point of delta-G. That's South Dakota's constant, computed from South Dakota data only.

**Step four, the band.** The band runs from plus 4.0 to plus 7.9 points of delta-G. 29 counties sit inside it, 10 are above it, and 27 are below it.

The implied extra votes are:
- plus 2,269 for the in-band 29;
- plus 754 for the 10 above the band;
- minus 30 for the seven ranch counties.

Here's the big caveat. Minnehaha alone accounts for plus 1,519 of that plus 2,269, about two-thirds. Minnehaha also has two precincts, 0416 and 0516, where the governor tally came in far below the Senate tally. So the in-band total depends heavily on one county, and that county has data questions.

**Vote centers.** The 12 vote-center counties shifted less than the 54 precinct counties. Their average delta-G was plus 2.61, against plus 5.31 for precinct counties, a gap of about 2.7 points. An earlier precinct-only model put that gap at about 2.6 points. When we reran that model with the locked formula, it came out at about 2.5. Same direction, similar size.

## 5. Floor and Ceiling (about 2 minutes)

The floor and the ceiling are the two edges that frame the middle band.

**The floor** is the seven ranch counties: Harding, Haakon, Campbell, Jones, Perkins, McPherson and Douglas. Each had a Democratic registration share under 14 percent in 2022. Their Democratic base is too small for the pattern to show. Harding is the most Republican baseline, with a 2022 Democratic vote share of 4.83 percent. All seven sit below the band.

The page also lists a second floor set from the forward-surplus run. These are the five most negative 2022 gaps: Aurora, Charles Mix, Miner, Gregory and Ziebach.

**The ceiling** is the two reservation counties, Oglala Lakota and Todd. They're heavily Democratic and had little room to move. Oglala Lakota's delta-G was plus 0.82 and Todd's was plus 3.91. One note for accuracy: Buffalo's Democratic registration share is actually a hair higher than Todd's.

The top five delta-G counties are Moody (plus 11.28), Roberts (plus 10.44), Buffalo (plus 10.30), Miner (plus 9.07) and Union (plus 9.00).

**South Dakota's constants.** We fit the forward surplus equation, S equals m times D over 100 plus b:
- 2022: m is minus 6.75 and b is plus 4.61.
- 2026: m is plus 3.70 and b is plus 6.88.

Both fits are weak. Registration share explains only 1 to 2 percent of the differences between counties.

In the labeled comparison table with Nebraska, Iowa and Kansas, South Dakota's 2026 slope sits well below all three neighbors. Its 2022 slope and both intercepts fall inside the neighbor range. Each state defines registration a bit differently, so the comparison is a flag, not a verdict.

**Counties to narrow out:**
- the ranch floor;
- the reservation ceiling;
- Minnehaha and Pennington, for their incomplete precincts;
- Buffalo, Clay and Ziebach, because they pull the fitted lines hard;
- Lincoln, as the only non-loss county.

## 6. Graphs (about 2 minutes)

The Graphs page has nine sections:

1. **Vote share against registration share.** Dots above the line have a positive gap.
2. **Delta-G for every county**, from Minnehaha, the largest, down to the smallest. The ranch floor is in green, the reservation ceiling in purple, and the top five in orange.
3. **Residuals.** Each county's delta-G minus the statewide average of plus 4.82.
4. **Delta-G against population.** This shows the vote-center counties sitting lower.
5. **The slope chart.** One gray line per county from 2022 to 2026.
6. **The forward-surplus fit.** The fitted lines are nearly flat.
7. **The stacked bars.** Blue is 2022 Democratic share, amber is the gain, a red tick marks a loss, and navy bars below zero are registered Democrats lost.
8. **Gain sorted by 2022 share.** A county's 2022 share doesn't predict its gain.
9. **Implied extra votes for the band of 29.**

## 7. Nebraska comparison (labeled; Nebraska data, about 1 minute)

*Nebraska numbers, shown only for comparison. Nebraska's 2026 figures were unofficial when computed. This uses Nebraska's own formula version, with a race-votes denominator and all registered voters.*

In Nebraska's 10 all-mail counties wholly inside the Third District, delta-G pooled at plus 6.04, with a county average of plus 5.79. The other 69 whole-CD3 counties pooled at plus 7.50, with an average of plus 5.72. All 79 together pooled at plus 7.38. Vote-share growth was plus 3.49 points in the all-mail group and plus 5.02 across CD3.

In other words, Nebraska's all-mail counties didn't stand out from the rest of the district. South Dakota has no all-mail counties, so there's no South Dakota version of that test.

I'm leaving out the Cedar County hand-count precinct figures. The audit sheets aren't in the source files I could re-check today.

## 8. Close (about 30 seconds)

To sum up:
- South Dakota's delta-G averaged plus 4.82, with a median of plus 4.78.
- 29 counties sit in the band.
- Vote-center counties moved about two and a half points less than precinct counties.
- Minnehaha drives most of the in-band implied votes.

This is a hypothesis, and the wiki shows the arithmetic so anyone can check it. The next step is records: cast vote records, ballot images, and reconciliation in Minnehaha and Pennington. Thank you.
