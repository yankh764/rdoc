# Rdoc - A command-line tool for launching documents
This bash script is dedicated for all the Linux readers whom spend all their time working on the terminal;    
therefore they launch everything from there.   
If you are the kind of person I described above, I believe that this tool would benefit you.  
This script purposes are to help you launch documents using your favorite PDF Viewer, which will    
save you a lot of time if you have lots of documents like me.

## Requirements and Dependencies
1. Bash 
2. GNU Core Utilities
3. grep
4. A PDF Viewer
5. A directory that contains all your documents.    

Note: The first 3 dependencies should be already installed by default on most linux distros.

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
    
Note: You can copy the program to wherever you wish but it is recomendded to keep it in your **PATH**.   

## Usage
* If you did the previous installation steps you can run the program from terminal simply by typing:   
    
    ``` Bash
    user # rdoc
    ```     

* It'll display a help message, read it and then you are ready to go.

## Issues 
* It's a minor issue but I think it's good that you'll be aware of it. Because of the fact that I added   
`disown` to the launching documents command and I couldn't find a way to check the return status of this    
command, if some error occures while launching the document it'll display the regular message:     
"Opening: /path/to/the/document".      
But it's actually failing and it won't launch the document.

## Contributing
Pull requests are welcomed and appreciated.
