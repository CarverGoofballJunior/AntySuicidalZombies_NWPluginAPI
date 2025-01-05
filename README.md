# AntiSuicidalZombies (2.0.0)
Plugin for the "SCP: Secret Laboratory" game, that prevents Zombies (SCP-049-2) from suiciding by walking into a Tesla, jumping into a void or being crushed by a bulk door or an elevator.

## Features
- Zombies can have effect(s) applied to them after walking into Tesla.
- Zombies, who jumped into void in HCZ, are teleported to one of the doors with no keycard permission in the same room. These rooms are: in SCP-106 room, Test Room and Armory.

## Installation
Place *AntiSuicidalZombies* dll in "...\AppData\Roaming\SCP Secret Laboratory\PluginAPI\plugins\global OR port_number".

## Config
|Name|Type|Default value|Description|
|---|---|---|---|
|is_enabled|bool|true|Should the plugin be enabled?|
|debug|bool|false|Should debug be enabled?|
|tesla_effect|Dictionary<string, EffectParameters>|Blurred:<br/>&nbsp;&nbsp;intensity:1<br/>&nbsp;&nbsp;duration:10 Burned:<br/>&nbsp;&nbsp;intensity:1<br/>&nbsp;&nbsp;duration:30|Effect(s) applied to zombies after walking into a tesla and their duration time.|
|crushed_effects|Dictionary<string, EffectParameters>|Concussed:<br/>&nbsp;&nbsp;intensity:5<br/>&nbsp;&nbsp;duration:10 Deafened:<br/>&nbsp;&nbsp;intensity:1<br/>&nbsp;&nbsp;duration:20 Slowness:<br/>&nbsp;&nbsp;intensity:30<br/>&nbsp;&nbsp;duration:30|Effect(s) applied to zombies after being crushed by a door or an elevator and their duration time.|
