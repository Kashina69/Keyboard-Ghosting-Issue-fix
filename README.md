# Keyboard-Ghosting-Issue-fix
This program ill remove your keyboard ghosting issue issue like if you are pressing one key and then another key is getting pressed like in my case it was i and then ] was getting automatically pressed so i suppressed the ] input for the next 2 second with this program 
## Steps to run
first check the code and put the value of the key which you are actually pressinand then the key which is getting pressed after that and then the suppression time ( for how long if that key input comes dont take it )

eg :
```c
// Define the key sequences to block
KeySequence blockedSequences[] = {
    {0x49, 0xDD, 2}, // 'i' followed by ']' within 0.5 seconds
    {0x4A, 0xDE, 2}, // 'j' followed by ''' within 0.5 seconds
    {0x38, 0xBB, 2}  // '8' followed by '=' within 0.5 seconds
    // Add more sequences here...
};
```
