## Avvertenze

- **Utilizza questo script solo su dispositivi di cui sei il proprietario o per cui hai ottenuto il consenso esplicito**.
- L'accesso non autorizzato a dati personali è illegale e viola la privacy.
-------------------------------------------------------------------------------------------------------------------------
## Autore

- **Creato da**: [GhostlyCode](https://github.com/hacktechgames)
Seguimi su Youtube https://www.youtube.com/@Gcod3
--------------------------------------------------------------------------------------------------------------------------
## Licenza

Questo script è rilasciato sotto licenza MIT. Consulta il file [LICENSE](LICENSE) per ulteriori dettagli.

---------------------------------------------------------------------------------------------------------------------------

# Script per l'estrazione dei dati dei browser

Questo script è progettato per estrarre i dati di accesso (credenziali, cookie, ecc.) dai browser Chrome, Firefox e Edge e salvarli su una penna USB con label **penusb**. I dati vengono salvati in un file ZIP chiamato `BrowserData.zip`.

## Requisiti

1. **Penna USB**:
   - La penna USB deve avere la label **penusb**.
   - Puoi assegnare la label manualmente tramite il menu **Proprietà** della penna USB in Esplora File, oppure utilizzando il comando PowerShell:
     ```powershell
     Set-Volume -FileSystemLabel "penusb" -NewFileSystemLabel "penusb"
     ```

2. **Sistema operativo**:
   - Lo script è stato testato su Windows 10 e Windows 11.

3. **Browser supportati**:
   - Google Chrome
   - Mozilla Firefox
   - Microsoft Edge

## Come utilizzare lo script

1. **Collega la penna USB**:
   - Inserisci la penna USB con label **penusb** nel PC.

2. **Esegui lo script**:
   - Copia il contenuto dello script in un file di testo e salvalo con estensione `.txt`.
   - Esegui lo script utilizzando un dispositivo come Flipper Zero o un emulatore di tastiera.

3. **Trova i dati estratti**:
   - Dopo l'esecuzione, il file `BrowserData.zip` sarà salvato nella radice della penna USB.
   - Apri il file ZIP per accedere ai dati estratti.

## Come leggere i dati estratti

I file estratti sono in formato SQLite o JSON.



