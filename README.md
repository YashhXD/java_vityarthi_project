## Java Vityarthi project submission by Yash Mehta 24BCE10638

## About Project 

Vityarthi's assigned project CCRM Campus Course and Records Manager is a java application which manages student , their courses enrolled , transcription and grades of them. This program supports imports and exports from CSV format,GPA information,data saving which is fully menu driven and easily understandable.

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

![Image 2025-09-24 at 18 51 34_6db4996d](https://github.com/user-attachments/assets/245e5322-0a86-4916-900d-c60b921c59f6)


### Eclipse Setup Steps
1.  Import the project using the File -> Import... wizard.
2.  The project structure will appear in the "Package Explorer".
3.  To run, right-click CrmApplication.java and select Run As -> Java Application.

![Image 2025-09-24 at 23 24 01_9d39b207](https://github.com/user-attachments/assets/1a68b8d7-2525-47aa-90b6-1a00b36ca695)
![Image 2025-09-24 at 23 24 18_d4cb1ee0](https://github.com/user-attachments/assets/951db32a-6e56-40dd-8d2e-c348942bebde)
![Image 2025-09-24 at 23 24 36_0e201b20](https://github.com/user-attachments/assets/dd528de6-e41b-461e-877a-7c8297e55993)
![Image 2025-09-24 at 23 24 57_3020e5d5](https://github.com/user-attachments/assets/14c4f0db-99f5-42a6-9505-18aa06bd31c9)

---

## Enabling Assertions
To enable assertions for internal checks:
1.  Go to **Run -> Run Configurations...**.
2.  Select your application configuration.
3.  Go to the **Arguments** tab.
4.  In the **VM arguments** box, add the flag: **-ea**.


---

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

![Image 2025-09-24 at 23 23 48_db59b000](https://github.com/user-attachments/assets/92d24874-1adc-4d14-be0b-c03f52a5f60d)
![Image 2025-09-24 at 20 06 32_52c7fd52](https://github.com/user-attachments/assets/b5179e61-0368-4c4d-b1dc-a03760508a9f)
![Image 2025-09-24 at 20 06 14_8a5bd7a2](https://github.com/user-attachments/assets/efc6416d-7d85-487f-ba5f-9f601220d326)