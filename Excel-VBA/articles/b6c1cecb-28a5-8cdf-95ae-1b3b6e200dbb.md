
# Application.UsableWidth Property (Excel)

Returns the maximum width of the space that a window can occupy in the application window area, in points. Read-only  **Double** .


## Syntax

 _expression_ . **UsableWidth**

 _expression_ A variable that represents an **Application** object.


## Example

This example expands the active window to the maximum size available (assuming that the window isn't already maximized).


```vb
With ActiveWindow 
 .WindowState = xlNormal 
 .Top = 1 
 .Left = 1 
 .Height = Application.UsableHeight 
 .Width = Application.UsableWidth 
End With
```


## See also


#### Concepts


[Application Object](19b73597-5cf9-4f56-8227-b5211f657f6f.md)
#### Other resources


[Application Object Members](4cb9ca42-8d07-cc9c-2d80-4eb9a5921e1e.md)
