# Podgląd /checkout — kierunek A (v5)

Prywatny podgląd do weryfikacji. **To nie jest produkcja www.paymove.io.**

Zaakceptowana wersja z 2026-11-15: akordeon bez linii góra/dół, odstęp pod tytułem 64px,
krok 3 z 7 logotypami (gwiazdy7).

Na desktopie sekcja „Uruchomisz w kilka minut.” przypina się przy scrollu (jak na Mobbin):
aktywny krok przełącza się sam (1 → 2 → 3, ok. 100vh na krok), scena po prawej robi crossfade.
Klik w krok nadal przewija do danego kroku. Na mobile (poniżej 800px) bez sticky — kroki jeden pod drugim.
`prefers-reduced-motion`: bez animacji.

`index.html` na desktopie jest szerokości 1440px; poniżej 800px włącza się układ mobilny.
