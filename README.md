# Dynamic Variables Check
 
Dynamic identification of variable values when debug running.   
When you debug shellcode, there are many function to be created, and might be some API Waiting to be identified.  
DVA can help you easily finish it.  
  
调试的时候动态检查局部变量的值。  
当你调试shellcode的时候，这里会有许多待创建的函数，或许还会有一些等待识别的系统API。  
DVA可以帮助你轻松的完成这些任务。  

## Create function for call insn
Hotkey: Shift-F  
Create func before:  
![](./picture/create_func_before.png)  

Put cursors on the target function, then press Shift-F:  
![](./picture/create_func_after.png)  

## Check local variables
DVA can identify all dll handle and system api(you can add the key word to the global variable api_key_word).

There has two action range, current block and whole function.  
* current block hotkey(recommend): Shift-B  
* whole function hotkey: Shift-A  
  
Ip stop on target block, then press Shift-B:  
![](./picture/Identifying_variables.png)

## Support
My ida pro is 8.2, the plugin suport 7.4 between 9.0 i guess.  
If you have any question, please open an issue on GitHub.
