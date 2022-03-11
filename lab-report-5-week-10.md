I found the differences between the two results by using ```diff``` as shown below.

![diff results](https://user-images.githubusercontent.com/92359561/157778933-0ad908f7-bfb4-4296-b288-5a746edfec0f.png)

For this lab report, I will be focusing on these two tests:

## Test #1
![test1](https://user-images.githubusercontent.com/92359561/157791871-2530d03d-7892-47cd-9813-33277c487cd3.png)

## Test #2
![test2](https://user-images.githubusercontent.com/92359561/157783650-a61c87eb-358f-4b4d-a3dd-1dfd32150e97.png)

---

For the first test, I believe that the class implementation of markdown-parse is correct because since the file contains only one line : ```[a](url &quot;tit&quot;)``` and the preview did not show it as a link. For example, 

![example](https://user-images.githubusercontent.com/92359561/157792914-e8ba301d-25b9-4c1b-bcef-c5d3a31323ce.png)

the expected output came from markdown-parse (bottom) instead of the my group's markdown-parse (top):
![test1](https://user-images.githubusercontent.com/92359561/157791871-2530d03d-7892-47cd-9813-33277c487cd3.png)

I believe a fix for my group's code could be to account for ```&quot```

---

For the second test, I believe it accounted for tests 494 to 498. From tests 494 to 498, I believe the outputs for both the class and group code are wrong. In the preview, all files except 496 show as valid links.

![example](https://user-images.githubusercontent.com/92359561/157799798-62dcc43b-5b6b-4b2c-9c1c-9bb31e661cdc.png)

So instead of these outputs:
![test2](https://user-images.githubusercontent.com/92359561/157783650-a61c87eb-358f-4b4d-a3dd-1dfd32150e97.png)

It should be

```
< [\(foo\]
< [foo(and(bar]
< []
< [foo\(and\(bar\]
< [<foo(and(bar]
```

I believe a possible fix would be to use an if statement to account for the necessary a tag since all the other files have an a tag except file 496.
