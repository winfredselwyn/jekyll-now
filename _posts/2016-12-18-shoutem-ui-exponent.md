# Steps for getting @shoutem/ui working with Exponent #

For an unidentified reason, yarn and npm are unable to add @shoutem/ui to package.json on a Windows machine.
Here's how to use the UI toolkit

## Windows ##

1. react-native init NewProject
2. yarn add @shoutem/ui @shoutem/theme @shoutem/animation
3. yarn global add exp

In project folder

4. exp convert

Refer to the following link to get custom fonts required by @shoutem/ui loaded

5. Load fonts : [Link](https://github.com/exponentjs/shoutem-example/blob/master/main.js#L20-L36)
6. Customize @shoutem/theme. Default styles are not available, and must be defined in main component.