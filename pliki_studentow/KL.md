# Forki w Git

Fork to funkcjonalność używana w systemach kontroli wersji, takich jak Git, która umożliwia utworzenie własnej kopii istniejącego repozytorium. Forki są szczególnie przydatne w projektach open source, gdzie wiele osób współpracuje nad tym samym kodem. Forkowanie pozwala użytkownikowi na niezależną pracę nad kodem bez wpływania na oryginalne repozytorium.

## Jak działa fork?

1. **Tworzenie kopii repozytorium**  
   Kiedy forkujesz repozytorium, tworzysz jego kopię na swoim koncie (np. na GitHubie). Ta kopia jest w pełni niezależna od oryginalnego repozytorium, co oznacza, że możesz wprowadzać w niej dowolne zmiany.

2. **Niezależna praca**  
   Po forku możesz klonować swoje zforkowane repozytorium na lokalny komputer, wprowadzać zmiany, dodawać nowe funkcje, poprawiać błędy itp.

3. **Pull request**  
   Jeśli chcesz, aby Twoje zmiany zostały dodane do oryginalnego repozytorium, możesz utworzyć tzw. *pull request*. Właściciel lub współpracownicy oryginalnego repozytorium mogą wtedy przejrzeć Twoje zmiany i zdecydować, czy je zaakceptować.

## Główne zastosowania forków

1. **Współpraca w projektach open source**  
   Forki są powszechnie używane przez osoby chcące wnieść wkład do publicznych projektów. Forkowanie umożliwia pracę nad kodem bez konieczności uzyskiwania dostępu do zapisu w oryginalnym repozytorium.

2. **Eksperymentowanie z kodem**  
   Możesz użyć forka do testowania nowych pomysłów lub funkcji bez ryzyka uszkodzenia oryginalnego projektu.

3. **Dostosowywanie projektu**  
   Forki pozwalają na modyfikację istniejącego projektu w celu dostosowania go do własnych potrzeb, nawet jeśli nie zamierzasz dzielić się swoimi zmianami z twórcami oryginalnego repozytorium.

## Fork vs Klon

- **Fork** to kopia repozytorium utworzona na zewnętrznej platformie (np. GitHubie), zazwyczaj w celu pracy nad projektem niezależnie od jego oryginalnych twórców. 
- **Klon** to lokalna kopia dowolnego repozytorium, którą pobierasz na swój komputer, aby pracować nad nią w swojej przestrzeni roboczej.

## Proces forkowania na GitHubie

1. Przejdź do strony repozytorium, które chcesz forknąć.
2. Kliknij przycisk **Fork** (znajdujący się w prawym górnym rogu strony).
3. Repozytorium zostanie skopiowane na Twoje konto.
4. Skopiuj URL swojego forka i użyj polecenia `git clone` do pobrania repozytorium na komputer:

   ```bash
   git clone <url-twojego-forka>
