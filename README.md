# CMSC389J: Introduction to Reverse Engineering
<p style="text-align: center;">
Chase Kanipe, Vinnie Caporola
</p>

## Prerequisites and Description
 - **Prerequisites:** C- or better in CMSC250 and CMSC216
 - **Credits:** 1
 - **Faculty Advisor:** Jonathan Katz
 - **Course Instructors:** Chase Kanipe and Vinnie Caporola

The focus of Introduction to Reverse Engineering is for students to gain experience in a high
demand practice of cybersecurity though weekly reversing assignments. In this course students will
be challenged to think outside the box in order to solve reversing challenges. Assignments will be
challenges focused in the analysis of Linux binaries including various malware. Various tools for
reversing will be demonstrated in class such as Binaryninja/IDA, gdb, strace, objdump, readelf,
pev, etc. The goal of this class is to have students go from a beginner to an intermediate level
reverse engineer. Students will be expected to have some assembly experience (calling conventions,
stack/heap, registers), but we will refresh and introduce students to the x86 assembly language.

### Class Details

 - **Day/Time:** Friday 3:00-3:50
 - **Location:** CSI 3118

### Textbooks and Required materials

No textbooks required. Readings will be recommended as the semester goes on. A laptop with VMware or VirtualBox. Class VM will be provided.

### Topics Covered

 - Static binary analysis
 - Dynamic binary analysis
 - PE32/+ vs ELF32/64
 - API Hooking  
 - Legacy code analysis
 - Malware
 - Fuzzing/Symbolic Execution

## Software Used

| Virtualization Software  | Static Analysis Tools  |
|---|---|
| VMWare  | Binary Ninja  |
| **Symbolic Execution**  | **Dynamic Analysis Tools**  |
| Valgrind  | GDB/EDB  |

## Homeworks

Homeworks will be 1-2 page write ups on the analysis and findings of the provided files. Some will be question driven, while others are open ended. The point to the write ups is to explain and document the reversing process, not to have everyone get the same answer. This is to benefit those who attempt the
homeworks, the main focus of these writing assignments is to gauge the students’ thinking and methodology. Correct answers will factor into this but effort and methodology will hold the most weight.


| Assignments 1-5 | Assignments 6-11 |
|---|---|
| HW #0: What's your experience? Ethics  | HW #6: Write and LD-PRELOAD |
| HW #1: Bufferoverflow Attack  | HW #7: Crypto - Break the scheme |
| HW #2: Static Analysis I | HW #8: AP RE - Malware |
| HW #3: Static Analysis II  | HW #9: Update the old database |
| HW #4: Dynamic Analysis I  | HW #10: Swap out legacy library |
| HW #5: Dynamic Analysis II  | HW #11: Fuzzing/Symbolic Execution |



## Projects

Groups of 2-3 will have a choice of handmade challenges each falling
under a specific topic in the course OR they may choose something to reverse engineer and do something interesting! The projects will presented at the end
of the semester in front the class to share findings and interesting things. The handmade challenges will be more difficult than the weekly assignments, to reflect the time and group work involved.


## Quizzes

Three 10-15 minute quizzes, spread out on important over arching topics that we want to emphasize. Quizzes will be higher level, not as technical as what may be found as homework questions. Quizzes will be themed: Static Analysis, Dynamic Analysis, and Forensics.

## Grading

Homeworks and quizzes will be scanned and graded using Gradescope. Students will have 2 weeks to request a regrade from the time of receiving their grade. Grades will be posted on the CS Grade Server. You are responsible for all materials discussed in lecture and posted on the class repository, including announcements, deadlines, policies, etc.

| Quizzes  | Homeworks |
|---|---|
| 27%  | 73%  |

## Schedule

| Week # | Lecture Topic | Assignment |
|---|---|---|
| 0  | What is RE? Ethics, C review, Assembly, calling conventions  |   |
| 1  | Advanced Assembly: Linking, Bytecode, Instruction format  | HW #0  |
| 2  | Static Analysis I: Linux file headers, file types, dynamic libraries | HW #1 |
| 3  | Static Analysis II: Dissasembly, Libc Basic block analysis, patching  | HW #2 |
| 4  | Quiz #1, Dynamic Analysis I gdb/edb, packers  | HW #3 |
| 5  | Dynamic Analysis II: Obfuscation, self modifying code  | HW #4 |
| 6  | API hooking, LD_PRELOAD  | HW #5 (due)  |
| 7  | Quiz #2, Applied RE: Breaking Crypto  | HW #6 |
| 8  | Applied RE: Malware triage  | HW #7 |
| 9  | Applied RE: Legacy code base I | HW #8 |
| 10  | Applied RE: Legacy code base II  | HW #9 |
| 11  | Quiz #3: Symbolic Execution/Fuzzing, Side channel  | HW #10 |
| 12  | Malware and Detection: Trojans, Protocols, Snort  | HW #11 |
| 13  | Large Binaries I: Pwn Island 3  | HW #12 |
| 14  | Large Binaries II: Pwn Island 3  | HW #13 |
| 15  | Special Topics: TBD  | HW #14 |


<div style="page-break-after: always;"></div>
## Communication
We will interact with students outside of class in primarily two ways: in-person during office hours and slack. Email should only be used for emergencies and not class related questions (e.g., homework).

### Faculty Advisor

 - Jonathan Katz - **jkatz AT cs.umd.edu**

### Course factors

 - Chase Kanipe - **chasekanipe AT gmail** (Office Hours: TBD)
 - Vinnie Caporola - **vcapra1 AT umd.edu** (Office Hours: TBD)

## Excused Absense and Academic Accomidations
See the section titled “Attendance, Absences, or Missed Assignments” available at Course Related Policies.


## Disability Support Accommodations

See the section titled “Accessibility” available at Course Related Policies.

## Academic Integrity

Note that academic dishonesty includes not only cheating, fabrication, and plagiarism, but also includes helping other students commit acts of academic dishonesty by allowing them to obtain copies of your work. In short, all submitted work must be your own. Cases of academic dishonesty will be pursued to the fullest extent possible as stipulated by the Office of Student Conduct.

It is very important for you to be aware of the consequences of cheating, fabrication, facilitation, and plagiarism. For more information on the Code of Academic Integrity or the Student Honor Council, please visit http://www.shc.umd.edu.


## Course Evaluations

If you have a suggestion for improving this class, don’t hesitate to tell the instructor or TAs during the semester. At the end of the semester, please don’t forget to provide your feedback using the campus-wide CourseEvalUM system. Your comments will help make this class better.
