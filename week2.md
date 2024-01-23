https://perthirtysix.com/tool/wordle-solver

![image](https://github.com/AndrewSalls/reflections/assets/77992504/2e6662b6-b68d-4233-b9bc-78bd2e799113)

![image](https://github.com/AndrewSalls/reflections/assets/77992504/19b490de-2691-4404-9f88-e24a7b432183)

This week, I looked at Shri Khalpada's Visual Wordle Solver. The solver consists of five columns of letters, and lines connecting letters to every other letter that could be used in a valid Wordle word.
Being a solver, this visualization is highly interactive. You can click on letters to lock them in as correct, reducing the lines connecting letters to just lines that connect to the correct letter. You can also enter incorrectly placed letters, which will hide any lines that don't connect to that letter at all, and incorrect letters, which will hide any lines that connect to that letter at all.

This visualization has two main components, its effectiveness as a visualization of valid letter combinations, and its effectiveness as a solver. As a solver, it is probably as powerful as possible without just looking up what the daily word is (although if you're using a solver, you might as well do that).
I'm not as interested in the solver component, since Wordle is easy (go play dordle https://dordlegame.io/, or cell tower https://www.andrewt.net/puzzles/cell-tower/), so I'll mainly focus on how well designed the solver is for ease of use and understandability.

As a visualization of the valid letter combinations remaining at a given Wordle game state, I think that the solver is overall good. The bottom section where you can enter incorrect and incorrectly placed letters matches the color scheme of the official Wordle game, and the correctly placed letters sync with the main visual, so entering a letter will cause the visual to update like you clicked on a letter.
The main visual looks great, with the many lines mostly being a cool visual that helps depict the decreasing number of possible solutions as you enter more information. However, the lines can be overwhelming, especially at the start when many letters have hundreds of possible words.
There is an option to hide the lines, but it completely hides the lines. I would have liked to see an option to only show lines adjacent to the last letter you clicked on, to get the same effect without the messy overlap. One feature that helps counteract the lines being hard to use for information is that every letter connected to the selected letter lights up in a similar green color.
I believe that those connected letters are tinted based on the number of possible words they are a part of, but the tinting is not very strong.

Lastly, I think that the visual should have allowed clicking on squares again to switch between correct, incorrectly placed, incorrect, and unselected. Right now, it only switches between correct and unselected. The only way to add incorrectly placed or incorrect letters is to use the bottom section, which is inconsistent with the correct letters, which can be placed with either part of the visualization.
Doing this would also make it easy to ban the few letters that are not a part of any valid Wordle word. For example, V can never be in the last letter position. Despite this, the solver lets you mark those letters as selected. If it is already possible to have letters be marked as incorrect directly on the visual, you can have these invalid letters start off marked as incorrect, while matching the overall design.
