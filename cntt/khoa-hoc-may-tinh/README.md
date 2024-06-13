# Lộ trình tự học ngành Khoa học máy tính

# Contents

- [Tóm tắt](#summary)
- [Cộng đồng](#community)
- [Giáo trình](#curriculum)
- [Quy định](#code-of-conduct)
- [Giấy phép](#license)

# Summary

The OSSU curriculum is a **complete education in computer science** using online materials.
It's not merely for career training or professional development.
It's for those who want a proper, *well-rounded* grounding in concepts fundamental to all computing disciplines,
and for those who have the discipline, will, and (most importantly!) good habits to obtain this education largely on their own,
but with support from a worldwide community of fellow learners.

It is designed according to the degree requirements of undergraduate computer science majors, minus general education (non-CS) requirements,
as it is assumed most of the people following this curriculum are already educated outside the field of CS.
The courses themselves are among the very best in the world, often coming from Harvard, Princeton, MIT, etc.,
but specifically chosen to meet the following criteria.

**Courses must**:
- Be open for enrollment
- Run regularly (ideally in self-paced format, otherwise running multiple times per year)
- Be of generally high quality in teaching materials and pedagogical principles
- Match the curricular standards of the [CS 2013](CURRICULAR_GUIDELINES.md): Curriculum Guidelines for Undergraduate Degree Programs in Computer Science

When no course meets the above criteria, the coursework is supplemented with a book.
When there are courses or books that don't fit into the curriculum but are otherwise of high quality,
they belong in [extras/courses](extras/courses.md) or [extras/readings](extras/readings.md).

**Organization**. The curriculum is designed as follows:
- *Intro CS*: for students to try out CS and see if it's right for them
- *Core CS*: corresponds roughly to the first three years of a computer science curriculum, taking classes that all majors would be required to take
- *Advanced CS*: corresponds roughly to the final year of a computer science curriculum, taking electives according to the student's interests
- *Final Project*: a project for students to validate, consolidate, and display their knowledge, to be evaluated by their peers worldwide

**Duration**. It is possible to finish within about 2 years if you plan carefully and devote roughly 20 hours/week to your studies. Learners can use [this spreadsheet
](https://docs.google.com/spreadsheets/d/1bkUU90y4rKYQHwY5AR2iX6iiPTrPEsYs75GkCAkrgm4/copy) to estimate their end date. Make a copy and input your start date and expected hours per week in the `Timeline` sheet. As you work through courses you can enter your actual course completion dates in the `Curriculum Data` sheet and get updated completion estimates.
  
> **Warning:** While the spreadsheet is a useful tool to estimate the time you need to complete this curriculum, it may not be up-to-date with the curriculum. Use the spreadsheet just to estimate the time you need. Use the [OSSU CS website](https://cs.ossu.dev) or [the repo](https://github.com/ossu/computer-science) to see what courses to do.

**Cost**. All or nearly all course material is available for free. However, some courses may charge money for assignments/tests/projects to be graded.
Note that both [Coursera](https://www.coursera.support/s/article/209819033-Apply-for-Financial-Aid-or-a-Scholarship?language=en_US) and [edX](https://courses.edx.org/financial-assistance/) offer financial aid.

Decide how much or how little to spend based on your own time and budget;
just remember that you can't purchase success!

**Process**. Students can work through the curriculum alone or in groups, in order or out of order.
- We recommend doing all courses in Core CS, only skipping a course when you are certain that you've already learned the material previously.
- For simplicity, we recommend working through courses (especially Core CS) in order from top to bottom. Some students choose to study multiple courses at a time in order to vary the material they are working on is a day/week. A popular option is to take the math courses in parallel with the introductory courses. Course prerequisites are listed to help you determine if you are prepared for a given course.
- Courses in Advanced CS are electives. Choose one subject (e.g. Advanced programming) you want to become an expert in and take all the courses under that heading. You can also create your own custom subject; the Discord community may provide feedback on your planned subject.

**Content policy**. If you plan on showing off some of your coursework publicly, you must share only files that you are allowed to.
*Respect the code of conduct* that you signed in the beginning of each course!

**[How to contribute](CONTRIBUTING.md)**

**[Getting help](HELP.md)** (Details about our FAQ and chatroom)

# Community

- We have a Discord server! [![Discord](https://img.shields.io/discord/744385009028431943.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/wuytwK5s9h) This should be your first stop to talk with other OSSU students. Why don't you introduce yourself right now? [Join the OSSU Discord](https://discord.gg/wuytwK5s9h)
- You can also interact through GitHub issues. If there is a problem with a course, or a change needs to be made to the curriculum, this is the place to start the conversation. Read more [here](CONTRIBUTING.md).
- Add **Open Source Society University** to your [Linkedin](https://www.linkedin.com/school/11272443/) profile!

> **Warning:** There are a few third-party/deprecated/outdated material that you might find when searching for OSSU. We recommend you to ignore them, and only use the [OSSU CS website](https://cs.ossu.dev) or [OSSU CS Github Repo](https://github.com/ossu/computer-science). Some known outdated materials are:
>  - An unmaintained and deprecated firebase app. Read more in the [FAQ](./FAQ.md#why-is-the-firebase-ossu-app-different-or-broken).
>  - An unmaintained and deprecated trello board
>  - Third-party notion templates

# Curriculum

**Curriculum version**: `8.0.0` (see [CHANGELOG](CHANGELOG.md))

- [Yêu cầu tối thiểu](#prerequisites)
- [Mở đầu](#intro-cs)
  - [Giới thiệu về Lâp trình](#introduction-to-programming)
  - [Giới thiệu về Khoa học máy tính](#introduction-to-computer-science)
- [Phần chính](#core-cs)
  - [Lập trình căn bản](#core-programming)
  - [Toán căn bản](#core-math)
  - [Công cụ cho KHMT](#cs-tools)
  - [Hệ thống căn bản](#core-systems)
  - [Lý thuyết căn bản](#core-theory)
  - [Bảo mật căn bản](#core-security)
  - [Ứng dụng căn bản](#core-applications)
  - [Đạo đức căn bản](#core-ethics)
- [Phần nâng cao - Định hướng học](#advanced-cs)
  - [Lập trình](#advanced-programming)
  - [Hệ thống](#advanced-systems)
  - [Lý thuyết](#advanced-theory)
  - [Bảo mật thông tin](#advanced-information-security)
  - [Toán](#advanced-math)
- [Dự án cuối chương trình](#final-project)

---

## Prerequisites

- [Core CS](#core-cs) assumes the student has already taken [high school math](https://github.com/ossu/computer-science/blob/master/FAQ.md#how-can-i-review-the-math-prerequisites), including algebra, geometry, and pre-calculus.
- [Advanced CS](#advanced-cs) assumes the student has already taken the entirety of Core CS
and is knowledgeable enough now to decide which electives to take.
- Note that [Advanced systems](#advanced-systems) assumes the student has taken a basic physics course (e.g. AP Physics in high school).


## Intro CS

Đây là điểm khởi đầu cho những người chưa biết gì về Khoa học máy tính và muốn thử xem liệu ngành này có phù hợp với họ không.

Khóa học gốc | Thời lượng học | Thời gian học mỗi tuần | Cần học gì trước? | Khóa Tiếng Việt
:-- | :--: | :--: | :--: | :--:
[CS50 phụ đề Tiếng Việt trên Youtube](https://youtube.com/playlist?list=PLJ3cEjfn1AKRdtE2KNLCw0sgBfdmAeulI) | 10 weeks | 10 hours/week | none | [chat](https://discord.gg/syA242Z)

NÊN HỌC: Bạn có thể học 

## Core CS

Các môn trong này đều **bắt buộc**.

### Lập trình

Đây là phân mục về lập trình.

**Topics covered**:
`functional programming`
`design for testing`
`program requirements`
`common design patterns`
`unit testing`
`object-oriented design`
`static typing`
`dynamic typing`
`ML-family languages (via Standard ML)`
`Lisp-family languages (via Racket)`
`Ruby`
`and more`

Khóa học gốc | Thời lượng học | Thời gian học mỗi tuần | Cần học gì trước? | Khóa Tiếng Việt
:-- | :--: | :--: | :--: | :--:
[Systematic Program Design](coursepages/spd/README.md) | 13 weeks | 8-10 hours/week | none | Chưa có
[Programming Languages, Part A](https://www.coursera.org/learn/programming-languages) | 5 weeks | 4-8 hours/week | Systematic Program Design ([Hear instructor](https://www.coursera.org/lecture/programming-languages/recommended-background-k1yuh)) | Chưa có
[Programming Languages, Part B](https://www.coursera.org/learn/programming-languages-part-b) | 3 weeks | 4-8 hours/week | Programming Languages, Part A | Chưa có
[Programming Languages, Part C](https://www.coursera.org/learn/programming-languages-part-c) | 3 weeks | 4-8 hours/week | Programming Languages, Part B | Chưa có
[Object-Oriented Design](https://www.coursera.org/learn/object-oriented-design) | 4 weeks | 4 hours/week | [Basic Java](https://www.youtube.com/watch?v=GoXwIVyNvX0) | Chưa có
[Design Patterns](https://www.coursera.org/learn/design-patterns) | 4 weeks | 4 hours/week | Object-Oriented Design | Chưa có
[Software Architecture](https://www.coursera.org/learn/software-architecture) | 4 weeks | 2-5 hours/week | Design Patterns | Chưa có


### Toán

Discrete math (Math for CS) is a prerequisite and closely related to the study of algorithms and data structures. Calculus both prepares students for discrete math and helps students develop mathematical maturity.

**Các chủ đề sẽ được học**: `discrete mathematics` `mathematical proofs` `basic statistics` `O-notation` `discrete probability` `and more`

Khóa học gốc | Thời lượng học | Thời gian học mỗi tuần | Notes | Cần học gì trước? | Khóa Tiếng Việt
:-- | :--: | :--: | :--: | :--: | :--:
[Calculus 1A: Differentiation](https://openlearninglibrary.mit.edu/courses/course-v1:MITx+18.01.1x+2T2019/about) ([alternative](https://ocw.mit.edu/courses/mathematics/18-01sc-single-variable-calculus-fall-2010/index.htm)) | 13 weeks | 6-10 hours/week | The alternate covers this and the following 2 Khóa học gốc | [high school math](FAQ.md#how-can-i-review-the-math-prerequisites) | [Giải tích I](https://youtube.com/playlist?list=PLlX7racszQb4by9cDXEeRPj4Rj1AePZuq) 
[Calculus 1B: Integration](https://openlearninglibrary.mit.edu/courses/course-v1:MITx+18.01.2x+3T2019/about) | 13 weeks | 5-10 hours/week | - | Calculus 1A | [Giải tích II](https://youtube.com/playlist?list=PLmX3a81qI69J9v3Wz991Jx9o1HU7bZ5eR)
[Calculus 1C: Coordinate Systems & Infinite Series](https://openlearninglibrary.mit.edu/courses/course-v1:MITx+18.01.3x+1T2020/about) | 6 weeks | 5-10 hours/week | - | Calculus 1B | [Giải tích III](https://youtube.com/playlist?list=PLrv7xM5GiQtHjZzzlW8CCSfu9Sx5qLruH)
[Mathematics for Computer Science](https://openlearninglibrary.mit.edu/courses/course-v1:OCW+6.042J+2T2019/about) ([alternative](https://ocw.mit.edu/courses/6-042j-mathematics-for-computer-science-fall-2010/)) | 13 weeks | 5 hours/week | [2015/2019 solutions](https://github.com/spamegg1/Math-for-CS-solutions) [2010 solutions](https://github.com/frevib/mit-cs-math-6042-fall-2010-problems) [2005 solutions](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2005/assignments/). | Calculus 1C | - [Toán rời rạc](https://youtube.com/playlist?list=PLh1Hfe0GTSA4aXrjXDH0UrTY9tZ8adydI) <br> - [Xác suất thống kê](https://youtube.com/playlist?list=PLWEmkaCZrXhjoZ4EoAEx7_Kk5sWiG5M9A)

### Công cụ

Understanding theory is important, but you will also be expected to create programs. There are a number of tools that are widely used to make that process easier. Learn them now to ease your future work writing programs.

**Các chủ đề sẽ được học**: `terminals and shell scripting` `vim` `command line environments` `version control` `and more`

Khóa học gốc | Thời lượng học | Thời gian học mỗi tuần | Cần học gì trước? | Khóa Tiếng Việt
:-- | :--: | :--: | :--: | :--:
[The Missing Semester of Your CS Education](https://missing.csail.mit.edu/) | 2 weeks | 12 hours/week | - | [Kì Học Bị Thiếu Của Giáo Trình Khoa Học Máy Tính](https://missing-semester-vn.github.io/) 

### Hệ thống

**Các chủ đề sẽ được học**: `procedural programming` `manual memory management` `boolean algebra` `gate logic` `memory` `computer architecture` `assembly` `machine language` `virtual machines` `high-level languages` `compilers` `operating systems` `network protocols` `and more`

_PS: Mặc dù thêm bên cạnh "Khóa Tiếng Anh tương ứng" cho hai khóa đầu nhưng nó không thực sự liên quan đến nhau. Việc học khóa Tiếng Anh **NandToTetris** được khuyến khích hơn nếu bạn có Tiếng Anh tốt._

Khóa học gốc | Thời lượng học | Thời gian học mỗi tuần | Bài tập bổ sung | Cần học gì trước? | Khóa Tiếng Việt
:-- | :--: | :--: | :--: | :--: | :--:
[Build a Modern Computer from First Principles: From Nand to Tetris](https://www.coursera.org/learn/build-a-computer) ([alternative](https://www.nand2tetris.org/)) | 6 weeks | 7-13 hours/week | - | C-like programming language | [Kiến trúc máy tính](https://youtube.com/playlist?list=PLG92h61c7jzCFtOuwrbiMy4IASS9CQcTS)
[Build a Modern Computer from First Principles: Nand to Tetris Part II ](https://www.coursera.org/learn/nand2tetris2) | 6 weeks | 12-18 hours/week | - | one of [these programming languages](https://user-images.githubusercontent.com/2046800/35426340-f6ce6358-026a-11e8-8bbb-4e95ac36b1d7.png), From Nand to Tetris Part I | [Phân tích và thiết kế hệ thống](https://youtube.com/playlist?list=PLVrHxivsV5nw7RErJ6eabmG_s7cAuvK0e)
[Operating Systems: Three Easy Pieces](coursepages/ostep/README.md) | 10-12 weeks | 6-10 hours/week | - | Nand to Tetris Part II | [Nguyên lý hệ điều hành](https://youtube.com/playlist?list=PLgaUq0lEBS4Z5aZvZ0IBeigFZ_wBcnOVC)
[Computer Networking: a Top-Down Approach](http://gaia.cs.umass.edu/kurose_ross/online_lectures.htm)| 8 weeks | 4–12 hours/week | [Wireshark Labs](http://gaia.cs.umass.edu/kurose_ross/wireshark.php) | algebra, probability, basic CS | [Mạng máy tính](https://youtube.com/playlist?list=PLAWl4sDZTi7swN1NS7E-4AZIRacmGQDES)

### Lý thuyết

**Bao gồm các chủ đề**:
`divide and conquer`
`sorting and searching`
`randomized algorithms`
`graph search`
`shortest paths`
`data structures`
`greedy algorithms`
`minimum spanning trees`
`dynamic programming`
`NP-completeness`
`and more`

Các khóa Tiếng Anh dưới đây đều có phụ đề Tiếng Việt trong video. Cả 4 khóa! 

Khóa học gốc | Thời lượng học | Thời gian học mỗi tuần | Cần học gì trước? | Khóa Tiếng Việt
:-- | :--: | :--: | :--: | :--:
[Divide and Conquer, Sorting and Searching, and Randomized Algorithms](https://www.coursera.org/learn/algorithms-divide-conquer) | 4 weeks | 4-8 hours/week | any programming language, Mathematics for Computer Science | Chưa có
[Graph Search, Shortest Paths, and Data Structures](https://www.coursera.org/learn/algorithms-graphs-data-structures) | 4 weeks | 4-8 hours/week | Divide and Conquer, Sorting and Searching, and Randomized Algorithms | Chưa có
[Greedy Algorithms, Minimum Spanning Trees, and Dynamic Programming](https://www.coursera.org/learn/algorithms-greedy) | 4 weeks | 4-8 hours/week | Graph Search, Shortest Paths, and Data Structures | Chưa có
[Shortest Paths Revisited, NP-Complete Problems and What To Do About Them](https://www.coursera.org/learn/algorithms-npcomplete) | 4 weeks | 4-8 hours/week | Greedy Algorithms, Minimum Spanning Trees, and Dynamic Programming | Chưa có

### Bảo mật

**Bao gồm các chủ đề**
`Confidentiality, Integrity, Availability`
`Secure Design`
`Defensive Programming`
`Threats and Attacks`
`Network Security`
`Cryptography`
`and more`

Ngoại trừ khóa đầu tiên là của edX, các khóa sau của Coursera đều có phụ đề Tiếng Việt

Khóa học gốc | Thời lượng học | Thời gian học mỗi tuần | Cần học gì trước? | Khóa Tiếng Việt
:-- | :--: | :--: | :--: | :--:
[Cybersecurity Fundamentals](https://www.edx.org/course/cybersecurity-fundamentals) | 8 weeks | 10-12 hours/week | - | Chưa có
[Principles of Secure Coding](https://www.coursera.org/learn/secure-coding-principles)| 4 weeks | 4 hours/week | - | Chưa có
[Identifying Security Vulnerabilities](https://www.coursera.org/learn/identifying-security-vulnerabilities) | 4 weeks | 4 hours/week | - | Chưa có


Chọn **một** trong hai khóa sau đây:

Khóa học gốc | Thời lượng học | Thời gian học mỗi tuần | Cần học gì trước? | Khóa Tiếng Việt
:-- | :--: | :--: | :--: | :--:
[Identifying Security Vulnerabilities in C/C++Programming](https://www.coursera.org/learn/identifying-security-vulnerabilities-c-programming) | 4 weeks | 5 hours/week | - | Chưa có
[Exploiting and Securing Vulnerabilities in Java Applications](https://www.coursera.org/learn/exploiting-securing-vulnerabilities-java-applications) | 4 weeks | 5 hours/week | - | Chưa có

### Core applications

**Bao gồm các chủ đề**:
`Agile methodology`
`REST`
`software specifications`
`refactoring`
`relational databases`
`transaction processing`
`data modeling`
`neural networks`
`supervised learning`
`unsupervised learning`
`OpenGL`
`ray tracing`
`and more`

Khóa học gốc | Thời lượng học | Thời gian học mỗi tuần | Cần học gì trước? | Khóa Tiếng Việt
:-- | :--: | :--: | :--: | :--:
[Databases: Modeling and Theory](https://www.edx.org/course/modeling-and-theory)| 2 weeks | 10 hours/week | core programming | Chưa có
[Databases: Relational Databases and SQL](https://www.edx.org/course/databases-5-sql)| 2 weeks | 10 hours/week | core programming | Chưa có
[Databases: Semistructured Data](https://www.edx.org/course/semistructured-data)| 2 weeks | 10 hours/week | core programming | Chưa có
[Machine Learning](https://www.coursera.org/specializations/machine-learning-introduction)| 11 weeks | 9 hours/week | Basic coding | Chưa có
[Computer Graphics](https://www.edx.org/course/computer-graphics-2) ([alternative](https://cseweb.ucsd.edu/~viscomp/classes/cse167/wi22/schedule.html))| 6 weeks | 12 hours/week | C++ or Java, linear algebra | Chưa có
[Software Engineering: Introduction](https://www.coursera.org/learn/introduction-to-software-engineering) | 4 weeks | 8-10 hours/week | Core Programming, and a [sizable project](FAQ.md#why-require-experience-with-a-sizable-project-before-the-Software-Engineering-courses) | Chưa có

### Core ethics

**Bao gồm các chủ đề**:
`Social Context`
`Analytical Tools`
`Professional Ethics`
`Intellectual Property`
`Privacy and Civil Liberties`
`and more`

Các khóa học đều trên Coursera và có phụ đề Tiếng Việt trong video.

Khóa học gốc | Thời lượng học | Thời gian học mỗi tuần | Cần học gì trước? | Khóa Tiếng Việt
:-- | :--: | :--: | :--: | :--:
[Ethics, Technology and Engineering](https://www.coursera.org/learn/ethics-technology-engineering)| 9 weeks | 2 hours/week | none | Chưa có
[Introduction to  Intellectual Property](https://www.coursera.org/learn/introduction-intellectual-property)| 4 weeks | 2 hours/week | none | Chưa có
[Data Privacy Fundamentals](https://www.coursera.org/learn/northeastern-data-privacy)| 3 weeks | 3 hours/week | none | Chưa có


## Advanced CS

Sau khi hoàn thành **Core CS** thì giờ sẽ là lúc chọn chuyên ngành hẹp. Cần phải học hết phần chuyên ngành hẹp mà bạn đã chọn

### Advanced programming

**Bao gồm các chủ đề**:
`debugging theory and practice`
`goal-oriented programming`
`parallel computing`
`object-oriented analysis and design`
`UML`
`large-scale software architecture and design`
`and more`

Khóa học gốc | Thời lượng học | Thời gian học mỗi tuần | Cần học gì trước? | Khóa Tiếng Việt 
:-- | :--: | :--: | :--: | :--:
[Parallel Programming](https://www.coursera.org/learn/scala-parallel-programming)| 4 weeks | 6-8 hours/week | Scala programming | Chưa có
[Compilers](https://www.edx.org/course/compilers) | 9 weeks | 6-8 hours/week | none | Chưa có
[Introduction to Haskell](https://www.seas.upenn.edu/~cis194/fall16/)| 14 weeks | - | - | Chưa có
[Learn Prolog Now!](https://www.let.rug.nl/bos/lpn//lpnpage.php?pageid=online) ([alternative](https://github.com/ossu/computer-science/files/6085884/lpn.pdf))*| 12 weeks | - | - | Chưa có
[Software Debugging](https://www.udacity.com/course/software-debugging--cs259)| 8 weeks | 6 hours/week | Python, object-oriented programming | Chưa có
[Software Testing](https://www.youtube.com/playlist?list=PLAwxTw4SYaPkWVHeC_8aSIbSxE_NXI76g) | 4 weeks | 6 hours/week | Python, programming experience | Chưa có

(*) book by Blackburn, Bos, Striegnitz (compiled from [source](https://github.com/LearnPrologNow/lpn), redistributed under [CC license](https://creativecommons.org/licenses/by-sa/4.0/))

### Advanced systems

**Bao gồm các chủ đề**:
`digital signaling`
`combinational logic`
`CMOS technologies`
`sequential logic`
`finite state machines`
`processor instruction sets`
`caches`
`pipelining`
`virtualization`
`parallel processing`
`virtual memory`
`synchronization primitives`
`system call interface`
`and more`

Khóa học gốc | Thời lượng học | Thời gian học mỗi tuần | Cần học gì trước? | Ghi chú | Khóa Tiếng Việt
:-- | :--: | :--: | :--: | :--: | :--:
[Computation Structures 1: Digital Circuits](https://learning.edx.org/course/course-v1:MITx+6.004.1x_3+3T2016) [alternative 1](https://ocw.mit.edu/courses/6-004-computation-structures-spring-2017/) [alternative 2](https://ocw.mit.edu/courses/6-004-computation-structures-spring-2009/) | 10 weeks | 6 hours/week | [Nand2Tetris II](https://www.coursera.org/learn/nand2tetris2) | Alternate links contain all 3 courses. | Chưa có
[Computation Structures 2: Computer Architecture](https://learning.edx.org/course/course-v1:MITx+6.004.2x+3T2015) | 10 weeks | 6 hours/week | Computation Structures 1 | | Chưa có
[Computation Structures 3: Computer Organization](https://learning.edx.org/course/course-v1:MITx+6.004.3x_2+1T2017) | 10 weeks | 6 hours/week | Computation Structures 2 | | Chưa có

### Advanced theory

**Bao gồm các chủ đề**:
`formal languages`
`Turing machines`
`computability`
`event-driven concurrency`
`automata`
`distributed shared memory`
`consensus algorithms`
`state machine replication`
`computational geometry theory`
`propositional logic`
`relational logic`
`Herbrand logic`
`game trees`
`and more`

Khóa học gốc | Thời lượng học | Thời gian học mỗi tuần | Cần học gì trước? | Khóa Tiếng Việt 
:-- | :--: | :--: | :--: | :--:
[Theory of Computation](https://ocw.mit.edu/courses/18-404j-theory-of-computation-fall-2020/) ([alternative](http://aduni.org/courses/theory/index.php?view=cw)) | 13 weeks | 10 hours/week | [Mathematics for Computer Science](https://openlearninglibrary.mit.edu/courses/course-v1:OCW+6.042J+2T2019/about), logic, algorithms | Chưa có
[Computational Geometry](https://www.edx.org/course/computational-geometry) | 16 weeks | 8 hours/week | algorithms, C++ | Chưa có
[Game Theory](https://www.coursera.org/learn/game-theory-1) | 8 weeks | 3 hours/week | mathematical thinking, probability, calculus | Chưa có 

### Advanced Information Security

Khóa học gốc | Thời lượng học | Thời gian học mỗi tuần | Cần học gì trước? | Khóa Tiếng Việt 
:-- | :--: | :--: | :--: | :--:
[Web Security Fundamentals](https://www.edx.org/course/web-security-fundamentals) | 5 weeks | 4-6 hours/week | understanding basic web technologies | Chưa có
[Security Governance & Compliance](https://www.coursera.org/learn/security-governance-compliance) | 3 weeks | 3 hours/week | - | Chưa có
[Digital Forensics Concepts](https://www.coursera.org/learn/digital-forensics-concepts) | 3 weeks | 2-3 hours/week | Core Security | Chưa có
[Secure Software Development: Requirements, Design, and Reuse](https://www.edx.org/course/secure-software-development-requirements-design-and-reuse) | 7 weeks | 1-2 hours/week | Core Programming and Core Security | Chưa có
[Secure Software Development: Implementation](https://www.edx.org/course/secure-software-development-implementation) | 7 weeks | 1-2 hours/week | Secure Software Development: Requirements, Design, and Reuse | Chưa có
[Secure Software Development: Verification and More Specialized Topics](https://www.edx.org/course/secure-software-development-verification-and-more-specialized-topics) | 7 weeks | 1-2 hours/week | Secure Software Development: Implementation | Chưa có
 
### Advanced math

Khóa học gốc | Thời lượng học | Thời gian học mỗi tuần | Cần học gì trước? | Khóa Tiếng Việt
:-- | :--: | :--: | :--: | :--: 
[Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) | - | - | [high school math](FAQ.md#how-can-i-review-the-math-prerequisites) | Chưa có
[Linear Algebra](https://ocw.mit.edu/courses/mathematics/18-06sc-linear-algebra-fall-2011/) | 14 weeks | 12 hours/week | corequisite: Essence of Linear Algebra | Chưa có
[Introduction to Numerical Methods](https://ocw.mit.edu/courses/mathematics/18-335j-introduction-to-numerical-methods-spring-2019/index.htm)| 14 weeks | 12 hours/week | [Linear Algebra](https://ocw.mit.edu/courses/mathematics/18-06sc-linear-algebra-fall-2011/) | Chưa có
[Introduction to Formal Logic](https://forallx.openlogicproject.org/) | 10 weeks | 4-8 hours/week | [Set Theory](https://www.youtube.com/playlist?list=PL5KkMZvBpo5AH_5GpxMiryJT6Dkj32H6N) | Chưa có
[Probability](https://projects.iq.harvard.edu/stat110/home) | 15 weeks | 5-10 hours/week | [Differentiation and Integration](https://www.edx.org/course/calculus-1b-integration) | Chưa có

## Final project

Part of learning is doing.
The assignments and exams for each course are to prepare you to use your knowledge to solve real-world problems.

After you've completed Core CS and the parts of Advanced CS relevant to you,
you should identify a problem that you can solve using the knowledge you've acquired.
You can create something entirely new, or you can improve some tool/program that you use and wish were better.

Students who would like more guidance in creating a project may choose to use a series of project oriented courses.
Here is a sample of options
(many more are available, at this point you should be capable of identifying a series that is interesting and relevant to you):

Khóa học gốc | Thời lượng học | Thời gian học mỗi tuần | Cần học gì trước? 
:-- | :--: | :--: | :--: | 
[Fullstack Open](https://fullstackopen.com/en/) | 12 weeks | 15 hours/week | programming
[Modern Robotics (Specialization)](https://www.coursera.org/specializations/modernrobotics) | 26 weeks | 2-5 hours/week | freshman-level physics, linear algebra, calculus, [linear ordinary differential equations](https://www.khanacademy.org/math/differential-equations)
[Data Mining (Specialization)](https://www.coursera.org/specializations/data-mining) | 30 weeks | 2-5 hours/week | machine learning
[Big Data (Specialization)](https://www.coursera.org/specializations/big-data) | 30 weeks | 3-5 hours/week | none
[Internet of Things (Specialization)](https://www.coursera.org/specializations/internet-of-things) | 30 weeks | 1-5 hours/week | strong programming
[Cloud Computing (Specialization)](https://www.coursera.org/specializations/cloud-computing) | 30 weeks | 2-6 hours/week | C++ programming
[Data Science (Specialization)](https://www.coursera.org/specializations/jhu-data-science) | 43 weeks | 1-6 hours/week | none
[Functional Programming in Scala (Specialization)](https://www.coursera.org/specializations/scala) | 29 weeks | 4-5 hours/week | One year programming experience
[Game Design and Development with Unity 2020 (Specialization)](https://www.coursera.org/specializations/game-design-and-development) | 6 months | 5 hours/week | programming, interactive design

## Congratulations

After completing the requirements of the curriculum above,
you will have completed the equivalent of a full bachelor's degree in Computer Science.
Congratulations!

What is next for you? The possibilities are boundless and overlapping:

- Look for a job as a developer!
- Check out the [readings](extras/readings.md) for classic books you can read that will sharpen your skills and expand your knowledge.
- Join a local developer meetup (e.g. via [meetup.com](https://www.meetup.com/)).
- Pay attention to emerging technologies in the world of software development:
  + Explore the **actor model** through [Elixir](https://elixir-lang.org/), a new functional programming language for the web based on the battle-tested Erlang Virtual Machine!
  + Explore **borrowing and lifetimes** through [Rust](https://www.rust-lang.org/), a systems language which achieves memory- and thread-safety without a garbage collector!
  + Explore **dependent type systems** through [Idris](https://www.idris-lang.org/), a new Haskell-inspired language with unprecedented support for type-driven development.

![keep learning](https://i.imgur.com/REQK0VU.jpg)

# Code of conduct
[OSSU's code of conduct](https://github.com/ossu/code-of-conduct).

## How to show your progress

[Fork](https://www.freecodecamp.org/news/how-to-fork-a-github-repository/) the [GitHub repo](https://github.com/ossu/computer-science) into your own GitHub account and put ✅ next to the stuff you've completed as you complete it. This can serve as your [kanban board](https://en.wikipedia.org/wiki/Kanban_board) and will be faster to implement than any other solution (giving you time to spend on the courses).

# Team

* **[Eric Douglas](https://github.com/ericdouglas)**: founder of OSSU
* **[Josh Hanson](https://github.com/joshmhanson)**: lead technical maintainer
* **[Waciuma Wanjohi](https://github.com/waciumawanjohi)**: lead academic maintainer
* **[Contributors](https://github.com/ossu/computer-science/graphs/contributors)**
