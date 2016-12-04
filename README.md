# RG16-028-ten-160
ten-160

U pitanju bi bila mala 3D igra (na dva 2D pozadini). Igra bi bila random dungeon generator, u kome bi se prilikom učitavanja mape slučajnim izborom pojavio broj protivnika (između 10 i 160). Napretkom kroz nivoe, mogu da se nasleđuju health i da se broje poeni.

# TODO:
  - Napraviti početnu stranu
  - Napraviti meni
    - Sadržaj menija: Start, Opcije, Napusti
        - Opcije: Muziku uključi/isključi
  - Kreirati pozadinu
    - Omogućiti da se kreće po pozadini
    - Omogućiti generisanje pozadina u zavisnosti od količine neprijatelja
  - Dodati glavnog lika
    - Omogućiti mu da se kreće kroz mapu
    - Napraviti mu health bar (možda i magick bar)
        - Health se prenose u sledeći nivo uz male dodatke
    - Borbene komande, udarci i gađanje
  - Dodati protivnike
    - Omogućiti im da se kreću po mapi
    - Generisati ih između 10-160 i na osnovu toga odrediti veličinu mape
    - Napraviti im načine napada, udarci i gađanje
  - Poeni
    - Dodavanje poena po dva kriterijuma
        - Količina ubijenih protivnika
        - Vreme potrebno za to
 - Kraj
    - Kada lik više nema preostalih života
    - Ponuditi opciju restart i quit
    - Poene čuvati na rang listi (10 najboljih)