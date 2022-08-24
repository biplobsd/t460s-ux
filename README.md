# t460s-ux
Some useful change for lenovo thinkpad t460s


## 3 finger browser back<->forward (Win10)
- Enable three fingers switching apps in 'Synaptics Control Panel/Gestures/Drags and Slides>Three Fingers->Switching apps'
- Download -> [win10/synaptics3fingerBrowserBackForward.reg](win10/synaptics3fingerBrowserBackForward.reg)
- Double click synaptics3fingerBrowserBackForward.reg
- Run PowerShell as Admin `Stop-Service "SyntpEnhService"; kill -name SynTPEnh; kill -name SynTPHelper; Start-Service "SynTPEnhService"`

[More details](https://stackoverflow.com/a/49823162)
