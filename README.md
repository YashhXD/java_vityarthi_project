## Java Vityarthi project submission by Yash Mehta 24BCE10638

## About Project 

Vityarthi's assigned project CCRM Campus Course and Records Manager is a java application which manages student , their courses enrolled , transcription and grades of them. This program supports imports and exports from CSV format,GPA information,data saving which is fully menu driven and easily understandable.

<img width="488" height="394" alt="menu 1" src="https://github.com/user-attachments/assets/1006ec0e-ac8d-4ea3-ac60-3270e7f1427e" />

---

### Pre-requisites
* Java Development Kit (JDK) version 11 or higher.
* Eclipse IDE for Java Developers.

## Procedure to Run
1. firstly fork/clone the repository
2. Compulation using `javac -d bin src/**/*.java`
3. Execute the code with `java -cp bin edu.ccrm.Main`


### Executing from Eclipse 
1.  Import the project using **File -> Import... -> General -> Projects from Folder or Archive**.
2.  Navigate to src/main/java/edu/ccrm/cli/CrmApplication.java.
3.  Right-click on CrmApplication.java and select **Run As -> Java Application**.

<img width="242" height="387" alt="file_structure" src="https://github.com/user-attachments/assets/d91d7c34-f362-41d2-9ad0-ca8147817ae4" />

---

### Evolution of Java

- 1995: Java 1.0 released by Sun Microsystems
- 1997: Java 1.1 with JDBC, RMI, and reflection
- 2000: Java 1.3 with HotSpot JVM
- 2004: Java 5 with generics, annotations, autoboxing
- 2014: Java 8 with lambdas, streams, new date/time API
- 2017: Java 9 with module system
- 2018: Java 11 as LTS version
- 2021: Java 17 as current LTS version
- 2023: Java 21 with virtual threads

### Java ME vs. SE vs. EE

| Feature    | Java ME (Micro Edition)     | Java SE (Standard Edition) | Java EE (Enterprise Edition)       |
| ---------- | --------------------------- | -------------------------- | ---------------------------------- |
| *Target*   | Embedded Devices, IoT       | Desktop & Server Apps      | Large-scale, Web Applications      |
| *Core API* | Subset of Java SE           | Core Java Language         | Superset of Java SE                |
| *Example   | Old Mobile Games            | **This CCRM Project*       | Online Banking Systems             |

### Java Architecture: JDK, JRE, JVM
* *JVM (Java Virtual Machine):* An abstract machine that provides the runtime environment to execute Java bytecode. This is what makes Java "write once, run anywhere."
* *JRE (Java Runtime Environment):* The software package needed to run a Java application. It includes the JVM and core libraries.
* *JDK (Java Development Kit):* The full kit for building Java applications. It includes everything in the JRE plus development tools like the compiler (javac).

---

## Setup and Installation

### Windows Java Install Steps
1.  Download a JDK (e.g., version 17 LTS) from a provider like [Adoptium](https://adoptium.net/).
2.  Run the installer and follow the on-screen instructions.
3.  Verify the installation by opening a Command Prompt and running java -version.

<img width="802" height="274" alt="image" src="https://github.com/user-attachments/assets/42440039-91b4-4e6c-a845-c5c0868161c8" />



### Eclipse Setup Steps
1.  Import the project using the File -> Import... wizard.
2.  The project structure will appear in the "Package Explorer".
3.  To run, right-click CrmApplication.java and select Run As -> Java Application.

<img width="639" height="648" alt="eclipse_installation" src="https://github.com/user-attachments/assets/a92b83b1-232e-4dd0-a9b4-cd2cbc829162" />

---

## Enabling Assertions
To enable assertions for internal checks:
1.  Go to **Run -> Run Configurations...**.
2.  Select your application configuration.
3.  Go to the **Arguments** tab.
4.  In the **VM arguments** box, add the flag: **-ea**.

<img width="938" height="682" alt="config" src="https://github.com/user-attachments/assets/87621839-a000-4a55-b653-754f5f27f335" />

---
## Demo usage
<img width="485" height="855" alt="adding_student" src="https://github.com/user-attachments/assets/f77f0d7a-d693-404d-9fe6-79e5f6c517f4" />
<img width="491" height="873" alt="student_list" src="https://github.com/user-attachments/assets/ccb143fa-4283-4afe-b611-cb3a6fb8ba14" />
<img width="1154" height="916" alt="updating_student" src="https://github.com/user-attachments/assets/5b6f42f8-05f8-4504-8b1e-63121cacd3c9" />
<img width="699" height="891" alt="viewing_profile" src="https://github.com/user-attachments/assets/2ae38839-6964-4ba6-af6d-7add862bf160" />


## Technology Mapping Table
 ___________________________________________________________________________________
| Syllabus Topic             | File / Location of Demonstration                      |
| ---------------------------|-------------------------------------------------------|
| *OOP (All Pillars)*        | Person (abstract), Student/Instructor (inheritance)   |
| *Design Pattern: Singleton*| edu.ccrm.config.AppConfig.java                        |
| *Design Pattern: Builder*  | edu.ccrm.domain.Course.java                           |
| *Custom Interface*         | edu.ccrm.interfaces.Searchable.java                   |
| *Custom Exceptions*        | edu.ccrm.exceptions package                           |
| *NIO.2 & File I/O*         | ImportExportService.java, BackupService.java          |
| *Java Stream API*          | TranscriptService.java (GPA Calc), CourseService.java |
| *Recursion*                | edu.ccrm.util.DirectoryUtils.java                     |
| *Anonymous Inner Class*    | CrmApplication.java (in manageStudents method)        |
|____________________________|_______________________________________________________|

