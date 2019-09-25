# Test _git

This simplistic but effective testing.

1.  Open a regular Powershell console in the "test _git" folder.
2.  `Import-Module ..\src\posh-git.psd1`  
    You should immediately see the default posh-git prompt
3.  `git status`  
    You should get a message of no commits and no files are tracked. Note that
    the .gitignore file excludes the `_git` path.
4.  `cd f`  
    The posh-git prompt remains. Running `git status` returns the same message, but showing the relative path to .gitignore
    
