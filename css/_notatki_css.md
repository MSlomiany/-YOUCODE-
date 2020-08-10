 # wybór przez selektor
 - można dodać id do np. nagłówka <h1 id="header">
    wtedy selektor przyjmie postać <h1#header {styl}>
 - można dodać znacznik np. <h1:first-child {styl}>
 - gwiazdka oznacza wszystkie znaczniki <* {styl}>
 - style pakujemy w znaczniki <style></style> najlepiej w <head>

 # osadzanie CSS w dokumencie HTML
 - w <head> <link rel="stylesheet" href="ścieżka">
 - można, ale nie polecany <h1 style="artubut1:wartosc1; atrybut2:wartosc2">    

 # color
 - <transparent> - przeźroczystość
 - <currentColor> - kolor z nadrzędnej sekcji, aktualny kolor

 div {
    height: 200px;
    background-color: royalblue;
    background-image: url(/content/kitku.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
}

