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