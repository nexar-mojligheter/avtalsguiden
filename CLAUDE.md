# AvtalsGuiden

> Researchad affärsmöjlighet från Nexar Academy. Den fullständiga marknadsresearchen
> ligger i skillen **affärsplan** — kör `/affarsplan` för att läsa den.

## Vad vi bygger
Juridiskt säkert hantverkaravtal på 5 minuter – skyddar både dig och hantverkaren. AvtalsGuiden är Sveriges smartaste digitala avtalstjänst för ROT-arbeten och hantverkstjänster. Till skillnad från statiska PDF-mallar guidar vi dig steg för steg, anpassar avtalet efter ditt uppdrag och låter båda parter signera digitalt – direkt i mobilen. Slipp kostsamma tvister och känn dig trygg från offert till slutbesiktning.

## Stack (ändra inte utan att fråga)
- Next.js + Tailwind (frontend)
- Supabase (databas + auth)
- Vercel (deploy)
- Claude API där appen behöver AI

## Kommandon
- `npm run dev` — kör lokalt
- `npm run build` — bygg + felkoll (kör efter varje ändring)
- `npm run lint` — lint

## Så jobbar vi (viktigt)
- Bygg i **små steg** — kör `npm run build` efter varje ändring och visa resultatet.
- **Fråga vid större vägval** (tech, datamodell, pris) i stället för att gissa.
- Lägg **aldrig** hemligheter/nycklar i koden — bara i `.env.local`.
- Håll det **enkelt** — en MVP som bevisar värdet, inte en färdig produkt.

## Projektminne (DU ansvarar för det — användaren ska aldrig behöva be)
- Efter varje avklarat steg: uppdatera `docs/FRAMSTEG.md` (byggt + nästa steg).
- Vid varje vägval: logga en rad i `docs/BESLUT.md` (datum + 1 mening om varför).
- Bocka av i `docs/UPPGIFTER.md` allt eftersom.
- **Vid sessionsstart: läs `docs/FRAMSTEG.md` FÖRST** och sammanfatta "var vi var".
- Använd din inbyggda auto-memory för build-kommandon och buggfixar.

## Kom igång
Läs `/affarsplan`, föreslå sedan en konkret **4–6-stegsplan** för MVP:n — sen kör vi.

<!-- nexar:opportunity slug=avtalsguiden -->
