# db-social-platform

1. Seleziona tutti gli utenti e calcolane l'età (25)

   SELECT \*,
   YEAR(CURDATE()) - YEAR(birthdate) AS age
   FROM Users;

2. Seleziona tutti i post senza Like (13)
3. Conta il numero di like per ogni post (165)
4. Ordina gli utenti per il numero di media caricati (25)
5. Ordina gli utenti per totale di likes ricevuti nei loro posts (25)
6. Seleziona tutti i post degli utenti tra i 20 e i 30 anni (49)
7. Seleziona il numero di post e di media per ogni utente (25)

BONUS 8. Seleziona tutti i post che contengono il tag 'serata' (8) 9. Ordina i post in base al numero di tag (165) 10. Ordina gli utenti in base al numero di tag usati nei loro post (25)
