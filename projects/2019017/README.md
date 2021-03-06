# Μάθημα: Επικοινωνία Ανθρώπου-Υπολογιστή

### Ονοματεπώνυμο: Καλαθάς Αλέξανδρος
### Αριθμός Μητρώου: Π2019017

## Σύνοψη
### Πίνακας Περιεχομένων:
| Εβδομάδα | Παραδοτέο |
| --- | --- |
| 1 | Εισαγωγή: [First deliverable](#Παραδοτέο-1) |
| 2 | Άσκηση προγραμματισμού (Button): [Second deliverable](#Παραδοτέο-2) |
| 3 | Άσκηση γραμμής εντολών (hci - mp3): [Third deliverable](#Παραδοτέο-3) |
| 4 | Άσκηση προγραμματισμού (Image processing): [Fourth deliverable](#Παραδοτέο-4) |
| 5 | Άσκηση γραμμής εντολών (hci - groff): [Fifth deliverable](#Παραδοτέο-5)|
| 6 | Συμμετοχικό περιεχόμενο: [Sixth deliverable](#Παραδοτέο-6) |
| 7 | Άσκηση προγραμματισμού (Menu Pie): [Seventh deliverable](#Παραδοτέο-7)|
| 8 | Άσκηση γραμμής εντολών (hci - emacs org mode): [Eighth deliverable](#Παραδοτέο-8) |
| 9 | Άσκηση προγραμματισμού (Mouse Eraser): [Ninth deliverable](#Παραδοτέο-9) |
| 10 | Άσκηση γραμμής εντολών (hci - vim configuration file): [Tenth deliverable](#Παραδοτέο-10) |
| 11 | Συμμετοχικό περιεχόμενο: [Eleventh deliverable](#Παραδοτέο-11) |
| 12 | Τελική αναφορά και αίτημα ενσωμάτωσης για βαθμολόγηση |

Αρχικά είχα ξεκινήσει να κάνω την αναφορά μου στο hci-lab fork μου και μετά από δύο εβδομάδες έφτιαξα την σωστή αναφορά στο hci. Εδώ είναι το [ιστορικό](https://github.com/p19kala/hci-lab/commits/%CE%A02019017?after=9473a2524c479c9c475b31f929ac00e9db6c2dfe+34&branch=%CE%A02019017&path%5B%5D=projects&path%5B%5D=2019017) της αναφοράς στο hci-lab. Όλα τα commits έγιναν μέσα στη διορία για κάθε παραδοτέο.

Όλα τα παραδοτέα (εκτός απο 1) έγιναν commit την εβδομάδα της διορίας τους, δηλαδή από την κάθε Τρίτη στις 19:00:00 έως την επόμενη Τρίτη στις 19:00:00 (η ώρα αυτή είναι όταν ξεκινάει η διάλεξη). Το παραδοτέο που δεν έγινε κομιτ είναι το δεύτερο της 11ης εβδομάδας (συμμετοχικό περιεχόμενο), δηλαδή η βιογραφία. 
Σε κάποιες περιπτώσεις υπήρχαν και μικρές βελτιώσεις μετά τη διορία, όπως μια πληροφορία στο [5ο παραδοτέο](#Παραδοτέο-5) για τα εσωτερικά λινκ (anchors) του groff. Σε μερικές απλές ασκήσεις έκανα επιπλέον ενέργειες, τις οποίες περιγράφω αναλυτικά στα αντίστοιχα παραδοτέα. Μια απο αυτές είναι η 7η εβδομάδα με το [Menu Pie](#Παραδοτέο-7) η οποία αρχικά χρειαζόταν να κάνω μόνο comment out μερικές γραμμές κώδικα.

Αντιμετώπισα πολλές δυσκολίες στις ασκήσεις, ιδιαίτερα στις γραμμής εντολών. Καθώς ήταν η πρώτη φορά που χρησιμοποιούσα σύστημα Linux, έπρεπε να αφιερώσω πολύ χρονο στην εξοικοίωση με τις λειτουργίες του συστήματος και το τερματικό (δεν είχα εργαστεί σε τερματικό στο παρελθόν). Οι δύο πρώτες ασκήσεις ([mp3](#Παραδοτέο-3) και [groff](#Παραδοτέο-5)) πήραν την πιο πολύ ώρα, αν και η πρώτη άσκηση οφειλόταν στο γεγονός ότι έτυχε εκεινή την εβδομάδα να έχει πρόβλημα το εργαλείο youtube-dl και έψαχνα εναλλακτικές (googler). Για την δεύτερη διάβασα το man page της groff και μετά από πολύ έρευνα στο stackexchange έμαθα για τα πολλά θέματα του ελληνικού πληκτρολογίου με το pdf (το οποίο περιγράφω στην αντίστοιχη παράγραφο). Από όλες τις ασκήσεις είμαι πιο περήφανος για αυτήν διότι στην αρχή φαινόταν αδύνατη.

## Παραδοτέο 1
#### [My repository](https://github.com/p19kala/hci/tree/2019017)
#### [My profile](https://github.com/p19kala)
### Εισαγωγή:

Ως στόχους για αυτό το μάθημα έχω να περάσω με καλό βάθμο και να χρησιμοποιήσω τις γνώσεις που θα αποκτήσω σε άλλα μαθήματα και αργότερα στην καριέρα μου, γιατί πιστεύω ότι η διεπαφή χρήστη με υπολογιστή παίζει σημαντικό ρόλο στην ανάπτυξη ενός λογισμικού. Επιπλέον να μάθω το περιβάλλον Linux, που θα χρησιμοποιήσουμε στα εργαστήρια. Για να εκπληρώσω αυτούς τους στόχους θα προσπαθήσω και εκτός μαθήματος να χρησιμοποιώ τα εργαλεία του εργαστηρίου για να εξοικειωθώ γρήγορα. Όσο για τις ανάγκες μου από το μάθημα, θα ήθελα να μάθω την αλληλεπίδραση μεταξύ χρήστη και υπολογιστή, την ιστορία πάνω στη δημιουργία των user interfaces (όπως είδαμε συνοπτικά στο πρώτο μάθημα) και πώς να δημιουργώ κι εγώ ένα interface. Συγκεκριμένα, τον τρόπο με τον οποίο εισάγουμε δεδομένα μέσω πληκτρολογίου, ποντικιού και μικροφώνου και τον τρόπο που ο υπολογιστής τα εμφανίζει στην οθόνη, πώς κατάφεραν οι άνθρωποι να εφεύρουν κάτι τέτοιο και πώς λειτουργούσαν τα πρώτα interfaces. Δεν μπορώ να καταλάβω πώς ακριβώς ένα μηχάνημα που αναγνωρίζει μόνο 0 και 1 μπορεί να μεταφράσει όταν πατάμε ένα πλήκτρο ή μιλάμε στο μικρόφωνο, οπότε ελπίζω μέσα από αυτό το μάθημα να μου λυθεί αυτή η απορία και να αποκτήσω περαιτέρω γνώσεις πάνω στον υπολογιστή και τη διεπαφή με τον χρήστη. 

## Παραδοτέο 2

Διάλεξα την άσκηση με το κουμπί. Εκτός από την έξτρα λειτουργία που ζητούσε η άσκηση, άλλαξα τη τοποθεσία του Χ και της λεπτής κάθετης γραμμής, το χρώμα του background και του κουτιού, το κείμενο από "REMOVE" σε "slide" και την κίνηση που κάνει όταν ο χρήστης κάνει hover με το ποντίκι. Όταν κάνει κλικ στο κουμπί, τον κατευθύνει σε ένα τραγούδι στο youtube και το κουτί εμφανίζει ένα εικονίδιο "download" με κόκκινο background. Αρχικά είχα πρόβλημα με το που να βρω τα hex values των χρωμάτων ώστε να αλλάξω το background και το κουτί του κουμπιού, οπότε έψαξα στο google και βρήκα την ιστοσελίδα w3schools. Εκεί είχε και πως αντιδρούσαν όλα τα χρώματα μεταξύ τους. Στη συνέχεια έκανα trial and error με τις τιμές του έτοιμου κώδικα για να μάθω τι κάνει η καθεμία και έτσι κατάφερα να αλλάξω την εμφάνιση από το αρχικό κουμπί σε μία της επιλογής μου. Τροποποίησα το κώδικα HTML και SCSS.

Σύνδεσμος στην άσκηση του \_remix: [Button](https://github.com/p19kala/site/blob/master/_remix/button.md)
<br/>
Σύνδεσμος στην ιστοσελίδα netlify μου με το embed: [Netlify link](https://p19kala.netlify.app/remix/button/)
<br/>
Σύνδεσμος στο εκτελέσιμο: [Codepen](https://codepen.io/p19kala/pen/pobgEKo)

Preview:<br/>
![default](https://i.imgur.com/LZWpiai.png)

## Παραδοτέο 3

Διάλεξα την άσκηση "download mp3" από το σετ ασκήσεων [HCI](https://github.com/epidrome/dokey#hci). Εγκατέστησα το youtube-dl, το googler και το mpv στο Linux σύστημά μου και μετά από πολλές ώρες κατάφερα να κατεβάσω ένα αρχείο σε μορφή mp3 και να το ακούσω. Εγκατέστησα και το asciinema για το recording. Έθεσα και το idle_time σε 0.2 δευτερόλεπτα για να μην καθυστερεί όπως έλεγε στις οδηγίες και ξεκίνησα εγγραφή.

Αρχικά κάλεσα το 'googler' για να βρω το βίντεο που ήθελα και αντέγραψα το id του. Η εντολή `-w` παίρνει ως arguement μια ιστοσελίδα και ψάχνει αποτελέσματα εκεί. Έπειτα χρησιμοποίησα το 'youtube-dl' με τις εντολές `--extract-audio` και `--audio-format mp3` για να κατεβάσω μόνο τον ήχο του βίντεο και σε mp3 μορφή. Έβαλα την εντολή `-o` και ένα custom filename μέσα στα μονά εισαγωγικά. Στο τέλος είναι το id του βίντεο. Αφού ξεκίνησε η αναπαραγωγή χρησιμοποιώντας το 'mpv', περίμενα 11 δευτερόλεπτα και το σταμάτησα πατώντας το `Q`.

Το [asciinema link](https://asciinema.org/a/eA3ydCOwAVi0EIFp8e7CvkawT).

Preview:<br/>
![default](https://i.imgur.com/1RnWv5m.png)

## Παραδοτέο 4

Για την επόμενη άσκηση προγραμματισμού διάλεξα το Image processing. Έπρεπε να χρησιμοποιήσω ένα συνδυασμό filters στην προεπιλεγμένη εικόνα που θα εμφανίζονται όταν ο δείκτης του ποντικιού πήγαινε πάνω σε αυτή. Εκτός από αυτό που ζητούσε η άσκηση, άλλαξα το χρώμα του background από άσπρο για να είναι πιο εύκολο στα μάτια, μεγένθυνα την εικόνα και τη διευθέτησα στο κέντρο. Από φίλτρα έβαλα το sepia ώστε όλη η φωτογραφία να έχει το ίδιο χρώμα και μετά το hue-rotate() για να αλλάξει. Έπειτα πρόσθεσα το invert για να αντιστραφεί και στο τέλος το contrast με σκοπό να κάνω το τοπίο πίσω από τον ανανά λίγο πιο σκούρο.

Σύνδεσμος στην άσκηση του \_remix: [Image Filter](https://github.com/p19kala/site/blob/master/_remix/image-filter.md)
<br/>
Σύνδεσμος στην ιστοσελίδα netlify μου με το embed: [Netlify link](https://p19kala.netlify.app/remix/image-filter/)
<br/>
Σύνδεσμος στο εκτελέσιμο: [Codepen](https://codepen.io/p19kala/pen/eYzrzqB)

Preview:<br/>
![default](https://i.imgur.com/hRVEach.png)

## Παραδοτέο 5

Για τη δεύτερη άσκηση γραμμής εντολών επέλεξα από το σετ [HCI](https://github.com/epidrome/dokey#hci) να κάνω format τη τελική αναφορά μου χρησιμοποιώντας το groff (GNU troff). Χρησιμοποίησα το vim για να επεξεργαστώ το αρχείο. Έβαλα ένα πίνακα περιεχομένων με εντολές του preprocessor tbl χρησιμοποιώντας pipelining. Ο λόγος που εμφανίζεται "table wider than line width" warning ειναι επειδη μετατρεπει καθε ελληνικο γραμμα σε χαρακτήρα unicode  με την εντολη `-k` ώστε το pdf να αναγνωρίζει τους ελληνικούς χαρακτήρες. Μαζεύονται τόσα πολλά σύμβολα σε μια γραμμή (στην εβδομάδα 6), που με ειδοποιεί ότι δεν έχει αρκετό χώρο στο table. Παρόλα αυτά στο output βλέπουμε ότι δεν παρουσιάζει πρόβλημα οπότε το αγνοούμε. Επίσης είναι λοξά τα γράμματα (εκτός από τα κεφαλαία) και προς το παρόν δεν υπάρχει λύση για αυτό το πρόβλημα. Τα Ελληνικά δεν δέχονται καμία μορφή font (όπως bold και διαφορετικό τύπο γραμματοσειράς) το οποίο είναι πιθανόν να οφείλεται στο ότι τα μετατρέπει σε unicode. Γενικά, καλύτερα να χρησιμοποιηθεί το αγγλικό αλφάβητο με το groff. Τα εσωτερικά λινκ (anchors) υπάρχουν στο troff και nroff αλλά δεν υποστηρίζονται στο groff (source: https://n-t-roff.github.io/heirloom/doctools/troff.pdf)

Σημείωση: Το πολυτονικό σύστημα δεν δουλεύει στο pdf και μετά από πολύ ψάξιμο έμαθα ότι φταίει το font του pdf αλλά δεν μπόρεσα να το αλλάξω στα Linux (κάποιοι υποστήριζαν ότι είναι αδύνατο να αλλάξει), οπότε αφαίρεσα όλους τους τόνους χρησιμοποιώντας το vim και την εντολή `:%s`

Έκανα install το εργαλείο Kazam για να δείξω τη δουλειά μου:

![AltText](https://i.imgur.com/aE7C8la.gif)

## Παραδοτέο 6
 
### A1)

Πρόσθεσα entry για το **Unreal Engine** [εδώ](https://github.com/p19kala/_gallery/blob/master/unreal-engine.md) και δύο φωτογραφίες. Thumbnail [εδώ](https://github.com/p19kala/images/commit/37fe62e23574ba1648b8b1f049833bbf47378199) και κανονικό μέγεθος [εδώ](https://github.com/p19kala/images/commit/03c691b5a501f7acdcb789900160c3ac55570835). Tags στο Netlify εμφανίζονται [εδώ](https://p19kala.netlify.app/tags/#epic-games-inc) και [εδώ](https://p19kala.netlify.app/tags/#blueprint).

Πρόσθεσα entry για το **Microsoft Natural Keyboard** [εδώ](https://github.com/p19kala/_gallery/blob/master/microsoft-natural-keyboard.md) και δύο φωτογραφίες. Thumbnail [εδώ](https://github.com/p19kala/images/blob/master/microsoft-natural-keyboard-thumb.jpg) και κανονικό μέγεθος [εδώ](https://github.com/p19kala/images/blob/master/microsoft-natural-keyboard.jpg). Tags στο Netlify εμφανίζονται [εδώ](https://p19kala.netlify.app/tags/#microsoft) και [εδώ](https://p19kala.netlify.app/tags/#keyboard).

### A2)

**Αλλαγές:** 

Δημιούργησα ένα καινούργιο χρονολόγιο για συσκευές εισόδου και πρόσθεσα το δικό μου entry και τα προυπάρχοντα Apple Mouse και Engelbart Mouse. Πήρα ως εικόνα για το χρονολόγιο το ποντίκι Engelbart.

#### Πρώτη εγγραφή:
- [programming.md](https://github.com/p19kala/site/commit/e2e20206c3bd5f0d7dd51f4faa21cc19ce23bca2) από το \_timeline. Πρόσθεσα το "unreal-engine". Netlify [link](https://p19kala.netlify.app//timeline/programming/)
- [tools.md](https://github.com/p19kala/site/commit/b7933af52f1a99df07e79c864b646490ba6cab83) από το \_slides. Πρόσθεσα το "unreal-engine". Netlify [link](https://p19kala.netlify.app//slides/tools/)

#### Δεύτερη εγγραφή:
- [input-devices.md](https://github.com/p19kala/site/blob/master/_timeline/input-devices.md) από το \_timeline. Netlify [link](https://p19kala.netlify.app//timeline/input-devices/)
- [archetypes.md](https://github.com/p19kala/site/blob/master/_slides/archetypes.md) από το \_slides. Πρόσθεσα το "microsoft-natural-keyboard". Netlify [link](https://p19kala.netlify.app//slides/archetypes/)

#### Έξτρα:
- [\_config.yml](https://github.com/p19kala/site/blob/master/_config.yml) για την ενημέρωση όλων των συνδέσμων με το δικό μου url.
- [.gitmodules](https://github.com/p19kala/site/blob/master/.gitmodules) για το συντονισμό των submodules \_gallery και images στα αντίστοιχα fork μου.

Επισκόπηση μερικών αλλαγών:</br>
![default](https://i.imgur.com/2Ah075d.png)
![default](https://i.imgur.com/rawUvBD.png)

## Παραδοτέο 7
Διάλεξα την άσκηση Menu Pie για την οποία έπρεπε να μειώσω τις επιλογές του μενού από 12 σε 4. Έκανα comment out 8 επιλογές από το CSS και από την HTML. Επέλεξα να έχω τις επιλογές Login, Games, Register και Home. Επειδή ήταν πολύ εύκολη, έκανα και κάτι παραπάνω. Πήγα στο μπλοκ `.csstransforms .cn-wrapper li` και αύξησα κάθε transform: rotate() σε 165 μοίρες ώστε να εμφανίζεται το μενού από τα δεξιά. Στο μπλοκ `.csstransforms .opened-nav li` αύξησα το χρόνο που κάνουν οι επιλογές να εμφανιστούν απο 0.3 σε 0.4 δευτερόλεπτα και τη διάρκεια να φτάσουν στη τελική τους θέση σε 0.5. Επιπλέον άλλαξα το χρώμα του OPEN, του button, της γραμματοσειράς των επιλογών, του shop-icon στην HTML (`<path fill="red"`) και του background.

Σύνδεσμος στο \_remix: [Menu-Pie](https://github.com/p19kala/site/blob/master/_remix/menu-pie.md)
<br/>
Σύνδεσμος στο embed: [Netlify](https://p19kala.netlify.app/remix/menu-pie/)
<br/>
Σύνδεσμος στο εκτελέσιμο: [Codepen](https://codepen.io/p19kala/pen/GRqVNeJ)

Preview:<br/>
![default](https://i.imgur.com/9f2Umuw.png)

## Παραδοτέο 8
Διάλεξα την ασκήση "organize your notes with emacs" από το σετ [HCI](https://github.com/p19kala/dokey#hci). Σκοπός ήταν να χρησιμοποιήσω το org mode του Emacs για να οργανώσω κάποιες πληροφορίες, οπότε δημιούργησα ένα TODO list. Με `#+TITLE` προσδιορίζω των τίτλο του αρχείου και με `#+AUTHOR` τον συγγραφέα. Η προεπιλεγμένη out-of-the-box μορφή του org mode ήταν πολύ απλή, οπότε για να ειναι πιο ευανάγνωστο βρήκα ένα macro στο ιντερνετ και το έβαλα στο .emacs config file μου. Αυτό χρησιμοποιεί το prettify-symbol-mode του emacs για να μετατρέψει 3 χαρακτήρες σε unicode σύμβολα. Πρόσθεσα επιπλέον σύμβολα και για χαρακτήρες της επιλογή μου. Επιπλέον άλλαξα το χρώμα των γραμματοσειρών του τίτλου, του συγγραφέα και του τίτλου επιπέδου 1 γιατί ήταν πολύ σκούρο και δεν φαινόταν.

### Επεξήγηση macro και εντολών που δεν φαίνονται στο terminal:
Με το `tab` επεκτείνω γρήγορα ένα TODO list. Πρώτα τα "παιδιά" της επιλεγμένης λίστας και έπειτα τα υποδέντρα τους. Με `[]` έχω ένα κενό checkbox, με `[-]` έχω ένα κύκλο που δείχνει μια εργασία σε εξέλιξη και με `[Χ]` έχω ένα συμπληρωμένο checkbox. Αν βάλω `-` χωρίς αγκύλες, το macro το μετατρέπει σε μια σφαίρα. Ο ένας αστερίσκος `*` (τίτλος επιπέδου 1) γίνεται μια πλήρη σφαίρα μέσα σε ένα κύκλο και οι δύο αστερίσκοι `**` (τίτλος επιπέδου 2 ή υπότιτλος) ένας κύκλος.

Για να ξεκινήσω το emacs σε terminal χρησιμοποίησα την εντολή `-nw`, διαφορετικά άνοιγε το emacs σε νέο παράθυρο εκτός του τερματικού. Για να σώσω μια αλλαγή στο αρχείο μου έχω την εντολή `C-x C-s` (Ctrl+x και έπειτα Ctrl+s) και για να βγω από το συγκεκριμένο buffer `C-x k enter` (Ctrl+x, έπειτα k και μετά enter). Αν θέλω να τερματίσω (kill) το emacs κάνω `C-x C-c` (Ctrl+x και έπειτα Ctrl+c). 

[Asciinema link](https://asciinema.org/a/F2Jas1b3XAtZ3EOoGA51t1ro5).

Preview:<br/>
![default](https://i.imgur.com/OZIo2nb.png)

## Παραδοτέο 9
Πήρα την άσκηση Mouse Eraser. Σκοπός ήταν να αλλάξω τις εικόνες και να μεγενθύνω τη σβήστρα. Όμως το μέγεθος r (radius) της σβήστρας είχε ήδη την μέγιστη τιμή (50) οπότε το μίκρυνα. Έκανα πιο έντονη τη διαγραφή από το addColorStop() για να παίρνει λιγότερο χρόνο η διαγραφή και άλλαξα τις διαστάσεις των δυό νέων εικονών και του canvas

Σύνδεσμος στο \_remix: [Mouse Eraser](https://github.com/p19kala/site/blob/master/_remix/mouse-eraser.md)
<br/>
Σύνδεσμος στο embed: [Netlify](https://p19kala.netlify.app/remix/mouse-eraser/)
<br/>
Σύνδεσμος στο εκτελέσιμο: [Codepen](https://codepen.io/p19kala/pen/vYXKmOM)

Preview:<br/>
![default](https://i.imgur.com/5FJS44n.png)

## Παραδοτέο 10
Άσκηση `edit the vim or shell editor configuration file` από το σετ ασκήσεων hci. Χρησιμοποίησα το vim για να βάλω plug-ins στο .vimrc αρχείο. Ο κώδικας για το syntax highlighting ήταν ήδη στο αρχείο, οπότε έδειξα στο asciinema πώς φαίνεται χωρίς το syntax. Διάλεξα το Syntastic plug-in από το Vim Awesome το οποίο δίνει στο vim μια δυνατότητα να εντοπίζει συντακτικά λάθη και να με ενημερώνει σε ποιά θέση βρίσκονται με highlight. Για να ενεργοποιηθεί βγαίνω από το edit mode του vim με `ESC` και αποθηκεύω τις αλλαγές στο αρχείο με `:w`. Αν υπάρχει λάθος, το Syntastic θα μου δειξει τη θέση του. Εκτός απο αυτό πρόσθεσα και το `set number` για να αριθμεί *πάντα* τις γραμμές, το οποίο βοηθάει στο debugging μεγάλων αρχείων (όπως στο [Παραδοτέο 5](#Παραδοτέο-5) με το groff).

[Asciinema link](https://asciinema.org/a/emsP2cCFN7grDcYdv7J3i1LYD).

Preview:<br/>
![default](https://i.imgur.com/Ub8X4aD.png)

## Παραδοτέο 11
Μελέτη περίπτωσης για την καταχώρησή μου Unreal Engine: [cs κείμενο](https://github.com/p19kala/site/blob/master/_case-study/cs-unreal-engine.md) και [κώδικας](https://github.com/p19kala/site/blob/master/_case-study/unreal-engine.md) για το Netlify. Το αποτέλεσμα εμφανίζεται [εδώ](https://p19kala.netlify.app//case-study/unreal-engine/).

## Ενότητα μπονους
Πήρα μέρος στις σύντομες ερωτήσεις του classtime σε όλες τις διαλέξεις. Καθώς η ιστοσελίδα είναι υπερβολικά απλή και δεν υπάρχει προφίλ, δεν μπορώ να βάλω κάποιο λινκ. Το όνομά μου εκεί είναι Alexandros Kalathas. Φαντάζομαι κρατάει τις απαντήσεις μας μετά από καιρό οπότε θα με δείτε. Εγγράφηκα με το ionio email μου.

## Συμπεράσματα
Οι αρχικοί στόχοι μου καλύφθηκαν σε μεγάλο ποσοστό. Σε κάθε διάλεξη μιλούσαμε για την ιστορία των διεπαφών και παλιών συσκευών/υπολογιστών/λογισμικών (Xerox Star, Sketchpad, ποντίκι με 1 κουμπί, η πρώτη επιφάνεια εργασίας) και πώς εξελίχθηκαν σήμερα (ποντίκι με πολλά κουμπιά, γραφικό περιβάλλον χρήστη). Περίμενα να μάθουμε κι εμείς πώς να δημιουργούμε ένα interface, αλλά ίσως αυτό ήταν πολύ προχωρημένο για το έτος μας. Εξοικοιώθηκα με το περιβάλλον Linux καθώς χρειάστηκε στις ασκήσεις και είχα λίγη βοήθεια από το εργαστήριο, αλλά για το περισσότερο ποσοστό χρειάστηκε πολύ χρόνο από τη μεριά μου (reddit, stackexchange, quora, github). Οι προσδοκίες μου από το μάθημα τελικά ήταν διαφορετικές από αυτό που είδαμε στις διαλέξεις. Νόμιζα θα κάναμε και το τρόπο που επικοινωνεί ο υπολογιστής με τον άνθρωπο από την οπτική γωνία της αρχιτεκτονικής και λογισμικού του (ο υπολογιστής μετατρέπει κάθε ενέργειά μας σε 0 και 1 και μόνο έτσι τις καταλαβαίνει, αλλά πως ακριβώς γίνεται αυτό). Αυτό ήταν από τη δική μου πλευρά λάθος ερμηνεία των στόχων στη σελίδα του μαθήματος [εδώ](https://di.ionio.gr/gr/studies/undergraduate-studies/courses/591/).

## Πηγές:

Παραδοτέο 2:

- [How to put link in HTML for a button](https://stackoverflow.com/a/20343328)

- [Colours' hex values in CSS](https://www.w3schools.com/cssref/css_colors.asp)

Παραδοτέο 3:

- [Installing and configuring youtube-dl](https://github.com/scastillo/not-youtube-dl/blob/master/README.md)

- [MPV manual to control the player](https://mpv.io/manual/master/)

- [MPV installation](https://mpv.io/installation/)

- [Googler installation and usage](https://github.com/jarun/googler#installation)

- [Commands for Asciinema](https://asciinema.org/docs/usage)

Παραδοτέο 5:

- [Groff basics tutorial](https://www.youtube.com/watch?v=bvkmnK6-qao)

- [Add images with Groff](https://lists.gnu.org/archive/html/groff/2010-04/msg00042.html)

- [Clickable links with Groff](https://www.reddit.com/r/groff/comments/ac7tkb/clickable_web_links_in_your_final_pdf/)

- [Make Groff recognize special unicode characters (Greek, German umlauts etc.)](https://stackoverflow.com/a/53626338)

- [Changing font size](https://www.gnu.org/software/groff/manual/html_node/Changing-Type-Sizes.html)

- [Page control](https://www.gnu.org/software/groff/manual/html_node/Page-Control.html)

- [Groff Macros](https://www.youtube.com/watch?v=kJ_TXZB4Gm4)

- [Kazam screen capture - Usage and Installation](https://itsfoss.com/kazam-screen-recorder/)

Παραδοτέο 6:

- [Unreal Engine info](https://en.wikipedia.org/wiki/Unreal_Engine)

- [Photorealistic forests using UE4](https://www.youtube.com/watch?v=TtIN4_RZwZE)

- [Microsoft Natural Keyboard info](https://en.wikipedia.org/wiki/Microsoft_ergonomic_keyboards)

Παραδοτέο 7:

- [Colours' hex values in CSS](https://www.w3schools.com/cssref/css_colors.asp)

Παραδοτέο 8:

- [Symbols Macro](https://www.reddit.com/r/emacs/comments/brt0sk/prettifysymbolsmode_is_so_cool/)

- [Circle icons](https://www.symbolsofit.com/en/circle/)

- [Org mode quickstart](https://orgmode.org/quickstart.html#fn.1)

- [Save and Quit Emacs](https://linuxhint.com/emacs_save_quit/)

- [Detailed Emacs guide](https://www.digitalocean.com/community/tutorials/how-to-use-the-emacs-editor-in-linux)

Παραδοτέο 9:

- [Drawing Arcs in Canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes#Arcs)

Παραδοτέο 10:

- [Save and exit an edited file in Vim](https://stackoverflow.com/questions/56265246/vim-no-write-since-last-change-even-though-i-changed-the-file)

- [Syntastic](https://vimawesome.com/plugin/syntastic)

Παραδοτέο 11: Ίδιες πηγές με παραδοτέο 6.
