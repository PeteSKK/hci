# Επικοινωνία ανθρώπου υπολογιστή
**Ονοματεπώνυμο: Θωμάς-Σπυρίδων Πασχάλης   
ΑΜ: Π2019110**      
**profile:** https://github.com/p19pasc   
**netlify:** https://codingexercisesp2019110.netlify.app/
| Εβδομάδα* | Παραδοτέο |
| --- | --- |
| 1 |**[Εισαγωγή](#Στόχοι-και-ανάγκες-του-μαθήματος)** - **[Περιγραφή εργαλείων](#Περιγραφή-εργαλείων)**| 
| 2 |**[Mouse form](#Mouse-Form)**| 
| 3 |**[Set-up the main dependencies and demonstrate your base system](#set-up-the-main-dependencies-and-demonstrate-your-base-system)**|
| 4 |**[Mouse option](#Mouse-option)**|
| 5 |**[Text editor and plug-ins for code highlighting and autocompletion](#text-editor-and-plug-ins-for-code-highlighting-and-autocompletion)**| 
|   |**[Check the weather](#check-the-weather)**|
| 6 |**[Συμμετοχικό περιεχόμενο Α μέρος](#Συμμετοχικό-περιεχόμενο-Α-μέρος)**|
| 7 |**[Image processing](#image-processing)**|
| 8 |**[Download mp3](#Download-mp3)**|
| 9 |**[Image zoom](#Image-zoom)**|
| 10 |**[Μanage your bookmarks](#Manage-your-bookmarks)**|
| 11 |**[Συμμετοχικό περιεχόμενο Β μέρος](#Συμμετοχικό-περιεχόμενο-Β-μέρος)**|
|    |**[Συμπεράσματα](#Συμπεράσματα)**|
| 12 | Τελική αναφορά* |     
<br>

Ο παραπάνω πίνακας αποτελεί αναφορά των ασκήσεων που υπολοποίησα σε όλη την διάρκεια του εξαμήνου οι οποίες καλύπτουν σε έναν γενικό βαθμό τις βασικές γνώσεις για την ενασχόληση 
με τις γλώσσες προγραμματισμού **HTML** και **CSS** κυρίως, ενώ το ίδιο συμβαίνει και για την γραμμή εντολών. Όσον αφορά τις εργασίες που πραγματοποιήσα(οι οποίες είναι όλες εμπρόθεσμες) και αφιέρωσα αρκετό κόπο και χρόνο καταχωρήθηκε μια μεγαλύτερη προσπάθεια για την υλοποίηση pipelining και shell scriptint(χωρίς βέβαια να είναι απολύτως επιτυχής), καθώς και έκανα χρήση διαφορετικών εργαλείων για την παρουσίαση των ίδιων ζητουμένων της κάθε άσκησης. Παρομοίως δίνοντας έμφαση στον παράγοντα του χρόνου αυτή την φορά, κάλυψα τις βασικές απαιτήσεις του συμμετοχικού περιεχομένου με ικανοποιητικές πληροφορίες και εικόνες. Συμπληρώνοντας, η αναζήτηση στο διαδίκτυο ήταν απαραίτητη ιδιαίτερα στις ασκήσεις γραμμής εντολών και συμμετοχικού περιεχομένου και βρίσκεται στην κατηγορία **[Πηγές πληροφοριών](#Πηγές-πληροφοριών)**.   

# Στόχοι και ανάγκες του μαθήματος

Έχοντας διασχίσει το πρώτο έτος του τμήματος πληροφορικής του Ιονίου πανεπιστημίου οδεύουμε στο να συναντήσουμε το μάθημα "Επικοινωνία ανθρώπου υπολογιστή". Μέσα από τον τίτλο
του μαθήματος αναγνωρίζουμε την αξία του και τις γνώσεις που μας προσδίδει. Ως πρώτη επαφή με το αντικείμενο νιώθουμε την ανάγκη να κατανοήσουμε κάποια βασικά χαρακτηριστικά όπως το χρονικό διάγραμμα που αναφέρεται και τις εφαρμοργές της τεχνολογίας που ασχολείται. Ακόμη είναι σημαντικό να γνωρίζουμε τους διαφορετικούς τρόπους με τους οποίους ο άθρωπος αλληλεπιδρά με τους υπολογιστές καθώς και να αποκτήσουμε κριτική σκέψη για την ύπαρξη τους γύρος μας, αφού αποτελούν αναπόσπαστο κομμάτι της καθημερινότητας. Ας ελπίσουμε μέσα από το μάθημα αυτό να διασφαλίσουμε τις γνώσεις που μας προσφέρει και να ανακαλύψουμε γεγονότα και πληροφορίες τις οποίες δεν έχουμε συναντήσει.

# Περιγραφή εργαλείων

Αναφερόμενος για τις ασκήσεις προγραμματισμού εργαστήκαμε ανεπιφύλακτα στην πλατφόρμα **Codepen** που αναπαριστά τον συνδυασμό τριών γλωσσών προγραμματισμού **HTML**,**CSS**, **JS**. Μεγαλύτερη βαρύτητα δίνεται στην γραμμή εντολών δηλαδή στο περιβάλλον linux, όπου βασικά εργαλεία είναι το **Homebrew** και **Asciinema** αφού επιτρέπουν την εγατάσταση επιμέρους εργαλείων και την καταγραφή του terminal αντίστοιχα. Ξεκινόντας από τις βασικές ασκήσεις(warmup) εμφανίζονται οι κύριες εντολές όπως `nano`,`ls -a` και τα εργαλεία
**neofetch** , **VIM** , **Wttr.in** και παρόμοια, με τα οποία παρουσιάζουμε τα χαρακτηριστικά του υπολογιστή, επεξεργαζόμαστε αρχεία και παρακολουθούμε τις καιρικές συνθήκες. Εμβαθύνοντας σε γενική μορφή  πραγματοποίησα συνδυασμό των **Googler** , **Youtube-dl** , **Buku** που αποσκοπούν στις αναζητήσεις στο διαδίκτυο και την εγκατάσταση αρχείων τύπου mp3,mp4,gif κτλπ. Επιπλέον για να μην παραλείψω το συμμετοχικό περιεχόμενο το βασικό εργαλείο που χειρίστικα ήταν το **Git** με την βοήθεια της αναζήτησης στο **Google**
για την ενασχόληση με git submodules. Όλα αυτά που συνέβαλαν στην ολοκλήρωση των εργασιών λοιπόν, αναλύονται ακόμη περισσότερο παρακάτω.
# Ασκήσεις προγραμματισμού
### Mouse Form

Όπως αναφέρεται και στον πίνακα περιεχομένων την συκγεκριμένη εβδομάδα πραγματοποίησα μια από τις εργασίες προγραμματισμού. Ώς πρώτη εντύπωση οι κώδικες από τις εργασίες που μας δόθηκαν φαίνοταν απαιτητικοί και δημιούργησαν μεγάλη σύχγχυση. Ανάμεσα στην μεγάλη λίστα  των ασκήσεων προγραμματισμού έχοντας εξερευνίσει τις απαιτήσεις από  κάποιες από αυτές κατέληξα να πραγματοποιήσω την **"Mouse Form"**. Πρόκειται για ένα παράθυρο που εφμανίζεται στο χρήστη τον οποίο υποχρεώνει να συμπληρώσει αναλυτικά την ημερομηνία γέννησης του κάτι το οποίο είναι πολύ συνηθισμένο στον χώρο του διαδικτύου. Ο κώδικας βασιζόταν στην HTML και CSS αποκλειστικά γεγονός το οποίο με οδήγησε στο να εστιάσω απλός στις δύο αυτές γλώσσες προγραμματισμού και ειδικότερα στην HTML. Η μόνη απαίτηση λοιπόν ήταν να προσαρμόσω κάποιες ήδη υπάρχουσες εντολές που επαναλαμβάνοταν διαρκώς ώστε να δημιουργήσω ένα επιπλέον κουτάκι που παίρνει ως δεδομένα τα φύλα (άνδρας,γυναίκα).
* Σύνδεσμος για: [pibook](https://github.com/p19pasc/site/blob/master/_remix/mouse-form.md)    
* Σύνδεσμος για: [pibook(Netlify)](https://codingexercisesp2019110.netlify.app/remix/mouse-form/) 
* Σύνδεσμος για: [codepen](https://codepen.io/p19pasc/pen/rNLLOwd)
<br>

### Mouse option
 
<img align="right" width="500" height="410" src="https://i.postimg.cc/rFnGKQHh/Screenshot-248.png"> 
Ύστερα από αρκετή ώρα αναζήτησης στις διαθέσιμες ασκήσεις προγραμματισμού κατέληξα να επιλέξω την συγκεκριμένη άσκηση . Πρόκειται για ένα πλαίσιο το οποίο δίνει τη δυνατότητα στον χρήστη να κάνει κλικ στις επιλογές που του εμφανίζει. Συγκεκριμένα οι επιλογές ήταν δύο στην αρχή και επεκτίνοντας τον κώδικα πρόσθεσα άλλες δύο. Το περιεχόμενο τους αποτελείται από πολύ μικρά κειμενάκια και εικόνες τα οποία αναφέρονται στις πρώτες διαφάνειες που έχουμε αναλύσει στο μάθημα "Εκικοινωνία ανθρώπου-υπολογιστή". Συγκεκριμένα αναφέρθηκα στο γεγονός ότι η τεχνολογία εξελίσσεται αλλά ο άνθρωπος δεν μπορεί να αλλάξει εύκολα συνήθεια γιαυτό ο τρόπος με τον οποίο αλληλεπιδρά με τον υπολογιστή παραμένει ο ίδιος. Επίσης σύγκρινα τις ικανότητες που κατείχαν οι χρήστες των πρώτων σταθερών  υπολογιστών σε σχέση με τους χρήστες της σύγχρονης εποχής  αφού οποιαδήποτε ενέργεια πραγματοποιούταν από εντολές που πληκτρολογούταν στην γραμμή εντολών.         


* Σύνδεσμος για: [pibook](https://github.com/p19pasc/site/blob/master/_remix/mouse-option.md)  
* Σύνδεσμος για: [pibook(Netlify)](https://codingexercisesp2019110.netlify.app/remix/mouse-option/)
* Σύνδεσμος για: [codepen](https://codepen.io/p19pasc/pen/BazrXVj)
<br>

### Image processing

Έχοντας αποκτήσει μερική εμπειρία σχετικά με το μάθημα, η προσθήκη φίλτρων στην εργασία **Image processing** έγινε με περισσότερη άνεση. Καλούμαστε να πειραματιστούμε και να προσθέσουμε και συνδυάσουμε φίλτρα ώστε να αλλάζει η εμφάνιση και τα χρώματα της εικόνας που μας δίνεται. Οι τροποποιήσεις είναι απλές και αφορούν αποκλειστικά την **CSS** σβίνοντας, προσθέτοντας και αλλάζοντας εντολές στα "block" του αρχικού κώδικα, συγκεκριμένα στις γραμμές 9-16 και 82-85. Για
παράδειγμα `brightness(%)` για την φωτεινότητα της εικόνας, `blur(px)` για το θόλωμα της εικόνας, `shadow(px px px colour)` για την προσθήκη σκιών.  <br>
 
* Σύνδεσμος για: [pibook](https://github.com/p19pasc/site/blob/master/_remix/image-filter.md)
* Σύνδεσμος για: [pibook(Netlify)](https://codingexercisesp2019110.netlify.app/remix/image-filter/)
* Σύνδεσμος για: [codepen](https://codepen.io/p19pasc/pen/ExyBoRX) 

<p align="center">
<img src="https://i.postimg.cc/nhCgjsdr/ezgif-com-gif-maker.gif" width=250>
 <p/>
<br>

### Image zoom

Καταπληκτικός συνδυασμό της **Image processing** αποτελεί η **Image zoom**. Από την ονομασία της καταλαβαίνουμε ότι πρόκειται για έναν συνδυασμό της **HTML** και **CSS** που πραγματοποιεί μεγιστοποίηση(zoom in) στο κέντρο μιας εικόνας. Κληθήκαμε να προσθέσουμε την εικόνα και τα φίλτρα της **Image processing** στην συγκεκριμένη άσκσηση ώστε να προκύψει ένας συνδυασμός. Προσωπικά δεν κράτησα τελείως ατόφια τα φίλτρα κυρίως αύξησα την φωτεινότητα πριν το hover και την μείωσα κατά την διάρκεια του προσθέτοντας την εντολή `filter: brightness(%)` στο `body` και στο `.wrap`. Πρόσθεσα στο block κώδικα `html` εντολή για διαμόρφωση χρωμάτων ` background-image: repeating-radial-gradient(colour1, colour2 %,....,clour x %)` , αλλάζοντας και το μήκος-πλάτος της εικόνας ενώ η προσθήκη των φίλτρων που είχα στην προηγούμενη άσκηση τοποθετήθηκε στο ίδιο σημείο με το δεύτερο `brightness`. Ακόμη μια αλλαγή έγινε στο χρώμα του τίτλου πάνω από την εικόνα μέσω της `hmtl{color:}`. Προφανώς η επεξεργασία αυτή ήταν απλή χωρίς την απαίτηση εξειδικευμένων γνώσεων αλλά ταυτόχρονα ήταν πολύ ενδιαφέρον και προσφέρει ωραίο αποτέλεσμα ύστερα από έναν συνδυασμό εντολών. 
* Σύνδεσμος για: [pibook](https://github.com/p19pasc/site/blob/master/_remix/image-zoom.md)
* Σύνδεσμος για: [pibook(Netlify)](https://codingexercisesp2019110.netlify.app/remix/image-zoom/)
* Σύνδεσμος για: [codepen](https://codepen.io/p19pasc/pen/JjRGxWq)<br>
<p align="center">
<img src="https://i.postimg.cc/6pnJN1Ys/imagezoom.gif">
 <p/>
<br>


# Ασκήσεις γραμμής εντολών

### Set-up the main dependencies and demonstrate your base system
Έχοντας εμβαθύνει στο μάθημα ήρθαμε αντιμέτωποι με την πρώτη άσκηση γραμμής εντολών. Για τον λόγο αυτό υποχρεωθήκαμε να εγκαταστήσουμε στον υπολογιστή μας ένα virtual machine και να εργαστούμε σε περιβάλλον linux και συγκεκριμένα στο terminal ακολουθόντας και εκτελόντας αρχικά μια σειρά εντολών (homebrew,asciinema) ώστε να μπορούμε να καταγράψουμε 
τις γραμμές κώδικα των εργασιών. Αφορμή της επιλογής της συγκεκριμένης άσκησης ήταν το γεγονός ότι απαιτούσε την απόκτηση βασικών γνώσεων που χρειαζόμαστε ώστε να τροποποιούμε τα εμφανησιακά στοιχεία της γραμμής εντολών και να αποκτούμε πρόσβαση στα αρχεία του υπολογιστή μέσω αυτού. Παρά την ύπαρξη των εύκολων ζητουμένων, ως πρώτη επαφή με τη γραμμή εντολών πραγματοποιήθηκε πολύ κόπος και αρκετές αναζητήσεις στο διαδίκτυο ώστε να ολοκληρωθεί η εργασία κατανοώντας την ευκολία που μας προσφέρει η σύγχρονη τεχνολογία σε σχέση με την τεχνολογία των σταθερών υπολογιστών εκείνης της εποχής. Στον παρακάτω σύνδεσμο παρουσιάζεται η λίστα των αρχείων μου `ls` , η τροποποίηση του ονόματος μέσω `nano ~/.bashrc` και η παρουσίαση των χαρακτηρηστικών του υπολογιστή με `neofetch_ και _hardinfo`.
* Παρουσίαση με: [asciinema](https://asciinema.org/a/376625)

<p align="center">
<img src="https://i.postimg.cc/sDKc4BgW/hardinfo.png" height=400 width=600>
 <p/>   
<br>  
   
### Text editor and plug-ins for code highlighting and autocompletion 
Ως δεύτερη άσκηση γραμμής εντολών επέλεξα να είναι απλή και να παρέχει γνώσεις για την επεξεργασία κειμένων. Βασισμένος στο εργαλείο vim που στην πραγματικότητα είναι σαν κειμενογράφος δημιούργησα το asciinema που θα αναφέρω παρακάτω. Πρώτα από όλα θα ήθελα να αναφέρω πως για την παρουσίαση της χρήσης του vim χρησημοποίησα έναν δοσμένο κώδικα 
σε **Python** από το μάθημα Κρυπτογραφίας (caesar algorithm). Έχοντας εξοικειωθεί με το εργαλείο αυτό έκανα χρήση  κάποιων βασικών εντολών του. Όπως γίνεται αντιλυπτό σε έναν κειμενογράφο βασικές εντολές θεωρούνται η διαγραφή μιας λέξης ή γράμματος είτε πολλών γραμμών(πχ. 7), η αντιγραφή-επικόλληση και η υπογράμμηση λέξεων. Την πραγματοποίηση των εντολών αυτών αντιπροσοπεύουν οι συνδυασμοί πλήκρων: ``dw, x, 7dd, yy, p``  και η εντολή ``syntax off-on`` αντίστοιχα. Παρ' όλα αυτά σημαντικά είναι το "i" που επιτρέπει την επεξεργασία κειμένου, ``esc`` για την έδοδο από την διαδικασία επεξεργασίας καθώς και το ``:q`` ή ``:q!`` για την πλήρη έξοδο από το vim.      
* Παρουσίαση με: [asciinema](https://asciinema.org/a/371205).  
<br>

### Check the weather	
<img align="left" width="350" height="280" src="https://i.postimg.cc/SsWS6PYM/croped.png"> 
Μία ακόμη καταπληκτική δυνατότητα που μας παρέχεται αποτελεί η ενημέρωση του καιρού. Αυτό είναι εφικτό να επιτευτχθεί με την χρήση της υπηρεσίας παροχής πληροφοριών καιρικών συνθηκών "wttr.in". Εντυπωσιασμένος λοιπόν αποφάσισα να παρουσιάσω τις καιρικές συνθήκες που επικρατούν στην Κέρκυρα,στην Νέα Υόρκη και στο Λονδίνο. Εμβαθύθοντας στις ικανότητες της "wttr.in", ανακλύπτουμε πως παρέχει πληροφορίες τόσο για τα αεροδρόμια όσο και για αξιοθέατα ολόκληρου του κόσμου. Έτσι δεν μας φαίνεται περίεργο πως οι ικανότητες της καλύπτουν και πληροφορίες για την πανσέληνο του φεγγαριού. Κατέβαλα προσπάθειες και αφιέρωσα πολλές ώρες και μέρες στο εργαλείο "ansiweather" αλλάζοντας τα default δεδομένα, αλλά οι ενέργειες μου ήταν ανεπιτυχείς και μέσω των αναζητήσεων στο διαδίκτυο δεν πρόβαλαν κάποια κοινή πράξη ώστε να παραδειγματιστώ.<br>
    <br>
    
  * Παρουσίαση με: [asciinema](https://asciinema.org/a/380594)
<br>

### Download mp3
Οι απεριόριστες δυνατότητες που παρέχει η γραμμή εντολών για άλλη μια φορά επιβαιβεώνεται με την παροχή αναζήτησης στο διαδίκτυο. Με δύο απλά εργαλεία το **Googler** και **Youtube-dl** καταφέρνουμε να αναζητήσουμε το αγαπημένο μας τραγούδι(mp3),βίντεο(mp4) και να το εγκαταστήσουμε στον υπολογστή μας. Ύστερα με την βοήθεια του **Mpv** μπορούμε να το ακούσουμε μέσο της γραμμής εντολών ή να το αναπαραστήσουμε σε ένα ξεχωριστό παράθυρο, όπως απεικονίζεται _στην παρακάτω φωτογραφία_. Βέβαια τα εργαλεία αυτά περιλαμβάνουν πάρα πολλές εντολές-συντομεύσεις κουμπιών και είναι ανάγκη να τις αποσαφηνίσουμε ώστε να χρησημοποιήσουμε τις κατάλληλες. Στην περίπτωση μου έκανα χρήση των: `googler -w youtube.com (songname)` για την αναζήτηση μέσα στο **Youtube** το τραγούδι που επιθυμώ, `youtube-dl --extract-audio --audio-format mp3 url` για το κατέβασμα αποκλειστικά του ήχου από τον σύνδεσμο που δώσαμε και `mpv (songname).mp3` ώστε να ακούσουμε το τραγούδι. Για την σωστή τοποθέτηση και σύνταξη των εντολών απαιτείται αρκετός κόπος, δηλαδή αρκετές ώρες δοκιμάζοντας εντολές ώστε να πετύχουμαι το αποτέλεσμα που επιθυμούμε. Συγκεκριμένη δυσκολία δεν υπάρχει, απλά χρειάζεται η αφιέρωση χρόνου όπως ανέφερα και αρκετές αναζητήσεις στο διαδίκτυο. Ακόμη ένα παράδειγμα **Pipelining** που μπορούμε να πραγματοποιήσουμε είναι η αναπαράσταση ενός βίντεο ή τραγουδιού κατευθείαν μέσω του mpv όπως φαίνεται στο τέλος του asciinema και στην _φωτογραφία_.

* Παρουσίαση με: [asciinema](https://asciinema.org/a/376134)<br>
<p align="center">
<img height=600 width=700 src="https://i.postimg.cc/6qcVBMSD/Screenshot-from-2020-11-29-23-20-15.png" >
<p/><br>

### Manage your bookmarks
Η αναζήτηση στο διαδίκτυο είναι κάτι πολύτιμο, αφού αποκτάμε πληροφορίες και ψυχαγωγία. Αυτό μπορεί να γίνει με το εργαλείο **Buku**. Ουσιαστικά προσομοιάζεται σαν ένας browser στα πλαίσια της γραμμής εντολών και η βαρύτητα δίνεται στην αποθήκευση των συνδέσμων(url) που επιθυμούμε να τους ξαναχρησημοποιησούμε. Στο παρακάτω **asciinema** πραγματοποίησα έναν συνδυασμό του **Googler** με το οποίο αναζητώ συνδέσμους όπως και στην προηγούμενη άσκηση και στην συνέχεια τους επεξεργάζομαι με το **Buku**. Αναλυτικότερα έκανα χρήση πολύ βασικών εντολών καθώς υπάρχουν πάρα πολλές που εξυπηρετούν τις ανάγκες του κάθε χρήστη. Έχοντας τα url με σκοπό να τα αποθηκεύσουμε γράφουμε `buku -w nano(ή οποιοδήποτε text editor)` , ύστερα για να δούμε την λίστα μας με τα bookmarks `buku -p (εμφανίζει όλη τη λίστα) ή buku -p number(1,2,3..) (εμφανίζει το συγκεκριμένο bookmark)` ,καθώς για να κάνουμε διαγραφή `buku -d (διαγραφή όλων των bookmarks) ή buku -d number(1,2,3...) (διαγραφή συγκεκριμένου buku)`.

  * Παρουσίαση με: [asciinema](https://asciinema.org/a/378864)
<br>
<p align="center">
<img height=400 width=800 src="https://i.postimg.cc/sgXj1P08/ezgif-com-resize.gif" >
<p/><br>

# Συμμετοχικό περιεχόμενο Α μέρος

Ώς πρώτη επαφή με το συμμετοχικό περιεχόμενο αποφάσισα να κάνω αναφορά σε δύο εντυπωσιακές καινοτομίες το Siri και το projection keyboard. Που είναι σχετικά σύγχρονες ιδέες και σχετίζονται με την διάδραση και αλληλεπίδραση του ανθρώπου με τους υπολογιστές.
* Σύνδεσμος για τα **images**: [apple-siri](https://github.com/p19pasc/images/blob/master/apple-siri.jpg), [apple-siri-thumb](https://github.com/p19pasc/images/blob/master/apple-siri-thumb.jpg), [projection-yboard](https://github.com/p19pasc/images/blob/master/projection-keyboard.jpg), [projection-keyboard-thumb](https://github.com/p19pasc/images/blob/master/projection-keyboard-thumb.jpg)
* Σύνδεσμος για την **gallery**: [projection-keyboard.md](https://github.com/p19pasc/_gallery/blob/master/projection-keyboard.md), [apple-siri.md](https://github.com/p19pasc/_gallery/blob/master/apple-siri.md)
* Σύνδεσμος για **slides**(Projection-keyboard): [archetypes.md](https://github.com/p19pasc/site/blob/master/_slides/archetypes.md), [netlify](https://codingexercisesp2019110.netlify.app//slides/archetypes/)
* Σύνδεσμος για **timeline**(Apple-siri): [multimedia.md](https://github.com/p19pasc/site/blob/master/_timeline/multimedia.md),[netlify](https://codingexercisesp2019110.netlify.app//timeline/multimedia/)  

# Συμμετοχικό περιεχόμενο Β μέρος

Το Β' μέρος του συμμετοχικού περιεχομένου αποτελούσε υπερβολικά χρονοβόρο και επεκτήνει τις πληροφορίες που πραγματοποιήσαμε στο Α΄μέρρος. Συγκεκριμένα αναφέρθηκα στην χρήση των
καινοτομιών στην καθημερινότητα, τον τρόπο κατασκευής του Projection keyboard, τα πλεονεκτήματα-μειονεκτήματα και τα Ιστορικά γεγονότα ενός σημαντικού προσώπου που συνέβαλε στην 
δημιουργία του Siri και άλλων τεχνολογιών.
* Γενικός σύνδεσμος **case study**:[netlify](https://codingexercisesp2019110.netlify.app/case-study/)
* Συνδεσμος για **case study**(Apple-Siri):[cs-apple_siri](https://github.com/p19pasc/site/blob/master/_case-study/cs-apple_siri.md), [apple-siri.md](https://github.com/p19pasc/site/blob/master/_case-study/apple-siri.md),[netlify](https://codingexercisesp2019110.netlify.app//case-study/apple-siri/)
* Σύνδεσμος για **case study**(Projection-Keyboard):[cs-projection_keyboard](https://github.com/p19pasc/site/blob/master/_case-study/cs-projection_keyboard.md), [projection-keyboard.md](https://github.com/p19pasc/site/blob/master/_case-study/projection-keyboard.md),[netlify](https://codingexercisesp2019110.netlify.app//case-study/projection-keyboard/)
* Σύνδεσμος για **images**(συγκεκριμένα για πρόσωπο της βιογραφίας): [adam-cheyer](https://github.com/p19pasc/images/blob/master/adam-cheyer.jpg)
* Σύνδεσμος για **biography**(Apple-Siri):[bio-Adam-Cheyer](https://github.com/p19pasc/site/blob/master/_biography/bio-adam_cheyer.md),[Adam-Cheyer](https://github.com/p19pasc/site/blob/master/_biography/adam-cheyer.md),[netlify](https://codingexercisesp2019110.netlify.app//biography/adam-cheyer/)
 
 **_Οι πηγές για το υλικό που αντλήθηκε για το συμμετοχικό περιεχόμενο αναφέρονται στην βιβλιογραφία_**
 
 # Συμπεράσματα
 
 Έχοντας καλύψει τις απαιτήσεις του μαθήματος και συμμετάσχει σε όλες τις διαλέξεις και εργαστήρια, συμπληρώνοντας σχεδόν όλα τα κουίζ και απαντόντας σε ερωτήσεις σε πραγματικό
 χρόνο νιώθω την ανάγκη να εκφράσω κάποιες απόψεις. Πράγματι η γενική ιδεολογία που κατήχα για το μάθημα, δηλαδή το χρονικό πλαίσιο που διαδραματίζει, η αλληλεπίδραση με τον υπολογιστή, οι τεχνολογικές ανακαλύψεις έλαβαν χώρα. Βέβαια παρατηρούμε ότι η απλή σκέψη για αυτές τις ιδέες είναι διαφορετική απ' ότι να τις μαθαίνουμε και να τις κατανοούμε πραγματικά. Συμπερένοντας κατά την άποψη μου ενώ το μάθημα ήταν δυσνόητο στα αρχικά στάδια, πλέον έχοντας ολοκληρώσει το μεγαλύτερο μέρος του εξαμήνου και έχοντας καταβάλει αρκετό κόπο, οι στόχοι του έχουν ολοκληρωθεί προσωπικά.
 
# Πηγές πληροφοριών
### Ασκήσεις προγραμματισμού
**Image processing:** [CSS filter](https://www.w3schools.com/cssref/css3_pr_filter.asp)  <br>
**Image zoom:** [backround colour](https://www.w3schools.com/cssref/pr_background-image.asp)
### Ασκήσεις γραμμής εντολών

- [homebrew](https://docs.brew.sh/Homebrew-on-Linux)  
  - [asciinema](https://asciinema.org/docs/installation)  
* **Set-up the main dependencies and demonstrate your base system :** <br> 
       Αλλαγή ονόματος στην γραμμή εντολών:<br> 
     - [Vitux](https://vitux.com/how-to-customize-ubuntu-bash-prompt/)<br> 
       Χαρακτηρηστικά του υπολογιστή:<br> 
     - [Neofetch](https://github.com/dylanaraps/neofetch)<br>
     - [Hardinfo](https://www.youtube.com/watch?v=iKJ-9yEanns)<br>   
* **Text editor and plug-ins for code highlighting and autocompletion :** [Useful Vim Commands](https://www.youtube.com/watch?v=yfxRHSSGgSg&ab_channel=linuxhint), [VIM Syntax Highlighting](https://www.youtube.com/watch?v=P5US8U8-KmA&ab_channel=linuxhint)
* **Check the weather:** [wttr.in](https://github.com/chubin/wttr.in),[ansiweather](https://github.com/fcambus/ansiweather)<br>
* **Download mp3:** <Br>
     - [Googler](https://github.com/jarun/googler) <br>
     - [Pipelining](https://unix.stackexchange.com/questions/594777/watch-and-download-video-from-youtube-with-mpv-only)<br>
       Youtube-dl:<br>
     - [Github](https://github.com/ytdl-org/youtube-dl)<br>
     - [Youtube](https://www.youtube.com/watch?v=9A-HLSvtBWc) <br>
       Mpv:<br>
     - [Github](https://github.com/mpv-player/mpv)<br>
     - [Youtube](https://www.youtube.com/watch?v=BbP0VRISSk0)<br>
 *  **Manage your bookmarks:** [github](https://github.com/jarun/Buku) <br>
### Συμμεχοτικό περιεχόμενο
- [Crop thumb images](https://www.img2go.com/)
- [gitsubmodules](https://github.blog/2016-02-01-working-with-submodules/)
- [Clone repository](https://www.youtube.com/watch?v=i7lRIICGPts)
- Apple-Siri(case study):
     - [Wiki](https://en.wikipedia.org/wiki/Siri)
     - [Pocket-lint](https://www.pocket-lint.com/apps/news/apple/112346-what-is-siri-apple-s-personal-voice-assistant-explained)
     - [Apple(Official Site)](https://www.apple.com/siri/)
- Apple-Siri(biography):
     - [APB](https://www.apbspeakers.com/speaker/adam-cheyer/)
     - [Big Speak](https://www.bigspeak.com/cheyer-kittlaus-siri-viv/)
     - [Adam Cheyer(Official Site)](http://adam.cheyer.com/site/home)
 - Projection-Keyboard:
     - [Elecfreaks](https://www.elecfreaks.com/blog/post/open-source-laser-projection-keyboard.html)
     - [Robopeak](http://www.robopeak.com/blog/?p=282)
     - [HowStuffworks](https://electronics.howstuffworks.com/gadgets/travel/virtual-laser-keyboards.htm)
     - [Wikipedia](https://en.wikipedia.org/wiki/Projection_keyboard)
### Εμφανησιακή επεξεργασία 
- [Ανέβασμα εικόνων](https://postimages.org/)   
  - [Καλιμπράρισμα εικόνων](https://www.youtube.com/watch?v=f4ifdKCH7VI&ab_channel=PeterC)  
  - [Crop  thumb images](https://www.img2go.com/)
  - [Gif Maker](https://ezgif.com/)
* [Markdown](https://www.markdownguide.org/basic-syntax/#images-1)









