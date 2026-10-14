# debug_log.md
# Author: [Kelly Lam]

## Bug 1
Error type: syntax-typo error 'amount'
File + line: The file was /home/klam9/ism3232/module05_functions/week8_buggy.py, line 22 and 13. 
What the error means: The key error showed 'amount' was wrong, meaning that something wasn't matching up to be able to run the code correctly. 
What I told the duck: After running the code/debug I saw that line 22 and 13 had a key error in 'amount'. When going through the line of codes, I saw that in line 4 there was a typo, 'amout' instead of amount with the help of DEBUG print. 
What I tried: I tried reviewing the code from the beginning to see if there was any mistakes to start from there and I saw the typo in line 4.
How I fixed it: By fixing the spelling on line 4 from 'amout' to 'amount' so the code can process it. 

## Bug 2
Error type: '>' not supported between instances of 'int' and 'str' 
File + line: /home/klam9/ism3232/module05_functions/ + line 24 and line 17.
What the error means: that it could not run because the return amount is in an int instead of a string. 
How I fixed it: instead of '1000', I removed the ' because it is an int and not a string. 

## After Fixing Both Bugs
Final output: Total: $5150.00 accross 3 records 
True
Did pytest pass? Yes

## AI Literacy Reflection
Did I use AI? No
If yes -- exact prompt I used: ___
What AI explained: I did not need AI because of the DEBUG print, I also reviewed each line of code to make sure there wasn't any syntax/typo errors because those mistakes are simple to fix. 
What I changed myself: I went through the code to see if there was any typo error mistakes first line by line and I saw that in the first bug in id:1 the amount was a typo 'amout' instead of 'amount'. And with line 17, the return amount is suppose to be an int so no ' is needed. 
Can I explain every fixed line? Yes

## What I learned
I learned that typos are a very common mistakes and that you should review your code line by line first. I also learned that having a DEBUG print is helpful to locate the bug faster. With the debug print it was able to identify which line of code was having issues. 