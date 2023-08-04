# [Signals-and-Pipes-under-UnixLinux](Signals-and-Pipes-under-UnixLinux.pdf)

## Objective
We would like to create a multi-processing application based on the signals and pipes/fifos facilities under Linux. The idea is to have a parent process fork 5 children processes. The first 2 processes are partners that belong to team 1 while processes 3 & 4 are partners that belong to team 2. Process 5 is the co-processor that helps its parent doing calculations.

## Description  
- [Project Description](Signals-and-Pipes-under-UnixLinux.pdf)

## Key Features
The project encompasses the following key features:

**1- Pipes:** Shared memory is used as a means of communication and data exchange between different processes. Processes can read from and write to a shared memory segment, enabling efficient and fast communication.

**2- Fifo:**

 ## How 
 - Clone the repository to your local machine.
 - In terminal:  </br>
1- Make sure you have the libfreetype6-dev library installed   </br>
  ```
 sudo apt update
 sudo apt install libfreetype6-dev
 ```
&emsp; &ensp; 2- Then you can run the program using:

 ```
 cd IPC-under-linux-Project2/source_code
 make
 ./parent
 ```
 - Monitor the output and check the generated files (**spy.txt** and **receiver.txt**) for the decoded messages
 
## Configuration
You can customize the following parameters in the source code:

- Number of helper processes
- Number of spy processes
- Thresholds for successful and failed decoding operations

Feel free to modify these parameters in **inputVariables.txt** to suit your specific needs.</br>
(*The maximum vlaue for variables is 40, which is the assumed maximum number of file columns, any greater values will be assumed 40*)

## Languages And Tools:

- <img align="left" alt="Visual Studio Code" width="40px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/visual-studio-code/visual-studio-code.png" /> <img align="left" alt=  "OpenGl" width="60px" src="https://upload.wikimedia.org/wikipedia/commons/e/e9/Opengl-logo.svg" /><img align="left" alt="C" width="50px" src="https://user-images.githubusercontent.com/25181517/192106070-46255bcf-65e6-4c6b-a296-bf8d0d8fb2a7.png" /><img align="left" alt="GitHub" width="50px" src="https://raw.githubusercontent.com/github/explore/78df643247d429f6cc873026c0622819ad797942/topics/github/github.png" /> <img align="left" alt="Linux" width="50px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Tux.svg/800px-Tux.svg.png" /> 

<br/>
