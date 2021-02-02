# smoke_alarm_hackpack_cpp

The official C++ ICPC Hackpack for UCF Team Smoke Alarm

## How to install

1. Navigate to your VS code snippets folder. In Linux, this can be found at ~/.config/Code/User/snippets

2. Clone this repository into that folder using "git clone <https://github.com/conradsmi/smoke_alarm_hackpack_cpp>"

3. Back up your existing cpp.json file (simply renaming it to something else is fine), then create a hard link between the repo's file and the new snippet file using "ln smoke_alarm_hackpack_cpp/cpp_hackpack.json cpp.json". This will make updating the file easier, and also lets VSCode actually use the file.

## Updating

1. Since there is now a hard link between the snippet file VSCode uses and the repo file, all you have to do is "git pull" and both the repo file and the VSCode file will update.
