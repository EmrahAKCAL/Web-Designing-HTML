<h1>HTML'de Liste Oluşturma</h1>
<table>
  <thead>
    <th>Sırasız Listeler</th>
    <th>Sıralı Listeler</th>
  </thead>
  <tbody>
    <td>< ul> </td>
    <td>< ol> </td>
  </tbody>
  </table>
  <h2>1-Sırasız Listeler</h2>
Sırasız bir HTML listesi için <b><i>< ul> < /ul></i></b> etiketi kullanılır. Her liste öğesi <b><i>< li></i></b>etiketiyle başlar. Burada listenin başına <ul><li>şeklinde işaret ekler.</li></ul>
  Bu işareti değiştirmek için <b><i>< ul></i></b> içerisine <b><i>stle="list-style-type:</i></b>eklenir ve işaret tipi girilir. 
  Sıralamasız işaret tipleri
  <ul>
    <li><b><i> circle:</i></b> Daire şeklinde işaret eklemek için</li>
    <li><b><i>square:</i></b> Kare eklemek için</li>
    <li><b><i>disc:</i></b> Disk şeklinde işaret ekler(bu listede olduğu gibi)</li>
  </ul>
<h2>2-Sıralı Listeler</h2>
  Sıralı bir liste <b><i>< ol></i></b>etiketi ile başlar . Her liste öğesi <b><i>< li></i></b> etiketiyle başlar. Liste öğeleri varsayılan sayılarla(1, 2, 3 ..)işaretlenecektir.<br>
  Bu işareti değiştirmek için <b><i>< ol type=""></i></b> içerisine <b><i> 1, A, a, I veya i </i></b> işaret tiplerinden girilir. <br> Örneğin A-B-C... şeklinde listelemek için <i>type="A"</i> yazılır.<br>
 Eğer belli bir sayıdan sonra başlamasını istiyorsak <b><i>start=" "</i></b> etiketi eklenir. Örneğin 5'ten başlamasını istiyorsak <i>< ol type="1" <b><i>start="5" </i></b>></i> yazılmalıdır.<br>
  Liste içerinde bir alt liste de eklenenebilir. Bunu ilgili <i>< li></i>etiketi içerisinde yeniden sırasız/sıralı (ul/ol) etiketi kullanılır.<br> 
  <b>ÖRNEK:</b>
  <ol type="1">
            <li>Mango
                <ol type="a">
                    <li>Faydaları</li>
                    <li>Yetiştiği Yer</li>
                </ol>
            </li>
            <li>Üzüm
                <ul style="list-style-type: symbols();">
                    <li>Faydaları</li>
                    <li>Yetiştiği Yer</li>
                </ul>
            </li>
            <li>Kiraz
                <ul style="list-style-type:georgian;">
                    <li>Faydaları</li>
                    <li>Yetiştiği Yer</li>
                </ul>
            </li>
        </ol>
  <h2>3- HTML Açıklama Listeleri</h2>
 Bu kısımda listenen ürünlerin önüne herhangi bir işaret getirmez. Bir ürünün ismi/soru için <b><i>< dt></i></b> etiketi,  açıklama kısmı için ise <b><i>< dd></i></b> etiketi kullanılır. Bu etiketler açıklama listesi <b><i>< dl></i></b>  etiketi içerisine alınır. <br> Örneğin soru(< dt>) ve  cevap (< dd>) şeklinde bir çalışma tasarlamayalım.
    <dl>
        <dt>HTML Nedir?</dt>
        <dd>İngilizce Hyper Text Markup Language cümlesinin baş harflerinden oluşur. </dd>
        <dd>İşaretleme dili olan Html, web sayfalarının hazırlanmasında kullanılan sistemdir. Bir programlama dili olmayan Html bilgisayarlarımızda kullandığımız web sitelerinin oluşturulmasında kullanılır. </dd>
        <dt>Domain Nedir?</dt>
        <dd>Domain (alan adı); hatırlanması zor olan IP adresleri yerine kullanılması için internet otoriteleri tarafından geliştirilen bir isimlendirme yöntemidir.</dd>
        <dt>Web Hosting Nedir?</dt>
        <dd>Hosting veya Barındırma, bir web sitesinde yayınlanmak istenen sayfaların, resimlerin veya dokümanların internet kullanıcıları tarafından erişebileceği bir bilgisayarda tutulmasıdır. Bir başka değişle site barındırma hizmetidir.</dd>
        <dt>SEO Nedir?</dt>
        <dd> Web sitesinin arama motoru sonuçlarında daha iyi pozisyona gelmesi için yapılan çalışmalar bütünüdür.</dd>
    </dl>
 
