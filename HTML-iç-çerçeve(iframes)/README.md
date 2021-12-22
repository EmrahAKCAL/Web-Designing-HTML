<h1>HTML'de İç Çerçeve Oluşturma</h1>
Bir web sayfasını bir web sayfası içinde görüntülemek için bir HTML <b><i>< iframe></i></b> kullanılır. <br>
HTML <b><i>< iframe></i></b> etiketi bir satır içi çerçeveyi belirtir.
Geçerli HTML belgesine başka bir belge gömmek için bir satır içi çerçeve kullanılır.<br>

<b><i>< iframe src="url" frameborder="0" width="500" height="400" name="sayfa1"></i></b>
<ul>
<li><b><i>src=" " </i></b> Çerçeve içerisine sabit bir sayfa veya dosya eklemek için kullanılır.</li>
<li><b><i>frameborder=" "</i></b> Çerçevenin etrafında kenarlık olup olmayacağını tanımlar. 0 yapıldığında kenarlık gösterilmez,1 yapıldığında ise çerçeve kenarlıklarını gösterir.</li>
<li><b><i>width=" "</i></b> ve <b><i>height=" "</i></b> Çerçevenin genişliği ve yüksekliğini belirlemek için kullanılır.</li>
<li><b><i>name=" " </i></b> Çerçevenin içerisinde bir sayfa açmak istiyorsak ilgili sayfanın <i>< a href></i>(bağlantı) kısmındaki <b><i> target</i></b> etiketiyle konumlandırılır.(<i>< a href="dosya/sayfa bağlantısı" <b>target="sayfa1"</b>></i> )</li>
<li><b><i>title=" "</i></b>Ekran okuyucular tarafından iframe içeriğinin ne olduğunu okumak için kullanılır.</li>
</ul>
<b>NOT:</b> Çerçeve içerisine video eklemek için <i>src</i> niteliğinde videonun <i>url</i>sini ekleyiniz.<br><br>
<b>İç çerçeve örnek görüntüler</b><br><br>

![iframes1](https://user-images.githubusercontent.com/48285856/147101069-ff7ab5d2-b505-4eec-a441-393b75fd2e0c.png)

![iframes2](https://user-images.githubusercontent.com/48285856/147101581-1b4f8033-8c1e-4761-85c6-8242dcbf564b.png)

<br><br><br>
<a href="https://codepen.io/pen/">Çalışmaları Derlemek İçin Tıklayınız</a>
