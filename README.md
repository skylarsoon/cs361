Communication contract:


A. To REQUEST the data, your program must modify pipeline.txt by writing to the file the word "run". 
    For example: 
        `f = open("pipeline.txt", "w")` <br/>
        `f.write("run")` <br/>
        `f.close()` <br/>
        <br/>
B. To RECEIVE the data, your program must read pipeline.txt after the user has finished doing their input. If pipeline.txt does not equal "run" then you should read the input.
    For example: 
        `f = open("pipeline.txt", "r")` <br/>
        `sleep(5)` <br/>
        `searchOption = f.read()` <br/>
        `if searchOption != "run":` <br/>
            `print(searchOption)` <br/>


C. UML Diagram:

![Link to diagram](https://ibb.co/S6MVCCk)
