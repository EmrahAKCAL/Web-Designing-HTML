<h1>HTML'de Tablo Oluşturma</h1>
HTML'deki bir tablo, satırlar ve sütunlar içindeki tablo hücrelerinden oluşur. Tablo oluşturmak için <b><i>< table></i></b> etiketi kullanılır.<br>
<table>
<thead>
<tr>
<th>Etiket</th>
<th>Açıklama</th>
</thead>
<tbody>
<tr>
<td><b><i>< caption></i></b> </td>
<td>Tabloya üst bilgi(başlık) eklemek için kullanılır.</td>
</tr>
<tr>
<td><b><i>< thead></i></b> </td>
<td>Başlık içeriğini bir tabloda gruplandırır.</td>
</tr>
<tr>
<td> <b><i>< tr></i></b> </td>
<td> Tablo satırı anlamına gelir.</td>
</tr>
<tr>
<td>  <b><i>< th></i></b> </td>
<td>Tablodaki bir başlık hücresini tanımlar ve içindeki metin kalındır.</td>
</tr>
<tr>
<td><b><i>< tbody></i></b></td>
<td>Gövde içeriğini bir tabloda gruplandırır.</td>
</tr>
<tr>
<td><b><i>< td></i></b></td>
<td> Tablodaki bir hücreyi tanımlar.</td>
</tr>
<tr>
<td><b><i>< td rowspan=""></i></b></td>
<td> Tablodaki 2 satırları birliştirir.</td>
</tr>
tr>
<td><b><i>< td rowspan=""></i></b></td>
<td> Tablodaki 2 sütunları birliştirir.</td>
</tr>
</tbody>
</table>
 <h2>Örnek: HTML'de Kimlik Kartı Oluşturma</h2>
 <table>
 <thead>
 <tr>
 <th colspan="4">Kimlik Kartı </th>
 </tr>
 </thead>
 <tbody>
 <tr>
 <td> ADI</td>
 <td> BARIŞ</td>
 <td colspan="2" rowspan="3"><img src="tables-image/baris-akarsu.jpg" width="150" alt="fotoğraf"></td>
 </tr>
 <tr>
  <td>SOYADI</td>
  <td>AKARSU</td>
  </tr>
  <tr>
 <td>DOĞUM TARİHİ</td>
  <td>29.06.1979</td>
  </tr>
  <tr>
<td colspan="2">SERİ NO</td>
<td colspan="2">A01Y08196</td>
</tr>
 </tbody>
 </table>
 <br><br><br><a href="https://codepen.io/pen/">HTML Çalışmasını Derle Sayfasına Git</a>
