<div align="center">

## Real mask you password


</div>

### Description

This code mask symbol in TextBox. Nobody (unmask-programm) cant show you password. Four line of code protect you programm.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Vitaliy Bykov](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/vitaliy-bykov.md)
**Level**          |Advanced
**User Rating**    |3.0 (18 globes from 6 users)
**Compatibility**  |VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Custom Controls/ Forms/  Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/custom-controls-forms-menus__1-4.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/vitaliy-bykov-real-mask-you-password__1-9060/archive/master.zip)





### Source Code

```
'Place at Form TextBox.
'General Declarations
Dim pswd As String
'
Private Sub Text1_KeyPress(KeyAscii As Integer)
  pswd = pswd + Chr(KeyAscii)
  KeyAscii = Asc("*")
End Sub
'You can replace string KeyAscii = Asc("*") to
'KeyAscii = 0 and TextBox is no symbols "*"
```

