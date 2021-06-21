# ----------------------
EB version 2.1.512

Feb 12. 2019

Programmed by Anna Pryslopska (pryslopska.com)

Please report bugs to: anna.pryslopska@uni-tuebingen.de

# ----------------------

# Description

Simple reading time experiment template. Participants view a fixation point in the middle of the first letter of the sentence. After fixating the point, the whole sentence appears, as well as a second fixation point. When participants fixate a second fixation point or read the sentence for longer than 20000 ms. the sentence disappears. Some sentences are followed by a comprehension question with two answer alternatives. 

Please enable the notes (View > Properties > Note) for more information about all actions and triggers.

# Structure

The experiment is structured as follows:

1. Background information about the participants (contains questions about: gender, handedness, dominant eye, age, native Bundesland, and native language(s).)
2. Exercise
   - Fixation check
   - Sentence display with fixation check
   - Question display (if a question is coded)
3. Main experiment (divided into two block with a break in between)
   - Fixation check
   - Sentence display with fixation check
   - Question display (if a question is coded)

The break can be skipped by pressing "s".

(Re)Calibration takes place:

- Before the exercise.
- After the exercise.
- After the first block in the main experiment.
- Whenever the participants fail to fixate either of the fixation points.

This experiment has many redundancies built in. Should information be missing from the fixation or interest area reports, please check the message report.

The experiment consists of 4 lists. These are encoded in the trial data source in the column "LIST". This column is used in the randomization setting as the splitting column. Please consult the notes on how the TRIAL procedure is split.

# Hardware

This experiment was programmed for SR Research Eyelink 1000 desktop build, monocular mount and with the illuminator on the right. The display is 1920x1080. A game pad is used for navigation (two bottom buttons, left (6) and right (7)).

# Warning message

Warning message 2637 about a MultiLine Text Resource in EXPERIMENT->TRIAL->QUESTION->QUESTION_EVENTS->DISPLAY_Question->MULTILINE_TEXT_RESOURCE means that there are no interest areas generated for the question display. This is done here on purpose, but can be changed on the respective display.

# License

This work is licensed under the Creative Commons Attribution-NonCommercial 4.0 International.

Licensees may copy, distribute, display and perform the work and make derivative works and remixes based on it only if they give the author or licensor the credits (attribution) in the manner specified by these.

Licensees may copy, distribute, display, and perform the work and make derivative works and remixes based on it only for non-commercial purposes.