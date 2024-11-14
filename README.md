# COMP0246: Modelling and Motion Planning

This repo will be used in order for us to compare our code for each lab. 

The main branch will be used for latest files uploaded by the professor (I will add them to main manually since the professor doesn't have a github repo)

**I assume we can use any conda environment (you can use comp0241) for now or you can create a new conda environment and do ```pip install -r requirements.txt``` that I'm going to add to the main branch as well**

You can then either download the file direclty from moodle or use the following steps to download from here.

Don't forget to push your code to your branch when you are done editing!!

Steps for github setup:

1. Choose any directory on your laptop and clone the repository:  
 ```git clone https://github.com/joefarah850/comp0246```

2. Go into the cloned folder:  
```cd comp0246```

3. Add your branch:  
```git checkout -b <branch_name>```

Now you can work on your branch. And after making the changes do  

4. Add the changes  
```git add .```

5. Commit  
```git commit -m “<message>”```

6. Push to remote  
```git push origin <branch_name>```

--------------------------------------

After I update the main branch of our repo, you guys can add the new files locally or just download them from *Moodle*

1. Check what the different folders and files are between your local and the remote (obviously the files you modified will show up but just look at the new files)  
```git diff --name-only <branch_name> main```

2. Get the added files without modifying the changes that you already made to previous files  
```git checkout main -- <file_name>```

For the <file name> just copy what you see when you do the previous step.

3. Add the changes  
```git add .```

4. Commit  
```git commit -m “<message>” ```

5. Push to remote  
```git push origin <branch_name>```
