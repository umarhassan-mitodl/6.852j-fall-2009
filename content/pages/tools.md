---
content_type: page
description: This section provides guidelines on using the Tempo Toolkit, a collection
  of tools to simplify the process of developing and validating Input/Output Automata
  (IOA) systems.
draft: false
hide_download: true
hide_download_original: null
learning_resource_types:
- Tools
ocw_type: CourseSection
title: Tools
uid: 0da48dce-2322-7545-e627-49a6d0a030be
---
## The Tempo Toolkit

### Tempo Basics

To precisely model and prove properties of distributed algorithms in an asynchronous network, we introduced Input/Output Automata (IOA) formalism. The Tempo Toolkit is a collection of tools to simplify the process of developing and validating IOA systems. (Tempo actually works with Timed Input/Output Automata, a more powerful version of IOA that includes timing constraints. For our purposes, we will not make use of the timing features.)

The toolkit consists of the Tempo language, which closely matches the format of the pseudocode used in the book to describe IOA, a syntax checker to validate your IOA code, as well as connections to a homegrown simulator, the PVS theorem prover, and the UPAAL model-checker.

### Your Requirements

When specified by the problem set, you will be required to write your distributed algorithm in the Tempo language and validate it with the syntax checker. You will **not** be required to use the other tools included with the toolkit—simulation, theorem proving, model-checking—but are welcome to try if you have some experience with these techniques. We recommend that you experiment with writing your code in Tempo for the relevant questions in Part B of Problem Set 2. We will **require** you to hand in syntax-checked Tempo code starting with Problem Set 3.

### Installing the Tempo Toolkit

Windows, Mac, and Linux versions of the toolkit could previously be found at VeroModo. We recommend that you download the version including the Eclipse-based user interface. For this to work, you must have Java version 1.5 or better. The latest versions of Java can be downloaded [here](http://www.java.com/en/download/index.jsp).

Within the install directories see `doc/Tempo_Guide.pdf` for an overview of both the TIOA formalism and the Tempo language. The same file is also available here:

The Tempo Language User Guide and Reference Manual ({{% resource_link "7e5a76b4-0eff-76c8-2e41-4e8e96ccecdf" "PDF - 1.0MB" %}}) (Courtesy of Nancy Lynch, Stephen J. Garland, Dilsun Kaynar, Laurent Michel, and Alex Shvartsman. Used with permission.) Section 3 provides some toy examples of TIOA algorithms implemented in Tempo.