# JavaScript Palindrom Kontrol Edici 🔄

Bu proje, kullanıcının girdiği bir kelimenin **palindrom** (baştan ve sondan okunuşu aynı olan kelime, örn: "nalan") olup olmadığını kontrol eden temel bir JavaScript algoritması içerir.

Program sadece "Evet" veya "Hayır" demekle kalmaz; kelimenin harflerini baştan ve sondan karşılıklı olarak (ilk harf ile son harf, ikinci harf ile sondan ikinci harf vb.) eşleştirerek kıyaslama adımlarını ekrana yazdırır.

**Projenin İşlevleri:**
* `prompt` aracılığıyla kullanıcıdan dinamik olarak kelime girdisi alır.
* Girilen kelimedeki boşlukları temizler (`trim`) ve büyük/küçük harf duyarlılığını ortadan kaldırır (`toLowerCase`).
* Kelimenin uzunluğunun yarısına kadar (`Math.floor(len / 2)`) dönen bir `for` döngüsü ile simetrik harf kıyaslaması yapar.
* Tek harfli merkezleri (tek sayıda harfe sahip kelimelerin tam ortasındaki harf) başarıyla tespit edip gösterir.
* Kıyaslama adımlarını ve final sonucunu HTML DOM içerisindeki bir `div` elementine satır satır yazdırır.

**Kullanılan Teknolojiler:**
* HTML
* CSS
* Vanilla JavaScript (Saf JS)
