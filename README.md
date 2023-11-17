# SteelSeries Sonar debloater

This disables Steel-Series outputs and removes all SteelSeries. [^1]
[^1]:Re-install Sonar if u need to modify any in-app setting.


#### 1. Install Sonar, configurate the app & microphone section.
#### 2. [**Download**](https://github.com/gzmatte/sonar/releases/download/1/SS-Debloat.bat)
#### 3. Open the batch and UALÁ!




</br>





</br>


------------------------

## TROUBLESHOOTING

If u have any of the following problems, edit the "Sonar.bat" in desktop.

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

You can check the name of your outputs in the Windows Sound panel (just run mmsys.cpl)


