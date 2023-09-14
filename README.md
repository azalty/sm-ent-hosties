# Check out [Hosties+](https://github.com/azalty/sm-hosties-plus)!
I have finally decided to make my own Hosties fork, after seeing that old maintainers (dataviruset, Entity/Sples1) weren't going to maintain the project anymore.\
I have also tried contacting K4ryuu that said they were updating Hosties, but that was over a year ago, and no progress was shown on GitHub, Discord, or anywhere else. I didn't get any answer from them.

Due to [personal reasons and worries](https://forums.alliedmods.net/showthread.php?p=2779428#post2779428) about the "KitsuneLab" group's motivations, which were the developers of ENT_Hosties, I have decided to create a fork called [Hosties+](https://github.com/azalty/sm-hosties-plus), instead of simply contributing to the existing ENT_Hosties project.

My work on Hosties+ is, and will always be free to re-use, modify, fork..., in accordance with the GNU GPL 3 license.

---

# sm-ent-hosties
A reupload of ENT_Hosties by Entity/Sples1\
[Original AlliedModders thread](https://forums.alliedmods.net/showthread.php?t=307634)

This is the 4.2.3b version. Some LRs are bugged.\
Pull requests and future maintaining of the project is appreciated.

Some files might have been altered and the plugin might not compile as is due to outdated code/syntax or me messing with some files.\
**I cannot guarantee that this is the original untouched code!** (although based on their timestamp, they probably are original since they all share the same)

## Moral point of view
This is reuploaded without the creator's consent (Entity/Sples1).\
This version **was** available publicly on AlliedModders and on the creator's discord server.\
I participated in the project, helping by reporting bugs.

The license, GNU GPL 3, legally allows this reupload, even if the creator doesn't want to.

Thanks Entity for this plugin. It's sad to see you go from the AlliedModders community to do private requests only.\
Free and open-source software is what makes the SourceMod community live. It benefits everybody.

## Known bugs
- The "anti-cheat" feature is bugged in a lot of LRs.
- The plugin uses SMLib to strip weapons, which is outdated and causes the players to gain tasers when using the Custom Weapon Skin module for Zephyrus store. It might happen with other Custom Weapon Skins plugins as well.
  - UPDATE: The real cause is unknown as of now. I'm still trying to patch ENT_Hosties. In the meantime, I made a simple fix [here](https://github.com/azalty/sm-ent-hosties-knife-fix).

## Improvements (compared to the original Hosties)
- Crashes related to tasers were fixed
- Varius bug fixes
- New features (check the changelog in the original AlliedModders thread for more infos)

## Why don't you fix it?
I'll try to fix some things myself to continue the project, but I'm doing other private things for my servers as well.\
If this plugin gets interest, I might start working on it.

If and when enough work is done, I'll archive this repo and start a new Hosties v5, because I don't want Entity to be associated to a fork they didn't agree to.\
All the creators will stay referenced as authors of the plugin though.\
Thanks all for making jailbreak/ba_jail a thing!
