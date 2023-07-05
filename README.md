--------------------------------------------------------------
target:
<a> elementinde çokça kullanılan attributelerden olan target özniteliği, linke basıldığında linkin nasıl açılacağını gösterir.
target="_blank" olursa link yeni pencerede açılır.
---------------------------------------------------------------
<a href="https://freecatphotoapp.com">
            <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back">
</a>

bu komutla bir resim linke dönüştürülmüştür
---------------------------------------------------------------
HTML YAPISI
<body>
  <header>
    <!-- Başlık ve menü -->
    <h1>ANA BAŞLIK</h1>
  </header>

  <main>
    <!-- Ana içerik -->
    <section>//bölümleri birbirinden ayırmak için kullanılır
        <h2>Önemli Başlık</h2>
        <p>Bu bölümde önemli bir konu hakkında bilgi bulunur.</p>
    </section>

    <section>
        <h2>Diğer Bölüm</h2>
        <p>Bu bölümde farklı bir konu veya içerik yer alabilir.p>
    </section>

  </main>

  <footer>
    <!-- Altbilgi -->
  </footer>
</body>
---------------------------------------------------------------
<ul> etiketi, sırasız listelerin oluşturulmasında yaygın olarak kullanılır. Bu liste türü, öğelerin sıralı bir şekilde numaralandırılmasına gerek olmadığı durumlarda kullanışlıdır. Örneğin, bir ürün listesi veya bir menü öğelerini göstermek için sırasız listeler tercih edilebilir.
itemleri <li> elementi ile yazarız

<ol> de <ul>'ye benzer fakat itemleri sıralı bir şekilde verir
---------------------------------------------------------------
<figure>
  <img src="image.jpg" alt="Resim açıklaması">
  <figcaption>Resim Açıklaması</figcaption>
</figure>

<figure> etiketi, HTML belgesinde medya içeriğini (resim, video, çizim vb.) gruplamak ve etiketlemek için kullanılır. <figcaption> etiketi ise medya içeriğinin açıklamasını veya başlığını temsil eder.

<figure> etiketi, medya içeriğini bir bütün olarak etiketlemek için kullanılır ve belgenin yapısını anlamlandırmada ve erişilebilirlik açısından faydalıdır. Ayrıca, CSS ile de özelleştirilebilir ve stile uygulanabilir.
----------------------------------------------------------------------
<em> elementi paragrafın bir parçasını vurgulamak için kullanılır
<strong>, bazı metinlerin çok önemli veya acil olduğunu belirtmek için kullanılır.
----------------------------------------------------------------------
<form> etiketi, HTML belgesinde kullanıcıdan veri girişi almak veya kullanıcıya bilgi göndermek için kullanılan bir yapısal etikettir.

<action> özniteliği ile verilerin gönderileceği URL'yi belirler. 

<input> bir web formundan veri toplamanın çeşitli yollarını sağlar. İmg öğeleri gibi, giriş öğeleri de kendi kendine kapanır ve kapatma etiketlerine ihtiyaç duymaz.

---->name<----- özniteliği, <input> elementinde kullanılan bir özniteliktir ve form verisi gönderimiyle ilişkilendirilmiş bir isim veya anahtar değerini temsil eder. Bu öznitelik, bir form alanının adını belirtir ve sunucuya verileri gönderirken bu alanı tanımlamak için kullanılır.
Bir form gönderildiğinde, formdaki her bir <input> elementi, name özniteliği ile belirtilen değeri sunucuya iletecektir. Sunucu tarafında, bu değerler form verilerinin işlenmesi veya kaydedilmesi için kullanılabilir.

----> placeholder<-----insanlara bir girdiye ne tür bilgilerin girilmesi gerektiği konusunda ipucu vermek için kullanılır.

---->required<----To prevent a user from submitting your form when required information is missing.There's no need to set a value

---->formda bulunan buton bir özellik vrilmesse formu action özniteliğindeki adrese form bilgilerini gönderir

----inputun altına buton koymama rağmen aynı satırda göründü bunun sebebi ikisininde inline element olmasıdır

----butona tıklandığında varsayılan olarak actiona bilgi gönderir fakat karışıklılıga sebep olmaması için type attributesini submit olarak ayarlamamız gerekir (varsayılan karışıklılığa sebep olabilir)

----You can use radio buttons for questions where you want only one answer out of multiple options.

----label elements are used to help associate the text for an input element with the input element itself
        -----There's another way to associate an input element's text with the element itself. You can nest the text within a label element and add a for attribute with the same value as the input element's id attribute.

----The id attribute is used to identify specific HTML elements. Each id attribute's value must be unique from all other id values for the entire page.

-----To make it so selecting one radio button automatically deselects the other, both buttons must have a name attribute with the same value.

------Since your radio buttons do not have a value attribute, the form data will include indoor-outdoor=on, which is not useful when you have multiple buttons.(inputa value ve name değerlerini form databasede karışıklık çıkarmaması için eklememiz gerekir AYNI ŞEY CHECKBOX İÇİN DE GEÇERLİ)
value değerini kolaylık açısından id ile aynı deper verilir

-----The fieldset element is used to group related inputs and labels together in a web form.(genelde div kullanılır fieldsetin yerine fieldsette varsayılan olarak içeriğe bir sınır ekler)
----The legend element acts as a caption for the content in the fieldset element. It gives users context about what they should enter into that part of the form.

----Forms commonly use checkboxes for questions that may have more than one answer.

------inputa name özniteliği vermek serverin formu daha rahat işlemesine olanak sağlar

-----Checkboxlardan birinin varsayılan olarak seçili olmasını istiyorsak checked özniteliği ekleyebiliriz(radio buton için selected eklemekle aynı şey)

-----a elemnti içinde bulunan metni bir bağlantıya dönüştürür

-----head elementinin içinde bulunan title elementi sayfanın üst kısmında ararma motorunda sayfanın adını gösterir

----- HTML'nin attributesi olan lang elementi sayfanın dilini ifade eder bizim oluşturduğumuz sayfanin dili şu anda ingilizcedir

-----UTF-8 metası içinde hangi karakter setleerini barındıracağını anlatır