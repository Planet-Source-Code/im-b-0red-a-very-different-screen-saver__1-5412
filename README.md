<div align="center">

## a \*\*\*VERY DIFFERENT\*\*\* Screen Saver


</div>

### Description

this is a totally differn't type of screensaver than what i've found here, this is actually pretty funny to just sit back and watch =-)
 
### More Info
 
add a timer (Timer1) with an interval of 175


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Im\_\[B\]0ReD](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/im-b-0red.md)
**Level**          |Beginner
**User Rating**    |3.3 (69 globes from 21 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Jokes/ Humor](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/jokes-humor__1-40.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/im-b-0red-a-very-different-screen-saver__1-5412/archive/master.zip)





### Source Code

```
Private Sub Form_KeyDown(KeyCode As Integer, Shift As Integer)
Unload Me
End Sub
Private Sub Form_KeyPress(KeyAscii As Integer)
Unload Me
End Sub
Private Sub Form_Load()
Form1.BackColor = vbBlack
Form1.BorderStyle = 0
Timer1.Interval = 175
End Sub
Private Sub Timer1_Timer()
ht = RandomNum(Min, Max)
wh = RandomNum(Min, Max)
Form1.Move wh, ht
Form1.Height = ht
Form1.Width = wh
Form1.Height = wh
Form1.Width = ht
End Sub
Public Function RandomNum(Min, Max) As Long
RandomNum = Int((Max - Min + 9500) * Rnd + Min)
End Function
```

