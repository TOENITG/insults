Shakespeare Insult Generator
===========
I detta projekt ska vi skapa flera olika förolämpningsprogram. Alla är inspirerade av denna variant och vi ska skriva om den några gånger.
https://github.com/katiequin335/ShakespeareanInsultGenerator/blob/master/Shakespeare.java
____________
Först: Ta alltid hjälp av varandra! Ingen programmerare är bättre än sin bästa kollega!
___________
Programmering 1
-----
Programmet här ovanför är just nu ganska så långt, onödigt långt. Läs försti genom vad du ska göra, så du har förstått instruktionerna. 
* Skapa ett projekt i NetBeans, låt det heta ``InsultGenerator``.
* Skapa en klass som heter ``InsultZero``och kopiera in koden ovan. Ändra det som behövs så att programmet går att köra och testa det.

* Första uppgiften är att skriva om programmet så att det stället för tre switch-case använder tra arrays för varje del och sedan, med hjälp av ```Math.Random()```slumpar tre ord, ett ur varje array, slår ihop detta och skriver ut på konsollen. Klassen ska heta ``InsultOne``.
* Andra uppgiften är att göra om första uppgiften och använda lämplig dialogruta för utskriften. Kolla på https://www.homeandlearn.co.uk/java/java_option_panes.html för hur de fungerar. Klassen ska heta ``InsultTwo``.
* Tredje uppgiften är ren överkurs, eftersom jag inte har talat om hur ni ska lösa det än:
** Programmet ska kunna startas från kommandoraden med en parameter som är ett heltal. Programmet ska sedan skriva ut lika många förolämpningar som parametern.
En ledtråd är ``public static void main(String[] args)`` där ni ska använda arrayen ``args`` på ett klokt sätt. Klassen ska heta ``InsultThree``.
________
Programmering 2
--------
Ni ska göra första och andrauppgiften från programmering 1, som uppvärmning och repetition av arrays. Sedan ska vi göra det svårare för oss.
* Skriv om förstauppgiften för programmering 1, så att allting sker i konstruktorn istället för i ``main()``. Låt era arrays bli ``private``, så ssyns de inte utanför klassen. Er main-matod ska enbart innehålla raden ``InsultFour insult = new InsultFour();``. Där fick ni även instruktion om vad klassfilen ska heta.

* Skapa nu tre textfiler där varie fil innehåller respektive array av förolämpningen. Det är bara texterna och inte måsvingar och kommatecken som ska vara med. Nu ska ni använda konstruktionen ``ArrayList<String>``för att lagra texterna. Här finns en bra genomgång https://www.w3schools.com/java/java_arraylist.asp att titta på. 
Alltså: Läs in de tre textfilerna till varsin ArrayList, som ni sedan slumpar en rad ur, sätter ihop och skickar till konsollen.
Här ska ni skapa en metod som returnerar en sträng som är den sammansatta förolämpningen. Vi ska göra så, för att vi ska återanvända denna klass i senare uppgifter. Klassen ska heta ``InsultFive``för enkelhets skull.
