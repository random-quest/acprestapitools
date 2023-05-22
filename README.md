
# Atlassian Cloud Platform REST API tools

*I'd like to start with this quote from "UNIX - A History and Memoir", by Brian Kernighan:*
> The user-level programmable shell, with control-flow statements and easy I/O redirection, made it possible to program by using programs as building blocks. As the shell’s programming capabilities grew, it became another high-level language in the programmer’s toolbox. And because it was a user-level program, not part of the operating system, it could be improved on and replaced by anyone with a better idea. The evolution from the original Unix shell through PWB, the Bourne shell and Bill Joy’s csh to today’s proliferation illustrates the benefits, and of course some of the drawbacks — it’s all too easy for incompatible versions to multiply.<br><br>
> Pipes are the quintessential Unix invention, an elegant and efficient way to use temporary connections of programs. The notion of streaming data through a sequence of processing steps is natural and intuitive, the syntax is exceptionally simple, and the pipe mechanism fits perfectly with the collec- tion of small tools. Pipes do not solve all connection problems, of course, but the fully general non-linear connections of Doug McIlroy’s original concept do not show up often in practice; linear pipelines are almost always good enough.<br><br>
> The notion of programs as tools and using them in composition is characteristic of Unix. Writing small programs that each do one thing well, rather than large and monolithic programs that try to do many things, has many benefits. Certainly there are times when monoliths make sense, but there are strong advantages to a collection of small(ish) programs that ordinary users can combine in novel ways.

**Table of Contents**
<!-- MarkdownTOC autolink="true" autoanchor="true" -->

- [Introduction and motivation](#introduction-and-motivation)
	- [a well-behaved Atlassian citizen](#a-well-behaved-atlassian-citizen)
- [Dependencies](#dependencies)
- [Bugs and feature requests](#bugs-and-feature-requests)

<!-- /MarkdownTOC -->

<a id="introduction-and-motivation"></a>
# Introduction and motivation
Working as an Atlassian consultant, I often need to accomplish feats that are impossible to achieve by using the Web UI, and if the Web UI provides facilitation, it is cumbersome, requires too many clicks, and hence is time consuming, and error-prone. 

As a Unix/Linux enthusiast, I prefer the keyboard. 

**acprestapitools** allows me to be creative by standing on the shoulder of giants by means of using traditional shell programming (including the power of pipes) - just the way Brian intended. 

For example
```shell
aj FIXME
```

<a id="a-well-behaved-atlassian-citizen"></a>

<a id="a-well-behaved-atlassian-citizen"></a>
## a well-behaved Atlassian citizen
**acprestapitools** solely makes use of the [Atlassian Cloud REST API](https://developer.atlassian.com/cloud/jira/platform/rest/v3/intro/). Hence, by definition, **acprestapitools** is a well behaved Atlassian citizen. You will find no database hacks in this toolset.

<a id="dependencies"></a>
# Dependencies
| Command | Description |
| :---: | --- |
| `zsh` | Sorry, all scripts require `/bin/zsh`. <br>Note: version needs to be greater than 5.5 (released 2018) `zsh --version` |
| `jq` |  jq is like sed for JSON data. <br>https://stedolan.github.io/jq/ |
| `xsv` | xsv is a command line program for indexing, slicing, analyzing, splitting and joining CSV files. <br>https://github.com/BurntSushi/xsv |


<a id="bugs-and-feature-requests"></a>
# Bugs and feature requests
https://github.com/random-quest/acprestapitools/issues?q=is%3Aopen+is%3Aissue+label%3Aenhancement
