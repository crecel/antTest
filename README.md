## what is Ant
Ant is the abbreviation for another neat tool. **Ant is a building tool based on Java** that combines the compilation,testing,deployment and other steps of software engineering and automates it.
Ant is similar to Make tool,but has no defects in Make tool.
## what is build
The process by which the code becomes executable file is called compilation.Because files depend on each other, you need to decide the order of compilation.**The compilation schedule is called build**.
## why is Ant
1. **cross-platform.** Ant is based on Java, so it has good cross-platform.
2. **easy to write and simple structure.** Configuration file is written in XML format, which improves readability.Ant can perform a variety of tasks by calling the Target tree. Each task implements a specific interface object.
3. **operation is simple.** Ant is made up of a built-in task and an optional task. An XML file(build file)is required for Ant to run.
4. **integrate into development environments.** Because of the features of Ant's cross-platform and simple operation, it is easy to integrate into some development environments.
## how to use Ant
1. install ant (brew install ant)
2. create a build.xml script in any directory
3. at the terminal, enter the build.xml script directory and input ant command
