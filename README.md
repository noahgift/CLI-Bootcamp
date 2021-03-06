# CLI-Bootcamp
Ideas on how to quickly learn to build command-line tools


## Part 1-Bash


###### Week1:  Using Linux

  * [Lesson 1:  Using Linux Shell Lab](https://github.com/noahgift/Coursera-DE-C2-Using-Linux)
  * [Lesson 2:  How shell piping works](https://github.com/noahgift/Coursera-DE-C2-Shell-Piping)
  * [Lesson 3: Using SSH](https://github.com/noahgift/ssh-tips-tricks)
 
###### Week2: Using Bash 

  * [Lesson 1: Create and Use .bashrc](https://github.com/noahgift/Coursera-DE-C2-configure-shell)
  * [Lesson 2: Sourcing shell variables from a script](https://github.com/noahgift/Coursera-DE-C2-shell-variables)
  * [Lesson3:  Using stdout and stdin](https://github.com/noahgift/Coursera-DE-C2-Standard-Streams)

###### Week3: Building Bash Scripts 

 * [Lesson 1:  Build a for loop in Bash](https://github.com/noahgift/Coursera-DE-C2-Use-Shell-Logic-and-Control-Flow)
 * [Lesson 2:  Truncate large files with Bash](https://github.com/noahgift/coursera-de-c2-truncate-file)
 * [Lesson 3: Building a command-line tool for data processing](https://github.com/noahgift/Coursera-DE-C2-bash-cli-reverse-string)
 * [Lesson 4: Build Bash CLI with options ](https://github.com/noahgift/Coursera-DE-C2-Lab3-Building-Bash-Scripts.git)

###### Week4: Composing File and Data Management Solutions with Linux

* [Lesson 1: Understand the search commands](https://github.com/noahgift/Coursera-DE-C2-search-commands)
* [Lesson 2: Setting permissions](https://github.com/noahgift/Coursera-DE-C2-Files-Directories-Permissions)
* [Lesson 3: Using regex to process text from file](https://github.com/noahgift/Coursera-DE-C2-using-regex-search)
* [Lesson 4: Search the filesystem with find](https://github.com/noahgift/Coursera-DE-C2-Lab4-Composing-File-Data-Solutions)

## Part 2-Build CLI in Python

* [python-click-cli-cookbook](https://github.com/noahgift/python-click-cli-cookbook)

## Challenges

### Bash and ZSH Challenges
* Customize your `~/.bashrc` with at least one alias, function and variable.
* Build a Bash CLI tool that takes options
* Truncate a large file and randomly sample at the same time
* Write a find command and a locate command
* Install [ohmzsh](https://ohmyz.sh), what did you learn?

### Python Challenges
* Pick a Python command-line tool library you are not familar with and build a module with a function that is called in a CLI.  A few examples:  
  * [python-fire](https://github.com/google/python-fire), 
  * [argparse](https://docs.python.org/3/library/argparse.html)
  * [python-click](https://click.palletsprojects.com/en/8.0.x/)
* Write a test for your python CLI tool
* Containerize your Python CLI tool and deploy to a public container repo like [Github Container Registry](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-container-registry) or [Docker Hub](https://hub.docker.com) or [Amazon Public Container Registry](https://aws.amazon.com/blogs/aws/amazon-ecr-public-a-new-public-container-registry/).  Here is an [example project](https://github.com/noahgift/container-from-scratch-python).

#### Additional Thoughts on Challenge

* How tiny can you make your container (hint try [alpine python](https://hub.docker.com/layers/python/library/python/3.9.0-alpine3.12/images/sha256-df77433749466a68bb599009753c9e5a8efaa3dd9c16450d442bb32f4c1fad4e?context=explore))?  What is the approach that shrinks the size?
* Can you lint your container with a linting tool like:  [hadolint?](https://github.com/hadolint/hadolint#how-to-use)  What about security scanning?
* Why would it be impressive to have a docker pull command for a CLI on your resume?
* Can you automatically build and push new containers in Github Actions?  [Hint...yes](https://github.com/noahgift/Python-MLOps-Cookbook/blob/main/.github/workflows/pythonapp.yml#L25).
* Can you build a GPT-3 CLI tool?  https://openai.com/blog/openai-api/

*GPT 3*:  
* Book:  https://learning.oreilly.com/library/view/gpt-3/9781098113612/ 
* Interview:  https://learning.oreilly.com/videos/52-weeks-of/021822022VIDEOPAIML/


### Advanced Challenges

* Write a CLI in a language you don't know:

  * [cli-rosetta](https://github.com/noahgift/cli-rosetta)
  * [Bash, Powershell and C# CLI](https://github.com/noahgift/DotNet-AWS/tree/main/chapters/chap1)

## References

* [Python Command Line Tools Course](https://learning.oreilly.com/videos/python-command-line/50131VIDEOPAIML/)
* [Python Command Line Tools-Book](https://learning.oreilly.com/library/view/python-command-line/61619PAIML/)
* [Python CI/CD for the Command-Line](https://learning.oreilly.com/videos/python-ci-cd-for/10092021VIDEOPAIML/)
* [Nuclear Powered CLI Tools](https://github.com/noahgift/nuclear_powered_command_line_tools)
* [mlops cookbook](https://github.com/noahgift/Python-MLOps-Cookbook)
