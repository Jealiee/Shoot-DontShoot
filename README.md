# Shoot / Don't Shoot

A short reaction time experiment made in [PsychoPy](https://www.psychopy.org/).
Participants see drawings of people one at a time and have to decide quickly whether to "shoot".

## The task

- Each person is shown for **0.7 s**, followed by a **2–3 s** break with a fixation cross (`+`).
- If the person is holding a **gun**, press **Enter** to shoot.
- If the person is holding a **camera**, a **phone** or **nothing**, don't press anything.
- Pictures are shown in random order without repeats, and the task lasts **about 30 seconds**.

At the end, participants see their results:

- **Correct:** correct answers out of all pictures shown
- **Accuracy:** the same, in %
- **Mean reaction time:** average time to press Enter on gun pictures, in ms

## How to run it

1. Install [PsychoPy](https://www.psychopy.org/download.html). The experiment was made with version 2026.2.
2. Download or clone this repository and keep all files together in one folder.
3. Open `main.psyexp` in PsychoPy **Builder** (File → Open).
4. Click the green **Run** button and fill in the participant number.
5. Press **Esc** at any time to quit.

Results for each participant are saved in the `data` folder.

## Files

| File / folder | What it is |
|---|---|
| `main.psyexp` | The experiment (open in PsychoPy Builder) |
| `conditions.csv` | List of all pictures with their condition (`threat` / `safe`) and correct answer |
| `Drawings/` | The pictures: `Gun` (30), `Camera` (17), `Phone` (30), `Nothing` (13) |

## Credits

All drawings were made by **Inga Szotowska**. Thank you very much, Inga, for the illustrations! This experiment would not exist without them.
