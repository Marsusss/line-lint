# line-lint
Checks whether there is a newline at the end of each file.

## Why add a newline character at the end of each file?
It is best practice to do so in the context of version controle as git will consider the last line before an addition to be changed by the editor because it will register a newline character to be created at this line. So it makes reading commits and git blaming nicer to look at.
