<h1>HTML'de Form Oluşturma</h1>
Kullanıcı girdisini toplamak için bir HTML formu kullanılır. Kullanıcı girişi genellikle işlenmek üzere bir sunucuya gönderilir.<br>
Kullanıcı girişi için bir HTML formu oluşturmak için <b>< form></b>öğesi kullanılır. <br>
<ul>
<li><b><i>< form action="register.php"></i></b> Form işleyicisi, giriş verilerini işlemek için bir komut dosyası içeren sunucudaki bir dosyadır.</li>
<li><b><i>< label for="ornek1"></i></b> Etiketi birçok form öğeleri için bir etiket tanımlar. <b>for</b> öğesi içerisine <b>input</b> <i>id</i>'si konumlandırılır.</li>
<li><b><i>< input type="text" id="ornek1" placeholder="Name"></i></b>
<ul>
<li><b>type=""</b> Giriş tipini belirtir. 
<ul>
<li><b>text</b> Tek satırlık bir metin giriş alanı görüntüler</li>
<li><b>radio</b> Bir radyo düğmesi görüntüler (birçok seçenekten birini seçmek için)</li>
<li><b>checkbox</b> Bir onay kutusu görüntüler (birçok seçenekten sıfır veya daha fazlasını seçmek için)</li>
<li><b>submit</b> Gönder düğmesi görüntüler (formu göndermek için)</li>
<li><b>button</b> Tıklanabilir bir düğme görüntüler</li>
<li><b>date</b> Tarih girmek için kullanılır</li>
<li><b>tel</b> Girdi tipi bir <b>telefon</b> olduğunu gösterir.</li>
<li><b>email</b> Girdi tipi bir <b>mail</b> olduğunu gösterir.</li>
<li><b>password</b> Girdi tipi bir <b>şifre</b> olduğunu gösterir.</li>
<li><b>file</b> Forma bir dosya eklemek için kullanılır.</li>
</ul>
</li>
<li><b>id=""</b> Kullanılan yerin kimliğidir. Nasıl ki her kimlik farklıysa her id de farklı olmalıdır.</li>
<li><b>placeholder=""</b> Input içerisinde soluk şeklinde gözükmesini istediğimiz ileti yazılır.</li>
</ul>
</li>
<li><b><i>< textarea name="" id="" cols="30" rows="3"></i></b> Bir metin alanı tanımlar.
<ul><li><b>cols</b> ve <b> rows</b> alanın genişliğini ve yüksekliğini belirtmek için kullanılır.</li></ul>
</li>
<li><b><i>< select id="meslek"></i></b> Öğesi bir açılır listeyi tanımlar
<ul>
<li><b><i>< option></i></b> Elemanlar seçilebilir bir seçenek tanımlar. Varsayılan olarak, açılır listedeki ilk öğe seçilidir. Önceden seçilmiş bir seçeneği tanımlamak için seçeneğe <b><i>selected</i></b> özniteliği ekleyin.
Kullanıcının birden fazla değer seçmesine izin vermek için <b><i>multiple</i></b> özniteliği kullanılır.</li>
</ul>
</li>
<li><b><i>< button type="reset"></i></b> Foruma button eklemek için kullanılır. Buttonun işlevi için <i>type</i> özelliğinde belirtilir.
<ul>
<li><b><i>reset</i></b> Form sayfasındaki girdileri temizlemek için kullanılır.</li>
<li><b><i>button</i></b> Butona kendimiz bir işlev vermek için kullanabiliriz.</li>
<li><b><i>submit</i></b> Gönder düğmesi görüntüler (formu göndermek için)</li>
</ul>
</li>
</ul><br><br>

![forms](https://user-images.githubusercontent.com/48285856/147058133-ee28a053-bc5b-4d0c-9187-792cc2cb0734.png)
