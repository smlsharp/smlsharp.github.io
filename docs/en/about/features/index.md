---
title: "SML# Features"
translated: true
---
SML# is a new programming language in the ML-family, having the following features.

* **Backward compatibility with Standard ML**
SML# can compile all programs that conform to the
definition of the Standard ML\cite{sml} with a few exceptions.

* **Record polymorphism**
SML# supports record polymorphism \cite{ohor95toplas}.
In SML# , field selection operators 
```#label```
and record patterns 
``` {field-pat,...}```
are fully polymorphic.
This feature is essential in modular development of programs
manipulating records, and is the key to extend ML with SQL.

* **Seamless integration of SQL**
SML# seamlessly integrates (currently a subset of) SQL.
Instead of providing built-in primitives to access
database servers, SML# integrate SQL expressions themselves as
polymorphically-typed first-class citizens.
This allows the programmer to directly access databases in
your polymorphic ML code.

* **Direct interface to C**
SML# programs can directly call C functions of your own
coding or in system libraries.
The programmer need only declare their names and types, without
writing mysterious ``stubs'' or conversion functions. 
The SML# generates external references to C functions,
which are resolved and linked by the system linker.
Both static and dynamic linking are supported.

* **Separate compilation and linking**
	SML# supports true separate compilation and linking.
	By writing an interface file, each source file is compiled
separately into an object file in the standard system format (e.g.\ ELF
format.)
	The separately compiled object files are then linked together
possibly with C functions and libraries into an executable program.

* **Multithread support for multicore CPUs**
The non-moving GC and direct C interface allow
SML# code to directly call POSIX thread library.
As far as the OS thread library support a multicore CPU,
SML# program automatically obtains multithread capability for
multicore CPUs.
With the non-moving fully concurrent GC we have just developed, 
concurrent threads run efficiently on a multicore CPU.
