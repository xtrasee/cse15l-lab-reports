[Link to my own markdownparse](https://github.com/xtrasee/markdown-parse-main)

[Link to the markdownparse I reviewed](https://github.com/xtrasee/markdown-parse)

# **My Own Markdownparse Tests**
Snippet 1: For snippet 1, by using the preview, the output I expect should be ```[url.com,`google.com, google.com, ucsd.edu]``` because on the preview, it shows all four lines of code to be a valid link.
![test 1](https://user-images.githubusercontent.com/92359561/155485544-4306ae0a-b6e1-41a7-9972-89f941cc1f52.png)

![test 1 fail](https://user-images.githubusercontent.com/92359561/155485662-642ccc64-ce9e-4804-83a3-d65c0b2f31fb.png)

Snippet 2: Again, by using the preview, I noticed that all three lines of code were able to generate a link. I expect ```[a.com, <a.com(())>, example.com]``` because in the first line, (b.com) was actually printed out like a regular line and the other two links were able to be completely generated.

![test 2](https://user-images.githubusercontent.com/92359561/155481909-f4444fc2-c88f-47a2-9134-d1306e472a0e.png)

![test 2 fail](https://user-images.githubusercontent.com/92359561/155481964-8e2c4be2-7af0-4cb6-94be-4c9d524b29b5.png)

Snippet 3:I checked all the links in the preview to see where it directs me to and I was able to confirm what links I should expect. The links I expected was ```[https://www.twitter.com, https://ucsd-cse15l-w22.github.io/, https://cse.ucsd.edu/]```

![test3](https://user-images.githubusercontent.com/92359561/155482843-1313bac5-3f52-441a-abd7-c28b15c4d8ba.png)

![test3 fail](https://user-images.githubusercontent.com/92359561/155482937-9a1a97f6-f17e-480a-b0f6-d3137afc6c7c.png)

# **MarkdownParse I Reviewed Tests**
Snippet 1:
![test 1](https://user-images.githubusercontent.com/92359561/155653546-89be2fd8-7d55-4ce2-a3ab-1f917767b86b.png)

![test 1 fail](https://user-images.githubusercontent.com/92359561/155653592-c82f1834-6af1-4d4e-a1b6-d07e2ced8c35.png)

Snippet 2:
![test 2](https://user-images.githubusercontent.com/92359561/155653632-59cd5a5b-6647-4f1f-8f0d-3fef8ae18b27.png)

![test 2 fail](https://user-images.githubusercontent.com/92359561/155653666-5daa3294-09f5-47bc-807d-8ccfa16c52c8.png)

Snippet 3:
![test3](https://user-images.githubusercontent.com/92359561/155653692-8715fca0-8eb1-44d8-908c-480182f14b46.png)

Snippet 3 actually passed the final test.

**Question 1: Do you think there is a small (<10 lines) code change that will make your program work for snippet 1 and all related cases that use inline code with backticks?**

Ans 1: I do believe there can be a small code change that will account the inline code with backticks. I think ```if statement``` could take care of that issue. I believe the ```if statement``` should be something like this: ```if (nextOpenBracket > 0 && markdown.charAt(nextOpenBracket - 1) == '`'``` but I am still unsure.

**Question 2: Do you think there is a small (<10 lines) code change that will make your program work for snippet 2 and all related cases that nest parentheses, brackets, and escaped brackets?**

Ans 2: I am unsure about if the code change can be small since it has to account for multiple things, this might require multiple if statements.

**Question 3: Do you think there is a small (<10 lines) code change that will make your program work for snippet 3 and all related cases that have newlines in brackets and parentheses?**

Ans 3: I think we could make a small code change for the program to work for snippet 3. However, I am not very sure. I believe some type of if statement that accounts for white spaces such as ```" "``` or ```"
"```.
