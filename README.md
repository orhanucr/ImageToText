# ImageToText
 Application to detect the text in the picture and convert it to text file.
 The images of the pages are in the ImageToText Pages Images folder.
 
#-----------------#

 	//Kameradan çekilen bir fotoğrafta ki yada galeriden seçilen bir fotoğrafta ki metinleri algılayıp text
	dosyası halinde çıkartıyor.
	
	//Bu textleri speaker aracılığı ile kullanıcıya dinleme imkanı veriyor.
	
	//Uygulama içerisinde çoklu dil destekli translate mevcut.
	
	//Uygulamanın kendi not defteri mevcut(Room database).
	
	//Kullanıcı ses ile de not ekleyebilir.
	
 
 #------------------#
 
    //text algılama
    implementation 'com.google.android.gms:play-services-mlkit-text-recognition:18.0.2'

    //Firebase
    implementation platform('com.google.firebase:firebase-bom:31.0.2')
    implementation 'com.google.firebase:firebase-analytics'
    implementation 'com.google.firebase:firebase-core:21.1.1'
    implementation 'com.google.mlkit:translate:17.0.1'

    testImplementation 'junit:junit:4.13.2'
    androidTestImplementation 'androidx.test.ext:junit:1.1.3'
    androidTestImplementation 'androidx.test.espresso:espresso-core:3.4.0'

    //Room
    implementation "androidx.room:room-runtime:2.4.3"
    annotationProcessor "androidx.room:room-compiler:2.4.3"

    //Recyclerview
    implementation "androidx.recyclerview:recyclerview:1.2.1"

    //Scalable Size Unit (Support for different screen sizes)
    implementation "com.intuit.sdp:sdp-android:1.0.6"
    implementation "com.intuit.ssp:ssp-android:1.0.6"

    //Rounded ImageView
    implementation "com.makeramen:roundedimageview:2.3.0"
    
    //Translate
    import com.google.mlkit.common.model.DownloadConditions;
    import com.google.mlkit.nl.translate.TranslateLanguage;
    import com.google.mlkit.nl.translate.Translation;
    import com.google.mlkit.nl.translate.Translator;
    import com.google.mlkit.nl.translate.TranslatorOptions;
 
    //Speech
    import android.speech.RecognizerIntent;

    //Speaker
    import android.speech.tts.TextToSpeech;
    

<h2>Uygulama Ekran Görüntüleri</h2>
<p float="left">
  <img src=https://github.com/orhanucr/ImageToText/assets/100219838/6dfcafdd-9fd0-47d3-95c7-3d6f57598ad6 width="27%" />
  <img src=https://github.com/orhanucr/ImageToText/assets/100219838/8f7dcf48-2afd-4ced-b728-52d550f7bcfd width="27%" />
  <img src=https://github.com/orhanucr/ImageToText/assets/100219838/b231e913-dae7-4462-9b37-2e0d0fd129d2 width="27%" />
  <img src=https://github.com/orhanucr/ImageToText/assets/100219838/de188a07-df88-4ef8-9492-ec8f8ca3f3d4 width="27%" />
  <img src=https://github.com/orhanucr/ImageToText/assets/100219838/2a38fcd2-6a25-490b-9e01-abbc49036bba width="27%" />
  <img src=https://github.com/orhanucr/ImageToText/assets/100219838/72cc6a0e-2e9d-46a7-ac72-fabfbed3024b width="27%" />
</p>




