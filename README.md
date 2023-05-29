# Image To Text
Fotoğraflarda ki metni algılayan ve metni bir metin dosyasına dönüştüren bir uygulama geliştirilmiştir. Uygulama, kullanıcının kamera ile çektiği veya galeriden seçtiği bir fotoğraftaki metni algılayarak metin dosyası olarak kaydetmektedir. Ayrıca, metinleri kullanıcıya dinleme imkanı sağlayan bir hoparlör özelliğiyle sunmaktadır. Uygulama, çoklu dil desteğiyle çeviri yapabilme özelliğine de sahiptir, böylece metinleri farklı dillere çevirebilirsiniz. Uygulamada ayrıca kendi not defteri bulunmaktadır ve bu notlar Room veritabanı kullanılarak saklanmaktadır. Kullanıcı ayrıca metin eklemek için sesli giriş yapma seçeneğine de sahiptir.
	
 
# Dependencies

- [com.google.android.gms:play-services-mlkit-text-recognition:18.0.2](https://developers.google.com/android/guides/releases#november_10_2022)
- [com.google.firebase:firebase-bom:31.0.2](https://firebase.google.com/support/release-notes/android#latest_sdk_versions)
- [com.google.firebase:firebase-analytics](https://firebase.google.com/support/release-notes/android#latest_sdk_versions)
- [com.google.firebase:firebase-core:21.1.1](https://firebase.google.com/support/release-notes/android#latest_sdk_versions)
- [com.google.mlkit:translate:17.0.1](https://developers.google.com/ml-kit/release-notes/android#17.0.0)
- [junit:junit:4.13.2](https://junit.org/junit4/)
- [androidx.test.ext:junit:1.1.3](https://developer.android.com/jetpack/androidx/releases/test#1.1.3)
- [androidx.test.espresso:espresso-core:3.4.0](https://developer.android.com/jetpack/androidx/releases/test#3.4.0)
- [androidx.room:room-runtime:2.4.3](https://developer.android.com/jetpack/androidx/releases/room#2.4.3)
- [androidx.room:room-compiler:2.4.3](https://developer.android.com/jetpack/androidx/releases/room#2.4.3)
- [androidx.recyclerview:recyclerview:1.2.1](https://developer.android.com/jetpack/androidx/releases/recyclerview#1.2.1)
- [com.intuit.sdp:sdp-android:1.0.6](https://github.com/intuit/sdp)
- [com.intuit.ssp:ssp-android:1.0.6](https://github.com/intuit/ssp)
- [com.makeramen:roundedimageview:2.3.0](https://github.com/makeramen/roundedimageview)


<h2>Translate</h2>

<h3>Import</h3>

<pre><code>import com.google.mlkit.common.model.DownloadConditions;
import com.google.mlkit.nl.translate.TranslateLanguage;
import com.google.mlkit.nl.translate.Translation;
import com.google.mlkit.nl.translate.Translator;
import com.google.mlkit.nl.translate.TranslatorOptions;
</code></pre>

<h2>Speech</h2>

<h3>Import</h3>

<pre><code>import android.speech.RecognizerIntent;
</code></pre>

<h2>Speaker</h2>

<h3>Import</h3>

<pre><code>import android.speech.tts.TextToSpeech;
</code></pre>
    

<h2>Application Screenshots</h2>
<p float="left">
  <img src=https://github.com/orhanucr/ImageToText/assets/100219838/6dfcafdd-9fd0-47d3-95c7-3d6f57598ad6 width="27%" />
  <img src=https://github.com/orhanucr/ImageToText/assets/100219838/8f7dcf48-2afd-4ced-b728-52d550f7bcfd width="27%" />
  <img src=https://github.com/orhanucr/ImageToText/assets/100219838/b231e913-dae7-4462-9b37-2e0d0fd129d2 width="27%" />
  <img src=https://github.com/orhanucr/ImageToText/assets/100219838/de188a07-df88-4ef8-9492-ec8f8ca3f3d4 width="27%" />
  <img src=https://github.com/orhanucr/ImageToText/assets/100219838/2a38fcd2-6a25-490b-9e01-abbc49036bba width="27%" />
  <img src=https://github.com/orhanucr/ImageToText/assets/100219838/72cc6a0e-2e9d-46a7-ac72-fabfbed3024b width="27%" />
</p>




