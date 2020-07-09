 <button atributes>opis</button>
 
 # atrybuty przycisków
 - <disabled> - wyłącza przycisk
 - <type> - rodzaj, domyślnie <type = "submit">
    - <submit> - przesyła wpisaną odpowiedź
    - <reset> - czyści pole formularza
 - button można zastąpić przez <input type="submit">
    - <button type="submit">nazwa</button> == <input type="submit" value="nazwa">
    - w <input> można podać również <type = "reset">
 
 # pozostałe rodzaje inputów
 - IE i SAFARI nie obsługuje
  * date
  * datetime-local
  * month
  * time
  * week
 - IE nie obsługuje
  * color
 - FIREFOX nie obsługuje
  * datetime-local
  * month
  * week

# inne inputy
 - <input type="password"> - pozwala na wpisanie zakropkowanego hasła
 - <input type="color"> - pozwala na wybór koloru, zwraca kolor w HEX
 - <input type="date"> - data
 - <input type="month"> - miesiąc/rok
 - <input type="time"> - godzina
 - wszystkie typy z datą/czasem można podać z atrybutem min/max
 - <input type="email"> - sprawdza czy jest "@"
 - <input type="file"> - plil
 - <input typee="hidden"> - ukryte pole
 - <input type="number"> - pozwala na liczby z domyślnym <step = "1">