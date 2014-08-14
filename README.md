*  wrong_compiler_cmd - it fails because of annotation processor `DemoProcessor` couldn't be found in classpath
*  correct_compiler_cmd - this is a correct sequence of compilation steps.

    1. first compile `DemoProcessor`
    2. then trying to compile Code.java

And absolutely the same story can be applied to `ajc` compiler.
