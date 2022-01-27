bazel compiler flags
====================

The goal is to set different compiler flags for external dependencies and 
own code as two different standards apply here. I want to use 
`-Wpedantic -Werror` for my code but cannot expect this from third party 
code.

[This](https://stackoverflow.com/questions/63588902/in-bazel-how-to-prevent-some-c-compiler-flags-from-passing-to-external-depend) is a good starting point.