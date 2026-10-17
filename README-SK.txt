DREAM IN DREAM – NASADENIE BEZ GITHUBU A ANDROID STUDIA

Tento priečinok je pripravený na zverejnenie ako statická webová aplikácia/PWA.

1. Rozbaľte ZIP.
2. Otvorte Netlify Drop: https://app.netlify.com/drop (môže vyžadovať účet).
3. Presuňte celý priečinok dream-in-dream-pwa do oblasti na nahratie. Ak rozhranie neakceptuje priečinok, nahrajte jeho obsah podľa pokynov služby.
4. Po zverejnení získate HTTPS adresu. Otvorte ju v Chrome, skontrolujte, že aplikácia sa načíta, a raz ju otvorte online, aby sa uložili súbory pre offline použitie.
5. Otvorte https://www.pwabuilder.com/, vložte HTTPS adresu, zvoľte Package for stores > Android > Generate Package > Other Android (ak je dostupné) a stiahnite balík. Postup a dostupné možnosti sa môžu meniť.
6. V ZIP balíku od PWABuilder hľadajte podpísaný APK, ak ste pri zostavení zvolili podpis. Preneste APK do Androidu a otvorte ho. Android môže žiadať povolenie inštalácie z daného zdroja.

DÔLEŽITÉ
- APK cez PWABuilder je obal nad zverejnenou webovou aplikáciou; prvé načítanie potrebuje internet a offline režim treba otestovať.
- Sny sú uložené lokálne v úložisku aplikácie/prehliadača. Pravidelne exportujte JSON zálohu a uložte ju mimo zariadenia. PDF je export na čítanie, JSON je na obnovenie.
- PIN v tomto prototype nie je šifrovanie dát. Záložné súbory JSON nie sú šifrované.
- Pri prenose do nového zariadenia použite Export a záloha > Stiahnuť zálohu JSON a potom na novom zariadení Importovať zálohu JSON.
