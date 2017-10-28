#### File to edit
`sudo leafpad /etc/rc.local &`

Add just above "exit 0" line

`sleep {delay in seconds} && sudo -iu {user} {full path to command}`

#### Example

`sleep 15 && sudo -iu pi /home/pi/bin/pbstart`
