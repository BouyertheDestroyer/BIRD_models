## BIRD Systems

This explains the systems in BIRD which can be used by mods.

## Bird Interaction

Whenever a Bird grabs or releases a prop that has a BindableEvent named "GrabUpdate", the BindableEvent will be fired. See the script inside the balloon for how a grab triggers popping the balloon. The arguments passed to the event are 1) the Player grabbing the object (use `Player.Character` to get the bird Model) and 2) a bool whether the object is being grabbed (true) or released (false).

<img width="162" alt="image" src="https://github.com/BouyertheDestroyer/BIRDmod/assets/150331530/90514ba6-87de-4e06-b48e-735b1544fcbe">

Whenever a Bird squawks while holding a prop with a BindableEvent named "SquawkEvent", the BindableEvent will be fired. See the script inside the flashlight for how a squawk turns the flashlight on and off. If the SquawkEvent has a child BoolValue named "MuteSquawk" whose Value is true, the BIRD will activate the prop without squawking.

<img width="306" alt="image" src="https://github.com/BouyertheDestroyer/BIRDmod/assets/150331530/32387e01-d24d-4e95-992f-bcbe44da104b">

Both of these BindableEvents can be parented to the grabbed Part (like in the balloon) or to the Parent of a grabbed Part (like in the flashlight).

## Respawning

Any Part or Model with the `Cleanup` [Tag](https://create.roblox.com/docs/reference/engine/classes/CollectionService) will be destroyed after staying still for a couple minutes. Anything with the `Respawn` Tag will respawn when removed. Important props should have both tags so they respawn if they get lost and abandoned in a hole.

<img width="205" alt="image" src="https://github.com/BouyertheDestroyer/BIRDmod/assets/150331530/bf22cd68-4e6b-4621-94dd-e1fe9e5b2ab9">

## Fire

Ignite a part by calling `game.ServerScriptService.Fire.ManuallyIgnite:Fire(part)`.

<img width="629" alt="image" src="https://github.com/BouyertheDestroyer/BIRDmod/assets/150331530/67bcaf7a-82c2-4bd4-bd6a-26f6160d87c3">

When a part ignites, two things happen:
1. A StringValue named "FireTag" gets inserted into the part. When the fire extinguishes, it is removed.
2. Any BindableEvent named "FireUpdate" in the part or the part's Parent will fire with a `true` argument. When the fire extinguishes, it will fire with `false`.

<img width="157" alt="image" src="https://github.com/BouyertheDestroyer/BIRDmod/assets/150331530/f89cbf97-09ed-478c-85e3-28e05300f378">
