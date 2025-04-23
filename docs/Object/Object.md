# Object

## Intro
Object is the based for all **drawable** objects. It is used a base for anything that you want to draw

## Attributes
| Name     | Description |
| -------- | ----------- |
| x : float | Where the object is on the x line |
| y : float | Where the object is on the y line |

## API Calls

setName(newName : string) : void

Sets the name of the Object

Example: 
```lua
local object = game.Workspace:getDrawObject("myObject")
object:setName("myDifferentObject")
```