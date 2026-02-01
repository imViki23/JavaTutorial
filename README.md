# Java

- **History**: High-level, object-oriented programming language developed by James Gosling and his team at Sun Microsystems in 1995. Originally named Oak, designed for portability across platforms. First public release in 1996. Sun Microsystems acquired by Oracle in 2010, which continues maintenance.

## 1. JDK vs JRE vs JVM

- **Development Workflow**: Java source files (.java) are compiled by the JDK's compiler into bytecode class files (.class). These can be packaged into JAR (Java Archive) files for distribution. The JRE, containing the JVM, executes the JAR files, allowing the program to run on any compatible platform.

| Component              | Description |
|------------------------|-------------|
| **JVM (Java Virtual Machine)** | Think of it as the "engine" that runs your Java programs. It takes the compiled Java code (bytecode) and executes it on your computer. Without JVM, Java programs can't run. It's like the player that makes the music from a CD. |
| **JRE (Java Runtime Environment)** | This is like a "package" that includes the JVM plus some extra libraries and files needed to run Java applications. If you just want to play (run) Java games or apps, you need JRE. It's everything you need to use Java programs, but not to create them. |
| **JDK (Java Development Kit)** | This is the full "toolbox" for creating Java programs. It includes the JRE (so you can run programs) plus tools like a compiler (to turn your code into bytecode), debugger (to fix bugs), and other helpers. If you're a programmer writing Java code, you need JDK. It's like having the studio equipment to record music, not just play it. |

## 2. Java vs C++: Technical Differences

- **Compilation and Execution**: Java source code is compiled to platform-independent bytecode, which runs on the JVM. C++ is compiled directly to native machine code for the target platform, requiring recompilation for different systems.

## 3. Understanding Bits and Memory Representation

A memory cell can hold single bit either 0 or 1.

### Single bit

<span>
    <table><td style="border: 1px solid gray;">0</td></table>
    <span>represents 0</span>
</span>
<table style="border: none; border-collapse: collapse;">
    <tr>
        <td style="border: none;"><table style="border: none;"><tr><td style="border: 1px solid gray;">1</td></tr></table></td>
        <td style="border: none;">represents 1</td>
    </tr>
</table>