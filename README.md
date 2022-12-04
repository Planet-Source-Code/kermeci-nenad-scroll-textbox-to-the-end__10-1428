﻿<div align="center">

## Scroll TextBox to the end


</div>

### Description

Scroll TextBox control to the end. This is usefull for chat programs, like mine on the picture.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Kermeci Nenad](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/kermeci-nenad.md)
**Level**          |Beginner
**User Rating**    |3.0 (12 globes from 4 users)
**Compatibility**  |VB\.NET
**Category**       |[Controls/ Forms/ Dialogs/ Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/controls-forms-dialogs-menus__10-3.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/kermeci-nenad-scroll-textbox-to-the-end__10-1428/archive/master.zip)





### Source Code

```
Hello,
I have been trying to find this example all over the net, and finally got to the idea how to do this.
All that you need is TextBox control, with properties multiline and vertical or both scrollbars.
After the textbox is filled with text, these three lines will do the job:
TextBox1.SelectionStart = TextBox1.Text.Length
TextBox1.SelectionLength = 0
TextBox1.ScrollToCaret()
Nenad Kermeci
```

