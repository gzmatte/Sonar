## NEW VERSIONS OR W11 MAY NOT START STEEL SERIES.
YOU NEED TO START STEELSERIES FROM THE ORIGINAL SHORTCUT AND AFTER THAT, START THE BATCH.

---

**If u have any of the following problems, edit the "Sonar.bat" in desktop.**

</br>

#### Incorrect Sound output.
```
:: This line sets the speaker you want to use.
:: Replace "Speakers" with your favorite Output Name.

SoundVolumeView.exe /SetDefault "Speakers"
```
</br>

#### Outputs not being disabled.
```
:: This line disables Sonar unnecessary outputs.
:: Replace the name beetween "" if not working.

SoundVolumeView.exe /Disable "SteelSeries Sonar - Aux"
SoundVolumeView.exe /Disable "SteelSeries Sonar - Gaming"
SoundVolumeView.exe /Disable "SteelSeries Sonar - Media"
SoundVolumeView.exe /Disable "SteelSeries Sonar - Chat"
SoundVolumeView.exe /Disable "SteelSeries Sonar - Stream"
```

</br>


You can check the name of your outputs in the Windows Sound panel (just run mmsys.cpl)
