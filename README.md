# Voice_Converter_with_Koeiromap

## 1. Description
This is a voice converter for Japanese based on the Koeiromap & Koeiro API. You can convert to the selected voice from the text inputed by keyboard and/or your voice. Unfortunately, the free Koeiro API service will end on July 18, 2023.　The demo in this article uses the free Koeiro API service, so I think it will not be available after that date, so it's bad!  

## 2. Operational Environment
- Browser: Microsoft Edge or Google Chrome on Windows 10/11 or Android

Note: The safari and the firefox is not supported.

## 3. Demo
[index.html](https://to-fujita.github.io/Voice_Converter_with_Koeiromap/index.html): This is a voice convert program based on Koeiromap & Koeiro API.
  
<a href="https://to-fujita.github.io/Voice_Converter_with_Koeiromap/index.html"><img src="https://to-fujita.github.io/Images/Voice_Converter_with_Koeiromap.jpg"></a>
  
<a href="https://to-fujita.github.io/Voice_Converter_with_Koeiromap/index.html"><img src="https://to-fujita.github.io/Images/Voice_Converter_with_Koeiromap-01.jpg"></a>

## 4. Details
I have confirmed this program on the Microsoft Edge and Google Chrome on Windows 10/11 or Android.  

### Usage
(1) Please click "index/html" at the "3. Demo" above.  
(2) If you input the text data by the keyboard, please input to the text box by Japanese. After input the "return key", the input text data will be read with the specified voice.  
(3) If you want to convert your voice to specified voice, please click the "音声入力OFF" above. Then, the display will be changed to the "音声入力ON". Afer that, please speak any japanese word, then, the specified voice will be outputted.  
(4) If you change the specified voice, please click the "音声変更", then set the "Voice-x", the "Voice-y" or the "音声スタイル".
(5) The converted voice data is able to save and to load as local file. Please click the "設定", then click the "OTHER OPTIONS". You can save or load the converted voice data as Base64 text data.
  
## 5. History
2023/05/01: Upload the first version.  
2023/05/06: Revised for adding to save and to load the converted data.
  
## 6. Reference
- [Koeiromap & Koeiro](http://koeiromap.rinna.jp/)
- [音声合成ができる「Koeiromap」の情報を調べてみて JavaScript を使って軽く試してみる【2023年4月8日時点】](https://qiita.com/youtoy/items/258ac8ed5313f64402a3)

  
## 7. License
- Programs: MIT
- All of the images, Koeiromap & Koeiro: Please confirm to each author.
  
## 8. Author
[T. Fujita](https://github.com/To-Fujita)
