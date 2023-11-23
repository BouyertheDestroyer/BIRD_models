# BIRDmod

Import Models and Scripts from Roblox Studio to BIRD private servers.

Run a mod by chatting "!run `assetId`". For example, chat "!run 15304569888" to spawn zombies.

## Creating a Mod

Open [bird-mod-template.rbxl](https://github.com/BouyertheDestroyer/BIRDmod/raw/main/bird-mod-template.rbxl) in Roblox Studio. This is a limited copy of the map with a sample mod.

Find MainModule in the Workspace. It contains a bunch of zombies, a flashlight, and a balloon.

<img width="1533" alt="image" src="https://github.com/BouyertheDestroyer/BIRDmod/assets/150331530/b0435304-29fd-4303-a159-a20f5a0c2eec">

You can add, change, or remove anything you want from MainModule. For example, you can add a McDonalds, HD Admin commands, and even your own Scripts. When the mod runs, everything parented under MainModule will get inserted into the Workspace in BIRD.

<img width="1273" alt="image" src="https://github.com/BouyertheDestroyer/BIRDmod/assets/150331530/5fd32569-4b71-4f31-af56-ac35e88c0268">

## Publishing the Mod

Select MainModule, right click, and choose `Save to Roblox...`. Do not change MainModule's Name or this will break.

<img width="400" alt="image" src="https://github.com/BouyertheDestroyer/BIRDmod/assets/150331530/f02deca7-2ef8-4670-8b7b-575e52ec74bc">
<img  width="300" alt="image" src="https://github.com/BouyertheDestroyer/BIRDmod/assets/150331530/37d615ea-dcb0-468a-97e9-3203c94bedce">

You'll see a publish window. Set whatever Title and Description you like. Make sure `Distribute on Marketplace` is enabled.

<img width="300" alt="image" src="https://github.com/BouyertheDestroyer/BIRDmod/assets/150331530/813c240e-d07d-448f-b994-94e0f8582c89">

Once you publish the asset, copy the number shown in the confirmation window. This is the asset's id which is needed to load the mod.

<img width="300" alt="image" src="https://github.com/BouyertheDestroyer/BIRDmod/assets/150331530/91436685-238d-4cc0-a8d5-b56432d41ea0">

Now join a private server, open the mod manager, create a mod and edit it.

![image](https://github.com/BouyertheDestroyer/BIRDmod/assets/150331530/68c880f0-e86c-48d0-8ec5-db4827c73444)

Paste the assetId and click the check mark. Here you can also change the mod title, description, thumbnail image asset id, and whether your mod is publicly shared with other players.

![image](https://github.com/BouyertheDestroyer/BIRDmod/assets/150331530/ed067008-e223-49a5-a9fa-7e89b044ec78)

Press the Play button to run your mod.

<img width="1008" alt="image" src="https://github.com/BouyertheDestroyer/BIRDmod/assets/150331530/6a6735ba-1e13-46b4-b0cb-bf4db7e3761a">

## BIRD Systems

BIRD has systems that add functionality and interaction. See ![BIRDsystems](BIRDsystems.md) to make mods that interact with bird grabbing, squawking, fire, prop respawning, and more.

<img width="629" alt="image" src="https://github.com/BouyertheDestroyer/BIRDmod/assets/150331530/67bcaf7a-82c2-4bd4-bd6a-26f6160d87c3">
