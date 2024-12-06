---
author: Lektion 8
date: MMMM dd, YYYY
paging: "%d / %d"
---

# Lektion 8

Hej och välkommen!

## Innan lektion

- Röstning om distanslektioner vecka 51 (tors & fre)

## Agenda

1. Frågor och repetition
2. Fortsättning projektbygge
3. Design övningar i klass
4. Eget arbete med handledning
5. Quiz frågor

---

# Fråga

Kommentera "våra" projektbygge-kod mer för när det kommer till OOP så snurrar det till i skallen på en. Det hade varit toppen!

# Svar

Vi tar lite extra tid under repetition för att kommentera.

---

# Fråga

Kommer du göra mer koppling till kod projekt?

# Svar

Nej, inte något större som är utöver reddit klonen. Det vore, i så fall, ett mycket mindre projekt utan OOP.

---

# Design övningar

1. Träningsapp
   - Logga mätvärden över tid (vikt, löptid, välj fritt)
   - Spara personliga rekord
   - Sätta och följa upp träningsmål
2. E-commerce
3. Discord klon

---

# E-commerce

- Köpa produkter (utifrån varukorg)
- Lägga produkter i varukorg
- Lägga till produkter i önskelista
- Spara varukorg i konto
- Spara önskelista som kan delas med andra
- Skapa kundkonto
- Radera kundkonto
- Ändra kundkonto
- Se historik av ordrar (för konto)
- Rating på produkter
- Recensioner på produkter

customers:

- id
- förnamn
- efternamn
- lösenord
- address
- telefonnummer
- epost

products:

- id
- namn
- beskrivning
- pris
- lager_antal INT
- thumbnailImageUrl

customer_ratings:

- id
- product_id
- customer_id
- rating DECIMAL (antal stjärnor)

customer_reviews:

- id
- product_id
- customer_id
- beskrivning TEXT

product_cart:

- user_id
- product_id
- produkt_antal

product_wishlist:

- id
- titel
- user_id
- datum

product_wishlist_products:

- product_id
- wishlist_id
- produkt_antal

orders:

- id
- user_id
- datum

order_products:

- product_id
- order_id
- produkt_antal
- pris_per_produkt

---

# Quiz frågor

- Varför är normalisering viktigt?
- Vad säger den första normalformen (1NF)?
- Vad säger den andra normalformen (2NF)?
- Vad säger den tredje normalformen (3NF)?
- Vad är skillnaden mellan One-to-Many och Many-to-One?
- Vad gör en left join?
- Vad är skillnaden mellan left joins och right joins?
- Varför behöver vi en left/right join för att hämta inlägg i reddit klonen?
