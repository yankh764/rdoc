# Rdoc - A command-line tool for launching documents
This bash script is dedicated for all the Linux readers whom spend all their time working on the Terminal;    
therefore they launch everything from there.   
If you are the kind of person I described above, I believe that this tool can help you and save you a lot of time.  
This script purposes are to help you launch documents using your favorite PDF Viewer, which will    
save you a lot of time if you have lots of documents like me.

## Requirements and Dependencies
1. Bash 
2. GNU Core Utilities
3. grep
4. sed
5. A PDF Viewer
6. A directory that contains all your documents.    

Note: The first 4 dependencies should be already installed by default on most linux distros.

## Installation 
* Make sure all the previous dependencies are installed and all the requirements are implemented.
* Clone this repo by typing:   
    
    ```Bash
    user # git clone https://github.com/yankh764/rdoc.git
    ```    

* Move to the cloned directory and type:    
    
    ```Bash
    root # cp rdoc /usr/local/bin/rdoc    
    root # chmod 755 /usr/local/bin/rdoc
    ```
    
Note: You can copy the program to wherever you wish but it is recomendded to keep it in your `$PATH`.   

## Usage
* If you did the previous installation steps you can run the program from terminal simply by typing:   
    
    ``` Bash
    user # rdoc
    ```     

* It'll display a help message, read it and then you are ready to go.

## Contributing
Pull requests are welcomed and appreciated.