# Τι νέο υπάρχει στο nvda


## 2016.4

Στα σημαντικότερα σημεία αυτής της κυκλοφορίας συμπεριλαμβάνονται η βελτιωμένη υποστήριξη για το Microsoft Edge; η λειτουργία περιήγησης για την εφαρμογή Mail των Windows 10; και σημαντικές βελτιώσεις στα παράθυρα διαλόγου του NVDA.

### Νέα Χαρακτηριστικά

* Το NVDA τώρα μπορεί να αναφέρει την ύπαρξη εσοχής γραμμής χρησιμοποιώντας τόνους. Αυτό μπορεί να ρυθμιστεί χρησιμοποιώντας το αναδυόμενο κουτί Αναφορά Εσοχής Γραμμής στο παράθυρο διαλόγου Ρυθμίσεις Μορφοποίησης Εγγράφου του NVDA. (#5906)
* Υποστήριξη για την οθόνη braille Orbit Reader 20. (#6007)
* Προστέθηκε η επιλογή να ανοίγει ο προβολέας εκφώνησης κατά την εκκίνηση. Αυτό μπορεί να ενεργοποιηθεί μέσω ενός πλαισίου επιλογής στο παράθυρο του προβολέα εκφώνησης. (#5050)
* Όταν ξανανοίγετε το παράθυρο του προβολέα εκφώνησης, τώρα πραγματοποιείται επαναφορά της θέσης και των διαστάσεων. (#5050)
* Τα πεδία παραπομπών στο Microsoft Word αντιμετωπίζονται τώρα ως υπερσύνδεσμοι. Αναφέρονται ως σύνδεσμοι και μπορούν να ενεργοποιηθούν. (#6102)
* Υποστήριξη για τις οθόνες braille Baum SuperVario2, Baum Vario 340 και HumanWare Brailliant2. (#6116)
* Κατ’ αρχήν υποστήριξη για την επετειακή έκδοση του Microsoft Edge. (#6271)
* Η λειτουργία περιήγησης τώρα χρησιμοποιείται όταν διαβάζετε email στην εφαρμογή mail των Windows 10. (#6271)

### Αλλαγές

* Το Liblouis Braille Translator αναβαθμίστηκε στην έκδοση 3.0.0. Συμπεριλαμβάνονται σημαντικές βελτιώσεις για το Ενοποιημένο Αγγλικό Braille. (#6109, #4194, #6220, #6140)
* Στο Διαχειριστή Πρόσθετων, τα κουμπιά Απενεργοποίηση Πρόσθετου και Ενεργοποίηση Πρόσθετου διαθέτουν τώρα συντομεύσεις πληκτρολογίου (alt+d και alt+e, αντίστοιχα). (#6388)
* Διάφορα ζητήματα αναπλήρωσης και στοίχισης στα παράθυρα διαλόγου του NVDA έχουν αντιμετωπιστεί. (#6317, #5548, #6342, #6343, #6349)
* Το παράθυρο διαλόγου Μορφοποίηση Εγγράφου έχει προσαρμοστεί έτσι ώστε να είναι δυνατή η κύλιση του περιεχομένου. (#6348)
* Προσαρμόστηκε η διάταξη του παραθύρου διαλόγου Προφορά Συμβόλων έτσι ώστε το πλήρες πλάτος του παραθύρου διαλόγου να χρησιμοποιείται για τη λίστα συμβόλων. (#6101)
* Κατά τη λειτουργία περιήγησης στους περιηγητές ιστού, με τις εντολές πλοήγησης χαρακτήρα για το πεδίο επεξεργασίας (e και shift+e) και το πεδίο φόρμας (f και shift+f) τώρα είναι δυνατή η μετακίνηση στα πεδία επεξεργασίας μόνο για ανάγνωση. (#4164)
* Στις ρυθμίσεις του NVDA για τη Μορφοποίηση Εγγράφου, η ”Αναγγελία αλλαγών στη μορφοποίηση μετά το δρομέα” έχει μετονομαστεί σε ”Αναφορά αλλαγών στη μορφοποίηση μετά το δρομέα”, επειδή επηρεάζει το braille όπως και την εκφώνηση. (#6336)
* Τροποποιήθηκε η εμφάνιση του “παραθύρου καλωσορίσματος” του NVDA. (#6350)
* Στα παράθυρα διαλόγου του NVDA τώρα τα κουμπιά ”ok" και ”Ακύρωση” είναι στοιχισμένα δεξιά στο παράθυρο διαλόγου. (#6333)
* Τα Στοιχεία Ελέγχου Αυξομείωσης τώρα χρησιμοποιούνται για τα πεδία εισαγωγής αριθμών όπως τη ρύθμιση ”ποσοστό μεταβολής του τόνου για τα κεφαλαία” στο παράθυρο διαλόγου Ρυθμίσεις Φωνής. Μπορείτε να εισάγετε την επιθυμητή τιμή ή να χρησιμοποιήσετε τα πλήκτρα άνω και κάτω βέλος ώστε να προσαρμόσετε την τιμή. (#6099)
* Ο τρόπος που αναφέρονται τα IFrame (έγγραφα τα οποία ενσωματώνονται σε έγγραφα) έχει γίνει πιο συνεπής στους περιηγητές ιστού. Τα IFrame τώρα αναφέρονται ως ”frame" στο Firefox. (#6047)

### Διόρθωση Σφαλμάτων

* Επιδιόρθωση σπάνιου ζητήματος κατά το οποίο στην έξοδο από το NVDA, με ανοιχτό τον προβολέα εκφώνησης, προέκυπτε σφάλμα. (#5050)
* Οι χάρτες εικόνων εμφανίζονται τώρα κανονικά κατά τη λειτουργία περιήγησης στο Mozilla Firefox. (#6051)
* Στο παράθυρο διαλόγου του λεξικού, αν πατήσετε το πλήκτρο Enter αποθηκεύονται οι αλλαγές και κλείνει το παράθυρο. Έως τώρα, όταν πατούσατε το enter δεν πραγματοποιούνταν καμία ενέργεια. (#6206)
* Τα μηνύματα τώρα εμφανίζονται σε braille όταν αλλάζετε λειτουργία εισόδου για μέθοδο εισόδου (φυσική είσοδος/αλφαριθμητική, πλήρους σχήματος/ημιτελούς σχήματος, κ.λπ.). (#5892, #5893)
* Αν απενεργοποιήσετε και αμέσως μετά ενεργοποιήσετε ένα πρόσθετο ή αντίστροφα, η κατάσταση του πρόσθετου επανέρχεται τώρα σωστά στην προηγούμενη κατάσταση. (#6299)
* Όταν χρησιμοποιείτε το Microsoft Word, τα πεδία αρίθμησης σελίδων στις κεφαλίδες τώρα μπορούν να αναγνωσθούν. (#6004)
* Το ποντίκι τώρα μπορεί να χρησιμοποιηθεί για να μετακινείται η εστίαση μεταξύ της λίστας συμβόλων και των πεδίων επεξεργασίας στο παράθυρο διαλόγου για την προφορά συμβόλων. (#6312)
* Επιδιόρθωση ενός ζητήματος κατά το οποίο, σε λειτουργία περιήγησης, σταματούσε η εμφάνιση της λίστας στοιχείων όταν το Microsoft Word περιείχε μη έγκυρο υπερσύνδεσμο. (#5886)
* Όταν πραγματοποιηθεί κλείσιμο από τη γραμμή εργαλείων ή τη συντόμευση Alt+F4, η κατάσταση του πλαισίου επιλογής για τον προβολέα εκφώνησης στο μενού του NVDA τώρα αντικατοπτρίζει την πραγματική ορατότητα του παραθύρου. (#6340)
* Η εντολή Επαναφόρτωση plugin δε δημιουργεί πλέον προβλήματα για ενεργοποιημένα προφίλ διαμόρφωσης, νέα έγγραφα σε περιηγητές ιστού και την επισκόπηση οθόνης. (#2892, #5380)
* Στη λίστα γλωσσών στο παράθυρο διαλόγου των γενικών ρυθμίσεων του NVDA, γλώσσες όπως τα Αραγονικά τώρα εμφανίζονται σωστά στα Windows 10. (#6259)
* Τα προσομοιωμένα πλήκτρα συστήματος (π.χ. ένα κουμπί σε μια οθόνη braille που προσομοιώνει το πάτημα του πλήκτρου tab) παρουσιάζονται τώρα στην επιλεγμένη γλώσσα του NVDA στη βοήθεια εισόδου και στο παράθυρο διαλόγου για τις χειρονομίες εισόδου. Ως τώρα, παρουσιάζονταν στα Αγγλικά. (#6212)
* Η αλλαγή της γλώσσας του NVDA (στο παράθυρο διαλόγου Γενικές Ρυθμίσεις) τώρα δεν εφαρμόζεται έως ότου γίνει επανεκκίνηση του NVDA. (#4561)
* Το πεδίο ”μοτίβο” για μια νέα καταχώρηση στο λεξικό δεν επιτρέπεται πλέον να παραμείνει κενό. (#6412)
* Επιδιόρθωση ενός σπάνιου ζητήματος κατά το οποίο η σάρωση για σειριακές θύρες σε ορισμένα συστήματα καθιστούσε κάποιους οδηγούς για οθόνες braille αδύνατο να χρησιμοποιηθούν. (#6462)
* Στο Microsoft Word, οι αριθμημένες κουκκίδες σε κελιά πινάκων τώρα διαβάζονται όταν πραγματοποιείται μετακίνηση ανά κελί. (#6446)
* Είναι τώρα δυνατό να ορίσετε χειρονομίες για τις εντολές που αφορούν στον οδηγό για την οθόνη braille Handy Tech στο παράθυρο διαλόγου Χειρονομίες Εισόδου του NVDA. (#6461)
* Στο Microsoft Excel, αν πατήσετε Enter ή αριθμητικό Enter όταν πλοηγείστε σε ένα λογιστικό φύλλο τώρα αναφέρεται σωστά η μετάβαση στην επόμενη γραμμή. (#6500)
* Το iTunes δεν παγώνει αναδιαστήματα για πάντα όταν χρησιμοποιείται η λειτουργία περιήγησης για το iTunes Store, το Apple Music, κ.λπ. (#6502)
* Επιδιόρθωση προβλημάτων στις εφαρμογές που βασίζονται στις εκδόσεις 64 bit του Mozilla και του Chrome. (#6497)
* Στο Firefox με ενεργοποιημένη την πολυεπεξεργασία, η λειτουργία περιήγησης και τα επεξεργάσιμα πεδία κειμένου τώρα λειτουργούν κανονικά. (#6380)

### Αλλαγές Για Κατασκευαστές

* Τώρα είναι δυνατό να παρέχονται app module για εκτελέσιμα που περιέχουν τελεία (.) στα ονόματά τους. Οι τελείες αντικαθίστανται από κάτω παύλες (_). (#5323)
* Το νέο gui.guiHelper module περιλαμβάνει εργαλεία που απλοποιούν τη δημιουργία wxPython GUI, συμπεριλαμβανομένης της αυτόματης εισαγωγής κενών διαστημάτων. Αυτό επιτρέπει την καλύτερη οπτική εμφάνιση και συνέπεια καθώς και τη διευκόλυνση της δημιουργίας νέων GUI από τους τυφλούς προγραμματιστές. (#6287)

## 2016.3

Στα σημαντικότερα σημεία αυτής της κυκλοφορίας συμπεριλαμβάνονται η δυνατότητα απενεργοποίησης μεμονωμένων πρόσθετων; η υποστήριξη για τα πεδία φόρμας στο Microsoft Excel; σημαντικές βελτιώσεις στην αναφορά χρωμάτων; επιδιορθώσεις και βελτιώσεις που σχετίζονται με αρκετές οθόνες braille; καθώς και επιδιορθώσεις και βελτιώσεις στην υποστήριξη του Microsoft Word.

### Νέα Χαρακτηριστικά

* Η λειτουργία περιήγησης μπορεί τώρα να χρησιμοποιηθεί για την ανάγνωση εγγράφων PDF στο Microsoft Edge στην έκδοση Anniversary Update των Windows 10. (#5740)
* Η διακριτή διαγραφή και η διπλή διακριτή διαγραφή τώρα αναφέρονται, αν χρειάζεται, στο Microsoft Word. (#5800)
* Στο Microsoft Word, ο τίτλος ενός πίνακα αναφέρεται τώρα, αν έχει προστεθεί. Αν υπάρχει περιγραφή, μπορεί να αποκτήσει ο χρήστης πρόσβαση σε αυτή, χρησιμοποιώντας την εντολή για το άνοιγμα εκτενούς περιγραφής (NVDA+d) στη λειτουργία περιήγησης. (#5943)
* Στο Microsoft Word, το NVDA τώρα αναφέρει πληροφορίες θέσης όταν μετακινούνται οι παράγραφοι (alt+shift+κάτω βέλος και alt+shift+άνω βέλος). (#5945)
* Στο Microsoft Word, το διάστιχο γραμμής τώρα αναφέρεται μέσω της εντολής αναφοράς μορφοποίησης του NVDA, όταν αλλάζει με διάφορες συντομεύσεις του Microsoft word και όταν μετακινείται ο χρήστης σε κείμενο με διαφορετικό διάστιχο γραμμής, αν η Αναφορά Διάστιχου Γραμμής έχει ενεργοποιηθεί στις Ρυθμίσεις Μορφοποίησης Εγγράφου του NVDA. (#2961)
* Στον Internet Explorer, τα δομικά στοιχεία HTML5 τώρα αναγνωρίζονται. (#5591)
* Η αναφορά σχολίων (όπως στο Microsoft Word) μπορεί τώρα να απενεργοποιηθεί μέσω του πλαισίου επιλογής Αναφορά Σχολίων στο παράθυρο διαλόγου Ρυθμίσεις Μορφοποίησης Εγγράφου του NVDA. (#5108)
* Τώρα είναι δυνατό να απενεργοποιηθούν μεμονωμένα πρόσθετα στο Διαχειριστή Πρόσθετων. (#3090)
* Επιπλέον αντιστοιχήσεις πλήκτρων έχουν προστεθεί για τη σειρά οθονών braille ALVA BC640/680. (#5206)
* Υπάρχει τώρα εντολή για μετακίνηση της οθόνης braille στην τρέχουσα εστίαση. Αυτή τη στιγμή, μόνο η σειρά ALVA BC640/680 διαθέτει σχετική εντολή, αλλά μπορεί να οριστεί χειροκίνητα για άλλες οθόνες στο παράθυρο διαλόγου Χειρονομίες Εισόδου, αν το επιθυμεί ο χρήστης. (#5250)
* Στο Microsoft Excel, μπορείτε τώρα να αλληλεπιδράσετε με τα πεδία φόρμας. Μετακινηθείτε στα πεδία φόρμας, χρησιμοποιώντας τη Λίστα Στοιχείων ή την πλοήγηση χαρακτήρα στη λειτουργία περιήγησης. (#4953)
* Μπορείτε τώρα να ορίσετε μια χειρονομία εισόδου για να πραγματοποιείται εναλλαγή της λειτουργίας απλής επισκόπησης, χρησιμοποιώντας το παράθυρο διαλόγου Χειρονομίες Εισόδου. (#6173)

### Αλλαγές

* Το NVDA τώρα αναφέρει τα χρώματα χρησιμοποιώντας ένα βασικό κατανοητό σύστημα 9 αποχρώσεων και 3 σκιάσεων, με διακυμάνσεις στη φωτεινότητα και την απαλότητα. Είναι προτιμότερο από το να χρησιμοποιούνται υποκειμενικά και λιγότερο κατανοητά ονόματα χρωμάτων. (#6029)
* Η ισχύουσα συμπεριφορά του NVDA+F9 και μετά NVDA+F10 έχει τροποποιηθεί ώστε να επιλέγεται το κείμενο στο πρώτο πάτημα του F10. Όταν το F10 πατηθεί δύο φορές (με γρήγορες διαδοχικές κινήσεις) το κείμενο αντιγράφεται στο πρόχειρο. (#4636)
* Το eSpeak NG αναβαθμίστηκε στην έκδοση Master 11b1a7b (22 June 2016). (#6037)

### Διόρθωση Σφαλμάτων

* Στη λειτουργία περιήγησης στο Microsoft Word, η αντιγραφή στο πρόχειρο τώρα διατηρεί τη μορφοποίηση. (#5956)
* Στο Microsoft Word, το NVDA τώρα αναφέρει σωστές πληροφορίες όταν χρησιμοποιούνται οι εντολές του Word για την πλοήγηση σε πίνακα (alt+home, alt+end, alt+pageUp και alt+pageDown) και την επιλογή πίνακα (προστίθεται το Shift στις εντολές πλοήγησης). (#5961)
* Στα παράθυρα διαλόγου του Microsoft Word, η πλοήγηση αντικειμένου του NVDA έχει βελτιωθεί σημαντικά. (#6036)
* Σε κάποιες εφαρμογές όπως το Visual Studio 2015, οι συντομεύσεις (π.χ. control+c για αντιγραφή) αναφέρονται τώρα σωστά. (#6021)
* Επιδιόρθωση ενός σπάνιου ζητήματος κατά το οποίο, όταν αναζητούνταν συριακές θύρες, σε ορισμένα συστήματα, κάποιοι οδηγοί για οθόνες braille ήταν αδύνατο να χρησιμοποιηθούν. (#6015)
* Η αναφορά χρωμάτων στο Microsoft Word είναι τώρα πιο ακριβής, καθώς οι αλλαγές στα θέματα του Microsoft Office τώρα λαμβάνονται υπόψη. (#5997)
* Η λειτουργία περιήγησης για το Microsoft Edge και η υποστήριξη για τις συμβουλές αναζήτησης στο Μενού Έναρξη διατίθενται και πάλι στις εκδόσεις των Windows 10 μετά τον Απρίλη του 2016. (#5955)
* Στο Microsoft Word, η αυτόματη ανάγνωση των κεφαλίδων πίνακα λειτουργεί καλύτερα όταν πρόκειται για κελιά που έχουν συγχωνευθεί. (#5926)
* Στην εφαρμογή Mail των Windows 10, το NVDA δεν αποτυγχάνει πλέον να διαβάζει το περιεχόμενο των μηνυμάτων. (#5635)
* Όταν είναι ενεργή η εκφώνηση των πλήκτρων των εντολών, τα κλειδιά κλειδώματος, όπως το Κλείδωμα Κεφαλαίων, δεν εκφωνούνται πλέον δύο φορές. (#5490)
* Τα παράθυρα διαλόγου ελέγχου λογαριασμού για τους χρήστες των Windows τώρα διαβάζονται σωστά στην έκδοση Anniversary update των Windows 10. (#5942)
* Στο Web Conference Plugin (όπως χρησιμοποιείται στο out-of-sight.net) το NVDA δεν αναπαράγει πλέον ήχους μπιπ και δεν εκφωνεί τις ενημερώσεις της γραμμής προόδου που σχετίζονται με ό,τι καταγράφει το μικρόφωνο. (#5888)
* Η εκτέλεση της εντολής Εύρεση Προηγούμενου ή Εύρεση Επόμενου στη λειτουργία περιήγησης θα πραγματοποιήσει τώρα σωστά αναζήτηση πεζών ή κεφαλαίων, αν η αρχική αναζήτηση έκανε διάκριση μεταξύ πεζών και κεφαλαίων. (#5522)
* Όταν γίνεται επεξεργασία των καταχωρήσεων στο λεξικό, ο χρήστης ενημερώνεται για μη έγκυρες συνήθεις εκφράσεις. Το NVDA δεν κρασάρει πλέον αν το λεξικό περιέχει μια μη έγκυρη συνήθη έκφραση. (#4834)
* Αν το NVDA δε μπορεί να επικοινωνήσει με μια οθόνη braille (π.χ. γιατί έχει αποσυνδεθεί), θα απενεργοποιήσει αυτόματα τη χρήση της οθόνης. (#1555)
* Έχει βελτιωθεί ελαφρώς το φιλτράρισμα στη λίστα στοιχείων στη λειτουργία περιήγησης, σε κάποιες περιπτώσεις. (#6126)
* Στο Microsoft Excel, τα μοτίβα παρασκηνίου που αναφέρει το NVDA ταιριάζουν τώρα με αυτά που χρησιμοποιούνται από το Excel. (#6092)
* Βελτιώθηκε η υποστήριξη για την οθόνη σύνδεσης στα Windows 10, συμπεριλαμβανομένης της ανακοίνωσης ειδοποιήσεων και της ενεργοποίησης του πεδίου κωδικού πρόσβασης μέσω αφής. (#6010)
* Το NVDA εντοπίζει τώρα σωστά τα δευτερεύοντα κουμπιά δρομολόγησης στη σειρά οθονών braille ALVA BC640/680. (#5206)
* Το NVDA μπορεί ξανά να αναφέρει τις αναδυόμενες ειδοποιήσεις των Windows στις τελευταίες εκδόσεις των Windows 10. (#6096)
* Το NVDA σταματά πλέον να μην αναγνωρίζει πατήματα πλήκτρων σε συσκευές συμβατές με Baum και τις οθόνες braille HumanWare Brailliant B. (#6035)
* Αν έχει ενεργοποιηθεί η εμφάνιση αριθμών εκτός σύνδεσης στις Ρυθμίσεις Μορφοποίησης Εγγράφου του NVDA, η αρίθμηση των γραμμών εμφανίζεται τώρα στις οθόνες braille. (#5941)
* Όταν έχει απενεργοποιηθεί η εκφώνηση, η αναφορά αντικειμένων (π.χ. αν πατήσετε NVDA+tab για αναφορά εστίασης) τώρα εμφανίζεται στον προβολέα εκφώνησης όπως θα αναμενόταν. (#6049)
* Στη λίστα μηνυμάτων του Outlook 2016, οι σχετικές πληροφορίες πρόχειρου δεν αναφέρονται πλέον. (#6219)

### Αλλαγές Για Κατασκευαστές

* Η απευθείας καταγραφή πληροφοριών από μια ιδιότητα, δε συνεπάγεται πλέον την επαναλαμβανόμενη επίκληση της ιδιότητας αυτής. (#6122)

## 2016.2.1

Αυτή η έκδοση επιδιορθώνει σφάλματα στο Microsoft Word:

* Το NVDA δεν προκαλεί πλέον σφάλμα του Microsoft Word στα Windows XP μετά την εκκίνησή του. (#6033)
* Αφαιρέθηκε η αναφορά γραμματικών λαθών, καθώς προκαλούνται σφάλματα στο Microsoft Word. (#5954, #5877)

## 2016.2

Στα σημαντικότερα σημεία αυτής της κυκλοφορίας συμπεριλαμβάνονται η δυνατότητα να υποδεικνύονται ορθογραφικά λάθη κατά το γράψιμο; υποστήριξη για την αναφορά γραμματικών σφαλμάτων στο microsoft word; καθώς και βελτιώσεις και επιδιορθώσεις στην υποστήριξη του microsoft office.

### Νέα χαρακτηριστικά

* Στη λειτουργία περιήγησης για το internet explorer και άλλα στοιχεία ελέγχου της microsoft, χρησιμοποιώντας πλοήγηση χαρακτήρα για να μετακινηθείτε ανάμεσα σε σημειώσεις (a και shift+a), τώρα μετακινήστε σε εισαγόμενο ή διαγραμένο κείμενο. (#5691)
* Στο Microsoft Excel, το nvda τώρα αναφέρει το επίπεδο μιας ομάδας από κελιά, καθώς και αν είναι συνεπτυγμένη ή αναπτυγμένη. (#5690)
* Πατώντας 2 φορές την εντολή Αναφορά Μορφοποίησης παρουσιάζονται οι πληροφορίες στη λειτουργία περιήγησης έτσι ώστε να μπορούν να εξεταστούν. (#4908)
* Στο Microsoft Excel 2010 και νεότερο, η σκίαση των κελιών και τα μοτίβα του παρασκηνίου τώρα αναφέρονται. Η αυτόματη αναφορά ελέγχεται από την επιλογή Αναφορά Χρωμάτων στις Προτιμήσεις Μορφοποίησης Εγγράφου του NVDA. (#3683)
* Νέος πίνακας μετάφρασης braille: Ελληνιστική κοινή. (#5393)
* Στην προβολή αρχείου καταγραφής συμβάντων, μπορείτε τώρα να αποθηκεύσετε το αρχείο χρησιμοποιώντας την συντόμευση control+s. (#4532)
* Αν η αναφορά ορθογραφικών λαθών είναι ενεργοποιημένη και υποστηρίζεται στο στοιχείο ελέγχου που έχει εστίαση, το nvda θα αναπαράγει έναν ήχο για να σας προειδοποιήσει για ορθογραφικά λάθη που έγιναν κατά το γράψιμο. Αυτό μπορεί να απενεργοποιηθεί χρησιμοποιώντας την νέα ρύθμιση "να παίζει ήχος για ορθογραφικά λάθη κατά το γράψιμο" στις ρυθμίσεις πληκτρολογίου του nvda. (#2024)
* Γραμματικά σφάλματα τώρα αναφέρονται στο microsoft word. Αυτό μπορεί να απενεργοποιηθεί χρησιμοποιώντας την νέα ρύθμιση "Να αναφέρονται γραμματικά σφάλματα" στις προτιμήσεις μορφοποίησης εγγράφου του nvda. (#5877)

### Αλλαγές

* Στην λειτουργία περιήγησης και σε επεξεργάσιμα πεδία κειμένου, το nvda αντιμετωπίζει τώρα το αριθμητικό πλήκτρο του enter με τον ίδιο τρόπο όπως και το βασικό πλήκτρο του enter. (#5385)
* Το nvda έχει μεταβεί στον συνθέτη ομιλίας eSpeak NG. (#5651)
* Στο Microsoft Excel, το nvda δεν αγνοεί πλέον την επικεφαλίδα μίας στήλης όταν υπάρχει κενή γραμμή μεταξύ του κελιού και της επικεφαλίδας. (#5396)
* Στο Microsoft Excel, οι συντεταγμένες τώρα ανακοινώνονται πριν από τις επικεφαλίδες για να μειωθεί η σύγχυση μεταξύ των επικεφαλίδων και του περιεχομένου. (#5396)

### Διόρθωση σφαλμάτων

* Στη λειτουργία περιήγησης, όταν επιχειρήσετε να χρησιμοποιήσετε την πλοήγηση χαρακτήρα για να μεταβείτε σε ένα στοιχείο που δεν υποστηρίζεται στο έγγραφο, το NVDA αναφέρει ότι δεν υποστηρίζεται αυτό, αντί να αναφέρει ότι δεν υπάρχει αυτό το στοιχείο σε αυτήν την κατεύθυνση. (#5691)
* Όταν εμφανίζεται λίστα με φύλλα στη λίστα στοιχείων στο microsoft excel, φύλλα που αποτελούνται μόνο από γραφήματα τώρα συμπεριλαμβάνονται. (#5698)
* το nvda δεν αναφέρει πλέον αχρείαστες πληροφορίες όταν γίνεται εναλαγή παραθύρων σε μια εφαρμογή java πολαπλών παραθύρων, όπως το IntelliJ ή το Android Studio. (#5732)
* Σε επεξεργαστές κειμένου που  βασίζονται στο Scintilla όπως το Notepad++, το braille τώρα ανανεώνεται σωστά όταν μετακινούμε τον δρομέα χρησιμοποιώντας μια οθόνη braille. (#5678)
* Το nvda δεν κολλά πλέον μερικές φορές όταν γίνεται ενεργοποίηση της εξόδου braille. (#4457)
* Στο Microsoft word, η στοίχιση της παραγράφου τώρα πάντα αναφέρεται στην μονάδα μέτρησης που έχει επιλεγεί από τον χρήστη (Παραδείγματος χάρη εκατοστά ή ίντσες). (#5804)
* Όταν γίνεται χρήση μιας οθόνης braille, πολλά μηνύματα του nvda που προηγουμένως μόνο αναγγέλλονταν τώρα εμφανίζονται επίσης και στο braille. (#5557)
* Σε προσβάσιμες εφαρμογές java, το επίπεδο στοιχείων δέντρου τώρα αναφέρονται. (#5766)
* Επιδιόρθωση διαφόρων κολλημάτων του Adobe Flash στο Mozilla Firefox σε κάποιες περιπτώσεις. (#5367)
* Στο google chrome και σε άλλους πλοηγούς που βασίζονται σε αυτό, κείμενο που βρίσκεται μέσα σε διαλόγους ή εφαρμογές τώρα μπορεί να διαβαστεί χρησιμοποιώντας λειτουργία περιήγησης. (#5818)
* Στο google chrome και σε άλλους πλοηγούς που βασίζονται σε αυτό, μπορείτε τώρα να αναγκάσετε το nvda να μεταβεί σε λειτουργία περιήγησης σε διαδικτυακούς διαλόγους ή εφαρμογές. (#5818)
* Στο internet explorer και σε άλλα στοιχεία ελέγχου της microsoft, μετακινώντας την εστίαση σε συγκεκριμένα στοιχεία, το nvda δεν μεταβαίνει λανθασμένα σε λειτουργία περιήγησης. Αυτό συνέβαινε για παράδειγμα όταν γινόταν μετακίνηση σε εισηγήσεις σε πεδία διευθύνσεων όταν γινόταν σύνθεση μηνύματος στο gmail. (#5676)
* Στο Microsoft word, το nvda δεν παγώνει πλέον σε μεγάλους πίνακες όταν η αναφορά επικεφαλίδων για στήλες και γραμμές είναι ενεργοποιημένη. (#5878)
* Στην λειτουργία περιήγησης στο microsoft word, οι εντολές μετακίνησης στο τέλος ή στην αρχή του στοιχείου υποδοχέα (κόμμα και shift+κόμμα) τώρα δουλεύουν και σε πίνακες. (#5883)

### Αλλαγές για κατασκευαστές

* Τα μέρη του nvda που είναι γραμμένα σε γλώσσα C++ τώρα κτίζονται με το Microsoft Visual Studio 2015. (#5592)
* Μπορείτε τώρα να παρουσιάσετε ένα μήνυμα κειμένου ή HTML στο χρήστη, στη λειτουργία περιήγησης, χρησιμοποιώντας το ui.browseableMessage. (#4908)

## 2016.1

Στα σημαντικότερα σημεία αυτής της κυκλοφορίας συμπεριλαμβάνονται η δυνατότητα κατ επιλογήν της μείωσης των άλλων ήχων; βελτιώσεις στην έξοδο braille και στην υποστήριξη οθονών braille; αρκετές σημαντικές βελτιώσεις στην υποστήριξη του microsoft office; και διορθώσεις στην κατάσταση περιήγησης στο iTunes.

### Νέα Χαρακτηριστικά

* Νέοι πίνακες μετάφρασης braille: Πολωνικά υπολογιστή οκτάστιγμο, Μογγολικά. (#5537, #5574)
* Μπορείτε να απενεργοποιήσετε τον δρομέα του braille ή να αλλάξετε το σχήμα του χρησιμοποιώντας τις νέες επιλογές εμφάνισης δρομέα και εμφάνισης σχήματος δρομέα στον διάλογο ρυθμίσεων του braille. (#5198)
* Το nvda τώρα μπορεί να συνδεθεί με την οθόνη braille HIMS Smart Beetle μέσω bluetooth. (#5607)
* Το nvda μπορεί κατ επιλογή να χαμηλώνει τους υπόλοιπους ήχους όταν εγκατασταθεί σε windows 8 και μεταγενέστερα. Αυτό μπορεί να καθοριστεί χρησιμοποιώντας την επιλογή κατάστασης βύθισης ήχου στον διάλογο ρυθμίσεων συνθέτη του nvda ή πατώντας NVDA+shift+d. (#3830, #5575)
* Υποστήριξη της οθόνης APH Refreshabraille σε κατάσταση HID, καθώς και για Baum VarioUltra και Pronto! όταν συνδέονται μέσω usb. (#5609)
* Υποστήριξη για τις οθόνες braille HumanWare Brailliant BI/B όταν το πρωτόκολλο είναι καθορισμένο σε OpenBraille. (#5612)

### Αλλαγές

* Η αναφορά της έμφασης τώρα είναι απενεργοποιημένη από προεπιλογή. (#4920)
* Στην λίστα στοιχείων στο microsoft excel, η συντόμευση για τις φόρμουλες έχει αλλάξει σε alt+r έτσι ώστε να διαφέρει από την συντόμευση για το πεδίο φιλτραρίσματος. (#5527)
* Αναβάθμιση του liblouis braille translator στην έκδοση 2.6.5. (#5574)
* Η λέξη "Κείμενο" δεν αναφέρεται πλέον όταν μετακινούμε τον δρομέα εστίασης ή εξέτασης σε αντικείμενα με κείμενο. (#5452)

### Διόρθωση Σφαλμάτων

* Στο iTunes 12, η λειτουργία περιήγησης τώρα αναβαθμίζεται σωστά όταν μια νέα σελίδα φορτώνει στο κατάστημα εφαρμογών. (#5191)
* Στο internet explorer και άλλα στοιχεία ελέγχου της microsoft, η μετακίνηση σε συγκεκριμένα επίπεδα επικεφαλίδων με την Πλοήγηση ενός γράμματος τώρα λειτουργεί όπως πρέπει όταν το επίπεδο κάποιας επικεφαλίδας έχει αντικατασταθεί για λόγους προσβασιμότητας (Συγκεκριμένα, όταν το επίπεδο στον κώδικα aria αντικαθιστά το επίπεδο ενός html tag). (#5434)
* Στο Spotify, η εστίαση δεν πέφτει συχνά σε "άγνωστα" αντικείμενα. (#5439)
* Η εστίαση τώρα επαναφέρεται σωστά όταν γίνεται επιστροφή στο spotify από κάποια άλλη εφαρμογή. (#5439)
* Όταν μεταβαίνουμε μεταξύ των λειτουργιών εστίασης ή περιήγησης, η λειτουργία τώρα αναφέρεται και στο braille εκτός από την ομιλία. (#5239)
* Το κουμπί έναρξης στην γραμμή εργασιών δεν αναφέρεται πλέον ως λίστα και / είτε σαν επιλεγμένη σε κάποιες εκδόσεις των windows. (#5178)
* Μηνύματα όπως "εισήχθη" δεν αναφέρονται πλέον όταν γίνεται σύνθεση μηνύματος στο microsoft outlook. (#5486)
* Όταν γίνεται χρήση οθόνης braille και όταν υπάρχει επιλεγμένο κείμενο στην τρέχουσα γραμμή (παραδείγματος χάριν όταν γίνεται αναζήτηση σε επεξεργαστή κειμένου που συναντάται στην τρέχουσα γραμή) η οθόνη braille θα πραγματοποιεί κύλιση όταν χρειάζεται. (#5410)
* Το nvda δεν κλείνει πλέον αθόρυβα όταν κλείνουμε ένα παράθυρο κονσόλας εντολών με alt+f4 στα windows 10. (#5343)
* Στην λίστα στοιχείων στην κατάσταση περιήγησης, όταν αλλάξει ο τύπος του στοιχείου, το κείμενο στο πεδίο φιλτραρίσματος τώρα καθαρίζεται. (#5511)
* Σε επεξεργάσιμα κείμενα σε εφαρμογές της mozila, η μετακίνηση του ποντικιού διαβάζει ξανά όπως πρέπει την κατάλληλη γραμμή, λέξη και λοιπά αντί για ολόκληρο το περιεχόμενο. (#5535)
* Όταν γίνεται μετακίνηση του ποντικιού σε επεξεργάσιμα κείμενα εφαρμογών της mozila, η αναγνωση δεν σταματά πλέον σε στοιχεία όπως συνδέσμους μέσα στην γραμμή ή λέξη που διαβάζεται. (#2160, #5535)
* Στο internet explorer, η ιστοσελίδα shoprite.com τώρα μπορεί να διαβαστεί σε κατάσταση περιήγησης αντί να αναφέρεται ως κενή. (#5569)
* Στο microsoft word, αλλαγές όπως "Εισήχθη" δεν αναφέρονται όταν η παρακολούθηση αλλαγών δεν εμφανίζεται. (#5566)
* Όταν γίνεται εστίαση σε ένα εναλλασσόμενο κουμπί, το nvda τώρα αναφέρει όταν αλλάζει από πιεσμένο σε μη πιεσμένο. (#5441)
* Η αναφορά της αλλαγής σχήματος του ποντικιού δουλεύει ξανά όπως πρέπει. (#5595)
* Όταν αναφέρεται η εσοχή γραμμής, μη αποσπόμενα διαστήματα αναφέρονται τώρα ως κανονικά διαστήματα. Προηγουμένως, αυτό μπορούσε να προκαλέσει ανακοινώσεις όπως "Διάστημα διάστημα διάστημα" αντί για "3 διαστήματα". (#5610)
* Κατά το κλείσιμο μιας λίστας προτεινόμενων χαρακτήρων σε μοντέρνα εφαρμογή της microsoft, η εστίαση επιστρέφει ειίτε στην είσοδο κειμένου ή στο επιλεγμένο κείμενο. (#4145)
* Στο microsoft office 2013 και μεταγενέστερα, όταν η κορδέλα είναι ρυθμισμένη να εμφανίζει μόνο καρτέλες, τα διάφορα στοιχία στην κορδέλα αναφέρονται όπως πρέπει όταν μια καρτέλα είναι επιλεγμένη. (#5504)
* Διορθώσεις και βελτιώσεις στην ανίχνευση χειρονομιών της οθόνης αφής. (#5652)
* Εξερευνήσεις πάνω στην οθόνη αφής δεν αναφέρονται πλέον στην βοήθεια εισόδου. (#5652)
* Το nvda δεν αποτυγχάνει πλέον να εμφανίσει σχόλια στην λίστα στοιχείων στο microsoft excel, αν ένα σχόλιό βρίσκεται σε ενοποιημένα κελιά. (#5704)
* Σε μια πολύ ασυνήθιστη περίπτωση, το nvda δεν αποτυγχάνει πλέον να διαβάσει περιεχόμενο φύλου στο microsoft excel όταν η αναφορά επικεφαλίδων στήλων και γραμμών είναι ενεργοποιημένη. (#5705)
* Στο google chrome, η πλοήγηση στην είσοδο κειμένου όταν συμπεριλαμβάνονται χαρακτήρες ανατολικής Ασίας τώρα δουλεύειε όπως πρέπει. (#4080)
* Όταν γίνεται αναζήτηση για apple music στο itunes, η κατάσταση περιήγησης για το κείμενο της λίστας των αποτελεσμάτων τώρα αναβαθμίζεται όπως πρέπει. (#5659)
* Στο microsoft excel, όταν πατήσουμε shift+f11 για να δημιουργήσουμε ένα νέο φύλο, η νέα θέση τώρα αναφέρεται αντί για τίποτα. (#5689)
* Διόρθωση σφαλμάτων με την εμφάνιση εξόδου braille όταν γινόταν εισαγωγή Κορεατικών χαρακτήρων. (#5640)

## 2015.4

Στα σημαντικότερα σημεία αυτής της κυκλοφορίας συμπεριλαμβάνονται βελτιωμένη απόδοση στα windows 10; συμπερίληψη στο Κέντρο διευκόλυνσης πρόσβασης στα windows 8 και μεταγενέστερα; βελτιώσεις στο microsoft excel, που συμπεριλαμβάνουν την εμφάνιση σε λίστα και τη μετονομασία φύλλων και την πρόσβαση σε κλειδωμένα κελιά προστατευμένων φύλλων; καθώς και υποστήριξη για την επεξεργασία εμπλουτισμένου κειμένου στο Mozilla Firefox, Google Chrome και Mozilla Thunderbird.

### Νέα Χαρακτηριστικά

* Το NVDA τώρα εμφανίζεται στο Κέντρο διευκόλυνσης πρόσβασης στα windows 8 και μεταγενέστερα. (#308)
* Όταν μετακινούμαστε ανάμεσα στα κελιά στο excel, αλλαγές μορφοποίησης τώρα αναφέρονται αυτόματα αν οι ανάλογες επιλογές είναι ενεργοποιημένες στο πλαίσιο διαλόγου Ρυθμίσεις Μορφοποίησης Εγγράφου του nvda. (#4878)
* Η επιλογή Αναφορά Έμφασης έχει προστεθεί στο πλαίσιο διαλόγου Ρυθμίσεις Μορφοποίησης του nvda. Ενεργοποιημένη από προεπιλογή, η επιλογή αυτή επιτρέπει στο nvda αυτόματα να αναφέρει την ύπαρξη κειμένου με έμφαση σε έγγραφα. Μέχρι τώρα, μόνο τα tags em και strong υποστηρίζονται στη Λειτουργία Περιήγησης για τον internet explorer και άλλα στοιχεία ελέγχου της microsoft. (#4920)
* Η ύπαρξη εισηγμένου ή διαγραμμένου κειμένου τώρα αναφέρεται στη λειτουργία περιήγησης για το internet explorer και άλλα στοιχεία ελέγχου της microsoft εάν η επιλογή για αναφορά αναθεωρήσεων συντάκτη είναι ενεργοποιημένη. (#4920)
* Όταν προβάλλεται η παρακολούθηση αλλαγών στη λίστα στοιχείων για το microsoft word, περισσότερες πληροφορίες εμφανίζονται τώρα όπως το ποιες ιδιότητες μορφοποίησης έχουν αλλάξει. (#4920)
* Microsoft excel: Η εμφάνιση σε λίστα καθώς και η δυνατότητα μετονομασίας φύλλων είναι τώρα δυνατή από τη λίστα στοιχείων του nvda (nvda+f7). (#4630, #4414)
* Είναι τώρα δυνατό να καθορίσει κάποιος το αν τα διάφορα σύμβολα θα στέλνονται σε συνθέτες φωνής (π.χ. αν θα προκαλούν κάποια παύση ή αλλαγή στον επιτονισμό) στο πλαίσιο διαλόγου Προφορά Συμβόλων. (#5234)
* Στο microsoft excel, το nvda τώρα αναφέρει τυχόντα μηνύματα εισόδου που έχουν σταλεί από το συγγραφέα του φύλλου στα κελιά. (#5051)
* Υποστήριξη των οθονών braille Baum Pronto! V4 και VarioUltra όταν συνδέονται μέσω bluetooth. (#3717)
* Υποστήριξη για την επεξεργασία εμπλουτισμένου κειμένου σε εφαρμογές της mozila όπως το google docs με την υποστήριξη braille ενεργοποιημένη στο Mozilla Firefox και στη σύνθεση html στο Mozilla Thunderbird. (#1668)
* Υποστήριξη για την επεξεργασία εμπλουτισμένου κειμένου στο Google Chrome και άλλους περιηγητές που βασίζονται στο chrome όπως το google docs με την υποστίρηξη braille ενεργοποιημένη. (#2634)
 * Αυτό προϋποθέτει έκδοση chrome 47 ή μεταγενέστερο.
* Στη λειτουργία περιήγησης στο microsoft excel, μπορείτε να μετακινήστε σε κλειδωμένα κελιά προστατευμένων φύλλων. (#4952)

### Αλλαγές

* Η επιλογή Αναφορά Αναθεωρήσεων Συντάκτη στο πλαίσιο διαλόγου Μορφοποίηση Εγγράφου του nvda είναι τώρα ενεργοποιημένη από προεπιλογή. (#4920)
* Κατά τη μετακίνηση ανά χαρακτήρα στο microsoft word με την αναφορά αναθεωρήσεων συντάκτη ενεργοποιημένη, λιγότερες πληροφορίες τώρα αναφέρονται για την παρακολούθηση αλλαγών, και έτσι η πλοήγηση είναι πιο αποτελεσματική. Για την προβολή των επιπρόσθετων πληροφοριών, χρησιμοποιήστε τη λίστα στοιχείων. (#4920)
* Αναβάθμιση του liblouis braille translator στην έκδοση 2.6.4. (#5341)
* Κάποια σύμβολα (Συμπεριλαμβανομένων κάποιων βασικών μαθηματικών συμβόλων) έχουν μετακινηθεί στο επίπεδο Κάποια, έτσι ώστε να αναφέρονται από προεπιλογή. (#3799)
* Εάν ο συνθέτης φωνής το επιτρέπει, θα πρέπει να υπάρχει παύση στην εκφώνηση για παρενθέσεις και την στενή παύλα (–). (#3799)
* Κατά την επιλογή κειμένου, το κείμενο τώρα αναφέρεται πριν την ένδειξη ότι γίνεται επιλογή, αντί για μετά. (#1707)

### Διόρθωση Σφαλμάτων

* Μεγάλη βελτίωση στην απόδοση κατά την πλοήγηση στη λίστα μηνυμάτων στο outlook 2010 και 2013. (#5268)
* Σε ένα γράφημα στο microsoft excel, η πλοήγηση με συγκεκριμένα πλήκτρα (όπως η αλλαγή φύλλων με το control+page up και control+page down) τώρα δουλεύει σωστά. (#5336)
* Διόρθωση της οπτικής εμφάνισης των κουμπιών στο προειδοποιητικό πλαίσιο διαλόγου που εμφανίζεται όταν προσπαθείτε να υποβαθμίσετε το nvda. (#5325)
* Στα windows 8 και μεταγενέστερα, το nvda τώρα ξεκινά πολύ γρηγορότερα, όταν είναι ρυθμισμένο να ξεκινά μετά την είσοδο στα windows. (#308)
 * Αν το ενεργοποιήσατε αυτό χρησιμοποιώντας μια προηγούμενη έκδοση του nvda, θα χρειαστεί να το απενεργοποιήσετε και να το ενεργοποιήσετε ξανά για να τεθεί σε ισχύ αυτή η αλλαγή. Ακολουθήστε αυτή τη διαδικασία:
  1. Ανοίξτε το πλαίσιο διαλόγου Γενικές Ρυθμίσεις.
  1. Αποεπιλέξτε την επιλογή Αυτόματη εκκίνηση του nvda μετά τη σύνδεσή μου στα windows.
  1. Πατήστε το κουμπί OK.
  1. Ανοίξτε ξανά το πλαίσιο διαλόγου Γενικές Ρυθμίσεις.
  1. Μαρκάρετε την επιλογή Αυτόματη εκκίνηση του nvda μετά τη σύνδεσή μου στα windows.
  1. Πατήστε το κουμπί OK.
* Βελτιώσεις στην απόδοση του UI Automation που συμπεριλαμβάνουν τον πλοηγό αρχείων ή την προβολή εργασιών. (#5293)
* Το nvda τώρα σωστά μεταβαίνει σε λειτουργία εστίασης όταν συναντάτε, χρησιμοποιώντας το πλήκτρο tab, ένα πλέγμα κουμπιών ελέγχου μόνο για ανάγνωση στη λειτουργία περιήγησης στο Mozilla Firefox, και άλλα κουμπιά ελέγχου Gecko. (#5118)
* Το nvda τώρα αναφέρει ορθά ότι "Δεν υπάρχει προηγούμενο" αντί για "δεν υπάρχει επόμενο", όταν δεν υπάρχουν άλλα αντικείμενα κατά τη σάρωση αριστερά σε κάποια οθόνη αφής.
* Επιδιόρθωση προβλημάτων όταν γίνεται πληκτρολόγηση πολλαπλών λέξεων στο πεδίο φίλτρου στο πλαίσιο διαλόγου Χειρονομίες Εισόδου. (#5426)
* Το nvda δεν παγώνει σε κάποιες περιπτώσεις, όταν γίνεται επανασύνδεση της οθόνης braille HumanWare Brailliant BI/B series μέσω usb. (#5406)
* Σε γλώσσες με ενοποιημένους χαρακτήρες, η περιγραφή χαρακτήρων λειτουργεί όπως πρέπει για κεφαλαίους χαρακτήρες στα Αγγλικά. (#5375)
* Το nvda δε θα παγώνει πλέον περιστασιακά όταν καλείτε το μενού έναρξης στα windows 10. (#5417)
* Στο skype για επιτραπέζιους υπολογιστές, ειδοποιήσεις που εμφανίζονται πριν εξαφανιστεί μια προηγούμενη ειδοποίηση, πλέον  αναφέρονται. (#4841)
* Ειδοποιήσεις τώρα αναφέρονται σωστά για το skype για επιτραπέζιους υπολογιστές, έκδοσης 7.12 και μεταγενέστερα. (#5405)
* Το nvda τώρα αναφέρει σωστά την εστίαση όταν κλείνουν αναδυόμενα μενού σε μερικές εφαρμογές όπως το jarte. (#5302)
* Στα windows 7 και μεταγενέστερα, το χρώμα αναφέρεται ξανά σε κάποιες εφαρμογές όπως το Wordpad. (#5352)
* Όταν γίνεται επεξεργασία στο powerpoint, κατά το πάτημα του enter γίνεται αυτόματη αναγγελία του εισαγόμενου κειμένου όπως αριθμημένες λίστες ή λίστες με κουκκίδες. (#5360)

## 2015.3

Στα σημαντικότερα σημεία αυτής της κυκλοφορίας συμπεριλαμβάνονται αρχική υποστήριξη για τα windows 10; η δυνατότητα απενεργοποίησης της Πλοήγησης Ενός Γράμματος στην Λειτουργία Περιήγησης (χρήσιμο για κάποιες διαδικτυακές εφαρμογές); βελτιώσεις στο internet explorer; και διορθώσεις για ανακατεμένο κείμενο όταν γινόταν πληκτρολόγηση με το braille ενεργοποιημένο.

### Νέα χαρακτηριστικά

* Η ύπαρξη ορθογραφικών λαθών ανακοινώνεται σε πεδία επεξεργασίας για τον internet explorer και άλλα στοιχεία ελέγχου html της microsoft. (#4174)
* Ακόμα περισσότερα unicode μαθηματικά σύμβολα τώρα αναγγέλλονται όταν εμφανίζονται σε κείμενο. (#3805)
* Εισηγήσεις αναζήτησης στην οθόνη έναρξης των windows 10 αναφέρονται αυτόματα. (#5049)
* Υποστήριξη για τις οθόνες braille EcoBraille 20, EcoBraille 40, EcoBraille 80 και EcoBraille Plus. (#4078)
* Στη λειτουργία περιήγησης, μπορείτε τώρα να ενεργοποιήσετε ή να απενεργοποιήσετε την πλοήγησή ενός γράμματος πατώντας nvda+shift+διάστημα. Όταν είναι απενεργοποιημένη, τα πλήκτρα πλοήγησης ενός γράμματος περνούν κατευθείαν στην εφαρμογή, το οποίο είναι χρήσιμο για κάποιες διαδικτυακές εφαρμογές όπως το gmail, το twitter και το facebook. (#3203)
* Νέοι πίνακες braille: Φινλανδικό εξάστιγμο, Ιρλανδικά βαθμού 1, Ιρλανδικά βαθμού 2, Κορεάτικα βαθμού 1 (2006), Κορεάτικα βαθμού 2 (2006). (#5137, #5074, #5097)
* Το qwerty πληκτρολόγιο στην οθόνη braille Papenmeier BRAILLEX Live Plus τώρα υποστηρίζεται. (#5181)
* Πειραματική υποστήριξη για τον περιηγητή διαδικτύου της microsoft Edge και για την μηχανή περιήγησης στα windows 10. (#5212)
* Νέα γλώσσα: Καναντική.

### Αλλαγές

* Αναβάθμιση του liblouis braille translator στην έκδοση 2.6.3. (#5137)
* όταν επιχειρήσετε να εγκαταστήσετε μια προηγούμενη έκδοση του nvda από εκείνη που είναι είδη εγκατεστημένη, θα προειδοποιηθείτε ότι αυτό δεν συνιστάται και πως το nvda θα πρέπει να απεγκατασταθεί πριν συνεχίσετε. (#5037)

### Διόρθωση σφαλμάτων

* Στην λειτουργία περιήγησης για τον internet explorer και άλλα στοιχεία ελέγχου html της microsoft, η γρήγορη μετακίνηση ανάμεσα σε πεδία φόρμας δεν συμπεριλαμβάνει λανθασμένα και λίστες παρουσίασης. (#4204)
* Στον Firefox, το NVDA δεν αναφέρει πλέον λανθασμένα το περιεχόμενο περιοχής καρτέλας όταν εστιάζετε εντός αυτής της περιοχής. (#4638)
* Στον internet explorer και άλλα στοιχεία ελέγχου html της microsoft, όταν χρησιμοποιώντας το πλήκτρο tab φτάσουμε σε τμήματα, άρθρα ή παράθυρα διαλόγου, δεν αναφέρεται λανθασμένα ολόκληρο το περιεχόμενο τους. (#5021, #5025)
* όταν χρησιμοποιούνται οθόνες braille της Baum/HumanWare/APH που περιλαμβάνουν και πληκτρολόγιο braille, η εισαγωγή braille δεν σταματά να λειτουργεί μόλις χρησιμοποιηθεί ένα άλλο είδος πλήκτρου στην οθόνη. (#3541)
* Στα windows 10, δεν αναφέρονται πλέον αχρείαστες πληροφορίες όταν πατήσουμε alt+tab ή alt+shift+tab για να γίνει εναλλαγή μεταξύ των εφαρμογών. (#5116)
* Κείμενο που πληκτρολογούμε δεν είναι πλέον ανακατεμένο όταν χρησιμοποιούνται συγκεκριμένες εφαρμογές όπως το microsoft outlook μαζί με οθόνη braille. (#2953)
* Στην λειτουργία περιήγησης για τον internet explorer και άλλα στοιχεία ελέγχου html της microsoft, το σωστό περιεχόμενο τώρα αναφέρεται όταν ένα στοιχείο εμφανίζεται ή αλλάζει και αμέσως εστιάζεται. (#5040)
* Στην λειτουργία περιήγησης στο microsoft word, η Πλοήγηση Ενός Γράμματος ανανεώνει τώρα σωστά την οθόνη braille και τον δρομέα εξέτασης όπως αναμένεται. (#4968)
* Στο braille, αχρείαστα διαστήματα δεν εμφανίζονται πλέον μεταξύ ή μετά από ενδείξεις για στοιχεία ελέγχου και μορφοποίησης. (#5043)
* Όταν μια εφαρμογή ανταποκρίνεται πολύ αργά και μεταβείτε  εκτός αυτής, τώρα το nvda είναι πολύ καλύτερο στην απόκριση του σε άλλες εφαρμογές στις πλείστες των περιπτώσεων. (#3831)
* Οι ειδοποιήσεις πλακιδίων στα windows 10 τώρα αναφέρονται σωστά όπως αναμένεται. (#5136)
* Η αξία πλέον αναφέρεται, καθώς αλλάζει, σε συγκεκριμένα (UI Automation) κουτιά ελέγχου, εκεί που αυτό δεν ήταν δυνατό προηγουμένως.
* Στην λειτουργία περιήγησης για περιηγητές διαδικτύου, η μετακίνηση με το πλήκτρο tab τώρα λειτουργεί όπως αναμένεται όταν κάποιος μεταβεί σε έγγραφο μέσα σε πλαίσιο. (#5227)
* Η οθόνη κλειδώματος των windows 10 μπορεί τώρα να απομακρυνθεί χρησιμοποιώντας μια οθόνη αφής. (#5220)
* στα windows 7 και μεταγενέστερα, το κείμενο δεν είναι πλέον ανακατεμένο όταν γίνεται πληκτρολόγηση σε συγκεκριμένες εφαρμογές όπως το wordpad και το skype μαζί με οθόνη braille. (#4291)
* Στην οθόνη κλειδώματος των windows 10, δεν είναι πλέον δυνατή η ανάγνωση του πρόχειρου, η πρόσβαση σε τρέχουσες εφαρμογές με το δρομέα επανεξέτασης, η αλλαγή της διαμόρφωσης του nvda και άλλα. (#5269)

