 # atrybuty input
 - <name> - nazwa pola
 - <value> - domyślna wartość wpisana w pole
 - <placeholder> - tekst wyświetlany w pustym polu
 - <type = "text"> - rodzaj inputu
 - <required> - konieczny do wypełnienia
 - <maxlength = "int"> - długość wpisu w środku
 - <autofocus> - automatyczne przeniesienie na pole formularza
 - <pattern> - wyrażenia regularne np. pattern="[a-zA-Z]{3,7}" - litery od A-Z małe i duże, od 3-7 liter
    - jeżeli chcemy dowolny pattern to pattern=".{2,} - pozwala na dowolne znaki, ale minimum 2 litery
 - <autocomplete ="on/off"> - autouzupełnianie
 - <disable> - dezaktywuje pole

 # atrybuty textarea
 - <rows = "int"> - liczba wierszy textarea
 - <cols = "int"> - liczba kolumn

 # atrybuty radio
 * <input type="radio"> - ustawienie inputu
 - <name> - pozwala uporządkować radia w jedną grupę (jednokrotny wybór)
 - <value> - konieczne do wysłania zaznaczonego radio
 - <checked> - domyślnie zaznaczone
 - <disable> - dezaktywuje pole
 - <required> - wymagane pole, wystarczy dodać do jednego z grupy
 - <autofocus> - przenosi na pole po odświeżeniu

 # atrybuty checkbox
 * <input type="checkbox"> - ustawienie inputu 
 - pozwala na wybór dowolnej liczby opcji, <name> nie działa ograniczająco
 - <required> powoduje, że konieczny jest wybór opcji z atrybutem <required>, chociaż inne również można
   
 # atrybuty select
 * <select name="name">
    * <option value="value">tutaj opcja</option>
 - <value> - wybrana wartość do przesłania
 - <name> - nazwa kategorii
 - <disabled> - zarówno do <select> jak i <option>, uniemożliwia wybór
 - <selected> - do <option>, zaznacza wybraną opcję domyślnie
 - <required> - do <select>, wymaga odpowiedzi
 - <autofocus> - do <select>, ustawia focus na pole wyboru
 - <multiple> - do <select>, umożlia zaznaczenie kilku elementów