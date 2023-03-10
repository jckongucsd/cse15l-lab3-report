

# Hello!, This is my Lab Report Week 3. 


## Part 1 

### Which methods in your code are called?

The method: handleRequest is called when I enter add-message?s=<String>

  
### What are the relevant arguments to those methods, and the values of any relevant fields of the class?

The relevant arguments to this method are:

- URI url: this is the URI that is received by the java program
  
- Num: this is the current index of the String array wordBank. This value is used to add an element to the String[] wordBank

- String[] wordBank: this is the string array that stores all the user’s input

  
### How do the values of any relevant fields of the class change from this specific request? If no values got changed, explain why.

- Num: with each input, the num variable increases by 1 in order to match the index

- String[] wordBank: this value changes by appending a new string input element into the array. 

  
  
  
![lab3_img1](https://user-images.githubusercontent.com/122569310/215379064-2dbe1405-c33c-4e3c-bea3-87cfe743eba2.png)

(above image is adding the word "hello" to the word bank)
  
  
![lab_3_img2](https://user-images.githubusercontent.com/122569310/215379058-0c078fcb-bd53-4f45-a5ed-57b066b120ab.png)
  
(above image is adding the word "hello world" to the word bank and showing the history of all the words added)

![lab3_img_code](https://user-images.githubusercontent.com/122569310/215556577-445200ea-5e72-4c57-9072-488685c3f660.png)

  (above image is showing the code behind the web app)

## Part 2 (Errors & Bugs)
  
reverseInPlace: Fixed by using a temporary int variable n

<img width="348" alt="Screen Shot 2023-02-13 at 1 58 22 PM" src="https://user-images.githubusercontent.com/122569310/218584168-debf8f9b-4903-4e64-bb47-b8b7c4b1aa63.png">




## Reversed: 
Failure Inducing Input: `int input2 = { 1,2,3,4,5}`
  
Expected output: `{5,4,3,2,1}`

Actual output: `{0,0,0,0,0,0,0,0}`
  
 ![image](https://user-images.githubusercontent.com/122569310/218590372-c1f95931-c247-4844-8907-1ba64dc0a161.png)


The reversed method fails to initialize the indices to the values of the original array in the new array. Instead all the values are zeros. If we want the code to work as expected we should make newArray a copy of arr, then we can leave the rest of the code as is. 

  
### Here is the corrected reverse(int[] arr) function:
 
  ![image](https://user-images.githubusercontent.com/122569310/218591041-fb2bb799-d290-4209-96ab-7ca6eebf7264.png)

  
Now, all tests is passed:
  
  ![image](https://user-images.githubusercontent.com/122569310/218591359-6d82865a-c790-4109-a77a-0263e2b07f0d.png)

## Part 3
  
I learned that coding bugs can often be caused by small syntax errors or incorrect logic and it is important to carefully review and test code before deployment. Also, Github is a useful tool for collaborating with others on code projects and tracking changes through version control. In addition, I also learned the difference between bugs and symptoms. 
  
 Here are some github commands I learned:
  
`git clone [repository url]: downloads a repository from a remote source to local machine.`

`git init: initializes an empty Git repository in the current directory.`

`git add [file name]: stages a file for commit.`

`git commit -m "[commit message]": creates a commit with a message.`

`git push: pushes local commits to the remote repository.`

`git pull: fetches and merges the latest changes from a rem`
