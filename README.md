# Podgląd /checkout — kierunek A (v5)

Prywatny podgląd do weryfikacji. **To nie jest produkcja www.paymove.io.**

Zaakceptowana wersja z 2026-11-15: akordeon bez linii góra/dół, odstęp pod tytułem 64px,
krok 3 z 7 logotypami (gwiazdy7).

Na desktopie mechanika jak na Mobbin (strona MCP): lewa kolumna z krokami przypina się,
a sceny po prawej jadą w pionie ze scrollem (widać, jak poprzednia wypływa do góry,
a kolejna wjeżdża od dołu). Przy liście kroków jest cienka szyna 2px, po której
aktywny odcinek jedzie płynnie, proporcjonalnie do scrolla. Akordeon rozwija się
i zwija z animacją wysokości. Klik w krok przewija do danej sceny.
Na mobile (poniżej 800px) bez sticky i bez szyny — kroki jeden pod drugim.
`prefers-reduced-motion`: bez animacji.

`index.html` na desktopie jest szerokości 1440px; poniżej 800px włącza się układ mobilny.
