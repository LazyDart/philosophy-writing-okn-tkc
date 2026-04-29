
Poniżej porządkuję wszystkie główne pojęcia, które wprowadziłeś, wraz z ich roboczymi definicjami i relacjami. Nie dopisuję nowych tez ponad to, co już się pojawiło — raczej czyszczę i układam aparat pojęciowy.

---

# 1. Poziom najbardziej fundamentalny

## [[Grunt]]
## [[Proces]]

## [[Różnica|Różnicowanie]]

---

# 2. Struktura i znaczenie

## [[Struktury różnicujące]]

## [[Znaczenie]]

## [[Nowość]]

---

# 3. Zmiana, powtórzenie i contraction

## [[Zmiana]]

## [[Stan]]

## [[Powtarzanie]]

## [[Contraction]]

## [[Dyskretyzacja]]

---

# 4. Tożsamość, trwanie, całość

## [[Tożsamość]]

## [[Trwanie]]

## [[Autopoiesis]]

## [[Kantian Whole]]
## Selekcja / [[Darwinizm Procesów]]

## [[Teleologia]]
---

# 5. Poziomy, abstrakcja, superweniencja

## [[Poziom abstrakcji]]*

## Fuzziness / blur

Ponieważ procesy są płynne, granice między poziomami nie są ostre.

Tak jak trudno powiedzieć, kiedy kopiec piasku przestaje być kopcem, tak trudno powiedzieć, kiedy dokładnie kończy się jeden poziom procesu, a zaczyna drugi.

## Emergence / [[Emergencja]]

## [[Superweniencja procesowa]]

---

# 6. [[Czas]]

## [[Przyszłość i przeszłość]]

---

# 7. Perspektywa i świadomość

## [[Perspektywa]]
## [[Subiektywna Perspektywa]]
## [[Świadomość]]

## [[Fenomenologia]]

---

# 8. Trzecioosobowość, intersubiektywność, komunikacja

## [[Świat taki jakim jest]]
## [[Trzecioosobowa perspektywa]]

## [[Komunikacja]]
## [[Intersubiektywność]]

## Obiektywność epistemiczna

**Obiektywność epistemiczna** to stabilizacja intersubiektywnych rezultatów.
Nie jest bezpośrednim dostępem do świata takiego, jaki jest.  
Jest raczej rekonstrukcją warunków mediacji na podstawie tego, co stabilnie przechodzi między perspektywami.
## [[philosophy-writing-okn-tkc/terms/Nauka|Nauka]]

---
# 9. Matematyzacja i teoria kategorii

## [[Morfizm]]
## Diagram komutatywny
**Diagram komutatywny** może modelować sytuację, w której różne ścieżki komunikacji prowadzą do zachowania tej samej struktury.
To byłoby formalne narzędzie opisu stabilnej intersubiektywności.
## Funktor (ChatGPT zaproponował) - nie wiem o co chodzi, może to obiecujące
**Funktor** może opisywać przejście między poziomami opisu, np.
- z fenomenologicznego do językowego,
- z językowego do naukowego,
- z subiektywnego do intersubiektywnego,    
- z lokalnej struktury do bardziej abstrakcyjnej.

## [[Teoria kategorii]]

---

# 10. Możliwa hierarchia pojęć zaproponowana przez ChatGPT

## Pojęcia pierwotne

Najbardziej podstawowe:

1. **proces**
2. **różnicowanie**
3. **relacja**
4. **contraction**
5. **perspektywa**
6. **mediacja**

## Pojęcia wtórne

Wyprowadzane z powyższych:

1. **struktura różnicująca**
2. **stan**
3. **powtórzenie**
4. **tożsamość**
5. **znaczenie**
6. **czas procesowy**
7. **komunikacja**
8. **intersubiektywność**
    
## Pojęcia dalsze / bardziej złożone

1. **autopoiesis**
2. **Kantian whole**
3. **poziomy abstrakcji**
4. **emergencja**
5. **obiektywność epistemiczna**
6. **nauka**
7. **formalizacja kategorialna**

---

# 11. Relacje między pojęciami — wersja strzałkowa

```text
grunt / chaos procesowy
    ↓
elementarne procesy
    ↓
różnicowanie
    ↓
różnice, które robią różnicę
    ↓
struktury różnicujące
    ↓
contraction
    ↓
dyskretyzacja / snapshot / granica / stan
    ↓
powtórzenie
    ↓
tożsamość względna
    ↓
trwanie procesu
    ↓
autopoiesis / Kantian whole
    ↓
poziomy abstrakcji / możliwa emergencja
```

Perspektywy i komunikacja:

```text
struktura różnicująca
    ↓
lokalny dostęp + contraction
    ↓
subiektywna perspektywa

subiektywna perspektywa A
    ↓
komunikacja jako morfizm
    ↓
mediacja trzecioosobowa filtruje transformację
    ↓
subiektywna perspektywa B

część struktury, która przetrwała A → B
    ↓
intersubiektywność

stabilne przetrwanie struktur między wieloma perspektywami
    ↓
obiektywność epistemiczna

systematyczna rekonstrukcja warunków mediacji
    ↓
nauka
```

---

# 12. Mermaid graf

```mermaid
flowchart TD

    A[Grunt / chaos procesowy] --> B[Elementarne procesy]
    B --> C[Różnicowanie]
    C --> D[Różnice, które robią różnicę]
    D --> E[Struktury różnicujące]
    
    E --> F[Contraction]
    F --> G[Dyskretyzacja]
    F --> H[Snapshot / stan]
    F --> I[Granice i całości]
    
    G --> J[Powtórzenie]
    H --> J
    I --> J
    
    J --> K[Tożsamość względna]
    K --> L[Trwanie procesu]
    L --> M[Autopoiesis]
    L --> N[Kantian whole]
    
    M --> O[Poziomy abstrakcji]
    N --> O
    O --> P[Możliwa emergencja]
    
    E --> Q[Perspektywa]
    F --> Q
    Q --> R[Subiektywna perspektywa A]
    Q --> S[Subiektywna perspektywa B]
    
    R --> T[Komunikacja / morfizm]
    T --> U[Mediacja trzecioosobowa]
    U --> V[Transformacja struktury]
    V --> S
    
    V --> W[Część struktury zachowana]
    W --> X[Intersubiektywność]
    X --> Y[Obiektywność epistemiczna]
    Y --> Z[Nauka jako rekonstrukcja mediacji]
    
    U -. niedostępna bezpośrednio .-> AA[Świat taki, jaki jest]
    AA -. warunkuje .-> U
```

---

# 13. Mermaid graf bardziej kategorialny

```mermaid
flowchart LR

    A[Perspektywa A<br/>struktura różnicująca SA]
    B[Perspektywa B<br/>struktura różnicująca SB]
    C[Perspektywa C<br/>struktura różnicująca SC]

    A -- "morfizm komunikacyjny f" --> B
    B -- "morfizm komunikacyjny g" --> C
    A -- "morfizm komunikacyjny h" --> C

    fM[Trzecioosobowa mediacja<br/>warunki fortunności] -. filtruje .-> A
    fM -. filtruje .-> B
    fM -. filtruje .-> C

    B --> I[Struktura zachowana<br/>intersubiektywność AB]
    C --> J[Struktura zachowana<br/>intersubiektywność AC]

    I --> O[Stabilizacja intersubiektywna]
    J --> O
    O --> N[Obiektywność epistemiczna]

    H[Diagram komutatywny:<br/>czy g ∘ f ≈ h?] --> O
```

---