[Link to my own markdownparse](https://github.com/xtrasee/markdown-parse-main)
[Link to the markdownparse I reviewed]()

***My Own Markdownparse Tests***
Snippet 1: For snippet 1, by using the preview, the output I expect should be ```[url.com,`google.com, google.com, ucsd.edu]``` because on the preview, it shows only the last three lines of code to be a valid link.
![test 1](https://user-images.githubusercontent.com/92359561/155485544-4306ae0a-b6e1-41a7-9972-89f941cc1f52.png)

![test 1 fail](https://user-images.githubusercontent.com/92359561/155485662-642ccc64-ce9e-4804-83a3-d65c0b2f31fb.png)

Snippet 2: Again, by using the preview, I noticed that all three lines of code were able to generate a link. I expect ```[a.com, <a.com(())>, example.com]``` because in the first line, (b.com) was actually printed out like a regular line and the other two links were able to be completely generated.

![test 2](<https://user-images.githubusercontent.com/92359561/155481909-f4444fc2-c88f-47a2-9134-d1306e472a0e.png)

![test 2 fail](https://user-images.githubusercontent.com/92359561/155481964-8e2c4be2-7af0-4cb6-94be-4c9d524b29b5.png)

Snippet 3:I checked all the links in the preview to see where it directs me to and I was able to confirm what links I should expect. The links I expected was ```[https://www.twitter.com,https://ucsd-cse15l-w22.github.io/,https://cse.ucsd.edu/]```

![test3](https://user-images.githubusercontent.com/92359561/155482843-1313bac5-3f52-441a-abd7-c28b15c4d8ba.png)

![test3 fail](https://user-images.githubusercontent.com/92359561/155482937-9a1a97f6-f17e-480a-b0f6-d3137afc6c7c.png)

***MarkdownParse I Reviewed Tests***
Snippet 1: For snippet 1, by using the preview, the output I expect should be ```[`google.com, google.com, ucsd.edu]``` because on the preview, it shows only the last three lines of code to be a valid link.
![test 1](https://user-images.githubusercontent.com/92359561/155480536-dd9666a1-bc2d-46f0-8cd0-6c5bb32a9b36.png)

![test 1 fail](https://user-images.githubusercontent.com/92359561/155480728-f07479f2-6b3d-44a4-9e76-126b881ed329.png)

Snippet 2: Again, by using the preview, I noticed that all three lines of code were able to generate a link. I expect ```[a.com, <a.com(())>, example.com]``` because in the first line, (b.com) was actually printed out like a regular line and the other two links were able to be completely generated.

![test 2](<https://user-images.githubusercontent.com/92359561/155481909-f4444fc2-c88f-47a2-9134-d1306e472a0e.png)

![test 2 fail](https://user-images.githubusercontent.com/92359561/155481964-8e2c4be2-7af0-4cb6-94be-4c9d524b29b5.png)

Snippet 3:I checked all the links in the preview to see where it directs me to and I was able to confirm what links I should expect. The links I expected was ```[https://www.twitter.com,https://ucsd-cse15l-w22.github.io/,https://cse.ucsd.edu/]```

![test3](https://user-images.githubusercontent.com/92359561/155482843-1313bac5-3f52-441a-abd7-c28b15c4d8ba.png)

![test3 fail](https://user-images.githubusercontent.com/92359561/155482937-9a1a97f6-f17e-480a-b0f6-d3137afc6c7c.png)
