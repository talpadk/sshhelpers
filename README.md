## A collection of scripts to make life with ssh even easier!

Currently only consists of one script:

* **ssa**, a tiny perl wrapper for ssh-add. <br />Improvements: If no path is specified for the key it attempts to use one from .ssh<br />Only prompts for password for keys not already added *(it checks if the key is already added and only calls ssh-add if it is not)*