# Stock Fingerprint for Shamrock
Shamrock cihazları için Stock Fingerprint ayarlama modülü.  
Bu Magisk modülü sayesinde Stock ROM Fingerprint'e(cihaz imzasına) sahip olabilir ve Google'ın SafetyNet kontrolünden geçebilirsiniz.

## Uyarı
* Modülün işe yaraması ve SafetyNet'in başarılı olması için basicIntegrity kontrolünün de başarılı olması gerekmektedir. Aksi takdirde hiçbir şekilde ctsProfile kontrolü başarılı olmayacaktır.
* Her custom ROM'da işe yaramayabilir. LineageOS 14.1 2018 Ağustos sürümü ile test edilmiştir ve Netflix bile kullanabilirsiniz.

## Bilinen Sorunlar
* Bazı ROM'larda Google Play Hizmetleri tarafından sistem güncellemesinin tetiklenmesine neden olabilir fakat sistemi asla güncelleyemez. Sadece gitmeyen sinir bozucu bir bildirim bırakır :p

## Kurulum
1. Magisk'in Hide özelliğini açıp MagiskHide menüsünden com.android.vending, com.google.android.gms ve com.google.android.gsf paket adını içeren bütün uygulamar için gizlemeyi aktif edin.
2. Modülü yükleyin.
3. İlk aşamada bahsedilen uygulamaları android ayarlarından durdurup verilerini temizleyin ve hemen ardından telefonu yeniden başlatın.
4. basicIntegrity kontrolü başarılıysa muhtemelen ctsProfile ve SafetyNet de tamamen başarılı olacaktır. Modülü kaldırmak için hiçbir ekstra işleme gerek yoktur ve sisteminizde hiçbir kalıcı iz bırakmaz.
