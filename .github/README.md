<!-- TITLE -->
<h2 align="center">a mod for Team Fortress 2 to play random sounds on kill</h2>
<div align="center">

[![Download](https://img.shields.io/github/downloads/BluestoneDE/random_killsounds/total.svg?style=for-the-badge&label=download&color=green&logo=DocuSign&logoColor=white)][download-link]
[![Issues](https://img.shields.io/github/issues-raw/BluestoneDE/random_killsounds?color=orange&logo=windows%20terminal&style=for-the-badge)][issues]
[![Creator](https://img.shields.io/github/followers/BluestoneDE?color=blue&label=_Bluestone_&logo=github&style=for-the-badge)](https://github.com/BluestoneDE)

[![banner](https://repository-images.githubusercontent.com/506568989/4796ff15-63af-4aed-aa8f-892696eb2328)][download-link]

</div>

# Installation
1. Download the latest version of the mod [here on GitHub][download-link].
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
If there are any specific problems, please create a [bug report][report] on the [issues tab][issues].

# Optional
You can play the same sounds **on hit** too.
1. Enable ***Play a hit sound everytime you injure an enemy*** in the **Advanced Options**
2. Select ***Percussion*** as hit sound.

If you have problems with the dropdown, you can use this command:
```cpp
tf_dingalingaling_effect "3"
```

<!-- LINKS -->
[download-link]: https://github.com/BluestoneDE/random_killsounds/releases/latest/download/270_random_killsounds.vpk
[report]: https://github.com/BluestoneDE/random_killsounds/issues/new?template=bug_report.md
[issues]: https://github.com/BluestoneDE/random_killsounds/issues
