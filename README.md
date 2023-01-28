# 🔗 Kurz Link Building a SEO
💼 Materiály ku kurzu [Link Building](https://www.it-academy.sk/kurz/linkbuilding-i-zaciatocnik/) a [SEO](https://www.it-academy.sk/kurz/zaklady-seo-optimalizacia-pre-vyhladavace-i/)

📑 Anotácia a Osnova kurzu
Kurz Linkbuilding je pre teba skvelou voľbou, ak sa chceš naučiť budovať odkazový profil pre svoj web. Osvojíš si základné zásady linkbuildingu a vhodné nástroje, ktoré ti pomôžu. Na konkrétnych postupoch a ukážkach ťa naučíme efektívne získavať vhodné odkazy a priviesť na svoj web viac návštevníkov. Ako absolvent kurzu Linkbuilding zvládneš pre svoj web získavať relevantné a cenné odkazy.

# 🛠️ Nástroje na Link Building a SEO
1. [Whitepress](https://www.whitepress.com)
2. [All My Links](https://allmylinks.com)
3. [Whitepress](https://www.whitepress.com)
4. [LinkLifting](https://linklifting.com/)
5. [Ahrefs Website Authority Checker Backlink Checker / Backlink Checker / Broken Link Checker](https://ahrefs.com/website-authority-checker)

# 📚 Odporúčané zdroje


# 📏 Štruktúra (Anatómia) Hypertextového Odkazu
![carbon](https://user-images.githubusercontent.com/24510943/215289258-9e4c33e2-55d3-4ee9-81ab-ceb97798063f.png)

```html
<h1>Štruktúra (Anatómia) Hypertextového Odkazu</h1>
<h2>Značky (Tagy) a Elementy</h2>
<!-- SK Otváracia Značka, Odkaz na Sprostredkované Miesto, Vidit. Text Odkazu, Uzatváracia Značka -->
<!-- EN Start Tag, Link Referral Location, Visible/Anchor Text Link, Close Tag -->
<a href="https://www.vita.sk">VITA | Online Kurzy a Školenia</a>
```
## Atribúty rel a ich Hodnoty
```html
<h2>Atribúty rel a ich Hodnoty</h2>  
<h3>Atribút rel=follow/nofollow</h3>
<!-- rel - Atribút, ktorý Rieši Vzťah Predávania Odkazovej Štavy Crawlerom -->
<!-- rel="nofollow" - Nechceme, aby Crawler Prechádzal Daný Odkaz a Prenášal Odkazovú Štavu -->
<a href="https://www.vita.sk" rel="follow">VITA | Online Kurzy a Školenia</a>
<a href="https://www.vita.sk" rel="nofollow">VITA | Online Kurzy a Školenia</a>
```
### 🔥 Atribút rel=sponsored
```html
<h3>Atribút rel=sponsored</h3>
<!-- rel="sponsored" - Označenie Odkazu, že Ide o Platený Odkaz (Nákup Odkazu, Články, PR)-->
<a href="https://www.vita.sk" rel="sponsored"> VITA | Online Kurzy a Školenia</a>
```
```html
### 🤼 Atribút rel=ugc
<h3>Atribút rel=ugc</h3> 
<!-- rel="ugc" - Označenie Odkazu, že Ide o Používateľmi Generovaný/Vytvorený Odkaz. Napríklad Používatelia Tvoria a Píšu Obsah s Odkazmi v Komentároch -->
<!-- rel="ugc" - User Generated Content -->
<a href="https://www.vita.sk" rel="ugc"> VITA | Online Kurzy a Školenia</a>
```
```html
## 🔑 Atribút title
<h2>Atribút title</h2>  
<!-- title - Titulok, Rozšírené Informácie o Kontexte Odkazu -->
<a href="https://www.vita.sk" title="Akreditované Online Kurzy a Školenia">VITA | Online Kurzy a Školenia</a>
```
## 🏳️ Atribút hreflang
```html
<h2>Atribút hreflang</h2>  
<!-- hreflang - Špecifikácia Jazyka Cieľovej Destinácie Odkazu -->
<a href="https://www.vita.sk" hreflang="sk"> VITA | Online Kurzy a Školenia</a>
<a href="https://www.vita.sk"  hreflang="en"> VITA | Online Courses</a>
```
## 🎯 Atribút target
```html
<h2>Atribút target</h2>  
<!-- target="_self" - Atribút target Určuje Ako sa Má Odkaz Otvoriť -->
<!-- target="_self" - Po Kliknutí na Odkaz sa Otvorí v Rovnakom Okne/Tabe Prehliadača -->
<a href="https://www.vita.sk" target="_self"> VITA | Online Kurzy a Školenia</a>
```
## 😶 Atribút target blank
```html
<!-- target="_blank" - Po Kliknutí na Odkaz sa Otvorí v Novom Okne/Tabe Prehliadača -->
<!-- target="_blank" - Po-Pupy a Možné Bezpečnostné Riziko -->
<a href="https://www.vita.sk"  target="_blank"> VITA | Online Kurzy a Školenia</a>
```
## 🔐 Atribút rel noopener noreferrer
```html
<h2>Atribút rel noopener noreferrer</h2>  
<!-- rel="noopener noreferrer" - noopener Zabraňuje Phisingu t.j. kradnutiu Informácií zo Zdrojovej Stránky, pretože Zabraňuje Zneužitie JavaScript Funkcie window.opener -->
<!-- rel="noopener noreferrer" - noreferrer Zaraňuje Prehliadači Poslať Cieľovej Stránky Informácie o Stránke, Odkiaľ Prišiel Používateľ Pomocou HTTP Hlavičky -->
<!-- Bez UTM Parametrov Potom Neviem Odkiaľ Prišiel Daný Používateľ -->
<a href="https://www.vita.sk"  target="_blank" rel="noopener noreferrer">VITA | Online Kurzy a Školenia</a>
```
