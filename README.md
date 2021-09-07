# Thinkpad Helix Hackitntosh

![Capture d’écran 2021-09-07 à 2 51 47 PM](https://user-images.githubusercontent.com/76212533/132409347-6f81b2fe-140f-4830-9ad9-5a9b480e361f.png)

Finally the last of the PCs I own is fully working

IT TOOK ME FOREVER TO FIX AUDIO ON THIS THING (had to DSDT patch it)

But yeah everything as far as i can see it works (BT, WiFi, iServices, Sidecar {with featureunlock.kext},Audio as pointed out by that statement on top which includes the terrible internal speakers and the combo jack actually working (mic and sound work) only one of the 2 cameras work but lets be honest, the people that use the rear camera on their hybrids are freaks (and by not working i mean its detected by the OS but its just a black image, the front one works just fine)

I've tested this build on both Monterey. (B1,B2,B3,B4,B5, currently updating to B6) (Patched HD4000 accel cuz rip ivy bridge iGPUs  https://github.com/dortania/OpenCore-Legacy-Patcher <--------- the only legacy mac patcher {that doesnt look up smbios info just hardware} that has HD4000 accel patches for monterey, DO NOTE THAT THEY DO NOT PROVIDE SUPPORT FOR HACKINTOSHES, SO IF YOU DECIDE TO USE MONTEREY, YOU'RE ON YOUR OWN in regards to that) 

Big sur (11.3 up to 11.4 but an 11.5.2 installer boots just fine so versions post 11.4 should work just fine), so far monterey runs fine, but the lack of ram really impeeds it being usable when running multiple apps (lockups and visible lag, on both big sur and monterey)

My model is equipped with an i5-3337U clocked @1.8ghz, 4gb of ram, Intel Centrino Advanced wlan, ALC269VC

I rescued this thing from an e-waste facility, came without a charger, and the screen was terribly cracked, bc of that i didnt include touchscreen fixes (I like my fingers not cut to shreds lol) 

![IMG_2290](https://user-images.githubusercontent.com/76212533/132410536-d33f82f0-ea2b-4953-b93f-5f179d7ba565.JPG)
(Machine Running big sur with working battery reporting)


Credits

@Acidanthera for Opencore and the kexts required for this to work

@Rehabman for the DSDT patching guide, aswell as the patches themselves

@Wolfie for showing me da wae on DSDT patching

@Dortania for Opencore Legacy Patcher

EduCovas for HD4000 patches 

