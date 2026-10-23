---
title: "Zasada 4: Zaufanie nie jest dziedziczone"
description: "Zaufanie przyznane jednemu podmiotowi nie rozciąga się automatycznie na całe jego otoczenie. Każdy element ekosystemu wymaga osobnej decyzji."
---

# Zasada 4: Zaufanie nie jest dziedziczone

Pierwsza zasada odebrała złudzenia co do ustawień domyślnych. Druga i trzecia ustaliły, komu i na jak długo ufamy. Teraz czas na pytanie o granice: **na kogo dokładnie rozciąga się to zaufanie?**

Ufasz aplikacji, bo ją sprawdziłeś. Rozumiesz, co robi i widzisz, jakie ma uprawnienia. Ale aplikacja rzadko działa w izolacji. Łączy się z chmurą, korzysta z zewnętrznych bibliotek, odpytuje serwery firm trzecich. Czy Twoje zaufanie do aplikacji automatycznie obejmuje całe to zaplecze? Nie.

## Pułapka łańcucha dostaw

Najczęstszym błędem jest założenie, że skoro ufamy głównemu podmiotowi, to ufamy też temu, z czym się on łączy. To myślenie oparte na przechodniości zaufania: skoro A ufa B, a B ufa C, to A ufa C. W cyfrowym świecie ta logika jest zabójcza.

To, że aplikacja jest bezpieczna, nie oznacza, że bezpieczna jest biblioteka, którą potajemnie ładuje. To, że ufasz deweloperowi, nie oznacza, że ufasz każdemu, komu on przekazuje dane. Zaufanie do jednego elementu nie jest przepustką do zaufania kolejnemu. Granice są ostre i nie rozmywają się w łańcuchu zależności.

## Zgodne z duchem Zero Trust

To podejście nie jest zaprzeczeniem Zero Trust, lecz jego praktycznym zastosowaniem. Prawdziwe Zero Trust – w przeciwieństwie do korporacyjnego produktu – właśnie na tym polega: żaden element systemu nie jest domyślnie zaufany, a dostęp jest przyznawany punktowo. Mikrosegmentacja, o której mówi się w kontekście sieci, to techniczny wyraz tej samej myśli: zaufanie nie rozlewa się po systemie. Jest przypisane do konkretnego miejsca i konkretnej transakcji. Ta uniwersalna zasada brzmi: **zaufanie nigdy nie jest dziedziczone**.

## Co to oznacza w praktyce

Gdy aplikacja prosi o dostęp do czegoś, co wydaje się niepowiązane z jej główną funkcją, nie zakładaj, że to niewinne. Może to nie ona. Może to już jej ekosystem. Może to zewnętrzna biblioteka, o której nie wiedziałeś.

Nie oznacza to, że masz żyć w cyfrowej jaskini i odmawiać wszystkiego. Oznacza to, że **samo połączenie nie jest podstawą do zaufania**. Nie przenoś zaufania z jednego podmiotu na drugi tylko dlatego, że są ze sobą połączone. Sprawdź, gdzie kończy się zaufanie do aplikacji, a gdzie zaczyna się ślepa wiara w jej otoczenie.

## Czwarta zasada

Zaufanie nie jest dziedziczone. Nie przechodzi z aplikacji na chmurę. Nie przechodzi z dewelopera na bibliotekę. Nie przechodzi z jednej sesji na drugą.

To jest czwarta zasada distrust. Granice zaufania są ostre. Nie pozwól, by rozmyły się w łańcuchu dostaw.
