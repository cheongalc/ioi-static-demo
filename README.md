# ioi-static-demo
This is a standalone version of "Ikan Oh Ikan", the Malay word game created for Hwa Chong Institution (High School)'s Malay Department. 

"Ikan Oh Ikan" is the game used in Hwa Chong's annual Malay Language Competition, which attracts around 200 Malay Special Programme students yearly. 

The latest iteration was held in June 2023 and official media coverage on it can be found [here](https://www.instagram.com/hwachong.official/p/CtD07eMLGKt/).

# How to Play
"Ikan Oh Ikan" is a Malay word game that tests students' vocabulary. Students are given a fixed sequence of 16 alphabets and the idea is to form as many valid Malay words as possible within 3 minutes. The longer the words, the better. 

Bubbles will rise from the bottom of the screen and each bubble contains 1 random alphabet from the fixed sequence. Students control a fish with their mouse, and the fish must "eat" the bubbles in the correct order to form a word. Points will be awarded for valid words and points will be deducted for invalid words. Students cannot submit the same word twice.

Note that the fish **head** must touch the bubble in order to eat it. Bubbles will pass behind the fish body, so it is important to make sure that the fish head is facing the correct direction. 

Here are the gameplay keystrokes:
1. Movement of the fish is controlled via the mouse.
2. You can hold `Shift` to disable eating of bubbles if you want the fish to traverse a large portion of the screen without collecting bubbles along the way.
3. Once a word has been formed, press `Space` to submit. Your submitted words will appear in a list on the right of the screen.
4. If the fish ate a wrong character, press `d` to delete the last character in the current word being formed.
5. If the  word list is too long, press `w` to scroll down.
6. Press `a` to return to the top of the word list if you have scrolled down.

The real game is played in 3 rounds of 3 minutes each, and the entire game's flow is controlled by an administrator panel which this demo does not include. This demo only allows users to try the game for 1 round of 3 minutes.

# Instructions to test the Demo
1. Use a browser with a Chromium engine (either Chrome or Microsoft Edge) and open https://cheongalc.github.io/ioi-static-demo.
2. Enter an arbitrary sequence of 16 alphabets into the input box labelled "Sila masukkan 16 huruf di dalam ini". Here is an example: `LIOUGDEWANKASTBH`.
3. Press "Submit" and the game will begin. The HTML canvas containing the game is on the left. The current word being formed, your word list, the sequence of 16 alphabets, and the timer is shown on the right.
4. Once 3 minutes are up, your submitted words will be displayed and the page will be refreshed.