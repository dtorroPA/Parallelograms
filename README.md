# Parallelogram Run

A Temple Run–style endless runner for Pre-AP Geometry (10th grade). Students play **Professor Protractor**, a geometry teacher running through the Temple of Euclid while the "Not-a-grams" (angry trapezoids and kites) chase them. At each stone gate, students see quadrilateral ABCD with congruence marks, parallel arrows, angle arcs, or measurements. They decide:

- **Left arch: PARALLELOGRAM!** The given information proves it.
- **Right arch: NOT ENOUGH INFO.** It might be a parallelogram, but that isn't proven.

**To use it, open `index.html` in any web browser.** No install is needed. It also works on GitHub Pages, Chromebooks, and tablets/phones (swipe controls).

## Criteria covered (sufficient)
1. Both pairs of opposite sides parallel
2. Both pairs of opposite sides congruent (tick marks, side lengths, or a rhombus)
3. Both pairs of opposite angles congruent (arcs, angle measures, or a rectangle)
4. One angle supplementary to both of its consecutive angles
5. Diagonals bisect each other (tick marks or segment lengths)
6. One pair of opposite sides both congruent and parallel

## Non-examples (not enough)
Only one pair of sides parallel (trapezoid) · one pair parallel and the *other* pair congruent (isosceles trapezoid) · only one pair of opposite sides congruent · consecutive sides congruent (kite) · only one pair of opposite angles congruent · consecutive angles congruent · an angle supplementary to only one neighbor · four angle measures that fail the test · only one diagonal bisected · congruent diagonals only · perpendicular diagonals only · mismatched tick marks.

## "What's missing?" gates
Some gates show partial marks, such as only AB ∥ DC, and ask what **additional information** would prove ABCD is a parallelogram. The two arches become **Option A** and **Option B**. One option completes a proof, and the other is a common trap. For example, AB ≅ DC works, but AD ≅ BC could give an isosceles trapezoid. Feedback redraws the diagram with the missing marks added and explains why the trap fails. The topics are a parallel pair, a congruent pair, opposite angles, one bisected diagonal, supplementary consecutive angles, and isosceles-trapezoid marks.

Diagrams are randomly generated each time, so no two runs are the same. Exactly half of the non-examples are drawn to *look* like parallelograms, using a parallelogram, rhombus, or rectangle that still fits the marks. The other half are drawn as their real counterexample shape, such as a trapezoid or kite. This teaches students to trust the marks and not the picture, and the feedback points it out when the picture was misleading.

## Classroom options
On the title screen, pick a **mode** and a **quick preset** (Study, Run, or Sprint), or open **Customize** to set each option yourself. The game remembers your choices on that device.

- **Mode:** Course (10, 16, or 24 gates, ending in an escape) or Endless (gates keep coming and the pace slowly increases until the runner is caught; tracks a best score)
- **Problem difficulty:** Basic (marks only, upright shapes), Standard (marks plus side lengths, angle measures, and diagonal lengths), Challenge (more tricky cases such as four-angle trapezoids, mismatched marks, and diagonal numbers, with more tilted diagrams)
- **Non-examples:** about 10%, 25%, or 50% (default) of the yes/no gates
- **"What's missing?" gates:** Off, Some (about 20%, default), or Lots (about 40%)
- **Runner speed:** Slow, Normal, Fast, Turbo
- **Time to answer:** 22 s, 14 s, 9 s, or 6 s
- **Gates come:** about every 7 s, 4 s, or 2.5 s of running
- **Obstacles:** Off, Light, Normal, Heavy
- **Lives:** 3, 5 (default), or unlimited (practice)
- **Obstacle hits:** cost a heart (default) or cost points only. After a hit, the runner flashes and can't be hurt for a moment.

Other features:
- **Hint:** "Read the givens in words" shows the given as text (half points)
- **Theorem Guide:** a reference sheet with marked diagrams of all six tests and the common traps
- **Results screen:** the student's name, the settings used, accuracy, a breakdown by criterion, and every missed gate with its diagram and explanation. Students can print it or save it as a PDF to turn in. Use **Pause → End Run** to finish early.

## Obstacles
- **Jump:** rubble walls across the whole path, and fallen columns in one lane (you can also dodge these)
- **Slide:** hanging vines and giant rulers
- **Dodge left or right:** stone pillars and flying protractors. Watch for the red "!" and the shadow on the path. Some protractors drift into a new lane.

While a question is on screen, the path is clear of obstacles so students can focus on the problem.

## Controls
`←`/`→` or `A`/`D`: choose an arch (or switch lanes between gates) · `Y`/`N`: choose an arch · `↑`/`Space`: jump · `↓`: slide · `H`: hint · `P`: pause · `M`: mute. You can also click the answer buttons on the question card.
