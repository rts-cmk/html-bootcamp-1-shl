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

## Opgave

Du skal nu lave et HTML dokument, som viser, at du behersker den overordnede HTML-struktur.

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

## Aflevering

Din aflevering foregår via GitHub. Du skal lave en pull-request fra dit eget repository til det repository, du har klonet fra.
