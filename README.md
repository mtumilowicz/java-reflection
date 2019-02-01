[![Build Status](https://travis-ci.com/mtumilowicz/java-reflection.svg?branch=master)](https://travis-ci.com/mtumilowicz/java-reflection)

# java-reflection
_Reference_: https://www.amazon.com/Java-Language-Features-Modules-Expressions/dp/1484233476

## preface
**Reflection** is the ability to obtain and change the program's 
state during **its execution**.

Reflection is composed of:
* **introspection** - querying information
    * **structural introspection** - querying about the 
    implementation of the data and code
    * **behavioral introspection** - querying about the
    runtime environment
* **intercession** - modifying state, adding new behaviours
    * **structural intercession** - modifying (or creating) new 
    data structures and code
    * **behavioral intercession** - modifying the runtime 
    environment
 
## java   
**Reflection in Java** is mainly - introspection, we can query
about class:
* fields,
* constructors,
* methods, 
* modifiers, 
* superclass. 

Intercession is supported in a very limited way, we can:
* create an instance of a class whose name is not known
  in the compile-time
* invoke methods
* get/set fields

but we **can't:**
* change the data structure at runtime (add a new field or a method):
* change the method execution (behavioral intercession)

# projects
* https://github.com/mtumilowicz/java11-reflection-classes
* https://github.com/mtumilowicz/java11-reflection-fields
* https://github.com/mtumilowicz/java11-reflection-executables
    * https://github.com/mtumilowicz/java11-reflection-methods
    * https://github.com/mtumilowicz/java11-reflection-constructors 