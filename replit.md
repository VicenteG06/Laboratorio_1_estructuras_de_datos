# C Lists and Stacks Lab

## Project Overview
This is a C programming exercise project focused on linked lists (ArrayList) and stacks. Students implement functions in `exercises.c` and verify their work using `bash test.sh`.

## Structure
- `exercises.c` — Student exercise file (the only file students should modify)
- `test.c` — Test suite (auto-compiled by test.sh)
- `arraylist.h` / `arraylist.c` — ArrayList TDA implementation
- `stack.h` — Stack TDA header
- `test.sh` — Build and test script; compiles test.c with gcc and runs tests

## Running
```bash
bash test.sh
```
Compiles `test.c` with `gcc -g -Wall -Werror` and runs the resulting `a.out`.

## Workflow
- **Start application**: `bash test.sh` (console output)

## Notes
- No frontend or backend web server — this is a pure C terminal project.
- The README explicitly states not to modify project structure (exercises.c only).
