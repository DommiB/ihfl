# ihfl - about

# overview
![overview](https://raw.githubusercontent.com/dommib/ihfl/master/overview.png)

# notes xattr
xattr nach dns-url aufgebaut 

```sh
user.ihfl.name=bla
user.ihfl.company=CoffeeShop
user.ihfl.type=rechnung
user.ihfl.tag=bestellung, online, www.blabla.de, paypal, 123.34€
user.ihfl.MD5=cbcd2b111966451ba1c744eab37fd6f9
user.ihfl.crypt=false
user.ihfl.compress=false
user.ihfl.prevnode=7b20395fe57c4e8dc46978dd53424b68
user.ihfl.nextnode=NULL
```
### TBD: 
- Name = Autor, absender, Bearbeiter usw -> aus OCR
- Company = Firma aus Logo -> OpenCV pattern matching
- Type = Rechnung, Vertrag, Kündigung -> aus OCR
- Tag = Keywords aus OCR? 
- MD5 = Hash der PDF -> Dient auch zur Vorschaut. Aus PDF wird ein PNG erstellt mit dem Hash als Name. Als Preview kann die Suche  dann das PNG laden -> schneller ? ! TBD 
- Crypt, Compress -> Noch nicht relevant, mal vorsehen (Compress vlt mit PNG als Vorschau leichter machbar) 
- Nodes: Idee dabei: Die Dokumente sollen eine Liste abbilden. z.B. kommt jeden Monate eine Abrechnung. Es wird eine verkettete Liste automisch aufgebaut. Dadurch kann man sich easy durch die Abrechnugnen klicken -> leichtere Verwaltung. 


# infos 
