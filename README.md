Communication contract:


A. To REQUEST the data, your program must modify pipeline.txt by writing to the file the word "run". 
    For example: 
        `f = open("pipeline.txt", "w")
        f.write("run")
        f.close()`
B. To RECEIVE the data, your program must read pipeline.txt after the user has finished doing their input. If pipeline.txt does not equal "run" then you should read the input.
    For example: 
        `f = open("pipeline.txt", "r")
        sleep(5)
        searchOption = f.read()
        if searchOption != "run":
            print(searchOption)`


C. UML Diagram:

![alt text]([http://url/to/img.png](https://ibb.co/S6MVCCk)https://ibb.co/S6MVCCk)
