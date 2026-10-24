# Flutter Quiz App

Ukážková Flutter aplikácia s úvodnou obrazovkou, kvízovými otázkami a vyhodnotením odpovedí.

## Spustenie

```bash
flutter pub get
flutter run
```

## Opravy

- sumarizácia používa číselný kľúč `question_index` namiesto textu otázky,
- index otázky sa po poslednej odpovedi nezvýši mimo rozsah zoznamu,
- reštart kvízu vymaže predchádzajúce odpovede.
