  **Browser**

  **Call stack/Execution stack**.
  
  - Whenever javascript prog starts, **Global Execution Context (GEC)** is added in call stack.
  - Then it will fetch next line of code and put into Call stack. Once that is execurted it is deleted and removed from call stack. and next line is put into call stack.
  - Please note that Call stack with execurtes directly and **not wait** for certain time so it is Synchronous.
  - If you want to perform async activity, async function put into call stack and moved to Web APis.

  **Web Api** 
  
  - Web API wait async function till specific time and then moved this into **callback queue/task queue/ message queue**
  - It inlcudes **setTimeout, DOM APIs, fetch and cosnsole**. 

  **Callback Queue**
  
  - Whenever Web API waiting time over, it push the function into Callback queue.
  - Callback if there because to prevent unnecessary handged OR execution blockage due to multple click by user unnecessarily.
    
  
   **Priority queue** 
   
   - We also have Priority queue whose priority is bit high than Callback queue.Means it executes prior to callback queue
   - It includes Promises and Mutation observerser
          
   **Event loop**
   - It acts as a bridge between Call stack and Callback and priority queue
   - It always take function from Callback and priority queue which is ready to execute and put that into Call stack to execute.      
 

![image](https://github.com/sarthirkjoshi/interview-preparation/assets/46737879/aef06d73-b005-4a69-99a6-c640893c504c)

![image](https://github.com/sarthirkjoshi/interview-preparation/assets/46737879/30febcfa-892e-4394-ad95-78aa81f7a1d1)
