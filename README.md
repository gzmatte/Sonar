# Steel Series Sonar - Debloater
This batch disables outputs and removes SteelSeries. [^1]
[^1]:U need to re-install Sonar if u need to modify any in-app setting.


#### 1. Install Sonar, configurate the app & microphone (in app).
#### 2. [**Download Bat**](https://github.com/gzmatte/sonar/releases/download/1/SS-Debloat.bat)
#### 3. Open the .bat and UALÁ!




</br>





</br>


------------------------

## TROUBLESHOOTING

If u have any problem with the outputs, Edit the "Sonar.bat" in desktop.

</br>

#### Incorrect Sound output.
```
:: This line sets your speaker after the bat.
:: Replace "Speakers" with your favorite Output Name.

SoundVolumeView.exe /SetDefault "Speakers"
```
</br>

#### Outputs not being disabled.
```
:: Replace the name of the outputs you want to disable.

SoundVolumeView.exe /Disable "SteelSeries Sonar - Aux"
SoundVolumeView.exe /Disable "SteelSeries Sonar - Gaming"
SoundVolumeView.exe /Disable "SteelSeries Sonar - Media"
SoundVolumeView.exe /Disable "SteelSeries Sonar - Chat"
SoundVolumeView.exe /Disable "SteelSeries Sonar - Stream"
```

You can check the name of your outputs in the Windows Sound panel, or just run mmsys.cpl


