Create a symlink to the assignemnt in the correct templates directory.
In my case, using Janus and Vim, the command was:

ln -s ./homework.tex ~/.janus/vim-latex/ftplugin/latex-suite/templates/assignment.tex

## Credit

When was looking for a good assignment template, I found Josh Davis'
article at
http://joshldavis.com/2014/02/12/doing-your-homework-in-latex/.
I forked [his repo][origin] to slim down the .tex to suit my needs when
starting assignments.

## License

This code is distributed under the MIT license. For more info, read the
[LICENSE](/LICENSE) file distributed with the source code.

[origin]: https://github.com/jdavis/latex-homework-template
