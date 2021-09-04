# source_code_analysis
Static Code Analysis is not just useful but also vital for software to work and for developers to understand their software. It simplifies the process of searching for bugs and errors, by pointing you right to them and helps identify issues. Static Code Analysis (also known as Source Code Analysis) is usually performed as part of a Code Review (also known as white-box testing) and is carried out at the Implementation phase of a Security Development Lifecycle (SDL).

A tool which will analyze source code and also recommend some effective methods to avoid the errors. This helps in eradicating problems such as buffer overflows, SQL Injection, XSS and many more, which will be of great help.

Steps performed:
i.	It all starts with reading the code.
ii.	A lexical analysis follows, where tokens are created and compared to vulnerability libraries, in a similar way of compilers.
iii.	Then, they can create an abstract representation of the code, through the construction of Abstract Syntax Trees (AST).
iv.	To deepen the analysis, tools can analyze the flow of execution. Using an Intermediate Representation (IR).
v.	The IR is the base for building a Control Flow Graph and a Symbol Table.
vi.	At this point, functions are analyzed. Independent, modular, and global analysis can be done.

