# C Preprocessing
## Hi everyone 
### I am here to demonstrate how the preprocessed (.i) file is modified before and after including the header file in the program.
### When we execute the .c file, .i file will be created. This is the first step in the compilation. This stage was done by the Preprocessor, not directly by the Compiler.
### This .i file is the preprocessed file. This file is the primary cause of removing comments, adding the header file if any are included in the program, and expanding all defined macros in this phase.
# Locating the Preprocessed file in the internal memory
### Observing the changes in the .i file can be done in the _'Turbo C++'_ software. Because Turbo C++ contains the _MS-DOS (Microsoft Disk Operating System)_ box, this DOS box will be useful to visualize the pre-processed file.
# Let us know the step-by-step process
## Step-1: 
### Open the Tubro C++ Software and write a code (Don't include any Header File in the Code).
### Save the code.
### Note: If you don't have the Turbo C++ Software, you can download it from the official website of Turbo C++
### For Windows: https://turbo-c.net/turbo-c-download/#Download_Turbo_C_for_Windows
### For Mac: https://turbo-c.net/turbo-c-download/#Download_Turbo_C_for_Mac
### For Linux: https://turbo-c.net/turbo-c-download/#Download_Turbo_C_for_Linux
### This will provide a zip file for download. After unzipping it, you have to download the _.msi (Microsoft Installer)_ file.
![Image](https://github.com/user-attachments/assets/5ae9ce78-f7b2-4fec-8c90-afd2c2f1d724)
## Step-2:
### Launch Turbo C++ software. The interface of the Turbo C++ software looks like.
![Image](https://github.com/user-attachments/assets/e34466ab-9979-4b73-a349-83e758b2d58f)
### To write code in this editor, click on File -> New. This will open a new file for writing code. As shown in the figure above.
## Step-3:
### Write a code in Turbo C++ without including the Header files in the code.
![Image](https://github.com/user-attachments/assets/4d355617-07c5-4efa-85aa-43115c93743d)
### After writing the code, save it. To save the file, click on File -> Save or click on _F2_
### The file must be saved with '.C' extension.sa
## Step-4:
### The saved C are stored in _C:\TURBOC3\BIN_ path.
### Open the MS-DOS box emulator. In the DOS box, the default virtual drive is 'Z'.
### Mount the local C drive by using the command _mount c: c:\turboc3_. But still will be in the Z drive to change it into the C drive _C:_ and hit enter. 
### Know the emulator is in the _C:\TURBOC3_ folder.
### Change directory to BIN in the turboc3 folder by using the command _CD BIN_
### Then the interface will be like
![Image](https://github.com/user-attachments/assets/67f815a5-cf0c-4339-bfdc-753e7898d18b)
## Step-4:
### Know, preprocess the C file that you saved by using the command _cpp_.
### Type _cpp <file_name>.C_ which creates .I file, here .i does mean the preprocessed file.
![Image](https://github.com/user-attachments/assets/597f1b5f-6b45-4e6a-9267-5f45d520f63c)
### To see the preprocessed file,  _type <file_name>.i_. This command will display the '.i' file in the emulator itself.
![Image](https://github.com/user-attachments/assets/d5e93919-a57f-4d74-ac87-46677222aa2b)
### If you want to open the .i file in editor mode navigate to _C:\TURBOC3\BIN_ and search for _<file_name>.i_ file.
![Image](https://github.com/user-attachments/assets/6345d442-359d-4f5b-880e-457499d5a782)
## Step-5:
### Modify the Program by including header files or macros.
![Image](https://github.com/user-attachments/assets/5bb9d5f4-cce5-4b5b-9732-a2a8ccf2919a)
### Once again, save the program and apply the _cpp <file_name>.C_ in MS-DOS box. The output will be
![Image](https://github.com/user-attachments/assets/bee6639f-e175-42f0-a819-b71aa59ebf47)
### You can observe a difference in the memory after including(Available memory is 4154208) and before including(Available memory is 4173368) the header files. 
![Image](https://github.com/user-attachments/assets/bee6639f-e175-42f0-a819-b71aa59ebf47)
### You can notice that here the header files are included, and Macros are also expanded.
![Image](https://github.com/user-attachments/assets/e3f50e09-0dc4-4552-a7cd-a3dab2f5cc2c)
