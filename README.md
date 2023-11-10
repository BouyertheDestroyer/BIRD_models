# BIRDmod

Run custom mods in BIRD private servers.

Run a mod by chatting "!run `assetId`". For example, chat "!run 15304569888" to spawn zombies.

## Creating a Mod

Open [bird-mod-template.rbxl](https://github.com/BouyertheDestroyer/BIRDmod/raw/main/bird-mod-template.rbxl) in Roblox Studio. This is a limited copy of the map with a sample mod.

Find MainModule in the Workspace. It contains a bunch of zombies, a flashlight, and a balloon.

<img width="1533" alt="image" src="https://github.com/BouyertheDestroyer/BIRDmod/assets/150331530/b0435304-29fd-4303-a159-a20f5a0c2eec">

You can add, change, or remove anything you want from MainModule. For example, you can add a McDonalds, HD Admin commands, and even your own Scripts. When the mod runs, everything parented under MainModule will get inserted into the Workspace in BIRD.

<img width="1273" alt="image" src="https://github.com/BouyertheDestroyer/BIRDmod/assets/150331530/5fd32569-4b71-4f31-af56-ac35e88c0268">

## Publishing the Mod

Select MainModule, right click, and choose `Save to Roblox...`. Do not change MainModule's Name or this will break.

<img width="438" alt="image" src="https://github.com/BouyertheDestroyer/BIRDmod/assets/150331530/f02deca7-2ef8-4670-8b7b-575e52ec74bc">
<img width="303" alt="image" src="https://github.com/BouyertheDestroyer/BIRDmod/assets/150331530/37d615ea-dcb0-468a-97e9-3203c94bedce">

You'll see a publish window. Set whatever Title and Description you like. Make sure `Distribute on Marketplace` is enabled.

<img width="930" alt="image" src="https://github.com/BouyertheDestroyer/BIRDmod/assets/150331530/813c240e-d07d-448f-b994-94e0f8582c89">

Once you publish the asset, copy the number shown in the confirmation window. This is the asset's id which is needed to load the mod.

<img width="389" alt="image" src="https://github.com/BouyertheDestroyer/BIRDmod/assets/150331530/91436685-238d-4cc0-a8d5-b56432d41ea0">

Now join a private server and chat "!run `assetId`" with your asset id and the mod will run.

<img width="1008" alt="image" src="https://github.com/BouyertheDestroyer/BIRDmod/assets/150331530/6a6735ba-1e13-46b4-b0cb-bf4db7e3761a">
