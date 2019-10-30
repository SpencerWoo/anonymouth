<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [<a id="top"></a>Anonymouth](#a-idtopaanonymouth)
- [Set Up](#set-up)
    - [<a id="introduction"></a>Introduction](#a-idintroductionaintroduction)
    - [<a id="dependencies"></a>Dependencies](#a-iddependenciesadependencies)
    - [<a id="run"></a>Run](#a-idrunarun)
- [Credits](#credits)
    - [<a id="license"></a>License](#a-idlicensealicense)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# <a id="top"></a>Anonymouth

![](src/edu/drexel/psal/resources/graphics/readme_Logo.png)

Document Anonymization Tool, Version 0.5<br>

The Privacy, Security and Automation Lab (PSAL)<br>
Drexel University, Philadelphia PA<br>
<https://psal.cs.drexel.edu/index.php/Main_Page>

# Set Up

### <a id="introduction"></a>Introduction

Anonymouth is a Java-based application that aims to give users to tools and knowledge needed to begin anonymizing documents they have written.

It does this by firing up JStylo libraries (an author detection application also develped by PSAL) to detect stylometric patterns and determine features (like word length, bigrams, trigrams, etc.) that the user should remove/add to help obsure their style and identity.

Though Anonymouth and it's team works hard to provide you with tools to help remove your identity from documents you have written, WE CAN IN NO WAY GUARANTEE THAT YOUR DOCUMENT IS ANONYMOUS OR NOT ANONYMOUS. Anonymouth is always giving you it's best guess, it's best idea of where your document stands, though that should not any any time be taken as an absolute (for example, you could have forgotten to remove your name from the document and Anonymouth has no way to know that that's your name and should remove it). What we can say is Anonymouth is only as good as you make it, and when used right can be helpful in guiding your document towards the right direction.

### <a id="dependencies"></a>Dependencies

Java 7 is required to run Anonymouth.
	
### <a id="run"></a>Run

The simplest way to run Anonymouth is to check out the `compiled` [branch](https://github.com/spencermwoo/anonymouth/tree/compiled) and run the compiled program.

# Credits

### <a id="license"></a>License

Anonymouth was released by the Privacy, Security and Automation lab at Drexel University in 2011 under the AGPLv3 license. A copy of this license is included with the repository/program. If for some reason it is absent, it can be viewed <a href="http://www.gnu.org/licenses/agpl.html">here</a>.
