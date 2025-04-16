# **tei_course**
bits of code for tei students. Odette was originally programmed by Frédéric Glorieux.
<br>
# Known styles
```xml
<ab type="ornament">My para</ab>
```

Below a list of normalized style name known, and their xml/tei transposition. Unknown styles are kept in a @rend attribute. Styles are here shown normalized as ascii lower case letter, but real life styles may contain capitals, accents, spaces, or punctuation. For example, **quotesalute** could appears as *&lt;Quote, Salute&gt;* for the user in its word processor (a style for a letter in a citation). 

## Paragraph level styles

**ab**
```xml
<ab type="ornament">content ¶</ab>
```
**address**
```xml
<address>
  <addrLine>content ¶</addrLine>
</address>
```
**argument**
```xml
<argument>
  <p>content ¶</p>
</argument>
```
**bibl**
```xml
<bibl>content ¶</bibl>
```
**byline**
```xml
<byline>content ¶</byline>
```
**camera**
```xml
<camera>content ¶</camera>
```
**caption**
```xml
<caption>content ¶</caption>
```
**castitem**
```xml
<castList>
  <castItem>content ¶</castItem>
</castList>
```
**castlist**
```xml
<castList>content ¶</castList>
```
**closer**
```xml
<closer>content ¶</closer>
```
**dateline**
```xml
<dateline>content ¶</dateline>
```
**def**
```xml
<entryFree>
  <def>content ¶</def>
</entryFree>
```
**desc**
```xml
<desc>content ¶</desc>
```
**docauthor**
```xml
<docAuthor>content</docAuthor>
```
**docimprint**
```xml
<docImprint>content ¶</docImprint>
```
**docdate**
```xml
<docDate>content ¶</docDate>
```
**eg**
```xml
<eg>content ¶</eg>
```
**epigraph**
```xml
<epigraph>
  <p rend="right italic…">content ¶</p>
</epigraph>
```
**epigraphl**
```xml
<epigraph>
  <l>content ¶</l>
</epigraph>
```
**entry**
```xml
<entry>content ¶</entry>
```
**fw**
```xml
<fw>content ¶</fw>
```
**index**
```xml
<index>
  <item>content ¶</item>
</index>
```
**l**
```xml
<l rend="center italic…">content ¶</l>
```
**label**
```xml
<label>content ¶</label>
```
**labeldateline**
```xml
<label type="dateline">content ¶</label>
```
**labelhead**
```xml
<label type="head">content ¶</label>
```
**labelsalute**
```xml
<label type="salute">content ¶</label>
```
**labelspeaker**
```xml
<label type="speaker">content ¶</label>
```
**lg**
```xml
<lg>
  <l>content ¶</l>
</lg>
```
**opener**
```xml
<opener>content ¶</opener>
```
**p**
```xml
<p rend="right italic…">content ¶</p>
```
**pb**
```xml
<pb n="…"/>
```
**postscript**
```xml
<postscript>
  <p>content ¶</p>
</postscript>
```
**q**
```xml
<q>content ¶</q>
```
**quote**
```xml
<quote>
  <p rend="right, italic…">content ¶</p>
</quote>
```
**quotedateline**
```xml
<quote>
  <dateline>content ¶</dateline>
</quote>
```
**quotel**
```xml
<quote>
  <l>content ¶</l>
</quote>
```
**quotesalute**
```xml
<quote>
  <salute>content ¶</salute>
</quote>
```
**quotesigned**
```xml
<quote>
  <signed>content ¶</signed>
</quote>
```
**role**
```xml
<castItem>
  <role>content ¶</role>
</castItem>
```
**roledesc**
```xml
<castItem>
  <roleDesc>content ¶</roleDesc>
</castItem>
```
**said**
```xml
<said>content ¶</said>
```
**salute**
```xml
<salute>content ¶</salute>
```
**salutation**
```xml
<salute>content ¶</salute>
```
**set**
```xml
<set>
  <p>content ¶</p>
</set>
```
**signed**
```xml
<signed>content ¶</signed>
```
**speaker**
```xml
<speaker>content ¶</speaker>
```
**stage**
```xml
<stage>content ¶</stage>
```
**term**
```xml
<index>
  <term>content ¶</term>
</index>
```
**trailer**
```xml
<trailer>content ¶</trailer>
```
## Character level styles

**abbr**
```xml
blah… <abbr>@ level</abbr> …blah
```
**add**
```xml
blah… <add>@ level</add> …blah
```
**actor**
```xml
blah… <actor>@ level</actor> …blah
```
**author**
```xml
blah… <author>@ level</author> …blah
```
**affiliation**
```xml
blah… <affiliation>@ level</affiliation> …blah
```
**age**
```xml
blah… <age>@ level</age> …blah
```
**bibl**
```xml
blah… <bibl>@ level</bibl> …blah
```
**c**
```xml
blah… <c>@ level</c> …blah
```
**code**
```xml
blah… <code>@ level</code> …blah
```
**corr**
```xml
blah… <corr>@ level</corr> …blah
```
**date**
```xml
blah… <date>@ level</date> …blah
```
**del**
```xml
blah… <del>@ level</del> …blah
```
**distinct**
```xml
blah… <distinct>@ level</distinct> …blah
```
**email**
```xml
blah… <email>@ level</email> …blah
```
**emph**
```xml
blah… <emph>@ level</emph> …blah
```
**geogname**
```xml
blah… <geogName>@ level</geogName> …blah
```
**gloss**
```xml
blah… <gloss>@ level</gloss> …blah
```
**name**
```xml
blah… <name>@ level</name> …blah
```
**num**
```xml
blah… <num>@ level</num> …blah
```
**pb**
```xml
blah… <pb>@ level</pb> …blah
```
**persname**
```xml
blah… <persName>@ level</persName> …blah
```
**placename**
```xml
blah… <placeName>@ level</placeName> …blah
```
**stage**
```xml
blah… <stage>@ level</stage> …blah
```
**title**
```xml
blah… <title>@ level</title> …blah
```
