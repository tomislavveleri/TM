# TM
https://github.com/tomislavveleri/TM

SELECT zaposlenik, SUM(broj_sati) AS ukupni_sati
FROM evidencija
GROUP BY zaposlenik;

