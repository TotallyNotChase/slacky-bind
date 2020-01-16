This is a plugin for [slacky](https://github.com/M4cs/Slacky), the selfbot for slack!

## Installation
* Clone this repo and put it in `slacky/plugins/custom` in the main [slacky](https://github.com/M4cs/Slacky) clone.
* Then change the files `slacky/plugins/custom/__init__.py/` and `slacky/__main__.py` accordingly. (follow the comments)

## Usage

Assumes prefix is `~`

| Command   | Description                               | Usage                    |
| :--: | :--: | :--: |
| bind add | Bind a message to a string/letter          | ~bind add "\<trigger\>" "\<message\>" |
| bind list | List all custom binds stored in config          | ~bind list |
| bind delete | Delete a bind given its index          | ~bind delete \<index\> |
| ps | Paste the message bound to given string          | ~ps "\<trigger\>"                  |

<p align="center">
  <center><h2 align="center">bind in Action!</h2><br><img src="bind_example.gif"></center>
</p>
