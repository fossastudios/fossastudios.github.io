---
layout: page
title: Notes for Ruby Certification Silver 2.1
---

## Syntax
### Comments

| **Single Line** | # comment |
| **Multi Line** | no multiline |
| **Embedded Docs** | =begin Documentation =end |
| **Here Docs** | string = <<-HTML documentation HTML [˜, -] |

### Literals


### Keywords (41)

They Have a special meaning to the Ruby parser. However, they
can be appended with @, @@ and $.

| **CONDITIONAL** | if | then | else | end |
|| case | when | elsif | unless |
| **OPERATORS** | and | or | not |
| **LOOPS**  | for | while | do | break |
|| in | next | redo | retry |
|| until | return |
| **LITERALS**  | true  | false | nil |  `_LINE_` |
|| `_ENCODING_` | `_FILE_` |
| **CONSTRUCTS**  | class  | def | defined? | module |
|| self | super | undef | alias |
| **BLOCKS** | BEGIN | END | begin | end |
||rescue | ensure | yield |
| **TOKENS** | =begin | =end | `__END__` |

Methods used like keywords.

| at_exit | catch | private | require |
| attr    | include | proc | throw |
| attr_accessor | lambda | protected |  
| attr_reader   | load | public |  
| attr_writer   |  loop | raise |  

Global Functions used like keywords.

| Array | chomp! | gsub! | select |
| Float | chop | iterator? | sleep |
| Integer | chop! | load | split |
| String | eval | open | spintf |
| URI | exec | p | srend |
| abort | exit | print | sub |
| autoload | exit! | printf | sub! |
| autoload? | fail | putc | syscall |
| binding | fork | puts | system |
| block_given? | format | rand | test |
| callcc | getc | readline | trap |
| caller | gets | readlines | warn |
| chomp | gsub | scan |  |

Object Methods

| allocate | freeze | kind_of? | superclass |
| clone | frozen? | method | taint |
| display | hash | methods | tainted? |
| dup | id | new | to_a |
| enum_for | inherited | nil? | to_enum |
| eql? | inspect | object_id | to_s |
| equal? | instance_of? | respond_to? | untaint |
| extend | is_a? | send |  |

### Comments    
### Literal
### Variables, constants and scope
### Operators
### Conditional branching
### Loops
### Exception handling
### Method calls
### Blocks
### Method definition
### Class definition
### Module definition
### Multilingualization
## built-in libraries
### Well-used built-in classes and modules
### Object
### Numerical classes
### String
### Array
### Hash
### Kernel
### Enumerable
### Comparable
## Object orientation
### Polymorphism
### Inheritance
### mix-in
