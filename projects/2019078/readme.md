**Oνoματεπώνυμο:Ορφέας Λάμπρου**

**ΑΜ:2019078**

[Αποθετήριο κώδικα](https://github.com/Orfeaslambrou/site)

| Περιεχόμενα |
| --- |
| [Σύνοψη](#1)|
| [Εισαγωγή](#a) |
| [Form Validation](#b) |
| [emacs](#c) |
| [css quaries](#d) |
| [wttr](#e) |
| [Image Filter](#f) |
| [awesome-console-service](#g) |
| [Ιmage Ζoom](#h) |
| [w3m](#i)|
| [Συμμετοχικό υλικό](#j) |
| [Συμπεράσματα](#k)|
| [Άρθρα και σελίδες](#l)

# Σύνοψη <a name="1"></a>

Σχετικά με την προοθεσμίες ήμουν αρκετά συνεπής με εξαίρεση τι τελευταίες εβδομάδες λόγω προσωπικών υποχρεώσεων.Υπήρξε μια ανησυχία με τις ασκήσεις γραμμών εντολών (για τις οποίες χρησιμοποιήσα το wsl,το homebrew και ό,τι άλλο ζητούσε το μάθημα) διότι δυσκολευόμουν να τις κατανοήσω και υλοποιήσω.Συγκεκριμένα με την άσκηση emacs και το org mode το οποίο δυστύχως μετά από πολύ προσπάθεια δεν την κατάφερα έτσι αρκέστηκα στις απλές δυνατότητες του.Στις υπόλοιπες γραμμές εντολλών δυσκολέυτηλα σε μικρότερο βαθμό αλλά μόλις κατάλαβα το νοήμα έγιναν πολύ πιο βατές.Όσω αφορά του προγραμματισμόυ δεν δυσκολεύτηκα αρκέτα με εξαίρεση την form validation,όμως το αποτέλεσμα είναι αρκετά ικανοποιητίκο καθώς σε πολλές από αυτές πειραματίστικα με διάφορες εντολές και λειτουργίες που ανακάλυψα στο διαδίκτυο κάνοντας την υλοποίηση τους διασκεδαστική κσι δημιουργική.
# Εισαγωγή <a name="a"></a>

Στο μάθημα επικοινωνία ανθρώπου και υπολογιστή οι προσδοκίες μου είναι να μπορέσω να κατανοήσω πλήρως το μάθημα και την ύλη που έχουν επιλέξει οι καθηγητές,καθώς και να μπορώ να την υλοποιήσω στην πράξη μέσω των εργαλείων που προσφέρει το μάθημα.Αυτό πιστεύω ότι θα πραγματοποιηθεί μέσω συνεχών πρακτικών εργασιών τις οποίες θα ήθελα να είναι απλές αλλά πρακτικές με εκπαιδευτικό κυρίως χαρακτήρα που θα διευρύνει την μηχανικότητα και δημιουργικότητα του φοιτητή.Για να επιτευχθούν τα προαναφερθέντα θα χρειαστεί τακτική μελέτη της ύλης από την πλευρά του φοιτητή και αρμονική συνεργασία με τους καθηγητές αλλά και με τους συνάδερφούς του.Προσωπικά ο όρος επικοινωνία ανθρώπου και υπολογιστή είναι μια έννοια άγνωστη μεν αλλά ενδιαφέρουσα δε Στόχος μου είναι τελειώνοντας το μάθημα να τον κατανοήσω πλήρως μαζί με τα όσα έχει να μου προσφέρει ως φοιτητής του τμήματος πληροφορικής καθώς και να εξοικιώθω με την γραμμή εντολών κάτι εντελώς πρωτόγνωρο για μένα.

# ΑΣΚΗΣΕΙΣ ΠΡΟΓΡΑΜΜΑΤΙΣΜΟΥ

## FORM VALIDATION  <a name="b"></a>

[Form validation](https://github.com/Orfeaslambrou/site/blob/2019078/_remix/form-validation.md) 

Στην άσκηση έπρεπε να κάνoυμε ένα πρόγραμμα που θα επικύρωνε τα στοιχεία που θα έβαζε ο χρήστης .Για να επιτευχθεί αυτό χρησιμοποίησα pattern έτσι ώστε σε  περίπτωση εισαγωγής αληθών στοιχείων από τον χρήστη να του γίνεται επικύρωση,ενώ σε αντίθετη να του βγάζει μήνυμα να εισάγει σωστά τα δεδομένα.Οι σωστοί τύποι για κάθε ζητούμενο είναι:  
**α)** 10 αριθμητικοί χαρακτήρες για το σταθερό νούμερο Ελλάδας  
**β)** ο τύπος *name@email.com* όπου *name* το όνομα διεύθυνσης του χρήστη,*@*  ο απαραίτητος χαρακτήρας για όλες τις ηλεκτρονικές διευθύνσεις,*email* ο πάροχος του εκάστοτε ηλεκτρονικού ταχυδρομείου και *gr* το όνομα του ελληνικού διαδικτυακού χώρου  
**γ)** 3 τετράδες αριθμών για το αριθμό πιστωτικής κάρτας  
Για να επιτευχθεί αυτό ο χρήστης θα πρέπει να γνωρίζει εξαρχής του ανάλογους τύπους .Επειδή αυτό είναι πολύ δύσκολο εώς αδύνατο θα πρέπει πριν κάθε εισαγωγή στοιχείων να υπάρχουν διάφορα σημάδια στον χρήστη έτσι ώστε να διευκολυνθεί η διαδικασία.Με την χρήση των title,value και placeholder ο χρήστης γνωρίζει αμέσως τι πρέπει να εισάγει .Eπίσης με την χρήση label γίνεται γνωστό το προαπαιτούμενο από την αρχή και ξεκαθαρίζεται για ακόμη μια φορά ο τύπος .Τέλος όλα τα προαναφερθέντα εργαλεία βελτιώνουν την εικόνα του περιβάλλοντος καθώς και την διάθεση του χρήστη.Τέλος το required χρησιμοποιείται για να ξέρει το πρόγραμμα ποια δεδομένα είναι σωστά και ποια όχι ώστε να γίνει η επικύρωση. 

<a href="https://ibb.co/4RYq6Ck"><img src="https://i.ibb.co/KxLPMBn/image.png" alt="image" border="0"></a>

*1.1 Η φόρμα που θα αντικρίσει ο χρήστης*


## CSS QUARRIES <a name="d"></a>


[css querries](https://github.com/Orfeaslambrou/site/blob/2019078/_remix/css-queries.md)

Για την άσκηση άλλαξα το font size από έναν σταθερό αριθμό πίξελ σε ποσοστό έτσι ώστε να προσαρμόζεται το μέγεθος της γραμματοσειράς αναλόγως με το παράθυρο. Επίσης έκανα αλλαγές στα χρώματα του backround και της γραμματοσειράς αλλάζοντας τους κωδικούς των χρωμάτων. Το χρώμα προσαρμόζεται με το μέγεθος του παραθύρου γράφοντας μέσα στο body του screen and (max width=...) τον κωδικό του χρώματος.Κάποιες άλλες αλλαγές που έκανα στο κύριο σώμα είναι να υπογραμμίσω το κείμενο με text-decoration:underline και text-allign:center για να εμφανίζεται το κείμενο στο κέντρο ώστε να είναι ευανάγνωστο.Επίσης για αισθητικούς κυρίως λόγους προστέθηκε το text-shadow με 1.3px ώστε να μην είναι τόσο έντονη η σκιά και δυσκολέψει τον χρήστη και η προσθήκη κύκλου στην οποία είναι δυνατή η επιλογή του χρώματος αλλά και του μεγέθους.Το μέγεθος και εδώ επίσης είναι σε ποσοστό ώστε να προσαρμόζεται με εκείνο του παραθύρου.

<a href="https://ibb.co/N7TbJy1"><img src="https://i.ibb.co/25ZHCk8/hello-world.png" alt="hello-world" border="0"></a>

*1.2 Απο τα αριστερά προς τα δεξιά τα παραθυρα με μέγεθος 1542,760,400 αντίστοιχα οπού το κείμενο και τα χρώματα προσαρμόζονται*


## IMAGE FILTER <a name="f"></a>

[image filter](https://github.com/Orfeaslambrou/site/blob/2019078/_remix/image-filter.md)

Εδώ στην εικόνα που απεικονίζεται όταν σύρουμε το ποντίκι πάνω αλλάζει η εμφάνιση της.Αυτό επιτυγχάνεται με την χρήση φίλτρων όπως το saturate οπού δίνει μια αίσθηση διάβρωσης στην εικόνα αλλά επίσης και με το constrast με το οποίο ρυθμίζεις την αντίθεση των χρωμάτων και το sepia μετατρέποντας την εικόνα μας σε μία με περισσότερη κλασική εντύπωση.Τέλος με brightness ρυθμίζεται η φωτεινότητα και με το invert η αναστροφή των χρωμάτων. 

<a href="https://imgbb.com/"><img src="https://i.ibb.co/TMvw48F/image.png" alt="image" border="0"></a>

*1.3 Η εικόνα χωρίς και με τα φίλτρα*

<a name="h"></a>
## IMAGE ZOOM

[image zoom](https://github.com/Orfeaslambrou/site/blob/2019078/_remix/image-zoom.md)


Στην image zoom έπρεπε να ρυθμίσουμε καποιές παραμέτρους ώστε να δώσουμε στην εικόνα τις ιδιότητες που θέλουμε.Μία από αυτές είναι το ύψος και πλάτος της αρχικής εικόνας το οποίο αλλάζει μέσω των width και height εσωτερικά του wrap {}.Η ουσία της άσκησης είναι στις τελευταιές γραμμές,μεσα στο .wrap:hover {} οπού πρόσθεσα τα απαραίτητα φίλτρα που είχα από την προηγούμενη άσκηση αλλά και κάποια που βρήκα σε σάιτ σχετικά με το αντικείμενο(βλέπε hue-rotate).Επίσης προσάρμοσα την ένταση του hover zoom από 125 σε 120%.Επίσης άλλαξα το φόντο και τη γραμματοσειρά στα χρώματα της προτίμησης μου.
 
 <a href="https://imgbb.com/"><img src="https://i.ibb.co/G2RmvB2/GATS.png" alt="GATS" border="0"></a>
 
*1.4 H γάτα μας στην κανονική μορφή της στα αριστερά και με τα φίλτρα ζουμαρισμένη στα δεξιά*



# ΑΣΚΗΣΕΙΣ ΓΡΑΜΜΗΣ ΕΝΤΟΛΩΝ

## EMACS <a name="c"></a>

Asccinema:[emacs](https://asciinema.org/a/2e0gMoZx2b1mYfKxIViGPsQuo)

Emacs είναι μια οικογένεια επεξεργαστών κειμένου.Στο unix θεωρείται ο παλαιότερος και πιο διαδεδομένος επεξεργαστής. 

Όπως βλέπουμε και στο βίντεο οι βασικές δυνατότητες είναι:

+ emacs για την έναρξη του emacs και δημιουργία καινούργιου κειμένου 
+ Crtl+x Ctrl+s για αποθήκευση κειμένου 
+ Ctrl+x Ctrl+c για έξοδος χωρίς αποθήκευση 
+ Crtl+X s Crtl+X Crtl+C για έξοδος και αποθήκευση -  emacs <όνομα κειμένου> για να ανοίξουμε ένα υπάρχον κέιμενο

<a href="https://ibb.co/SKrRKQm"><img src="https://i.ibb.co/9qtsqw4/emacs.png" alt="emacs" border="0"></a>

*2.1 Το περιβάλλον του emacs*

## WTTR  <a name="e"></a>

Asccinema:[wttr](https://asciinema.org/a/dfC3adSCQXWUbVDn2gDRg8bEC)

  Το wttr είναι ένα εργαλείο με το οποίο μπορούμε να κοιτάξουμε τον καιρό για οτιδήποτε χρειαστούμε με πολλές λεπτομέρειες τις οποίες εμείς καθορίζουμε.Οι εντολές που χρησιμοποιήθηκαν στο βίντεο είναι οι εξής:

 - curl wttr.in  
   - Εμφάνιση πρόγνωσης καιρού στην προκαθορισμένη τοποθεσία
 - curl wttr.in/<city's name> 
    - Εμφάνιση πρόγνωσης καιρού σε συγκεκριμένη τοποθεσία
 - curl wttr.in/<airport's name>  
    - Ίδια με την προηγούμενη , απλά γίνεται επισήμανση και για αεροδρόμια
 - curl wttr.in/<city's name>?u
    - Εμφάνιση πρόγνωσης καιρού αλλά με εναλλακτικές μονάδες μέτρησης
 - wttr.in/<city's name>/format=3
    - Γρήγορη εμφάνιση καιρού και θερμοκρασίας σε πραγματικό χρόνο με emoji
 - curl wttr.in/{city's name 1,city's name 2,city;s name 3}?format 3
    - Ίδια με την προηγούμενη αλλά με την προσθήκη περισσοτέρων τοποθεσιών
 - curl wttr.in/moon
    - Εμφάνιση σεληνιακής φάσης
 - curl <country's ISO 3166 code>wttr.in/<city's name> 
    - Εμφάνιση πρόγνωσης καιρού αλλά με την δυνατότητα επιλογής γλώσσας
     
    
    <a href="https://ibb.co/K7wQbDb"><img src="https://i.ibb.co/2PNLWSW/wttr.png" alt="wttr" border="0"></a>
    
    *2.2.Παράδειγμα στο οποίο η πρόγνωση για μια ισπανική πόλη εμφανίζεται στη γαλλική γλώσσα*
    
  ## awesome-console-service <a name="g"></a>
   
   Asciinema:[awesome-console-service](https://asciinema.org/a/381387)
   
  Για να διαβάσω τα νέα των επιχειρήσεων εκμεταλλεύτηκα την εντολή curl getnews.tech/world+cup που μου δινόταν.Επειδή όμως δεν ήθελα τα νέα για το παγκόσμιο κύπελο σκέφτηκα να αντικαταστήσω τους χαρακτήρες world+cup με το business.Έτσι ανακάλυψα πως έτσι μπορείς να μεταβείς στην οποιαδήποτε κατηγορία ειδήσεων ενδιαφέρεσαι  όπως sports,covid,economy και πολλά άλλα.
  
 <a href="https://ibb.co/LtTCndc"><img src="https://i.ibb.co/2tzjg3C/w3m.png" alt="w3m" border="0"></a>
 
  *2.3 Τα νέα για τον covid-19*
   
  ## w3m <a name="i"></a>
   
  Asciinema:[w3m](https://asciinema.org/a/381390)
   
 Το w3m είναι ένας ανοικτού κώδικα περιηγητής ο οποίος υποστηρίζει πολλές λειτουργίες.Το μόνο που έχουμε να κάνουμε είναι να πληκτρολογήσουμε w3m κενό και το λινκ της ιστοσελίδας που θέλουμε να επισκεφτούμε.Σε αυτήν μπορούμε να περιηγηθούμε με τα βελάκια και να ανοίξουμε νέα λινκς πατώντας έντερ πάνω τους.
 
 <a href="https://ibb.co/FxMHksK"><img src="https://i.ibb.co/mDwNrvG/aws.png" alt="aws" border="0"></a>
   
   *2.4 Η ιστοσελίδα του cnn με την χρήση w3m*
   
   
   # Συμμετοχικό υλικό <a name="j"></a>
   
   [images](https://github.com/Orfeaslambrou/images-1)
   
   [colossus](https://github.com/Orfeaslambrou/images-1/blob/master/colossus.md)
   
   
   # Συμπεράσματα <a name="k"></a>
   
Αναθεορώντας την πορεία μου στο μάθημα και τους αρχικους μου στόχους σε αυτό μπορώ να πω οτι έγινε σημαντική πρόοδος σε σύγκριση με την αρχή της χρονιάς.Συγκεκριμένα απέκτησα αρκετές γνώσεις όσω αφορά την επικοινωνία ανθρώπου και υπολογιστή,καθώς την κατανόηση της έννοιας αυτής σε ικανοποιητικό βαθμό κάτι το οποίο το είχα θέσει ως στόχο.Έπίσης κατάφερα μια μικρή εξοικίωση με την γραμμή εντολών όμως θα πρέπει να ομολογήσω πως δυσκολέυτηκα αρκέτα σε αυτό το κομμάτι ειδικά στην άρχη και έχω πολλά ακόμα να μάθω για να νοιώσω ικανοποιημένος και εξοικιωμένος με το αντικείμενο.Αυτό πιστεύω θα επιτευχθεί κατά κύριο λόγο με περισσότερη προσπάθεια από μέρος μου σε συνδιασμό με το υλικό που έχει δωθεί από τους καθηγητές.Τελειόνοντας το μάθημα προσωπικά θα μπω πιο βαθιά στον κόσμο της γραμμής εντολών και θα προσπαθήσω να το κάνω κομμάτι της καθημερινότητας μου διότι πιστεύω οι δυνατότητες είναι τεράστιες.Τέλος μετά τα μαθήματα ιστορίας του μαθήματος κάθε φορά που θα είμαι απέναντι σε έναν υπολογιστή θα τον βλέπω με αλλή οπτική λόγω των πληροφοριών που κατέχω πλέον όσω αφορά την ιστορία του.

# Άρθρα και σελίδες <a name="l"></a>
   
  Άρθρα και σελιδες που με βοήθησαν για την εκπόνηση της εργασίας
  
  https://www.sitepoint.com/client-side-form-validation-html5/
  
  https://code.tutsplus.com/tutorials/editing-images-in-css-filters--cms-25948
  
  http://ergoemacs.org/emacs/emacs_basics.html
  
  https://orgmode.org/
  
  https://github.com/chubin/wttr.in
  
  https://github.com/chubin/awesome-console-services
  
  http://w3m.sourceforge.net/
  
  https://www.w3schools.com/Css/
  
  https://el.imgbb.com/
  
  https://www.rapidtables.com/web/css/css-color.html

























