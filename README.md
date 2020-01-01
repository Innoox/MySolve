<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>MySolve</title>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
</head>
<body>
  # MySolve
 Programming_Task_UnrealEngine

### Stwórz projekt UE4 wg następujących założeń: 
<ul>
 <li>Tech specs:</li>
  <ul>
   <li>Wersja silnika 4.22+</li>
   <li>Główne mechaniki stworzone na blueprintach, dopuszczalne jest posiłkowanie się klasami w C++,
       wystawionymi do wykorzystania w blueprintach.</li>
   <li>Można wykorzystać dowolny z domyślnych szablonów tworząc nowy projekt.</li>
   <li>Przepływ informacji powinien być widoczny w logu.</li>
   <li>Aspekty wizualne projektu nie będą brane pod uwagę.</li>
   <li>Jako rozwiązanie proszę o dostarczenie plików z projektem, contentem oraz configami.</li>
  </ul>
  <br>
 <li>Main Tasks:</li>
  <ol type="1">
   <li>Rozgrywka odbywa się w pierwszej osobie.</li>
   <li>W edytorze, jest możliwość dodania na scenę aktora "BP_Container".</li>
   <li>W okienku szczegółów aktora "BP_Container" jest możliwość ustawienia zmiennej 
       "NeededObject" na jedną z dostępnych w rozwijalnej listy wartości. </li>
   <li>Gracz ma możliwość za pomocą klawiatury zespawnować na scenie przed sobą aktora 
       "BP_Minion". </li>
   <li>Na scenie może się znajdować maksymalnie pięciu aktorów typu"BP_Minion"
       zespawnowanych przez gracza. </li>
   <li>Gracz może wejść w interakcję z aktorem "BP_Minion", używając przycisku na
       klawiaturze. (Warunkiem na możliwość interakcji jest znajdowanie się blisko aktora i 
       wskazanie go celownikiem.) </li>
   <li>O możliwości wejścia w interakcję gracz jest oznajmiany, poprzez wyświetlenie się
       komunikatu "Interact" w okolicach celownika na ekranie. </li>
   <li>Interakcja z aktorem "BP_Minion" powoduje  wyświetlenie się widgetu
       "WB_Interaction Menu".</li>
   <li>Widget "WB_Interaction Menu" składa się z przycisków z napisami, które odpowiadają
       liście z aktora "BP_Container".</li>
   <li>Zamknięcie widgetu nastpępuje po kliknięciu lewym przyciskiem.</li>
   <li>Kliknięcie w jeden z dostępnych przycisków powoduje dodatkowo, że aktor "BP_Minion" z
       którym gracz był w interakcji idzie do najbliższego, znajdującego się na scenie aktora
       "BP_Container", posiadającego ustawioną zmienną "NeededObject" na wartość z
       klikniętego przycisku. </li>
   <li>Po dojściu aktora "BP_Minion" do aktora "BP_Container" w logu wyświetlana jest
       informacja o tym jaki minion "dostarczył" jaki przedmiot, a minion zatrzymuje się i
       pozostaje w miejscu czekając na dalsze rozkazy. </li>
  </ol>
</ul>
</body>
</html>
