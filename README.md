//Day 1
* What is java?
	- java is a programming language that is used to give instructions to a computer to perform any task.

* Real life example
	- if you are cook then java is your recipe.
* Features of java
	1)Platform independent
		- java program can run on any operating system.
		- because it runs on JVM and not directly on operating system.

* What happens when we write a java program ?
	step 1- Write a java program ProgramName.java
	step 2 - compile the java program using javac ProgramName.java
		- it will create the java class file
		- java class file is the bytecode
			- machine code
	step 3 - Run the program by giving command java ProgramName
			- JVM  will read the class file and shows the output.

* Things to keep in mind while writing a java program.

1) Always save the java file in folder as All files
2) We compile the java file by giving the command "javac FileName.java"
	- java class file is generated
3) to run the java program you will have to give command "java FileName"
	- your program will run and gives you the output.
4) '//' is used to give comment in java program file 
	-comments are the non executable lines of code
	- comments are written to explain others what we have written in the code.

* What is JDK?
	- JDK is Java Development Kit
		- A software package used run  a java program.
		- Its a toolkit to develop java program.

* Why do we need  JDK?
	- It contains all the tools required to run a java program.
		- A compiler to convert high level language to low level
		- Some helping tool for debugging , packaging, etc.
		- Runtime environment to run java program

* What does JDK contains?
	1) java compiler(javac)
		- to convert .java file to .class 
			-converting high level code to low level code
	2) JRE java runtime environment
		- to run a program
	3) Development tools	
		-Debugger, archiver, etc.
Without JDK we cannot run java program.

* Interview Question
	Q: What is JDK and why is it needed?
		-JDK stands for Java Development Kit 
		- It is a software package that provides all the tools needed to develop 		Java Programs.
		- Without JDK we cannot write and compile java code.
		- For example its like a carpenters toolbox without tools furniture cannot 		be build same like that without JDK we cannot build java program.
* Key point:
	- JDK = JRE + Tools + Compiler

* What is JRE?
	-JRE Java Runtime Environment
		-its a package needed( allows you) to run a java program.
	-For example its a Kitchen where recipe is cooked and served.
* Why do we need JRE?
	- Even we have written and compiled a java program we need an environment to run  	that java program.
	-JRE includes
		1) JVM java virtual machine
			- runs java program
		2) Libraries
			- pre build helpers codes that java programs use.
	- Without JRE computer will not understand how to run java program
* Interview question
	Q: What is JRE?
		- JRE stands for Java Runtime Environment
		- It is used to run java program.
		- It includes JVM  and libraries needed to execute the java program.
		- For example its a kitchen where recipe is cooked and served.
* What is JVM?
	- JVM is java Virtual Machine
		- it is the part of JRE  that actually executes the java program.
		- It understands the bytecode from .class file runs it on computer.

* Why is JVM needed?
	- when we compile the java program it becomes bytecode.
	- JVM reads that bytecode
	- convert it into machine code that computer understands.
	- Execute it
	- java is platform independent because of JVM
		-same bytecode can be run on any operating system

* Uses of JVM
	- converts bytecode to machine code
	- executes the program line by line
	- provides features like garbage collection.

* Interview question
	Q: What is JVM and why is java platform independent?
		-JVM stands for Java Virtual Machine
		- It runs bytecode and converts it into machine code for specific operating 		system.
		- Java is platform independent because the same bytecode can run on any operating system that has JVM.
	Q: What is the difference between JDK, JRE, and JVM?
		- JDK is java development kit
			-it provides tools and compiler to develop java program
		- JRE is java runtime environment 
			- it provides everything needed to run java program.
		- JVM is java virtual machine
			-it is inside the JRE and actually runs the bytecode




	
