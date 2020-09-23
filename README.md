<div align="center">

## Add Command Line\(s\) to your App\!


</div>

### Description

This code is simple and easy! This code allows you to run command from the start menu. EXAMPLE: Start> Run> C:\Folder\MyApp.Exe /NoSplash
 
### More Info
 
I have found NO Side Effects yet, but if you have ANY problems you can Download the Demo

I am SURE this code works though!

If you have any doubts then download the demo and

run this (INCLUDE QUOTES!)

"C:\WINDOWS\Profiles\Jason Barnes\Desktop\Project1.exe" /Nosplash


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Megagix](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/megagix.md)
**Level**          |Intermediate
**User Rating**    |4.8 (81 globes from 17 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__1-43.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/megagix-add-command-line-s-to-your-app__1-29096/archive/master.zip)





### Source Code

```
' Just add this code to your Project...
' You can Change Commands and Functions
Private Sub Form_Load()
If Command = "/hide" then
'Function Here
ElseIf Command = "/BLACKback" then
Me.BackColor = &H0&
end if
End Sub
```

