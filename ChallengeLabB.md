Point 1:

# Crea un nuovo gruppo. Ogni gruppo deve avere un nome univoco. Lo script deve verificare che non esistano nomi di gruppo duplicati nel sistema. Se viene trovato un duplicato, è necessario segnalare un errore e l'amministratore deve provare con un altro nome di gruppo.

chmod +x ./test.sh
./test.sh --> nome del gruppo

# Crea un nuovo utente. Ogni utente deve avere un nome univoco. Lo script deve verificare che non esistano nomi utente duplicati nel sistema. Se viene trovato un duplicato, è necessario segnalare un errore e l'amministratore deve provare un altro nome utente. L'utente avrà una shell di accesso Bash e apparterrà al gruppo creato nel passaggio precedente.



# Crea una password per ogni utente creato.




# Assicurarsi che il nuovo utente creato sia un membro del nuovo gruppo creato.



# Crea una directory nella radice / del file system con lo stesso nome creato dall'utente.



# Imposta la proprietà della directory sull'utente e sul gruppo creato.



# Imposta le autorizzazioni della directory sul controllo completo per il proprietario e sul controllo completo per il gruppo creato.



# Imposta le autorizzazioni per garantire che solo il proprietario di un file possa eliminarlo dalla directory.



# Assicurati che lo script sia eseguibile.