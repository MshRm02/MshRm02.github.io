---
title: GitHub Flow
icon: fas fa-flow
order: 1
---

<h2><strong>Czym w ogóle jest GitHub Flow?</strong></h2>

Szczególnie w dzisiejszych czasach programiści mogą dużo szybciej i częściej dostarczać nowe funkcjonalności. Tempo takich prac bardzo często pozwala na to, aby po deployu zawierającym jakiś bug w programie, zrezygnować z przywracania poprzedniej wersji aplikacji. Dużo szybciej będzie po prostu wykonać kolejny deploy zawierający już poprawkę. Taki sposób rozwoju oprogramowania nazywamy GitHub Flow.

<br>

<h2><strong>Zastosowanie GitHub Flow</strong></h2>

Niewątpliwą zaletą GitHub Flow jest jego prostota oraz szybkość dostarczania nowych funkcjonalności (bądź poprawiania błędów). Znajdzie on głównie zastosowanie w przypadku małych zespołów bądź pracy samodzielnej.

<br>

<h2><strong>Jak działa GitHub Flow?</strong></h2>

<h3>GitHub Flow przewiduje tylko dwa rodzaje gałęzi:</h3>
<ol>
<li><strong>master</strong>- tutaj znajduje się aktualna wersja aplikacji, to do tej gałęzi programiści będą tworzyć swoje branche</li>
<li><strong>gałęzie robocze</strong>- tutaj będą dodawane nowe funkcjonalności i poprawiane błędy</li>
</ol>
 <br>

 <h3>Flow</h3>
 W przypadku GitHub Flow staramy się tworzyć małe, samodzielne zadania, nad którymi można pracować w izolacji od innych. Zadanie powinno zostać podzielone na niezależne zadania, które trafiają do mastera w momencie, gdy zostaną one ukończone. Gałąź master zawsze jest stabilna i zawsze można bezpiecznie utworzyć branche od niej. Każdy branch, który jest pushowany do gałęzi master musi przejść testy i jego "bezpieczeństwo" musi być pewne, najlepiej przedyskutowane w zespole. 

 <br>

 <h3>Praca w modelu GitHub Flow składa się zasadniczo z kilku etapów:</h3>
 <ol>
 <li>Stworzenie brancha</li>
 <li>Praca nad nową funkcjonalnością</li>
 <li>Commit</li>
 <li>Pull request</li>
 <li>Dyskusja</li>
 <li>Deploy</li>
 <li>Merge</li>
 </ol>
 <br>

<h2><strong>Przykłady zastosowania</strong></h2>
<h3>Zastosowanie przy tworzeniu gry</h3>
Jeśli tworzymy grę pracując w małym zespole programistów model GitHub Flow może dobrze się sprawdzić. Podzielenie pracy na małe fragmenty znacznie ułatwi pracę. Dzięki zastosowaniu tego modelu wszyscy programiści będą mieli dostęp do wszystkich funkcjonalności zawartych w branchu main i łatwiej będzie pracowało się na "pełnym" kodzie. Wprowadzanie nowych funkcjonalności będzie zajmowało mniej czasu, ponieważ będą one podzielone na mniejsze fragmenty. Na przykład: osoba wprowadza funkcjonajność obejmującą sterowanie, kolejna wprowadza funkcjonalność obejmującą fizykę. Osoba pracująca nad dodaniem postaci bądź NPC do gry będzie miała pełny dostęp do już dodanych funkcjonalności i jego praca, również podzielona na mniejsze fragmenty będzie sprawniejsza. Jeśli jakaś funkcjonalność zawiera bugi przy deployu, wykonujemy deploy wersji z mastera i naprawiamy na naszym branchu wykryte problemy.

<h3>Zastosowanie przy tworzeniu aplikacji mobilnej</h3>
Załóżmy, że chcemy stworzyć w małym zespole aplikację mobilną o właściwie dowolnej funkcjonalności. Tak jak w poprzednim przykładzie przez zastosowanie GitHub Flow każdy programista ma dostęp do działającej i "świeżej" wersji oprogramowania. Nie trzeba przejmować się łataniem bugów na gałęzi głównej, ponieważ są one wychwytywane jeszcze przed mergem nowej funkcjonalności. Oczywiście dyskutowanie każdej, niewielkiej zmiany zajmuje czas, ale za to daje możliwość pracowania w działającym środowisku i szybkiego wprowadzania nowych funkcjonalności. Wprowadzone zmiany są łatwo śledzone i odtwarzalne.

<h2><strong>Podsumowanie</strong></h2>
Model GitHub Flow sprawdzi się fantastycznie przy pracy w niewielkiej grupie, pozwala on na szybką i łatwą współpracę w zespole. Niewątpliwą zaletą jest łatwe i bezpieczne wprowadzanie zmian oraz zapewnia szybki i bezproblemowy dostęp do najnowszej wersji kodu. Model ten wymaga dyskutowania nad każdą wprowadzoną zmianą, jednak w zamian daje pewność działania i szybkie wprowadzanie nowych funkcjonalności w zespole.