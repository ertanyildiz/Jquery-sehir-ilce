# Jquery ile şehirler ve ilçeler
JQuery ile şehirleri ve seçilen şehire göre ilçeleri getiren script


#### <i class="icon-file"></i> Kullanımı:
  

  script'i sayfaya dahil edin
   

    <script src="SehirIlce_Helper.min.js"></script>

**select** elementini form tag'inin arasına yazın (Şehir)

    <select id="countries_states1" name="sehir"  class="form-control bfh-countries" data-country="35" ></select>
**select** elementini form tag'inin arasına yazın (İlçe)

    <select class="form-control bfh-states" name="ilce"  data-country="countries_states1" data-state="Aliağa"></select>

**select** option attribute açıklamaları:

Attribute     | Açıklama
-------- | ---
country | 2 harfli ülke kodu. Şehir seçimi için kullanılır. blank false is boş olamaz. default :''
available    | Seçili şehirleri getirir. Virgüllere ayırarak şehir kodu girilir. Default: ''
blank     |Boolean. Boş select option. Default: true


**Not:** select elementi **<form>** tag'leri arasına yazılmazsa script çalışmayacaktır.

script'in orjinal repo'su: https://github.com/winmarkltd/BootstrapFormHelpers
