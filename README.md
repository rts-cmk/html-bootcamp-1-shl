
# HTML Bootcamp #1

HTML er en fantastisk måde at præsentere tekst, billeder og video på.

Da Sir Tim Berners-Lee opfandt HTML i starten af 1990-erne, var det hans tanke, at dette var det eneste, HTML skulle bruges til. Og hvis vi tænker lidt over det, er det så ikke netop dette en hjemmeside gør?

Som du ved, er HTML bygget op af noget vi kalder en `Document Object Model` eller `DOM`. Det vil sige, at **alt i et HTML-dokument er objekter**. Objekter i HTML er repræsenteret af `tags`.

Et tag er opbygget af et sæt markeringer, som vi kalder start- og slut-tags.

```
<>          </>
 ^           ^
 start tag   slut tag
```

Hvad der står inde i tagget, bestemmer hvordan objektet, som tagget repræsenterer, opfører sig.

Skriver du for eksempel `<p> </p>`, opfører objektet sig som et tekstafsnit.

Det rå indhold vi skriver imellem et tag-sæt, er det vi kalder **det håndgribelige indhold** - eller **tangible content**.

```html
<p>Lorem ipsum dolor sit amet ...</p>
```

Et tag kan have forskellige attributter, som yderligere definerer hvordan objektet skal opføre sig. For eksempel skal HTML-dokumentet vide, hvilken adresse en bruger skal sendes til, hvis hun klikker på **det håndgribelige indhold** imellem to `anchor-tags`.

```html
<a href="https://duckduckgo.com">Duck it!</a>
```

Der er nogle få undtagelser til reglen om et sæt tags.

> Hvis et objekts håndgribelige indhold udelukkende beskrives af taggets attributter, har objektet ikke noget slut-tag.

Dette kan være et image-, link- eller meta-tag. Det håndgribelige indhold i for eksempel et image-tag er beskrevet af attributten `src`:

```html
<img src="/assets/media/profile.png">
```
## Eksempler på forskellige HTML-tags til din opgave

| Tag            | Beskrivelse                                             | Eksempel                                                    |
|----------------|---------------------------------------------------------|-------------------------------------------------------------|
| `<h1>` – `<h6>` | Overskrifter i forskellig hierarkisk niveau             | `<h1>Dette er en hovedoverskrift</h1>`                      |
| `<p>`          | Afsnit med tekst                                        | `<p>Dette er et tekstafsnit.</p>`                            |
| `<a>`          | Link (anker)                                           | `<a href="https://example.com">Besøg eksempel</a>`          |
| `<img>`        | Billede                                               | `<img src="https://placehold.co/150x100" alt="Placeholder">`|
| `<ul>`         | Unordineret liste                                     | `<ul><li>Punkt 1</li><li>Punkt 2</li></ul>`                 |
| `<ol>`         | Ordineret liste                                      | `<ol><li>Første</li><li>Anden</li></ol>`                     |
| `<li>`         | Listeelement (bruges i `<ul>` og `<ol>`)               | Som ovenfor                                                 |
| `<strong>`     | Fremhævet tekst med betydning (typisk fed)             | `<strong>Vigtig tekst</strong>`                              |
| `<em>`         | Fremhævet tekst med betoning (typisk kursiv)           | `<em>Fremhævet tekst</em>`                                  |
| `<header>`     | Semantisk container for side- eller sektionoverskrift  | `<header><h1>Min side</h1></header>`                         |
| `<nav>`        | Navigationselement med links                            | `<nav><a href="/">Hjem</a> <a href="/kontakt">Kontakt</a></nav>` |
| `<section>`    | Semantisk sektion med relateret indhold                 | `<section><h2>Om os</h2><p>Information...</p></section>`    |
| `<article>`    | Selvstændigt indhold som fx blogpost, nyhed, osv.       | `<article><h2>Nyhed</h2><p>...</p></article>`                |
| `<footer>`     | Sidefod eller sektionens bund                            | `<footer>Copyright 2025</footer>`                            |
| `<div>`        | Generel container (ikke-semantisk)                      | `<div class="container">Indhold</div>`                       |
| `<span>`       | Inline container (ikke-semantisk)                        | `<span style="color:red;">Rød tekst</span>`                  |
| `<form>`       | Formular til brugerinput                                 | `<form><input type="text"><button>Send</button></form>`     |
| `<input>`      | Inputfelt i formular                                    | Som ovenfor                                                |
| `<button>`     | Klikbar knap                                           | Som ovenfor                                                |
| `<table>`      | Tabel                                                  | `<table><tr><th>Navn</th><th>Alder</th></tr><tr><td>Anna</td><td>30</td></tr></table>` |
| `<blockquote>` | Citatblok                                              | `<blockquote>Dette er et citat.</blockquote>`                |


## Kort om semantisk opbygning i HTML

Semantisk HTML betyder, at man bruger de HTML-tags, der bedst beskriver det indhold, man vil vise, i stedet for blot at bruge generelle containere som `<div>` eller `<span>`. Det gør din kode:

- Mere læsbar og forståelig for andre udviklere.
- Bedre for søgemaskiner (SEO).
- Bedre for skærmlæsere og andre hjælpemidler (tilgængelighed).
- Lettere at vedligeholde.

### Eksempler på semantiske tags

- Brug `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>` til at opdele din side i meningsfulde sektioner.
- Brug `<strong>` og `<em>` til at vise, hvilken tekst der er vigtig eller betonet.
- Brug `<table>` til tabulære data, i stedet for at lave en masse `<div>`-rækker.


## Opgave

Du skal nu lave et HTML dokument, som viser, at du behersker den overordnede HTML-struktur. Brug **semantisk** opmærkning når det er muligt 


* Opret en fil i dette repository, som du kalder `index.html`
* Filen skal indeholde:

  * `head`-sektion
  * `body`-sektion
  * `body`-sektionen skal have mindst 20 forskellige objekter med indhold
* Din HTML skal valideres på [https://validator.nu/](https://validator.nu/) (vælg "Check by text input")

Du må gerne bruge **lorem ipsum** til tekst, og til billeder kan du for eksempel bruge:

* [https://placehold.co](https://placehold.co) – genererer billeder i præcis den størrelse og farve du ønsker
* [https://dummyimage.com](https://dummyimage.com) – et andet godt alternativ til midlertidige billeder
* [https://unsplash.com](https://unsplash.com) – gratis professionelle billeder, dog ofte større i filstørrelse

Du skal ikke style dit dokument.

## Supplerende billedtjenester

| Navn                | Beskrivelse                                                                                                | Link                                           |
| ------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| **Unsplash**        | Meget stor samling af professionelle billeder i høj opløsning. Gratis til både privat og kommercielt brug. | [unsplash.com](https://unsplash.com)           |
| **Pexels**          | Gratis billeder og videoer i høj kvalitet. Alt må bruges uden kreditering.                                 | [pexels.com](https://www.pexels.com)           |
| **Pixabay**         | Billeder, illustrationer, videoer og lydfiler – alt gratis og ofte uden kreditering.                       | [pixabay.com](https://pixabay.com)             |
| **Freepik**         | Grafikker, ikoner, billeder. Nogle kræver attribution eller Premium, men meget er gratis.                  | [freepik.com](https://www.freepik.com)         |
| **Burst (Shopify)** | Gratis billeder specielt egnet til webshops og markedsføring.                                              | [burst.shopify.com](https://burst.shopify.com) |
| **Stocksnap.io**    | Stort udvalg af stockbilleder, alt gratis og uden copyright.                                               | [stocksnap.io](https://stocksnap.io)           |
| **Kaboompics**      | Gratis billeder med fokus på livsstil, interiør og farvepaletter.                                          | [kaboompics.com](https://kaboompics.com)       |

