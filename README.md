# -1_Code
## introduction
-1_code is a code system for html. It takes json data and will output html.
## header
<code>
{
  "content":{
    "header": {"font":"arial","colour":"#000000","header-text":"header_text","text-background":"none","text-decoration":"i","img-url":"https://img_url.com/example","background-colour":"img"},    
    "body-data":[{"background-colour":"img"},
                 {"background-img":"https://imgurl.com/path"}],
    "body":[
      {"font":"arial","colour":"#000000","section-text":"text","text-background":"none","text-decoration":"i"},
      {"font":"arial","colour":"#000000","section-text":"text","text-background":"none","text-decoration":"i"}
    ],   
  }
}
</code>
<ul>
<li>text:</li>
<ul>
  <li>text</li>
  </ul>
<li>font:</li>
  <ul>
    <li>Any web-safe font</li>
  </ul>
<li>text-decoration:</li>
<ul>
  <li>i for *italic*</li><li>b for **bold**</li><li>bi for ***bold and italic***</li><li>bq for block quotes</li><li>orli for ordered lists</li><li>unli for unordered lists</li><li>code for `code`.</li>
</ul>
<li>colour:</li>
  <ul>
    <li>hex code</li>
  </ul>
  <li>text-background:</li>
  <ul>
    <li>hex code or <code>none</code> for no background</li>
  </ul>
  <li>background-colour:</li>
  <ul>
    <li><code>img</code> for an image, <code>none</code> for no background or hex code</li>
  </ul>
  <li>img-url:</li>
  <ul>
    note: don't add this if <code>background-colour</code> is not <code>img</code>
    <li>Url to image</li>
  </ul>
</ul>
