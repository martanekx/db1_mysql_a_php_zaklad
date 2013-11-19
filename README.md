DB1 - základy PHP a MySql
======================

Popis souborů:
--------------
- index.php - hlavní soubor, který se spustí po příchodu na danou doménu

- inc/db_settings_EMPTY.inc.php - musíte změnit na db_settings.inc.php a doplnit údaje pro připojení k DB. 
Ukázka pro server students.kiv.zcu.cz:

			define("ORACLE_DATABASE_SERVER", "localhost");
			define("ORACLE_DATABASE_NAME", "");
			define("ORACLE_DATABASE_USER", "login");
			define("ORACLE_DATABASE_PASSWORD", "heslo");


- inc/predmety.class.php - vrstva zajišťující napojení na danou databázi

- css - adresář pro umístění CSS stylů a souvisejících obrázků


Další návody online:
--------------
- PHP a PDO detailně: http://wiki.hashphp.org/PDO_Tutorial_for_MySQL_Developers
- Úvod do PHP a PDO: http://www.phpro.org/tutorials/Introduction-to-PHP-PDO.html