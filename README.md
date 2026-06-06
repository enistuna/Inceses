<img width="1260" height="267" alt="inceses_logo" src="docs\inceses_logo.png" />

# **İnceses - Turkish Phonetic Transcriptor**
*  The phonetic transcriptor  was first written for the [İncesöz](https://github.com/enistuna/Incesoz) project back in 2024 and is now being shared as its own [Python package](https://pypi.org/project/inceses/1.0/) for easier usability. The function was first developed using the **Özgün Koşaner's** lecture notes from the Phonetics class at Dokuz Eylul University's Department of Linguistics. This project may get an update in the future with increased transcription accuracy.

## **Installation**
* To use the Turkish phonetic transciptor, first install the Python package to your file. Feel free to also check out the [PyPI page](https://pypi.org/project/inceses/1.0/).
```
pip install inceses
```

## **How to Use It**
```py
import inceses

transcription = inceses.phonetic_analysis('Enis Tuna ile yemeğe mi gittin?')

print(transcription)
>> "[ ɛnis tʰunα ile jɛme•e mi ɟittʰin? ]"
```
