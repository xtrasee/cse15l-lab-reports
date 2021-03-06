# **Lab Report 2**

## **Code Change #1**

[Test #1](https://github.com/xtrasee/markdown-parse-main/blob/main/test1.md)

- Code change:
![](https://user-images.githubusercontent.com/92359561/151645903-0863518f-df26-4741-ab79-9d2b4bec845e.png)
Symptom: 
![](https://user-images.githubusercontent.com/92359561/151644985-16e4641f-eb49-4df3-9220-5bfdce341261.png)
The relationship between the bug, the symptom, and the faling inducing input is to really test whether the code can distinguish an image from a link. Clearly, the output when I ran this breaking test is that it continuously runs and runs out of heap space. Therefore, since our output was not empty, we can see through the symptom when we ran our code that there is a bug.

---
## **Code Change #2**

[Test #2](https://github.com/xtrasee/markdown-parse-main/blob/main/test2.md)

- Code change: this was the same fix in test one because it made sure to stop after the first closeParen
![](https://user-images.githubusercontent.com/92359561/151645903-0863518f-df26-4741-ab79-9d2b4bec845e.png)
Symptom: 
![](https://user-images.githubusercontent.com/92359561/151645042-31bccf9e-7104-40bf-b622-00d149aeb08e.png)
The test file caused an out of memory error which was a symptom that pointed out to me that there was a bug in the intial code. However, rerunning it with the added code that defined the positioning of where the open/close brackets and the open/close parentheses should be, it printed out the correct output "[linkrus.com]" because it stopped right after the first parenthesis aka closParen.

---

## **Code Change #3**

[Test #3](https://github.com/xtrasee/markdown-parse-main/blob/main/test3.md)

- Code change: I attempted to fix the error but am unsure if I really fixed it 
![](https://user-images.githubusercontent.com/92359561/151647847-b5d46fb1-4146-4a97-9080-227c8a212744.png)

Symptom: 
![](https://user-images.githubusercontent.com/92359561/151647355-4ead8205-0e55-4210-92ff-a03e0a4f090c.png)

The test file caused an out of memory error which was a symptom that pointed out to me that there was a bug in the intial code. As. I reran with my new code, I did get the output I was expected, "[something.com]" however, I was unsure if it still read through all the characters in the file but only returned or link or if it just completely stopped after the closeParen. In this case, although the symptom of the bug is not clearly showinig, the bug could still be there.

---
