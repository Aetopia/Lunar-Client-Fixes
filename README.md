# Lunar-Client-Fixes
![image.png](https://github.com/Aetopia/Lunar-Client-Fixes/blob/main/lunar-client.png)  
A repository containing fixes for various Lunar Client problems.

## Issues and Fixes
### General

1. <b>Issue:</b> Cannot not use my MS Account in Lunar Client due to my account being under 18 years of age.  
   <b>Solution:</b> 
   > Change your account birthdate to something like `1/1/2000`.
   
2. <b>Issue:</b> Java VM crash upon launch.  
   <b>Solutions:</b> 
    > 1. Change your DNS to either Google DNS, Cloudflare DNS or OpenDNS and then attempt to launch Lunar Client.  
    > 2. Install your desired LC version via the official Minecraft Launcher and then use Lunar Client.

3. <b>Issue:</b> Lunar Client is not using my NVIDIA GPU.  
   <b>Solution:</b> 
   > Go `%USERPROFILE%\.lunarclient\jre\zulu16.30.15-ca-fx-jre16.0.1-win_x64\bin` and set `javaw.exe` to use your NVIDIA GPU in the NVIDIA Control Panel.
### Performance

1. <b>Issue:</b> FPS lowered as compared to raw Optifine.  
   <b>Solution:</b> 
   > Disable Menu Blur, disable resource intensive and useless mods and set all of Lunar Client's performance options to lowest.
   
2. <b>Issue:</b> Lunar Client is using too much memory!  
   <b>Solutions:</b>  
   > 1. Decrease the amount of allocated RAM to Lunar Client.
   > 2. Use [Lunar Client Lite](https://github.com/Aetopia/Lunar-Client-Lite-Launcher)'s `JVM Arguments` feature to control the memory management of Lunar Client.

3. <b>Issue:</b> Lunar Client freezes upon startup!  
   <b>Solution:</b>  
   > Enable `Disable Cosmetic Textures` within [Lunar Client Lite](https://github.com/Aetopia/Lunar-Client-Lite-Launcher)'s Options.
   
   
