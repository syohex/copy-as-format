# copy-as-format

Emacs function to copy buffer locations as GitHub/Slack/JIRA/HipChat/...
formatted code

## Supported Formats/Services

* BitBucket
* GitHub
* GitLab
* HipChat
* HTML
* JIRA
* Markdown
* Slack

## Usage

`M-x copy-as-format` or `C-u M-x copy-as-format`

Copy the current line or active region and add it to the kill ring as
GitHub/Slack/JIRA/HipChat/... formatted code. Format defaults to `copy-as-format-default`.
The buffer will not be modified.

With a prefix argument prompt for the format.

## See Also

* [git-link](https://github.com/sshaw/git-link)