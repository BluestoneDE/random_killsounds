<!-- TITLE -->
![banner](https://repository-images.githubusercontent.com/506568989/4796ff15-63af-4aed-aa8f-892696eb2328)
<h2 align="center">a mod for Team Fortress 2 to play random sounds on kill</h2>

# Installation
1. Download the latest version of the mod on [GitHub][download-link].
2. Move the downloaded .vpk file into your `steamapps\common\Team Fortress 2\tf\custom` directory.
3. Enable ***Play a last hit sound when one of your attacks kills an enemy*** in the **Advanced Options**.
4. Select ***Default*** as the last hit sound.

If you have problems with the dropdown, you can use this command:
```cpp
tf_dingalingaling_last_effect "0"
```
# Troubleshooting
You can try resetting all sounds with this console command:
```cpp
snd_restart
```
If there are any specific problems, please create an bug report on the [issues tab](https://github.com/BluestoneDE/random_killsounds/issues/new?template=bug_report.md).

# Optional
You can play the same sounds **on hit** too.
1. Enable ***Play a hit sound everytime you injure an enemy*** in the **Advanced Options**
2. Select ***Percussion*** as hit sound.

If you have problems with the dropdown, you can use this command:
```cpp
tf_dingalingaling_effect "3"
```

<!-- LINKS -->
[download-link]: https://github.com/BluestoneDE/random_killsounds/releases/latest/download/210_random_killsounds.vpk
