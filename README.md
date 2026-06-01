# 2025-p1a-inf-nis-MatProch
2025-p1a-inf-nis-MatProch created by GitHub Classroom
https://pslib-cz.github.io/2025-p1a-inf-nis-MatProch/index.html

# RePlate

## O projektu

RePlate je informační systém pro správu a redistribuci nevyužitých jídel ve školních jídelnách.  
Cílem systému je snížit plýtvání potravinami tím, že umožní studentům rezervovat nevyzvednuté porce za zvýhodněnou cenu.

Systém propojuje studenty, zaměstnance jídelny a administrátory do jedné platformy, která zajišťuje přehlednou evidenci jídel, rezervací a statistik potravinového odpadu.


---

## Hlavní funkce

- evidence nevyzvednutých jídel
- rezervace jídel studenty
- správa kapacity a dostupnosti porcí
- QR / PIN ověření při vyzvednutí
- notifikace o dostupných porcích
- historie objednávek
- statistiky zachráněných jídel
- administrace uživatelů a systému

---

## Uživatelské role

### Student
- prohlížení dostupných jídel
- rezervace porcí
- zrušení rezervace
- historie objednávek
- příjem notifikací

### Zaměstnanec jídelny
- přidávání nevyužitých jídel
- potvrzení vyzvednutí
- správa dostupnosti jídel

### Administrátor
- správa uživatelů
- správa systému
- přístup ke statistikám
- moderace obsahu

---

## Funkční požadavky

- uživatel se musí být schopen přihlásit do systému
- systém musí umožnit rezervaci dostupného jídla
- systém musí zabránit překročení kapacity porcí
- systém musí evidovat historii rezervací
- systém musí umožnit správu uživatelských rolí
- systém musí generovat statistiky o zachráněných porcích

---

## Nefunkční požadavky

- systém musí být dostupný 24/7
- odezva systému nesmí překročit 2 sekundy
- data uživatelů musí být zabezpečena
- aplikace musí být responzivní pro mobilní zařízení
- systém musí podporovat minimálně 500 současně přihlášených uživatelů

---

## Návrh databázových entit

- User
- Role
- Meal
- Reservation
- Pickup
- Notification
- Statistics

---

## Použité technologie

| Vrstva | Technologie |
|---|---|
| Frontend | React |
| Backend | Node.js / Express |
| Databáze | PostgreSQL |
| Autentizace | JWT |
| API | REST |
| Nasazení | Docker |

---

## UML diagramy

Projekt bude obsahovat:

- Use Case diagram
- Activity diagram
- Sequence diagram
- Class diagram
- ER diagram
- Deployment diagram

---

## Cíl projektu

Hlavním cílem projektu je vytvořit návrh moderního informačního systému, který pomůže omezit plýtvání potravinami a zjednoduší správu redistribuce jídel ve školním prostředí.

---

## Autoři

- Matěj Procházka
