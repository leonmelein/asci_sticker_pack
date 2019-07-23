# ![ASCI](https://github.com/leonmelein/asci_sticker_pack/raw/master/logo.png) ASCI Sticker Pack
_Het Sticker Pack voor ASCI, door ASCI_

Welkom bij het ASCI Sticker Pack! Alle stickers die je kent, zijn in deze repo aanwezig. Deze is gelinkt als _git submodule_ aan de Android app, dus die krijgt altijd de laatste stickers binnen. 

## Een sticker voorstellen
Als je een nieuwe sticker wilt voorstellen, maar deze niet zelf kan ontwerpen, geen probleem! Vraag erom via een [Issue](https://github.com/leonmelein/asci_sticker_pack/issues/new).

## Een sticker toevoegen
Natuurlijk kan ik het intekenen van verenigingsbegrippen niet alleen af. Alle hulp is welkom, en daarom kun je nu direct contributen aan het Sticker Pack via een pull request.

1. Maak een icoon als WebP-afbeelding van 512x512 pixels met transparantie, met 16px witruimte rondom. Zie voor de volledige specificaties [deze website](https://faq.whatsapp.com/general/26000226). Plaats deze in één van de mappen (1 = Classics, 2 = Food & Drinks, 3 = Events & Meetings, memes = Memes). 

    _*N.b.* In elk pack passen maximaal 30 stickers. Als je sticker niet in één van de bestaande packs past, vraag dan even om een nieuw pack door een [Issue](https://github.com/leonmelein/asci_sticker_pack/issues/new) aan te maken. Verder zijn de mapnamen suboptimaal, maar bij aanpassing breken bestaande installaties en moeten de packs opnieuw geactiveerd worden. Voorlopig houden we daarom deze namen aan.__

2. Bewerk `contents.json`. Voeg in het bestand onder het relevante pack even een verwijzing naar de sticker en max. 3 relevante emoji's toe.
```
{
          "image_file": "asci.webp",
          "emojis": ["💙"]
},
```

3.  Maak een [pull request](https://help.github.com/en/articles/creating-a-pull-request) aan en [verzoek mij je wijzigingen te reviewen](https://help.github.com/en/articles/requesting-a-pull-request-review). 

4.  Na je werk te hebben gecheckt en eventuele problemen te hebben opgelost, wordt je werk gemerged in het Sticker Pack.

5.  ???

6.  PROFIT! Gefeliciteerd, je hebt een sticker toegevoegd aan het ASCI Sticker Pack! Geniet van dit moment en bereid je voor op de complimenten van je mede-ASCI'ers. ✨
