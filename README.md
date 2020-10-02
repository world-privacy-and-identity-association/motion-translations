# Translation files for WPIA motion tool

This repository holds the translation files of WPIA motion tool which are translated with the transifex server.

Gigi: https://code.wpia.club

Transifex: https://www.transifex.com/wpia/motion/

To push and pull the data from the server the transifex command line tool can be used.

Install it in a python environment with

`$ sudo easy_install pip` 

`$ sudo pip install transifex-client`

see https://docs.transifex.com/client/installing-the-client for more details.

Ask the WPIA maintainer for the API access token and install on the machine.

`$ tx init --token=<your_Transifex_API_token>`

To push new text elements to be translated use

`$ tx push -s`

To get the latest translation use

`$ tx pull -a` 

