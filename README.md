<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1 align="center">
        <img src="https://github.com/Nightro-Fx/Performance-FastFlags/blob/main/img/Sober.png" width="40" alt="Logo"/> 
         Sober Fast Flags For Better Graphics
    </h1>
  





# Info
Sober, The Linux version of Roblox which allows the Linux community to enjoy games despite the lack of compatibility Linux has. this repository is used to make sober have best graphics than the default

#### ⚠️ DISCLAIMER  
FastFlags should **never** be used for hacking. These flags are strictly intended for FPS boosting and ping stabilization. If frustration over skill issues is driving you to consider hacking, it might be best to stay away from competitive games where you’re outplayed by genuine players. Please don’t harm the Linux community with selfish behavior.



# Getting Started
First we need to locate your _config.json_
- Make sure _Show Hidden File_ is toggled on (CTRL + H)
- Your config.json is located at `~/.var/app/org.vinegarhq.Sober/config/sober`
- We run: `xdg-open ~/.var/app/org.vinegarhq.Sober/config/sober/config.json`
- OR We can run `nano ~/.var/app/org.vinegarhq.Sober/config/sober/config.json`
-Can you find a ready-made version [here](https://github.com/Kosurs/High-Graphics-Sober-Fast-Flags-/blob/main/HQconfigs.json)
# First FFLag

###### Better Fps Unlock 
```json
"DFIntTaskSchedulerTargetFps": "29383" ,
"FFlagGameBasicSettingsFramerateCap5": "False" ,
"FFlagTaskSchedulerLimitTargetFpsTo2402": "False"
```

###### Occlusion Culling (it can came `False` by default)
```json
 "DFFlagUseVisBugChecks": "True",
```
###### Roblox futuristic lighting (phase3)
```json
   "FFlagDebugForceFutureIsBrightPhase3": "True",
```
###### Better Textures Quality (max: 3)
```json
"DFIntTextureQualityOverride": "3",
```
###### Better Camera Rendering (max: 3)
```json
"DFIntDebugRestrictGCDistance": "3"
```
###### GPU Culling
```json
"FFlagFastGPULightCulling3": "True",
```


