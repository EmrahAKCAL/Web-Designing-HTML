<h1>HTML'de Linklerin Kullanımı</h1>
Bağlantılar hemen hemen tüm web sayfalarında bulunur. Bağlantılar, kullanıcıların sayfadan sayfaya veya sayfa içerisinde kendi yollarını tıklamalarına izin verir. <br>
<b><i>< a href="url" target=""></i></b>link Metni<b><i>< /a></i></b><br>
<ul>
<li><b><i>a href="url"</i></b>: Bağlantıya tıklanıldığında gidecek sayfanın bağlantı adresi girilir. Bu bir html sayfası veya internet sayfası da olabilir.</li>
<li><b><i>target=""</i></b>: bağlantılı belgeyi nerede açmak için belirtir.
<ul>
<li><b><i>_self</i></b>: Aynı sekmede açar.</li>
<li><b><i>_blank</i></b>:Yeni bir sekmede açar.</li>
<li><b><i>_parent</i></b>:Ana çerçevede açar.</li>
<li><b><i>_top</i></b>: Pencerenin tam gövdesinde açar</li>
</ul>
</li>
</ul>
<h2>Bir Resmi Bağlantı Olarak Kullanmak</h2>
Bir görseli bağlantı olarak kullanmak için <b>< img></b> etiketini <b>< a></b> etiketin içine koymanız yeterlidir. <br>
<b>Örneğin:</b> < a href="" target=""> <b><i>< img src="resimadresi" width="resim boyutu" alt="Alternatif resim açıklaması"></i></b>< /a>
<h2>Sayfa İçerisinde Bağlantı Kurmak</h2>
Etiket kısmına tıklanıldığında sayfa içerisindeki ilgili bölüme gitmek için <b><i>< a href="#id-isim-etiketi">Bağlantı Metni< /a> </i></b> Bağlantısı kullanılır. 
Örneğin: <b>< a href="#Aslanprens"></b>Aslan Prens Masalı<b>< /a></b> <i>Aslan Prens Masalı</i> bağlantısına tıklanıldığında id="Aslanprens" etiketli bölüme gidecektir.<br> 
<b>< h4 id="Aslanprens">1-Aslan Prens Masalı< /h4></b>
  <br><br><br><a href="https://codepen.io/pen/">HTML Çalışmasını Derle</a>
