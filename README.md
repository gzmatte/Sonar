## Steel Series Sonar - Debloater
### This batch disables outputs and removes SteelSeries.
> U need to re-install if u need to modify any settings again.

------------------------

#### 1. Install Sonar, configurate the app & microphone (in app).
#### 2. [**Download Bat**](https://github.com/gzmatte/sonar/releases/download/1/SS-Debloat.bat)
#### 3. Open the .bat and UALÁ!



</br>


#### TROUBLESHOOTING SECTION

Edit the "Sonar.bat" in desktop and click the problem you have:

Outputs not being disabled.[1]

Incorrect Sound output.[2]


``` [1] 
:: Replace "Speakers" with your Preferred Sound Device.

SoundVolumeView.exe /SetDefault "Speakers"
```

</br>


```[2]
:: Replace the name of the outputs in this section of the bat:

SoundVolumeView.exe /Disable "SteelSeries Sonar - Aux"
SoundVolumeView.exe /Disable "SteelSeries Sonar - Gaming"
SoundVolumeView.exe /Disable "SteelSeries Sonar - Media"
SoundVolumeView.exe /Disable "SteelSeries Sonar - Chat"
SoundVolumeView.exe /Disable "SteelSeries Sonar - Stream"
```
