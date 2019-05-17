#+title: CMSC389J: Introduction to Reverse Engineering

The focus of Introduction to Reverse Engineering is for students to gain
experience in a high demand practice of cybersecurity though weekly reversing
assignments. In this course students will be challenged to think outside the
box in order to solve reversing challenges. Assignments will be
challenges focused in the analysis of Linux binaries including various
malware. Various tools for reversing will be demonstrated in class such as
Binaryninja/IDA, gdb, strace, objdump, readelf, pev, etc. The goal of this
class is to have students go from a beginner to an intermediate level reverse
engineer. Students will be expected to have some assembly experience (calling
conventions, stack/heap, registers), but we will refresh and introduce
students to the x86 assembly language.

* Class details

  Day/Time: Friday 12:00pm-12:50pm

  Location: CSI 3118

  See [[./Syllabus.pdf][Syllabus]] for more information

*** Faculty Advisor:
    + Jonathan Katz - *jkatz AT cs.umd.edu*
*** Course facilitators:
    + Christopher Brown - *chris03 AT terpmail.umd.edu*
      - Office Hours: TTh: 12:15pm-1:30pm, F: 11am-12pm & 1pm-2pm

    + Drake Petersen - *drakemp AT terpmail.umd.edu*
      - Office Hours: MWF: 1pm-2pm

* Schedule
  Slides will be available here before each class, found in *Week_X/Lecture*

  |-----------+-----------------------------------------+---------------------------|
  | *Week #*  | *Lecture Topic*                         | *Assignment*              |
  |-----------+-----------------------------------------+---------------------------|
  | 0 (2/1)   | What is RE? Ethics, C review, Assembly  |                           |
  |           | (x86/64),                               |                           |
  |-----------+-----------------------------------------+---------------------------|
  | 1 (2/8)   | Advanced Assembly: Linking, Instruction | HW #0 (due 2/7)           |
  |           | format, Linking, Buffer Overflow        |                           |
  |-----------+-----------------------------------------+---------------------------|
  | 2 (2/15)  | Static Analysis I: Linux file headers,  | HW #1 (due 2/14)          |
  |           | Disassembly, Dynamic libraries, Tools   |                           |
  |-----------+-----------------------------------------+---------------------------|
  | 3 (2/22)  | Static Analysis II: Libc/Syscalls,      | HW #2 (due 2/21)          |
  |           | Static Analysis problems, Patching      |                           |
  |-----------+-----------------------------------------+---------------------------|
  | 4 (3/1)   | Quiz #1, Dynamic Analysis I: gdb/edb,   |                           |
  |           | packers, Dynamic Analysis               | Quiz #0: Static Analysis  |
  |-----------+-----------------------------------------+---------------------------|
  | 5 (3/8)   | Dynamic Analysis II: Obfuscation,       | HW #3 (3/7)               |
  |           | self modifying code                     |                           |
  |-----------+-----------------------------------------+---------------------------|
  | 6 (3/15)  | API hooking, LD-PRELOAD                 | HW #5 (due 3/14)          |
  |           |                                         |                           |
  |-----------+-----------------------------------------+---------------------------|
  | 7 (3/22)  | *Spring Break*                          | *Spring Break*            |
  |-----------+-----------------------------------------+---------------------------|
  | 8 (3/29)  | Symbolic Execution/Fuzzing,             | HW #6 (due 3/28)          |
  |           | side channel                            |                           |
  |-----------+-----------------------------------------+---------------------------|
  | 9 (4/5)   | Quiz 2, Applied RE: Malware triage I    | HW #8 (due)               |
  |           | and analysis                            | Quiz #2: Dynamic Analysis |
  |-----------+-----------------------------------------+---------------------------|
  | 10 (4/12) | Applied RE: Malware triage II           | HW #9 (due)               |
  |           |                                         |                           |
  |-----------+-----------------------------------------+---------------------------|
  | 11 (4/19) | Applied RE: Legacy code base            | HW #10 (due)              |
  |           | reversing                               |                           |
  |-----------+-----------------------------------------+---------------------------|
  | 13 (4/26) | Quiz #3: Detection and Signaturing      | HW #11 (due)              |
  |           |                                         | Quiz #3: Applied RE       |
  |-----------+-----------------------------------------+---------------------------|
  | 14 (5/3)  | Special Topics                          | HW #12 (due)              |
  |           |                                         |                           |
  |-----------+-----------------------------------------+---------------------------|
  | 15 (5/10) | Special Topic: TBD                      | No Homework               |
  |-----------+-----------------------------------------+---------------------------|

* Resources
  Class VM: Kali 2018 (see #Resources in slack), user/pass: re/re

*** Recommended readings
    + [[https://nostarch.com/binaryanalysis][Practical Binary Analysis]] by Dennis Andriesse
    + [[https://ownyourbits.com/2018/05/23/the-real-power-of-linux-executables/][The real power of Linux executables]] by nachoparker
    + [[https://www.amazon.com/Practical-Reverse-Engineering-Reversing-Obfuscation/dp/1118787315][Practical Reverse Engineering]] by Bruce Dang, et. al (Windows)
    + [[https://nostarch.com/malware][Practical Malware Analysis]] by Michael Sikorski and Andrew Honig
    + [[https://github.com/0xTowel/UMDCTF-2017-Challenges][UMDCTF2017]] by CSEC crew
    + [[https://liveoverflow.com/binary_hacking/reverse_engineering.html][Reverse Engineering videos]] by LiveOvervflow

* Homeworks
  Homeworks will be 1-2 page write ups on the analysis and findings of the
  provided files. Some will be question driven, while others are open ended. The
  point to the write ups is to explain and document the reversing process, not
  to have everyone get the same answer. This is to benefit those who attempt the
  homeworks, the main focus of these writing assignments is to gauge the
  students' thinking and methodology. Correct answers will factor into this but
  effort and methodology will hold the most weight. Homeworks will be available
  in the appropriate week directory. (git pull)

  | *HW #0:* What is your RE experience? Ethics | *HW #6:* API Hooking -- write an LD-PRELOAD   |
  | *HW #1:* Bufferoverflow Attack              | *HW #8:* Angr -- Automatic CTF                |
  | *HW #2:* Static -- Analyze recovered data   | *HW #9:* AP RE -- Whats the damage? (malware) |
  | *HW #3:* Static -- Get a valid key          | *HW #10:* AP RE -- TBD                        |
  | *HW #4/7:* No Assignment                    | *HW #11:* AP RE -- Update old database        |
  | *HW #5:* Dynamic -- Get a key (Obf.)        | *HW #12:* TBD                                 |

* Quizzes
  Three 10-15 minute quizzes, spread out on important over arching topics that
  we want to emphasize. Quizzes will be higher level, not as technical as what
  may be found as homework questions. Quizzes will be themed: Static Analysis,
  Dynamic Analysis, and Applied RE.


* Grading
  All assignments will be submitted and graded through Gradescope.

   |-----------+-----|
   | Quizzes   | 27% |
   |-----------+-----|
   | Homeworks | 73% |
   |-----------+-----|
