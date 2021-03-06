<h1> Επικοινωνία Ανθρώπου Υπολογιστή</h2>

<h2> Ονοματεπώνυμο : Λάζατη Αικατερίνη - Μαρία</h2>
<h2> ΑΜ : Π2018077</h2>

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

<h3> Πίνκας Περιεχομένων</h3>

| Εβδομάδα | Παραδοτέο |
| --- | --- |
| 1 | [Εισαγωγή, περιγραφή των αναγκών και των στόχων μου για το μάθημα](#εισαγωγή,-περιγραφή-των-αναγκών-και-των-στόχων-μου-για-το-μάθημα) |
| 2 | [Άσκηση προγραμματισμού 1](#άσκηση-προγραμματισμού-1) | 
| 3 | [Άσκηση γραμμής εντολών 1](#άσκηση-γραμμής-εντολών-1) | 
| 4 | [Άσκηση προγραμματισμού 2](#άσκηση-προγραμματισμού-2) | 
| 5 | [Άσκηση γραμμής εντολών 2](#άσκηση-γραμμής-εντολών-2) | 
| 6 | [Συμμετοχικό περιεχόμενο A1 A2](#συμμετοχικό-περιεχόμενο-A1-A2) | 
| 7 | [Άσκηση προγραμματισμού 3](#άσκηση-προγραμματισμού-3 ) | 
| 8 | [Άσκηση γραμμής εντολών 3](#Άσκηση-γραμμής-εντολών-3) | 
| 9 | [Άσκηση προγραμματισμού 4](#Άσκηση-προγραμματισμού-4) | 
| 10 | [Άσκηση γραμμής εντολών 4](Άσκηση-γραμμής-εντολών-4) | 
| 11 | [Συμμετοχικό περιεχόμενο B1 B2](#Συμμετοχικό-περιεχόμενο-B1-B2) | 
| 12 | [Τελική αναφορά](#Τελική-αναφορά) [Πηγές](#Πηγές) | 

##
##
## Εισαγωγή, περιγραφή των αναγκών και των στόχων μου για το μάθημα

  Από το μάθημα **Επικοινωνία Ανθρώπου Υπολογιστή** (hci) προσδοκώ να έρθω σε επαφή με τα Unix συστήματα και να γνωρίσω πολυμεσικά (ή και μη) εργαλεία και εφαρμογές.\
    * Θα με ενδιέφερε να μάθω τους σκοπούς που εξυπηρετούν αυτές οι εφαρμογές/εργαλεία και πόσο επηρέασαν την σχέση ανθρώπου - υπολογιστή στο πέρασμα του χρλονου. Όπως για παράδειγμα, ποιός είναι ο λόγος που τα πλήκτρα του πληκτρολογίου έχουν αυτήν την διάταξη ή γιατί τα κουμπιά της ελαχιστοποίησης, τερματισμού των παραθύρων είναι πάνω δεξιά, πόσο βοήθησαν τα Windows για την εξάπλωση τον ηλεκτρονικών υπολογιστών τόσο στο εργασιακό περιβάλλον όσο και στα νοικοκυριά.    
    * Εκτός αυτού, σύμφωνα με της οδηγίες του μαθήματος περιμένω ότι θα ασχοληθούμε με πρακτικά θέματα όπως η δημιουργία εφαρμογών που αλληλεπιδρούν με τον χρήστη.  Αυτό, πιστεύω ότι θα είναι χρήσιμο για να μπορέσουμε να κατανοήσουμε τις δυσκολίες μου μπορεί να προκύψουν κατά την διάδραση με τον χρήστη.   

##
##
## Άσκηση προγραμματισμού 1

| Image Filter |https://github.com/KaterinaLaz/site/blob/master/_remix/image-filter.md|
| --- | --- |

  Χρησιμοποιήθηκαν τα φίλτρα `grayscale` και `hue-rotate`. 
  Το `hue-rotate` άλλαξε την θερμότητα τον χρωμάτων της εικόνας κατά 90 βαθμούς και το αποτέλεσμα είναι η εικόνα να έχει αποχρώσεις του **μπλε** και **ροζ**. 
  Το `grayscale` χρησιμοποιήθηκε ως hover έτσι όταν “περνάει” ο κέρσορας πάνω από την εικόνα αλλάζει χρωματικούς τόνους σε **άσπρο - μαύρο**.
  
  ![a](https://user-images.githubusercontent.com/56299928/103178251-ceab8a00-4889-11eb-938a-8a309fd31c4f.gif)

##
##
## Άσκηση γραμμής εντολών 1

| bash, neofetch, uname |https://asciinema.org/a/367451|
| --- | --- |

  Μέσω της εντολής  `sudo nano ~/.bashrc`  άλλαξα το command prompt name με το **ΑΜ** μου και παράλληλα από μπλέ χρώμα το άλλαξα σε **καφέ**. Αυτό επιτεύχθηκε με την τροποποίηση των γραμμών  `PS1` . Με την χρήση της εντολή  `source ~/.bashrc`  μπόρεσαν να εμφανιστούν  οι αλλαγές που προηγήθηκαν. \
  Με την εντολή  `neofetch`  εμφανίστηκαν στοιχεία, όπως το λειτουργικό που χρησιμοποιήθηκε, ποια είναι η κάρτα γραφικών του συστήματος κ.ο.κ. Το συγκεκριμένο command είναι χρήσιμο για περιπτώσεις που ο χρήστης επιθυμεί να πληροφορηθεί για τα τεχνικά χαρακτηριστικά του συστήματος του τόσο σε επίπεδο Software όσο και σε επίπεδο Hardware. Οι εντολές  `lscpu`  `free –giga`  `unake -v`  παρέχουν την δυνατότητα μιας ποιο εξειδικευμένης γνώσης για το σύστημα. Οι  `lscpu`  και  `free –giga`  απευθύνονται σε χαρακτηριστικά που αφορούν το Hardware ενώ  η  `unake -v`  στο Software. \
  Τέλος, παρουσιάστηκαν οι φάκελοι που έχει το σύστημα που χρησιμοποιώ, μέσο της εντολής  `ls`  και στην συνέχεια με την εντολή  `cd`  άλλαξα την διεύθυνση προς τον φάκελο που επιθυμώ να εργαστώ (Desktop). Έτσι, μέσο της  `less`  άνοιξα το αρχίσω *hel.txt*. 
  
  Καταγραφή με : asciinema 
  
  [![asciicast](https://asciinema.org/a/367451.svg)](https://asciinema.org/a/367451)
  
##
##
## Άσκηση προγραμματισμού 2

| Image Zoom |https://github.com/KaterinaLaz/site/blob/master/_remix/image-zoom.md |
| --- | --- |

  Σε αυτήν την εργασία χρησιμοποίησα το φίλτρο `.tint` από την εργασία **Image Processing**. Όταν ο κέρσορας "περνάει" από πάνω αλλάζουν οι χρωματικοί τόνοι στην δοθήσα φωτογραφία. 
  
  ![b](https://user-images.githubusercontent.com/56299928/103178422-5776f580-488b-11eb-97d1-ff15b7681f20.gif)

##
##
## Άσκηση γραμμής εντολών 2

| Vim |https://asciinema.org/a/371629|
| --- | --- |

  Η αρχική μορφή του **vim** ήταν πολύ απλή, έτσι λοιπόν εγκατέστησα τα plugins `vundle` κ’ `plug-in`.
  * **Vundle** : 
      Xρησιμοποιήθηκε κυρίως για το οπτικό αποτέλεσμα. 
      Παρόλο που κατέβασα αρκετά πακέτα κατέληξα να χρησιμοποιήσω το `guvboxr` το οποίο έχει μια retro μορφή με την βοήθεια του `.vimrc` και εντολών *set*.
  * **Plug-in** :
      Χρησιμοποίησα τα πακέτα `python-mode` , `jedi-vim` και `NERDTree`. 
      Τα  `python-mode` κ `jedi-vim`  μετατρέπουν το vim σε python editor όπου με τα πλήκτρα <Ctl+Space> εμφανίζετε η συντακτική συμπλήρωση που ενδέχεται να ταιριάζει σύμφωνα με την Python3.  
      Το `NERDTree` ουσιαστικά βοηθάει στην πλοήγηση στα αρχεία μέσο του vim.
 Εκτός από τα plugins χρησιμοποίησα την εντολή *set* για να προσθέσω αριθμούς στα αριστερά, όταν πατείτε το <Tab> μετακινείται ο κέρσορας 4 θέσεις και τέλος η γραμμή που τροποποιήθηκε τελευταία αποκτά μια σκίαση και το νούμερο της φωτίζεται ενώ τα νούμερα των υπόλοιπων γραμμών γίνονται γκρι. 
      
   Καταγραφή με : asciinem
  
  [![asciicast](https://asciinema.org/a/371629.svg)](https://asciinema.org/a/371629)
    
##
##
## Συμμετοχικό περιεχόμενο A1 A2
      
   Λόγο δικής μου παράληψης την 6η Εβδομάδα θα έπρεπε να είχα καταθέσει το συμμετοχικό υλικό και να μην είχα κάνει την Άσκηση Γραμμής Εντολών 3 καθώς προοριζόταν για την 7η Εβδομάδα σύμφωνα με της οδηγίες του μαθήματος (https://github.com/courses-ionio/hci).
   Δυσκολεύτηκα με το Netlify και δεν μπόρεσα να ακολουθήσω της οδηγίες. 
   
   
   | A1 | A2 |
   |---| --- |
   | [Iphone](https://github.com/KaterinaLaz/site/blob/master/iphone.md) | [Iphone Slides](https://github.com/KaterinaLaz/site/blob/master/_slides/method.md)| 
   | [Makey Makey](https://github.com/KaterinaLaz/site/blob/master/makey-makey.md) |[Iphone Timeline](https://github.com/KaterinaLaz/site/blob/master/_timeline/personal.md) |  
   | [Makey Makey Pic](https://github.com/KaterinaLaz/images/blob/e160742e4abc437f612fa11698a6f0fc174eab90/arduino.jpg) |[Makey Makey Slide](https://github.com/KaterinaLaz/site/blob/master/_slides/archetypes.md)|  
   | [Makey Makey Thumb Pic](https://github.com/KaterinaLaz/images/blob/2f47e8ee4b381c65740d3a8a8cd873a1561db4e5/arduino_mikri.png) |[Makey Makey Timeline](https://github.com/KaterinaLaz/site/blob/master/_timeline/learning.md)| 
   | [Iphone Pic](https://github.com/KaterinaLaz/images/blob/90e7609c12dd454303ec1f9274b957c409e327cd/iphone.png) | |
   | [Iphone Thumb Pich](https://github.com/KaterinaLaz/images/blob/15cb9911d5e9463b068609c07fdb23a382d10d1b/iphonw_mikro.png) | |
   
    
 ##       
 ##
 ## Άσκηση προγραμματισμού 3 
 
 | Sortable List | https://github.com/KaterinaLaz/site/blob/master/_remix/sortable-list.md |
 | --- | --- |
      
   Αρχικά, οι πίνακες με τα “Αντικείμενα “ μετακινήθηκαν στην μέση της οθόνης και αυξήθηκε ο κενός χώρος ανάμεσα από τον κάθε πίνακα κατά **30 pixel**. Εκτός αυτού το πλαίσιο των πινάκων μειώθηκε κατά **50%** και η γραμμή του περιγράμματος των πινάκων αυξήθηκε, δηλαδή έγινε ποίο χοντρή. \
   Στην συνέχεια, άλλαξε το χρώμα του background καθώς και τα χρώματα των γραμμάτων σε **Dark Slate Gray**, το background των πινάκων σε **Moccasin** και το περίγραμμα των πινάκων σε **Black**. 
           
  ![133484046_481246509522402_7980599394025225810_n](https://user-images.githubusercontent.com/56299928/103178439-72496a00-488b-11eb-8e4f-22fda1c828e4.png)

##
##
## Άσκηση γραμμής εντολών 3
      
   | Youtube-dl, Mocp | https://asciinema.org/a/375737 |
   | --- | --- |
      
   Δημιούργησα ένα **Directory** μέσα στο οποίο αποθήκευσα το τραγούδι **Adele – Rolling in the Deep** και τα **Thumbnails** του βίντεο. 
   Με το command `youtube-dl -x` έγινε εγκατάσταση μόνο του ήχου/τραγούδι από το βίντεο και με το command `youtube-dl --write-thumbnail` έγινε εγκατάσταση μόνο των Thumbnails. 
   Με την εφαρμογή **Mocp** περιηγήθηκα στα αρχεία του μηχανήματός μου και πραγματοποιήθηκε αναπαραγωγή του τραγουδιού. Το command `display` συνέβαλε στο να ανοίξω το αρχείο της εικόνας. 
   
   Καταγραφή με : asciinema
   
  [![asciicast](https://asciinema.org/a/375737.svg)](https://asciinema.org/a/375737)       

##
##
## Άσκηση προγραμματισμού 4
   
| Form Validation | https://github.com/KaterinaLaz/site/blob/master/_remix/form-validation.md |
| --- | --- |
      
  Στην άσκηση Form Validation πραγματοποιήθηκαν οι ακόλουθες αλλαγές. Προστέθηκαν τα πλαίσια **Email** και **Credit Card** σύμφωνα με την εκφώνηση της άσκησης. Συγκεκριμένα, ένα **Email** γίνεται αποδεκτό όταν έχει κατάληξη `@` και η **Credit Card** όταν δίνετε με την μορφή `χχχχ-χχχχ-χχχχ-χχχχ`. Στο ήδη υπάρχον πλαίσιο **Phone Number** το νούμερο γίνεται αποδεκτό μόνο αν έχει την μορφή `χχχχ-χχχχχ`.Επιπλέων, το backgraound από λευκό έγινε Light Gray σύμφωνα με την χρωματική παλέτα στο σάιτ της CSS.
  Για να καταφέρω να πραγματοποιήσω τον έλεγχο εισόδου δεδομένων στα πλαίσια συμβουλεύτικα το Client-Side Form Validation with HTML5.Ο. Ο έλεγχός είναι παρόμοιος μεταξύ των πλαισίων **Phone Number** και  **Credit Card**, όπου ουσιαστικά εξετάζει αν υπάρχει το κατάλληλο πλήθος αριθμών στο πλαίσιο. Ενώ, για το **Email** το χρησιμοποιησά την τεχνική που αναγράφει το άρθρο για το Twitter Username. 
  
  ![133786285_198362608638744_7027225024658162511_n](https://user-images.githubusercontent.com/56299928/103178447-88572a80-488b-11eb-883e-c02579335ce8.png)
        
##
##
## Άσκηση γραμμής εντολών 4
| Groff | https://www.dropbox.com/s/xyax53o1pgtehr2/Peek.gif?dl=0 |
| --- | --- |
      
  Η συγκεκριμένη άσκηση γραμμής εντολών άργησε κατά δύο βδομάδες να γίνει Comite. Η καθυστέρηση οφείλεται στο ότι υπολόγιζα τα συμπεράσματα της αναφοράς μου να τα γράψω χρησιμοποιώντας το **Vim** και το **Groff** αλλά το τελικό παραγόμενο αρχείο δεν αναγνώριζε τους ελληνικούς χαρακτήρες με αποτέλεσμα να μην μπορώ να το χρησιμοποιήσω.
  Στο **gif** απεικονίζεται ένα ενδεικτικό παράδειγμα. Συγκριμένα, το παραγόμενο αρχείο έχει έναν τίτλο (**General Commands Manual groff**), έναν συγγραφέα (**Lazari Katerina - Maria**) και δύο ενότητες. Στην πρώτη ενότητα, χρησιμοποιούνται εργαλεία παραμετροποίησης της παραγράφου και του κειμένου. Συγκεκριμένα, χρησιμοποιείται η εντολή `.IP – 2` που δημιουργεί λίστες και οι εντολές `.B` , `\[B]….\f[]` που την επιλεγόμενη λέξη/φράση την μετατρέπουν σε Bold. Στην δεύτερη χρησιμοποιούνται εργαλεία που αφορούν την μορφή της αναφοράς, όπως εργαλεία που δημιουργούν  πίνακες, κουτιά και εισάγουν εικόνες. Το κουτί δημιουργούται από τις εντολή `.BX`, ο πίνακας με τις εντολές `.TS` και `.TE` και η εικόνα γίνεται εισαγωγή με την εντολή `.PDFPIC`.  Tο φυσικό μέγεθος της εικόνας ήταν μεγάλο με αποτέλεσμα να δημιουργείται δεύτερη σελίδα. Αυτό το πρόβλημα αντιμετωπίστηκε σμικρύνοντας  και τοποθετώντας  στο αριστερό κομμάτι της σελίδας την εικόνα.
  Στο τέλος της σελίδας αναγράφεται η ημερομηνία που δημιουργήθηκε το αρχείο, αυτό πραγματοποιείται με την εντολή `.DA` στο Vim αρχείο.  
  
  Καταγραφή με την εφαρμογή peek, δημιουργήθηκε ένα gif το οποίο ανεβάστηκε στο προσωπικό μου dropbox. 
  
  ![Peek](https://user-images.githubusercontent.com/56299928/103178196-5a70e680-4889-11eb-82bf-4f8212600828.gif)       
    
##         
##
## Συμμετοχικό περιεχόμενο B1 B2
      
| Β1 | Β2 |   
| --- | --- |
| [Η Scratch ως εκπαιδευτικό εργαλείο](https://github.com/KaterinaLaz/site/blob/master/_case-study/scratch-and-education.md) | [Steve Jobs](https://github.com/KaterinaLaz/site/blob/master/_biography/steve-jobs.md) |
      
 ##
 ##
 ## Τελική αναφορά
      
  Οι στόχοι που είχα θέσει στην αρχή του εξαμήνου περιορίζονταν επί το πλείστον στο θεωρητικό πλαίσιο του μαθήματος και δεν μπορούσα να φανταστώ το πρακτικό μέρος του. Για να καταφέρω να ανταποκριθώ στις ασκήσεις του συμμετοχικού υλικού αναγκάστηκα να μελετήσω το βιβλίο του μαθήματος, γεγονός που με χαροποίησε, καθώς έμαθα την ιστορία αντικειμένων και εργαλείων που σημάδεψαν την σύγχρονη τεχνολογική ιστορία. Παράλληλα, οι ασκήσεις προγραμματισμού και γραμμής εντολών μου έδειξαν την άλλη πτυχή του μαθήματος που δεν είχα φανταστεί. Κάποια εργαλεία, όπως το Vim, που ήταν αρκετά δύσχρηστα με έβαλα στην διαδικασία να ψάξω τρόπους με τους οποίους θα ήταν ποιο εύκολη η διεπαφή με τον χρήστη. Τέλος, μου ήταν ευχάριστο, παρόλο που δυσκολεύτηκα αρκετά, το ότι ήρθα σε μια πρώτη επαφή με τις τεχνολογίες διαδικτύου.
           
##
##
### Πηγές
 
  * **Image Filter** :
    * 1 : [HTML](https://www.w3schools.com/html/default.asp)
    * 2 : [CSS](https://www.w3schools.com/css/default.asp) 
  * **Bash, Neofetch, Uname** :
    * 3 : [bash Command](https://phoenixnap.com/kb/change-bash-prompt-linux)
    * 4 : [neofetch Command](https://www.cyberciti.biz/howto/neofetch-awesome-system-info-bash-script-for-linux-unix-macos/) 
    * 5 : [uname Command](https://www.computerhope.com/unix/uuname.htm)
    * 6 : [Asciinema usage](https://asciinema.org/docs/usage)
  * **Vim** :
    * 7 : [Vim Editor tutorial](https://staff.washington.edu/rells/R110/) 
    * 8 : [Vim Editor tutorial](https://linuxhint.com/vimrc_tutorial/)
    * 9 : [Vundle tutorial](https://linuxhint.com/vim-vundle-tutorial/)
    * 10 : [Vundle](https://github.com/VundleVim/Vundle.vim)
    * 11 : [vim-colors-solarized](https://vimawesome.com/plugin/vim-colors-solarized-ours) 
    * 12 : [colors-solarized github](https://github.com/altercation/vim-colors-solarized)  
    * 13 : [guvboxr](https://vimawesome.com/plugin/guvboxr) 
    * 14 : [jedi-vim](http://i05nagai.github.io/memorandum/vim/jedi_vim.html) 
    * 15 : [jedi-vim github](https://github.com/davidhalter/jedi-vim) 
    * 16 : [python-mode github](https://github.com/python-mode/python-mode)  
    * 17 : [python-mode](https://realpython.com/vim-and-python-a-match-made-in-heaven/)
    * 18 : [vim-plug github](https://github.com/junegunn/vim-plug) 
    * 19 : [vim-python github](https://github.com/Vimjas/vim-python-pep8-indent) 
    * 20 : [NERDTree](https://vimawesome.com/plugin/nerdtree-red)
    * 21 : [set](https://linuxhint.com/configure_vim_vimrc/)
  * **Συμμετοχικό Περιεχόμενο A1 A2** :
    * 22 : [Iphone 1st Generetion - wiki](https://ehn.wikipedia.org/wiki/IPhone_)
    * 23 : [Makey Makey](https://makeymakey.com/pages/mission) 
  * **Sortable List** :
    * 2 : [CSS](https://www.w3schools.com/css/default.asp)
    * 23 : [CSS Colors](https://www.w3schools.com/cssref/css_colors.asp)
  * **Youtube-dl, Mocp** :
    * 25 : [youtube-dl github](https://github.com/ytdl-org/youtube-dl)
    * 26 : [Mocp github](https://github.com/jonsafari/mocp)
  * **Form Validation** :
    * 2 : [CSS](https://www.w3schools.com/css/default.asp)
    * 27 : [Client-Side Form Validation with HTML5](https://www.sitepoint.com/client-side-form-validation-html5/)
  * **Groff** :
    * 28 : [roff(7) - Linux manual page](https://man7.org/linux/man-pages/man7/roff.7.html)
    * 29 : [groff(1) - Linux manual page](https://man7.org/linux/man-pages/man1/groff.1.html)
    * 30 : [groff - Paragraphs-ms ](https://www.gnu.org/software/groff/manual/html_node/Paragraphs-in-ms.html)
    * 31 : [Tbl -- A Program to Format Tables](http://www.snake.net/software/troffcvt/tbl.html)
    * 32 : [Notes About groff](http://xed.ch/h/groff.html)
    * 33 : [Customizing groff/troff Macros and Other Basics - Video](https://www.youtube.com/watch?v=kJ_TXZB4Gm4)
    * 34 : [How to add images into groff ms documents Linux - Video](https://www.youtube.com/watch?v=TEsMqoYKw38)
  * **Εργαλεία καταγραφής** :
    * [asciinema](https://asciinema.org)
    * [peek github](https://github.com/phw/peek)
  * **Λοιπα εργαλεία** : 
    * [dropbox](https://www.dropbox.com/?landing=dbv2)
    * [README-Template.md](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
    * [P15GitHubStudent/SW_REPORT](https://github.com/P15GitHubStudent/SW_REPORT/blob/master/README.md)
    * [How to add gif/image to github in 10 SECONDS! - Video](https://www.youtube.com/watch?v=6NtplFpCMBM)

  




  
