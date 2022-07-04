# VN-chat
Better chat for QB-Core Framework

## Previews
(You can easly change colors)
### Full Chat
![Full Chat](https://cdn.discordapp.com/attachments/914259977370210415/993359535794307072/unknown.png)
### Alert
![Alert](https://cdn.discordapp.com/attachments/914259977370210415/993358720962674718/unknown.png)
### Error & Item Details 
![Alert](https://cdn.discordapp.com/attachments/914259977370210415/993358645259669504/unknown.png)

## Alerts/etc

# Modify Examplenation

If your `alert` is `ambualert`
```
...local msg = table.concat(args, " ")
            TriggerClientEvent("chatMessage", -1, "EMS ALERT", "ambualert", msg)...
```
Do this on chat's style.css
```
.ambualert {
  background-color: rgba(##, ##, ##, ##);
}
```
If `alert` is `error`
```
...local msg = table.concat(args, " ")
            TriggerClientEvent("chatMessage", -1, "EMS ALERT", "error", msg)...
```
Do this
```
.error {
  background-color: rgba(##, ##, ##, ##);
}
```


## Installation
### Manual
- Before you do it backup your old chat.
- Download the script and put it in this path - \resources\[cfx-default]\[gameplay].
- You don't need to ensure your script on config.

## Script forked and edited
credits [here](http://taptap.gigne.net/2020/08/no-pixel-chat.html#comments)