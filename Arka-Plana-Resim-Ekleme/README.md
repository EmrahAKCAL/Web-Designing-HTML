<h1> HTML'de Arka Plana Resim Ekleme </h1>
Bir HTML öğesine arka plan resmi eklemek için <b>< head></b> içerisine <b><i>< style> body {background-image: url('resimadresi'); background-repeat: no-repeat;}< /style></i></b> komut satırı kullanılır.<br>
<ul>
<li>Tüm sayfanın bir arka plan görüntüsüne sahip olmasını istiyorsak <b><i>< body></i></b>öğe üzerinde arka plan görüntüsünü belirtmek gerekir. Arka plan görüntüsünün kendini tekrar etmesini önlemek için <b><i>background-repeat</i></b> özelliği <b><i>no-repeat;</i></b> olarak ayarlayınız.</li>
<li>Arka plan resmi tüm sayfayı kaplaması için <b><i>bacground-size:</i></b> özelliği <b><i>cover</i></b> olarak ayarlanmalıdır. Resim tüm sayfayı kapladığına emin olmak için <b><i>background-attachment:</i></b> özelliği <b><i>fixed</i></b> olarak ayarlamak gerekir.</li>
</ul>
 <a href="https://codepen.io/pen/">HTML Çalışmasını Derle</a>
