# Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

id BIGINT PRIMARY KEY AUTO_INCRMENT,
id_brand INT(20) NOT NULL,
model VARCHAR(30) NOT NULL,
vin CHAR(17) UNIQUE NULL,
engine_type VARCHAR(15) NOT NULL,
gearbox VARCHAR(10) NULL,
shifts TINYINT(1) NULL,
release YEAR NULL,
price DECIMAL(10,2) NULL,
color VARCHAR(15) NULL,
body_type VARCHAR(15) NULL,
doors TINYINT(1) NULL,
feature TEXT(1000) NULL,
driving wheels TINYINT(1) NULL
image VARCHAR NULL,
available TINYINT(1) DEFAULT 0