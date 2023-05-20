# acprestapitools
Atlassian Cloud Platform REST API tools

## Requirements
| Command | Description |
| :---: | --- |
| `zsh` | Sorry, all scripts require `/bin/zsh`. Mostly, because I developing on MacOs. <br>Note: version needs to be greater than 5.5 (released 2018) `zsh --version` |
| `jq` | Naturally, I needed a powerful tool to process all that JSON from REST API. With jq, I found such a tool. <br>https://stedolan.github.io/jq/ |
| `xsv` | I find it often more intuitive to work with CSV files. <br>https://github.com/BurntSushi/xsv |
| `GNU sed` | Not sure if, and why we need specific GNU sed features. #FIXME |

## Backlog
### List all project permissions for a user. 
source https://community.atlassian.com/t5/Jira-questions/How-can-I-check-users-projects-permissions-in-new-Jira-cloud/qaq-p/988221
### make an overview page listing all cloud spaces and their space admins
