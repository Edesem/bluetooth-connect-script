<h1 align="center">BCN</h1>
<p align="center">Bluetooth connect/disconnect shell script</p>
A shell script that connects and disconnects bluetooth devices using dmenu.

Requires dmenu, however if you wanted to use something else like rofi I assume it would be very trivial to change it to that or even make it cli.

##
<p align="center">
<img src="./bcn.gif" alt="Video Preview" width="2000px">
</p>


### Install 

```
sudo curl -sL "https://raw.githubusercontent.com/Edesem/bluetooth-connect-script/main/bcn" -o /usr/local/bin/bcn
sudo chmod +x /usr/local/bin/bcn
```
### Update
Just redo the curl command

### Unistall
`sudo rm /usr/local/bin/bcn`

### License
[GLP 3.0](https://raw.githubusercontent.com/Edesem/bluetooth-connect-script/main/LICENSE)
