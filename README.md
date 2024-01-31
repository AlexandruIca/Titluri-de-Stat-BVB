# Titluri de Stat pe BVB

https://www.titluri-de-stat-bvb.ro

Site-ul se folosește de API-ul TradeVille (https://api.tradeville.ro) pentru a accesa datele legate de titlurile de stat [Fidelis](https://mfinante.gov.ro/web/trezor/titluri-de-stat-fidelis). Ele se pot sorta în funcție de:

- YTM.
- Dobândă.
- Monedă (în acest caz pentru fiecare monedă se sortează după YTM).
- Preț.

Se folosește contul demo dat de TradeVille, deci nu e nevoie de back-end special pentru site. Cum API-ul TradeVille e limitat la 20 de requesturi la fiecare 10 secunde, adaug un delay la fiecare request ca să nu fie probleme.

Am făcut acest front-end deoarece am vrut un mod foarte simplu de a accesa informații despre titlurile de stat Fidelis, și nu vreau să caut de fiecare dată prin PDF-uri, sau să mă conectez pe TradeVille, ca să văd numele lor.
