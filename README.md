<h3>Güncellemeler</h3>
<hr>
<label>Bu güncellemede eklenenler</label>
<ul>
  <li>Temalar eklendi</li>
  <li>İsteğe bağlı temalar otomatik oldu</li>
  <li>Otomatik çeviri eklendi</li>
  <li>Onload eklendi</li>
  <li>CSS Propertysi basitleştirildi</li>
  <li>Documention tamamen değişti</li>
</ul>
<hr>
<h4>Özellikler</h4>
<table width="100%">
<tr>
  <th>Özellik</th>
  <th>Syntax</th>
  <th>Örnek</th>
</tr>
<tr>
  <th>Css</td>
  <td>kw.api.css.property("query","value")</td>
  <td>kw.api.css.color("body","red")</td>
</tr>
<tr>
  <th>Theme</td>
  <td>kw.api.theme.theme</td>
  <td>kw.api.theme.dark</td>
</tr>
<tr>
  <th>Onload</th>
  <td>kw.api.onload(`function`)</td>
  <td>kw.api.onload(`<br>
    alert("Example")<br>
   `) </td>
</tr>
<tr>
 <th>HTML Lang</th>
  <td>setLang()</td>
  <td>kw.api.onload(`<br>
    setLang()<br>
   `) </td>
</tr>
<tr>
  <th>Outo Change theme</th>
  <td>chanceTheme()</td>
   <td>
    <script><br>
    kw.api.onload(`<br>
    chanceTheme()<br>
   `) <br>
     </script><br>
     < body theme="dark"></body>
     </td>
</tr>
<tr>
  <th>Hide</th>
  <td>kw.api.hide("query", "delay")</td>
  <td>kw.api.hide("div", 2000)</td>
</tr>
<tr>
  <th>Show</th>
  <td>kw.api.show("query", "delay")</td>
  <td>kw.api.show("div", 2000)</td>
</tr>
</table>
