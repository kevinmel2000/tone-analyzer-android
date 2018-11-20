[![](https://img.shields.io/badge/IBM%20Cloud-powered-blue.svg)](https://bluemix.net)
[![](https://img.shields.io/badge/platform-android-lightgrey.svg?style=flat)](https://developer.android.com/index.html)

# Create an Android application in Java which analyzes the emotion and tone of natural language

The IBM Cloud Mobile Starter for Watson Tone Analyzer showcases the Tone Analyzer service from Watson and gives you integration points for each of the IBM Cloud Mobile services.

## Requirements

* An [IBM Cloud](http://bluemix.net) account
* [Android Studio](https://developer.android.com/studio/index.html)
* A [Tone Analyzer](https://console.ng.bluemix.net/catalog/services/tone-analyzer/) service was provisioned for you when you created this project on IBM Cloud.

## Configuration

* Open the project in Android Studio and perform a Gradle Sync.
* No further configuration is needed. Your unique Tone Analyzer credentials were injected into your mobile app during generation.

## Run

* You can now build and run the application from Android Studio!

![ToneAnalyzerAndroid](README_Images/ToneAnalyzerAndroid.png) ![ToneAnalyzerAndroidClicked](README_Images/ToneAnalyzerAndroidClicked.png)

The application allows you to use the Watson Tone Analyzer service to analyze text. Tone Analyzer leverages cognitive linguistic analysis to identify a variety of tones at both the sentence and document level. This insight can then used to refine and improve communications. 

Enter text in the input text box and then click the Tone Analyzer button to see the results. The results will be shown under each category after the text has been analyzed. The tag visability will change based on the percentage returned from Watson, but you can click on tag directly to see the exact percentage.

## License

[Apache 2.0](LICENSE)
