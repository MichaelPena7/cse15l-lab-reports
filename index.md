**Lab Report 3**

For this lab, I will have chosen to study and research the "grep" command, as it seems the most appealing to me as it seems very useful in finding specific strings of texts in a large amount of files. 

To start, I went ahead and asked ChatGPT for a rundown on some grep command-line options!


I decided to pick "--color", "-m", "-c", and "-L" for this lab report! However, I would like to briefly state that each my command-line options for grep will start with "-r", as it helps a lot with recursively searching through "./written_2" without explicitly needing to state a file, allowing me to search through the entirety of "./written_2" and its subdirectories and text files rather than just searching through a singular file! 

**1. "--color"**

"grep -r --color [pattern]" is a command that will search through "./written_2" for files that contain the pattern, then print each file and its text one by one. However, using the "--color" option, the instances of the pattern will now be highlighted in a different color font, allowing for clear and easy access of where the pattern actually is in the files! Here are some examples:

![Image](grepex1.png)

![Image](grepex2.png)

Essentially, it makes searching for the exact instances of a pattern much easier! For example, if you wanted to read more about frogs, it would give a clear place as to which sentences in the text file have "frogs"! In my case, the text is highlighted in red.

**2. "-m"**

"grep -rm [n] [pattern]" is a command that will search through "./written_2" 'n' amount of times for the pattern, stopping the search once it reaches 'n' or there are no more matches, with 'n' being a positive integer. This can be helpful in giving the first few instances of the specified pattern Here are some examples:

![Image](grepex3.png)

![Image](grepex4.png)

Here, I set n to 1, allowing grep to simply show me the first instance of both hawaii and frogs, showing which file they appear in first.

**3. "-c"**

"grep -rc [pattern]" is a command that will search through "./written_2" for the pattern, and display the amount of times that aforementioned pattern is seen in that file. Here are two examples:

![Image](grepex5.png)

![Image](grepex6.png)

Here, we can see the amount of times that the words "frog" and "rain" appear in the Kauffman folder's contents. This is useful as it gives an understanding on which file discusses these topics the most, allowing for quick access over which files to prioritize when looking for the amount of that pattern.

**4. "-L"**

"grep -rL [pattern]" is a command that will search through "./written_2" for files that DO NOT contain the pattern. Essentially, it inverses what -rl does, and gives an output containing files that do not have the pattern here are some examples:

![Image](grepex7.png)
Here, I incuded the use of "-rc" to prove "-rL"! Note how chapters 8 and 9 of Kauffman are the only chapters that do not have any mention of the pattern "water", and as a result, are the only ones displayed in the output of "-rL".
![Image](grepex8.png)

In summary, this command is incredibly useful in finding the inverse content of what "grep -l" would normally display. In my cases, if you didn't want a file to mention "water", then chapters 8 and 9 would be the perfect place to start as -L would display them.

**Credits**

For credits, I simply asked ChatGPT for some grep command-line options, and it listed me some options! If I had any clarifications, I asked it as well!

![Image](Chathelp1.png)

![Image](Chathelp2.png)

