If you use Sonar, you notice that you can't disable the sonar outputs in app & if you only use this for the microphone, it's frustrating.

### ★ [Download here](https://github.com/gzmatte/sonar/releases/download/1/Sonar.bat)

★ Once Sonar starts, use the bat. It will automatically disable additional playback outputs.

</br>

> Not working? Edit the batch file and Ualá!

```
:: Replace "Speakers" with your Default Sound Device Name.

SoundVolumeView.exe /SetDefault "Speakers"

If keeps failing, check the output names in the bat with your installed ones.
```
