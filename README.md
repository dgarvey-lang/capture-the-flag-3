# Capture the Flag: Systems of Equations (3-1 Practice)

A browser game for practicing the 3-1 worksheet on solving systems of equations by graphing. Students answer questions to move their team's runner across the field and capture the other team's flag.

Open `index.html` in a browser to play.

## Modes

- **Two teams, one screen:** Red and Blue take turns at one computer or a projector.
- **Solo practice:** race a rival runner that moves every 40 seconds.
- **Live class game:** everyone plays on their own device. This mode only works in the published Claude artifact (https://claude.ai/artifact/3L3MRvbV3VFTzPeqT2zE65), because it uses the artifact's shared database. Opened from this repository, the live mode shows as unavailable and the other two modes work normally.

## Worksheet version

`3-1 Practice.html` has the same 3-1 problems as a one-player worksheet, with no game. All 15 problems are on one page, and each has its own **Check answer** and **Help** button. Help gives a hint first, and a second press shows the full worked solution. A progress bar tracks finished problems. At the bottom, a summary table shows how each problem went, and a **Restart worksheet** button clears everything (click it twice to confirm).

### Completion codes

Students type their full name at the top of `3-1 Practice.html`. When every problem is finished, the page shows a code like `T7G3-0T9K`. The code is built from the student's name and their results, so it only works with that name.

To check codes, open `verify.html`. You can check one name and code at a time, or paste a whole class as `name, code` lines (two columns copied from a spreadsheet work too). A valid code also shows how many problems the student got right on the first try and how many times they used the full solution. Capital letters, extra spaces and punctuation in names are ignored.

The codes stop casual copying between students. They are not real security: someone who reads the page's source code could work out how to make one.

### Print and save

The end of the worksheet has **Print / Save as PDF**, which prints the worksheet with the student's answers and puts the completion code on its own page, and **Save results**, which downloads a text file with the student's name, score, code and how each problem went.
