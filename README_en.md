__English__ ||| [简体中文](./README.md)
# Baymax Patch Tools​
*Hijack patch creation tool, by simulating the debugger's abnormal interrupt function in the hijack patch, supports modifying the program execution flow by modifying the register, memory and other data after the program triggers an interrupt.
# Tool Description：
Baymax Patch Tools releases a hijacked DLL for the target process to load the functional module PYG.DLL, realizing dynamic patching of the target process.
Baymax not only supports dynamically modifying instructions and data of the target module, but also simulates the OD break function, which can modify the corresponding registers, flag registers and memory data of the registers pointing to memory after breaking the target module, so as to achieve cracking it without modifying the target file.
# Function Introduction：

* Supports hijacking crack without modifying the file itself
* Support for patching processes with dynamic base addresses (ASLR)
* Support patching multiple DLL modules of the target process
* Support patching different EXEs with the same patch
* Support patching the memory data of a process at a specified address
* Support patching processes with feature code matching
* Support setting API HOOK decoding for shelled programs before patching data
* Support patching data after setting hardware breakpoints to interrupt the process
* Support setting abnormal breakpoints to modify the memory pointed to by registers or registers after interrupting the process
* Support setting conditional breakpoints for processes to determine whether to execute Patch based on the number of interrupts, register or memory values
* Support to set different conditional breakpoints for the same address to perform Patch for the interrupts that meet the conditions
* Support extracting global variables from instructions for storage and modification
* Support storing data and using stored data during process execution
* Support patching the memory pointed to by the memory marker after interrupt
* Support basic operation on data after interrupt
* Support for reading patch data from ini files
* Support for creating memory registers
* Support for creating debug patches to troubleshoot patch problems by yourself

Unpack password：www.chinapyg.com

## Screenshots

<img width="531" height="508" src="https://github.com/sicaril/Baymax-Patch-toOls/blob/main/pic/11.png"/>
<img width="537" height="673" src="https://github.com/sicaril/Baymax-Patch-toOls/blob/main/pic/12.png"/>
<img width="537" height="583" src="https://github.com/sicaril/Baymax-Patch-toOls/blob/main/pic/13.png"/>
