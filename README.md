# smoke_alarm_hackpack_cpp

The official C++ ICPC Hackpack for UCF Team Smoke Alarm!

## How to install

1. Clone this repository using "git clone <https://github.com/conradsmi/smoke_alarm_hackpack_cpp>".

2. Navigate to your VS code snippets folder. In Linux, this can be found at ~/.config/Code/User/snippets.

3. Create a hard link between the repo's file and the new snippet file using "ln (the repo's location) cpp.json". This will make updating the file easier, and also lets VSCode actually use the file.

## Updating

1. Since there is now a hard link between the snippet file VSCode uses and the repo file, all you have to do is "git pull" and both the repo file and the VSCode file will update.

## Snippet formatting rules

1. Every snippet tab trigger should be preceded by "hack_".

2. No class! Only struct!

3. Use snake_case for struct/variable names and camelCase for function names.

4. Loops/branches with one line of body code should not have curly braces.

5. Comment generously.

6. For data structures and algorithms, write a short one-line comment with a brief overview. For algorithms, include the time complexity in this description and put the use usage of the algorithm in parantheses in the name field (e.g. "Kruskal's Algorithm (MST)).
