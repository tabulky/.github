# Bezpečnostní zásady

## Hlášení bezpečnostních zranitelností

Bezpečnost našich projektů a dat našich uživatelů bereme velmi vážně. Pokud jste našli bezpečnostní zranitelnost, oceníme vaši pomoc při jejím zodpovědném nahlášení.

### Jak nahlásit bezpečnostní problém

**Prosím, NEHLASTE bezpečnostní zranitelnosti prostřednictvím veřejných GitHub issues.**

Místo toho použijte jednu z následujících metod:

1. **GitHub Security Advisories** (preferováno)
   - Přejděte na záložku "Security" v repozitáři
   - Klikněte na "Report a vulnerability"
   - Vyplňte formulář s podrobnostmi

2. **Soukromý email**
   - Kontaktujte bezpečnostní tým projektu
   - Uveďte "SECURITY" v předmětu emailu

### Co zahrnout do hlášení

Pomozte nám lépe porozumět problému tím, že zahrnete:

- Typ zranitelnosti (např. SQL injection, XSS, atd.)
- Úplné cesty souborů souvisejících se zranitelností
- Umístění dotčeného kódu (tag/branch/commit nebo přímý URL)
- Jakákoli speciální konfigurace potřebná k reprodukci problému
- Podrobné kroky k reprodukci zranitelnosti
- Proof-of-concept nebo exploit kód (pokud je možný)
- Dopad zranitelnosti a jak by ji mohl útočník zneužít

### Co můžete očekávat

- **Potvrzení**: Potvrdíme přijetí vašeho hlášení do 48 hodin
- **Komunikace**: Budeme vás informovat o postupu řešení
- **Oprava**: Budeme pracovat na opravě co nejrychleji
- **Zveřejnění**: Zveřejníme opravu a oceníme vaši pomoc (pokud si to budete přát)

## Podporované verze

| Verze | Podporovaná |
| ----- | ----------- |
| Aktuální | ✅ |
| Starší verze | ❌ |

## Bezpečnostní osvědčené postupy

### Pro uživatele

- Vždy používejte nejnovější verzi
- Pravidelně aktualizujte závislosti
- Neukládejte citlivá data v repositářích
- Používejte bezpečné přenosové protokoly (HTTPS, SSH)

### Pro přispěvatele

- Nikdy necommitujte citlivá data (klíče, hesla, tokeny)
- Používejte `.gitignore` pro vyloučení konfiguračních souborů
- Validujte a sanitizujte všechny vstupy
- Dodržujte zásadu nejmenších oprávnění
- Pravidelně kontrolujte závislosti na známé zranitelnosti

### Bezpečnost dat

Při práci s otevřenými formáty dat:

- **Validace**: Vždy validujte vstupní data podle schématu
- **Sanitizace**: Čistěte data před zpracováním
- **Šifrování**: Šifrujte citlivá data při přenosu i ukládání
- **Přístupová práva**: Nastavte správná oprávnění pro soubory a adresáře
- **Anonymizace**: Odstraňte osobní údaje z veřejných dat

## Bezpečnostní aktualizace

Sledujte bezpečnostní aktualizace:
- GitHub Security Advisories
- Dependabot alerts
- Automatické bezpečnostní updaty

## Zodpovědné zveřejnění

Dodržujeme zásady zodpovědného zveřejnění:

1. Bezpečnostní problémy nebudou veřejně zveřejněny, dokud nebude k dispozici oprava
2. Ocenime výzkumníky, kteří odpovědně nahlásí problémy
3. Poskytneme dostatek času na aktualizaci před veřejným zveřejněním

## Poděkování

Děkujeme bezpečnostnímu výzkumu komunity za pomoc udržet naše projekty bezpečné! 🙏
