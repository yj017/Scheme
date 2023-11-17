# Scheme
An interpreter for a subset of the Scheme language based on Python

* `scheme_eval_apply.py`: the recursive evaluator for Scheme expressions
* `scheme_forms.py`: evaluation for special forms
* `scheme_classes.py`: classes that describe Scheme expressions
* `questions.scm`: Scheme procedures for you to implement
* `scheme.py`: the interpreter REPL
* `pair.py`: defines the Pair class and the nil object
* `scheme_builtins`.py: built-in Scheme procedures
* `scheme_reader.py`: the reader for Scheme input
* `scheme_tokens.py`: the tokenizer for Scheme input
* `scheme_utils.py`: functions for inspecting Scheme expressions
* `ucb.py`: utility functions for use in 61A projects
* `tests.scm`: a collection of test cases written in Scheme
* ` mytests.rst`: a file where you can add your own tests

To start an interactive Scheme interpreter session, type:
```sh
$ python3 scheme.py
````
To exit the Scheme interpreter, press Ctrl-d on Mac/Linux (or Ctrl-z Enter on Windows) or evaluate the exit procedure (after completing problems 3 and 4):
```sh
$ scm> (exit)
````


