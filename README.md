# webpack-case-sensitivity

This repository represents a test case for a problem with `webpack --watch`. 

When a file requires a module file which has a different file name than the actual existing file and the name differs 
by just a letter case, then `webpack --watch` first finds and includes the file, but when I modify the `require`d files
it ignores them.
