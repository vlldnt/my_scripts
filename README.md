# Here my usefull script during the Holberton School Year

### About bashScript

 **bashScript** permits to create a new script bash in the working directory
   - Execute with `bash bashScript` or `./bashScript`
   - A `read -p` command is done to collect input to name your file.
   - Then the text `#!/bin/bash` with a new line is written in the new named file.
   - And `chmod u+x` is done to change the permissions.
   - Now edit your script.



### About cScript

 **cScript** create a new `.c` file the working directory
   - Execute with `bash bashScript` or `./bashScript`
   - A `read -p` command is done to collect inputs to name you file *(don't forgt to put the .c at the end)*
   - Already in your file.c
        - header : `"main.h"`
        - 3 lines for the comments `/** * * * */ `
        - a `return(0);` is added with `{ and }`
   - Now edit your file with vi.   


### About pushScript
 **pushScript** will ask you to input the name and the git add, the commit you want and will git push after.
   - Execute the script with `./pushScript`
   - Write the name of the file you want to `git add` first and press enter
   - Then same for the `git -m commit` *you don't need to push the `" "`* 
   - And press enter to `git push`
   - Congrats you've done the push to you Github 
