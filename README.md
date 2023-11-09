# BIRDmod

Run custom mods in BIRD VIP servers.

Run a mod by chatting "!run `assetId`". For example, chat "!run 15304569888" to spawn zombies.

## Creating a Mod

Open [bird-mod-template.rbxl](https://github.com/BouyertheDestroyer/BIRDmod/raw/main/bird-mod-template.rbxl) in Roblox Studio. This is a limited copy of the map with a sample mod.

Find MainModule in the Workspace. It contains a bunch of zombie Models. You can delete these and add your own Models. They must be parented under MainModule.

<img width="1667" alt="image" src="https://github.com/JoeBrosnihan/BIRDmod/assets/9636197/89b34c6b-cd17-4117-827e-3c94e2b6e8bf">

MainModule has some code which takes its children and adds them to the Workspace. Running the mod will run MainModule's code. You can replace this with your own code if you like.

## Publishing the Mod

Select MainModule, right click, and choose `Save to Roblox...`. Do not change MainModule's name or this will break.

<img width="420" alt="image" src="https://github.com/JoeBrosnihan/BIRDmod/assets/9636197/658de4a7-e329-43df-87c9-2cf27338fd24">

You'll see a publish window. Here it's ok to publish the mod with whatever Title and Description you want. Click to enable `Distribute on Marketplace`.

<img width="929" alt="image" src="https://github.com/JoeBrosnihan/BIRDmod/assets/9636197/c338a9eb-bf10-4587-91ba-94bb8f6f2e70">

Once you publish the asset, copy the number shown in the confirmation window. This is the asset's id which is needed to load the mod.

<img width="352" alt="image" src="https://github.com/JoeBrosnihan/BIRDmod/assets/9636197/71c61ea9-6559-4276-b17e-141d9d81527f">

Now join a VIP server and chat "!run `assetId`" with your asset id!

<img width="643" alt="image" src="https://github.com/JoeBrosnihan/BIRDmod/assets/9636197/93f2d4e5-483f-4441-9b4d-0f713880f9ee">
