# Steel Series Sonar - Debloater
This batch disables outputs and removes SteelSeries. [^1]
[^1]:U need to re-install if u need to modify any setting again.

------------------------

#### 1. Install Sonar, configurate the app & microphone (in app).
#### 2. [**Download Bat**](https://github.com/gzmatte/sonar/releases/download/1/SS-Debloat.bat)
#### 3. Open the .bat and UALÁ!

</br>

## TROUBLESHOOTING

1. Edit the "Sonar.bat" in desktop.
2. Find your problem and save the bat.

#### Incorrect Sound output
```
:: Replace "Speakers" with your Preferred Sound Device.

SoundVolumeView.exe /SetDefault "Speakers"
```

#### Outputs not being disabled.
```
:: Replace the name of the outputs you want to disable in this section of the bat:

SoundVolumeView.exe /Disable "SteelSeries Sonar - Aux"
SoundVolumeView.exe /Disable "SteelSeries Sonar - Gaming"
SoundVolumeView.exe /Disable "SteelSeries Sonar - Media"
SoundVolumeView.exe /Disable "SteelSeries Sonar - Chat"
SoundVolumeView.exe /Disable "SteelSeries Sonar - Stream"
```
