**Copying whole Directories with ```scp -r```**

We first run the command ```scp -r . cs15lwi22amk@ieng6.ucsd.edu:~/markdown-parse``` to copy the whole markdown-parse-main over to my remote account.

![copy](https://user-images.githubusercontent.com/92359561/153516444-631468fa-c78d-46c2-9e89-9a85d8f6c8ce.png)

After logging into my remote account, I was able to run my tests.
![test](https://user-images.githubusercontent.com/92359561/153521900-54aa2b64-fdf7-4618-ad9e-7d14a50f6bef.png)

We could also combinie the commands: ```scp```, ```;```,```ssh``` to copy the directory over and log into the remote account within one line.
![](https://user-images.githubusercontent.com/92359561/153530873-548ddeaf-3c5c-433d-8572-54f41b06e4f6.png)
![](https://user-images.githubusercontent.com/92359561/153531622-99f744ff-a80c-49b7-b73c-71ca2b45ebb6.png)

To run the tests on one line:
![](https://user-images.githubusercontent.com/92359561/153531185-89d79ebf-5033-49c0-8688-486ef334bd7c.png)
