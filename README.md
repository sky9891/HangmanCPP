# HangmanCPP
 Hangman Game built using C++

## Requirements
* g++
* git (optional)

## Compile & Run
To **clone** and **compile** this game, you will need to have **git** and **g++** installed on your computer.<br>
From your command line:

```bash
git clone https://github.com/sky9891/HangmanCPP
cd Hangman
g++ -O2  main.cpp hangman_functions.cpp -o hangman
```

Run on **macOS & Linux**:
```bash
./hangman
```

Run on **Windows**:
```cmd
hangman.exe
```

## intructions to play

### Before Compile & Run
 
 * The *codeword* is to be updated in the main.cpp, **use lowercase only**
 * also modify the *hint* in main.cpp
 * initialize *answer* with equal no of spaces as letters in *codeword*.

### After Compile & Run

 * You can enter only one letter at a time
 * for correct input, no loss
 * for incorrect letter input, 1 loss
 * Total loss depends on letters in *codeword*
















































































































































-------
CHEAT: you can input multiple letters or a word at a time and the code loops for all wrong and correct letters