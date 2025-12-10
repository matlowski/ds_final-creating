# ds_final-creating
Aby uruchomić notatnik należy wykonać poniższe kroki:
1. Zainstalować na swojej maszynie lokalnej najnowszą wersję pythona. Można to zrobić pobierając go z oficjalnej strony: https://www.python.org/ .
2. Następnym krokiem jest utowrzenie nowego folderu oraz wejście do niego: 

   $ mkdir new_folder 

   $ cd new_folder
    
4. W owym folderze należy utworzyć środowisko wirtualne:
   
   $ python -m venv venv
   
5. Kolejnym krokiem jest uaktywnienie środowiska wirtualnego, które może różnić się w zależności od systemu operacyjnego zainstalowanego na maszynie. Rozwiązania dla każdego systemu operacyjnego można znaleźć pod linkiem: https://docs.python.org/3/library/venv.html#how-venvs-work
6. Następnie należy zainstalować wszystkie pakiety zdefiniowane w pliku requirements.txt:

   $ pip install -r requirements.txt

7. Teraz należy uruchomić notatnik poleceniem:

   $ jupyter notebook
