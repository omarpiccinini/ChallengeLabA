Point 1:

# Remove directory

sudo rm -d direcotory      for  empty directory
sudo rm -r direcotory      for  non-empty directory

# Cambia directory in root

cd /

# Crea una o piu directory

@jacopo-zorza ➜ / $ sudo mkdir /IS
@jacopo-zorza ➜ / $ sudo mkdir /Engineering
@jacopo-zorza ➜ / $ sudo mkdir /Sales

# Crea un nuovo account di gruppo

@jacopo-zorza ➜ / $ sudo groupadd IS
@jacopo-zorza ➜ / $ sudo groupadd Engineering
@jacopo-zorza ➜ / $ sudo groupadd Sales

# Crea il gruppo e ci aggiunge l'utente

@jacopo-zorza ➜ / $ sudo useradd -m -s /bin/bash -g Engineering Engineering-admin
@jacopo-zorza ➜ / $ sudo useradd -m -s /bin/bash -g IS IS-admin
@jacopo-zorza ➜ / $ sudo useradd -m -s /bin/bash -g Sales Sales-admin

@jacopo-zorza ➜ / $ sudo useradd -m -s /bin/bash -g Engineering user2
@jacopo-zorza ➜ / $ sudo useradd -m -s /bin/bash -g IS user3
@jacopo-zorza ➜ / $ sudo useradd -m -s /bin/bash -g Sales user4

# Modifica il proprietario del file
@jacopo-zorza ➜ / $ sudo chown IS-admin.IS /IS
@jacopo-zorza ➜ / $ sudo chown Engineering-admin.Engineering /Engineering
@jacopo-zorza ➜ / $ sudo chown Sales-admin.Sales /Sales

# Modifica accesso al file

@jacopo-zorza ➜ / $ sudo chmod 1770 /IS
@jacopo-zorza ➜ / $ sudo chmod 1770 /Engineering 
@jacopo-zorza ➜ / $ sudo chmod 1770 /Sales

# Crea il documento all'interno del gruppo

@jacopo-zorza ➜ / $ sudo nano /IS/example.txt
@jacopo-zorza ➜ / $ sudo nano /Sales/example.txt
@jacopo-zorza ➜ / $ sudo nano /Engineering/example.txt

# Creo le password

@jacopo-zorza ➜ / $ sudo passwd user3 (Password3)
@jacopo-zorza ➜ / $ sudo passwd user2 (Password2)
@jacopo-zorza ➜ / $ sudo passwd user4 (Password4)

# Imposta la proprietà e le autorizzazioni per la directory /IS

@jacopo-zorza  ➜ / $ sudo chown IS-admin.IS /IS
@jacopo-zorza ➜ / $ sudo chmod 770 /IS

# Imposta la proprietà e le autorizzazioni per la directory /Engineering

@jacopo-zorza ➜ / $ sudo chown Engineering-admin.Engineering /Engineering
@jacopo-zorza ➜ / $ sudo chmod 770 /Engineering

# Imposta la proprietà e le autorizzazioni per la directory /Sales

@jacopo-zorza ➜ / $ sudo chown Sales-admin.Sales /Sales
@jacopo-zorza ➜ / $ sudo chmod 770 /Sales

# Crea un documento nella directory /IS

@jacopo-zorza ➜ / $ sudo nano /IS/confidential.txt

# Scrivi: "This file contains confidential information for the department."

# Imposta la proprietà e le autorizzazioni per il documento nella directory /IS

@jacopo-zorza ➜ / $ sudo chown IS-admin.IS /IS/confidential.txt
@jacopo-zorza ➜ / $ sudo chmod 740 /IS/confidential.txt

# Ripeti la stessa procedura per le directory /Engineering e /Sales

@jacopo-zorza ➜ / $ sudo nano /Engineering/confidential.txt
@jacopo-zorza ➜ / $ sudo chown Engineering-admin.Engineering /Engineering/confidential.txt
@jacopo-zorza ➜ / $ sudo chmod 740 /Engineering/confidential.txt

@jacopo-zorza ➜ / $ sudo nano /Sales/confidential.txt
@jacopo-zorza ➜ / $ sudo chown Sales-admin.Sales /Sales/confidential.txt
@jacopo-zorza ➜ / $ sudo chmod 740 /Sales/confidential.txt