# Spanzuratoarea---Proiect-
Implementarea jocului Hangman (Spânzurătoarea) pe placa Nucleo

La începutul jocului se generează un cuvânt aleator de lungime variabilă (aleasă destudenţi) şi, pentru fiecare caracter din cuvânt, se afişează „_” pe prima linie a afişajului LCD. 
Utilizatorul trebuie să ghicească cuvântul, având 6 încercări.
Caracterul dorit este ales de utilizator, la un moment dat, prin folosirea a 3 butoane (pushbuttons): un buton este folosit pentru parcurgerea caracterelor în ordine alfabetică (fiecare apăsare determină trecerea la următoarea literă), un buton va parcurge caracterele în ordine inversă, iar cel de-al treilea buton va confirma selecţia caracterului dorit. Dacă respectiva literă se află în cuvânt, pe poziţiile corespunzătoare din cuvânt se va afişa acea literă, in loc de „_”.
În cazul în care caracterul nu se află în cuvânt, numărul de încercări rămase este decrementat. Numărul de încercări se afişează pe LED-uri sau pe un rang din afişajul cu 7 segmente. În momentul în care numărul de încercări rămase ajunge la 0, afișajele cu 7 segmente se vor aprinde într-o configurație specială: de exemplu se aprind segmentele de pe exterior (a,b,c,d,e,f) pe rând, cu viteză mare.
Jocul se termină în momentul în care cuvântul a fost ghicit sau numărul de încercări a ajuns la 0, afişându-se un mesaj corespunzător pe LCD.
