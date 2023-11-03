## Steel Series Sonar - Debloater
### This batch disables outputs and removes SteelSeries.
> U need to re-install if u need to modify any settings again.

------------------------

#### 1. Install Sonar, configurate the app & microphone (in app).
#### 2. [**Download Bat**](https://github.com/gzmatte/sonar/releases/download/1/SS-Debloat.bat)
#### 3. Open the .bat and UALÁ!



</br>


> If u have any problems like:
> - After the bat the output isn't correct.
> - Outputs not being disabled.
>
> Edit the "Sonar.bat" in desktop.
```
:: Replace "Speakers" with your Default Sound Device Name.

SoundVolumeView.exe /SetDefault "Speakers"
```

```
:: If not works, replace the name of the outputs here:

SoundVolumeView.exe /Disable "SteelSeries Sonar - Aux"
SoundVolumeView.exe /Disable "SteelSeries Sonar - Gaming"
SoundVolumeView.exe /Disable "SteelSeries Sonar - Media"
SoundVolumeView.exe /Disable "SteelSeries Sonar - Chat"
SoundVolumeView.exe /Disable "SteelSeries Sonar - Stream"
```
