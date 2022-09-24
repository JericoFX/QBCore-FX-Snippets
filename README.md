# QBCore FX Snippets README

This extension has some useful snippets to use with vscode and qbcore, from simples function to complex solutions like polyzone creator, qb-menu, KeyMapping and more.

## Install

https://marketplace.visualstudio.com/items?itemName=JericoFX.qb-core-snippets

or by VSCode extension browser QB-Core FX Snippets

## Features

As above described, you can find some useful commands, like

```lua
--[[QBCore releated]]

GC or GetObject =>  to get the QBCore object.

CT => CreateThread.

tc or TriggerCallback => To trigger a callback.

Notify => Client or Server function.


KeyMapping => or km will create a RegisterKeyMapping with the commands and a link to the fivem Docs.

DrawNuiText, dw, Draw, Text, Dtext => Draw nui text.

ChangeNuiText, ct, ChangeText, Ctext => Change Text.

HideText, ht, Hide, Htext => Hide Nui Text.

KeyPressed, kp, Ktext => Emulate a Key Press Event.

MYSQL Functions.

QBCore:Client:OnPlayerLoaded => OnPlayerLoaded or OPL, opl.

QBCore:Client:OnJobUpdate => OnJobUpdate or OJU , oju.

Blip => will create a local function.

log => will create a print().

Debug => will use the QBCore.Debug() function.

Menu, CreateMenu => qb-menu trigger.

CreateCallback or CCallback => will trigger QBCore.Functions.

CreateCallback() Function.

AddRadial, CreateRadialOption => add radial Option.


--[[Fivem Appearance ones]]

getPedComponents, APGComp => getPedComponents(Player ID)

setPedTattoos, spt, APSTattoos => setPedTattoos(Ped,table)

setPlayerModel,spm,APSModel => setPlayerModel(model --[[string]])

setPlayerAppearance,spa,APSSet => setPlayerAppearance()
and a lot More...

--[[POLYZONES]]

EntityZone, PZone => Create an Entity Zone --[[https://github.com/mkafrin/PolyZone/wiki/EntityZone]]

CircleZone,CZ,CreateCircle,PolyCircle,CPoly => Create a Circle Zone

Boxzone,Box,PolyBox => Create a Box Zone
--[[1.6.0]]
--[[ps-zones https://github.com/Project-Sloth/ps-zones]]

PSPoly, PSPzone => create a ps-polyzone (name must be unique!)
PSbox => create a ps-boxzone (name must be unique!)
PSCircle => create a ps-circlezone (name must be unique!)
PSEntity => create a ps-entityzone (name must be unique!)
PSDestroy => destroy a zone, need to pass the name of the zone
PShandler, PSEvent => handler of ps-zones

--[[QB INVENTORY]]
useitem,Iuse => UseItem event (Server)

hasitem,Ihas => HasItem (Client and Server)

GetUsableItem,IGusable => check if is a player can use X item (server)

AddItem,Iadd => Add item

RemoveItem,Iremove => remove item

GetItemByName,IGname=> get Item by name

GetItemsByName => get ITEMS by name


```

## Release Notes

First Release

### 1.0.0

Initial release of QB-FX

### 1.1.0

Added qb-radialmenu options

### 1.4.0

Added MYSQL commands just put MYSQL and all the commands will appear with a comment to the Docs.

### 1.5.0

Added missing PolyZones snippets and some fivem-appearance ones.

### 1.6.0

Fixed qb-inventory exports and added Project Sloth snippets. ps-zones --[[https://github.com/Project-Sloth/ps-zones]]

**Enjoy!**
