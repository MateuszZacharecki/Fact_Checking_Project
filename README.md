## Fact checking project (text mining)

1. Dane w pliku train.tsv zawierają publiczne wypowiedzi i ocenę prawdziwości

2. Opis kolumn:

- **label**: ocena: pants-fire, false, barely-true, half-true, mostly-true, true
- **statement**: treść wypowiedzi
- **subject**: temat/tematy
- **speaker**: The person making the statement
- **speaker_job**: czyja wypowiedź
- **state**: stan
- **party**: partia
- **context**: kontekst, np. 'a town hall in Austin, Texas'

3. Cel: zbudować model, który przewidzi czy dana wypowiedź to bzdura (pants-fire)
