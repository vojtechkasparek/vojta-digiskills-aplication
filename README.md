# Vojtěch × DigiSkills: přihláška jako kontext

Dobrý den,

**tohle není statická přihláška jen ke čtení. Je to kontext.** Celá složka je psaná tak, aby ji mohl číst člověk, ale i jeho AI. Nahrajte ji do své AI (třeba jako projekt), vložte k ní instrukci z [`handover-agent.md`](handover-agent.md) a ptejte se. Například:

- "Kdo je Vojtěch a co by do našeho týmu mohl přinést?"
- "Jaká témata by u nás Vojtěch mohl lektorovat a jaké ne?"
- "Jaké jsou jeho zkušenosti?"

Agent odpovídá jen z informací v balíčku a u každé odpovědi řekne, odkud ji má. Co v balíčku není, přizná. Přesně tento princip práce je zároveň koncept, který vysvětluji ve videu. Je to reálná demonstrace, jak jde využít osobní kontext ve spolupráci s AI.

Tato přihláška nese koncept a zároveň ho sama demonstruje. 

## Dvě cesty (jak s balíčkem pracovat) 🙂

Nejjednodušší cesta je celý balíček otevřít v kódovacím nástroji (Claude Code, Codex, Cursor). Druhá možnost je soubory nahrát do projektu a jako instrukci využít následující prompty.

| Chcete…   | Otevřete                                                                                                                           |
| --------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| se ptát   | [`handover-agent.md`](handover-agent.md): jsou to instrukce pro vaši AI. Představí se, provede vás a po každé odpovědi nabídne, kam dál |
| číst sami | [`PRUVODCE-CLOVEK.md`](PRUVODCE-CLOVEK.md): tři trasy balíčkem podle Vašeho času, 5 / 15 / 30+ minut                               |

Video k přihlášce (lekce u whiteboardu): [youtu.be/-spU9lcHw7E](https://youtu.be/-spU9lcHw7E)

## Dívejte se mi pod ruce

[`audit-prace.md`](audit-prace.md) ukazuje, jak přihláška vznikla: co navrhla AI, co jsem rozhodl já a proč. Najdete v něm i čtyři místa, kde jsem AI přehlasoval, a vzorec, který z nich vychází. Každé lidské rozhodnutí jde dohledat ve složce `zdroje/`.

## AI navrhuje, vy rozhodujete. I o mně.

Učím, že AI má navrhovat a člověk rozhodovat. Proto přikládám i [`PRUVODCE-AI.md`](PRUVODCE-AI.md): brief pro neutrálního analytika. Ten balíček projde, oddělí doložené od pouze tvrzeného a ukáže slabá místa. Rozhodnutí nechá na vás.

## Co v balíčku je

| Soubor | Co z něj získáte |
|---|---|
| `handover-agent.md` | Instrukce, se kterou se vaše AI stane průvodcem balíčkem |
| `audit-prace.md` | Jak přihláška vznikla, kde jsem AI přehlasoval a proč. Na konci: co vidím na školeních (lidé nechodí s use casem) |
| `PRUVODCE-AI.md` | Brief pro neutrální rozbor balíčku včetně slabých míst |
| `PRUVODCE-CLOVEK.md` | Tři trasy pro čtení bez AI |
| `prompty/` | Čtyři prompty z téhle přihlášky. 01 a 03 mají výstup v balíčku, 02 a 04 jsou na video a stránku. Všechny jdou spustit na jiném vstupu |
| `zdroje/` | Očištěné podklady: zadání se záznamem rozhodnutí, analýza DigiSkills, expertní panel, karty dokladů |
| `whiteboard.jpg`, `whiteboard.md` | Kresba, kterou vypráví video: od druhého mozku k balíčku. Fotka a její textový přepis pro AI |

## Co tu nenajdete

Podklady jsem očistil. Nejsou tu firemní klienti, interní ani osobní čísla, jména studentů ani syrové poznámky z mého druhého mozku. Firmy, kde jsem školil (v `zdroje/02-analyza-digiskills.md`), jsou veřejné reference. Kde podklad chybí, je to napsáno (`[CHYBÍ PODKLAD]`) a nic není domyšlené.

## O mně

Učitel informatiky, lektor AI pro firmy a školy. Web: [vojtechkasparek.cz](https://www.vojtechkasparek.cz) · [LinkedIn](https://www.linkedin.com/in/vojta-kašpárek-713786291)

Díky za Váš čas a těším se na případnou spolupráci.

Vojtěch
