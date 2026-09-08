# PCCOM
PC Communication (PCCOM) is a Terminate-and-Stay-Resident (TSR) program for serial communication between two PCs. When linked together through serial ports, one PC serve as a Master while the other as Slave. The Master PC has control and can copy files to/from the other PC, perform file viewing, deletion, make/remove directory. The program has similar look to Norton Commander. PCCOM designed to work under MS-DOS but it can also be executed under Windows 10 and 11 through DOSBox. However, the connection feature between two PCs is only tested under MS-DOS environment.           

This tool is part of a final year project:  
<pre>
Project Title: 
     Interrupt Driven Resident Program for Communication     
University/College/Department: 
     University of Mosul, College of Science, Department of Computer Science  
Project Supervisors:
     Ayad Hussain Abdulqader,  ayad_alezzi [at] uomosul.edu.iq
     Ayad Tareq Imam, alzobaydi_ayad [at] iu.edu.jo             
Programmers: 
     TSR/Menus/Integration  : Hasan S.M. Al-Khaffaf, hasan.alkhaffaf [at] uod.ac
     Communication          : Midhar Zaid Tawfeq AlDabbagh
     Logistics/Communication: Anas Mohammad Ghazal, anas70 [at] gmail.com        
Programming Languages: 
     Pascal (Turbo Pascal)
     8086 Assembly Language (Turbo Assembler)            
Year: 
     1996/1997  
</pre>            
          
# Screenshot
PCCOM after execution from command line:
<img width="642" height="427" alt="image" src="https://github.com/user-attachments/assets/38f653b4-6c92-436a-b67c-c08e25b9c0fd" />
     
     

PCCOM after activation by pressing Alt + Ctrl + LShift
<img width="642" height="427" alt="image" src="https://github.com/user-attachments/assets/fda922cb-9192-4845-9421-3e92d787dd30" />     
The user can use Left/Right keys to switch between left and right panels.     

PCCOM Menus:     
The Left menu     
<img width="642" height="427" alt="image" src="https://github.com/user-attachments/assets/f14e3f46-f88a-4ead-8b0b-10eba7fa85f5" />     
This menu shows the options for the left file panel where user can choose file ordering type, disk drive, link to another PC that is connected using serial port, Refresh the directory by reading it again, and change drive.     

The Parameters menu     
<img width="642" height="427" alt="image" src="https://github.com/user-attachments/assets/117a48ea-d664-40c3-b4b0-f7daad94248a" />     
The Parameters menu shows the parameter for the communication line such as: transfer speed (115200, 57500, .., 3840) bits/s, data size (7 or 8), parity (Odd, Even, None), stop bits (1 or 2), serial port (COM1, .., COM4), communication privilege (read only or read/write) permission.     

The Files menu     
<img width="642" height="427" alt="image" src="https://github.com/user-attachments/assets/7e17e409-7055-452d-b254-a33e4e4c0cea" />     
The Files menu shows the option for files. The user can select file(s) using Insert key, choose many files using + key i.e. wild card selection, deselect multiple files using - key, invert selection using * key, view file using F3, copy file(s)/folder(s) to the other panel using F5, rename a file using F6, make a directory/folder using F7, delete file(s)/folder(s) using F8, navigating to the root directory using / key, exiting the program to the DOS prompt using F10, or unloading the TSR program from memory using "Unload program".     

     
The Options menu     
<img width="642" height="427" alt="image" src="https://github.com/user-attachments/assets/8ee1f36e-8ee1-4eec-ba5a-9eac3eecf286" />          
This menu provides the option of quitting without confirmation, clock On/Off (not implemented), Terminal, Refresh display to repaint the whole screen, and Link refreshment to refresh the link with the other PC. 


The Right menu     
<img width="642" height="427" alt="image" src="https://github.com/user-attachments/assets/5715ebc1-a399-4b43-92e0-7dda0c17d882" />     
Similar to Left menu but for the right panel, see above.

