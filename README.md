# MyTask
Spirng app without frontend

<h2>Popis projektu</h2>
Webová aplikace slouzi lidem po cele CR.
Poskytuje možnost zjednodušit zivot linym nebo produktivnim lidem, tím že oni mohou vytvářet tasky(napr.: “Vyhodte odpadky za 100 Kc”, “Kupte potraviny a uvařte mi večeři za 500Kc” atd.)
Zaroven lidi mohou se hlasit k tasky a vydelavat za ně penize.

<h2>Struktura projektu:</h2> 

User muze mit 2 role:
1) role_user
2) role_admin

Role_user umoznuje useru delat takove akce:

1.Vytvorit,upravovat, smazat task <br>
2.Vytvorit,upravovat, smazat comment <br>
3.Poslat acceptanceMessage(zajem o vyplneni taska)<br>
4.Oznacit task jako vyplneny (jako performer, jako owner)<br>
5.Podtvrdit acceptanceMessage(jako owner tasku naznacit konkretniho performera)<br>
6.Posilat zpravy (messages)<br>

Role_admin umoznuje useru delat vsechno, co muze delat obycejny user. 
Navic:

1.Smazat usera <br>
2.Vytvorit, smazat category <br>
3.Pridat, smazat task z category<br>


<h2>Navod na instalovani:</h2>

1.Vytvorit database myTask (username: postgres, password: admin)<br>
2.Pripojit se k database myTask v idea <br>
3.Spustit projekt <br>

Pro testovani aplikace jsme vytvorili nektere kolekce v postman.

<h2>Zkusenosti:</h2> 

Naučili jsme se tyto technologie: Spring security, JPA, Spring Boot, Elcipselink. Bohužel je nemůžeme porovnat s nějakými jinými technologiemi, jelikož zatím nemáme dostatek zkušeností  
