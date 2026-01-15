# Współtworzenie RustDesk

RustDesk z zadowoleniem przyjmuje wkład od każdego. Oto wytyczne, jeśli chcesz nam pomóc:

## Współtwórcy
Wszelkie wkłady do projektu RustDesk lub jego zależności powinny być zgłaszane w formie pull requestów na GitHubie. Każdy pull request zostanie przejrzany przez jednego z głównych współtwórców projektu (osobę posiadającą uprawnienia do włączania zmian) i następnie zostanie zaakceptowany do głównej gałęzi projektu lub otrzyma informację zwrotną dotyczącą wymaganych poprawek. Zasada ta dotyczy wszystkich wkładów, w tym również tych pochodzących od głównych współtwórców.

Jeżeli chcesz pracować nad konkretnym zgłoszeniem (issue), najpierw zarezerwuj je, dodając komentarz do odpowiedniego zgłoszenia na GitHubie. Pozwala to uniknąć dublowania pracy przez kilku współtwórców nad tym samym problemem.

## Lista kontrolna Pull Requesta

- Utwórz branch na podstawie gałęzi master i — jeśli to konieczne — wykonaj rebase do aktualnej wersji master przed wysłaniem pull requesta. Jeżeli zmiany nie scalają się poprawnie z gałęzią master, możesz zostać poproszony o wykonanie rebasa.

- Commity powinny być możliwie małe, przy jednoczesnym zachowaniu poprawności każdego z nich. Każdy commit powinien kompilować się samodzielnie i przechodzić testy.

- Każdy commit powinien zawierać podpis Developer Certificate of Origin (DCO)
(http://developercertificate.org), potwierdzający, że Ty (oraz Twój pracodawca, jeśli dotyczy) zgadzacie się na warunki licencji projektu.
  [project license](../LICENCE). W Git podpis ten dodaje się za pomocą opcji `-s`  polecenia `git commit`.

- Jeżeli Twoja poprawka nie jest przeglądana lub potrzebujesz, aby konkretna osoba ją sprawdziła, możesz oznaczyć recenzenta za pomocą @ w pull requeście lub komentarzu, albo poprosić o recenzję drogą mailową: [email](mailto:info@rustdesk.com).

- Dodaj testy związane z naprawianym błędem lub nową funkcjonalnością.

W celu zapoznania się ze szczegółowymi instrukcjami dotyczącymi pracy z Git, zobacz [GitHub workflow 101](https://github.com/servo/servo/wiki/GitHub-workflow).

## Kodeks postępowania

[Kodeks postępowania](CODE_OF_CONDUCT-PL.md)

## Komunikacja

RustDesk contributors frequent the [Discord](https://discord.gg/nDceKgxnkV).
