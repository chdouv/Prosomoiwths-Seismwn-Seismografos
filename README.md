# Προσομοιωτής σεισμών και σεισμογράφος
Πλατφόρμα παραγωγής σεισμών με σκοπό την μελέτη της στατικότητας κατασκευών με διαφορετικά δομικά και μηχανικά χαρακτηριστικά, καθώς και οπτικοποίησης των σεισμών με βάση το πλάτος των δονήσεων  σε χαρτί.

https://openedtech.ellak.gr/robotics2024/prosomiotis-sismon-ke-sismografos-robostar-1o-dimotiko-scholio-polichnis/

https://blogs.sch.gr/chdouvletis/2024/06/16/prosomoiotis-seismon-kai-seismografos-robostar-1o-dimotiko-scholeio-polichnis/

Προσομοιωτής σεισμών και σεισμογράφος

ΣΥΝΤΟΜΗ ΠΕΡΙΓΡΑΦΗ
Πλατφόρμα παραγωγής σεισμών με σκοπό την μελέτη της στατικότητας κατασκευών με διαφορετικά δομικά και μηχανικά χαρακτηριστικά, καθώς και οπτικοποίησης των σεισμών με βάση το πλάτος των δονήσεων  σε χαρτί.
ΣΤΟΧΟΙ:
•	Να διακρίνουν τα είδη των σεισμών.
•	Να διακρίνουν τα μηχανικά χαρακτηριστικά που επηρεάζουν τη στατικότητα κτιρίων και κατασκευών.
•	Να καταγράφουν τα δεδομένα ενός πειράματος και να τα παρουσιάζουν.
•	Να προγραμματίζουν συστήματα μέσω του microbit.
•	Να συλλέγουν δεδομένα από αισθητήρες και να ανταποκρίνονται σε αυτά με κινητήρες.
•	Να εργάζονται σε ομάδες.
ΤΡΟΠΟΣ ΕΡΓΑΣΙΑΣ ΟΜΑΔΑΣ
Η ομάδα ρομποτικής του σχολείου μας, που αποτελείται από μαθητές της ΣΤ και Ε τάξης, θα αναλάβει να ολοκληρώσει την εργασία. Οι μαθητές θα χωριστούν σε μικρότερες ομάδες όπου η καθεμιά θα είναι υπεύθυνη για ένα επιμέρους τμήμα της εργασίας. 
Ο υπεύθυνος εκπαιδευτικός θα αναλάβει να προετοιμάσει τους μαθητές στην χρήση των απαιτούμενων εξαρτημάτων και τον προγραμματισμό τους, να αναθέσει τις εργασίες κάθε υπο-ομάδας και να επιβλέπει την πορεία της εργασίας.
Οι μαθητές θα μπορούν είτε να εργάζονται στο εργαστήριο Πληροφορικής του σχολείου, μετά το πέρας των μαθητών είτε να παίρνουν τα υλικά στο σπίτι τους και να δουλεύουν αυτόνομα ή και ομαδικά.

ΑΠΑΙΤΟΥΜΕΝΟΣ ΕΞΟΠΛΙΣΜΟΣ:<BR>
Υλικά Κόστος <BR>
Micro:Bit x 3 	3 x 20,00 € <BR>
Edge Connector Breakout Board for BBC micro:bit - Pre-built x 3 	3 x 6,00 € <BR>
Μπαταριοθήκη 2xAA με JST PH & Διακόπτη x 3 	3 x 1,60 € <BR>
Hobby Motor 3-6V DC 17000-18000rpm with Wires  1,20 € <BR>
Ισχυρός Κινητήρας Δόνησης 20x25mm  1,60 € <BR>
Servo Micro 2.2kg.cm Plastic Gears (Waveshare SG90)  3,60 € <BR>
Servo Standard 6kg.cm Continuous Rotation 12,50 € <BR>
Jumper Wires 15cm Female to Male - Pack of 10 x 3 	3 x 1,80 € <BR>
Σύνολο 103,83 €<BR>

ΔΙΕΥΘΥΝΣΗ ΑΠΟΘΕΤΗΡΙΟΥ GITHUB:
https://github.com/chdouv/Prosomoiwths-Seismwn-Seismografos

Α. ΕΙΣΑΓΩΓΗ
Οι σεισμοί, είτε τους καταλαβαίνουμε είτε όχι, γίνονται συνεχώς και αποτελούν ένα φυσικό φαινόμενο που επηρεάζει τη ζωή μας, ιδιαίτερα στην Ελλάδα, που είναι μια σεισμογενής χώρα.

Στην εργασία αυτή, σκοπός μας είναι η κατασκευή μιας πλατφόρμας που θα παράγει σεισμούς (προσομοιωτής σεισμών), με την οποία οι μαθητές θα έχουν τη δυνατότητα να μελετήσουν την στατικότητα κατασκευών με διαφορετικά μηχανικά χαρακτηριστικά (υλικά κατασκευής, σύνδεσμοι, σχήμα κ.τ.λ.).

Επιπλέον, θα συνοδεύεται από σύστημα καταγραφής των σεισμών σε χαρτί με σκοπό την οπτικοποίηση των δονήσεων και του πλάτους τους.

Β. ΑΝΑΛΥΤΙΚΗ ΠΕΡΙΓΡΑΦΗ
Η κατασκευή αποτελείται από μία επίπεδη επιφάνεια στην οποία έχουν προσαρτηθεί κινητήρες (με ασύμμετρη τοποθέτηση βαριδίων στον άξονά τους) που ελέγχονται από ένα microbit και παράγουν δονήσεις με σκοπό την προσομοίωση σεισμών. Οι κινητήρες θα προκαλούν κατακόρυφες και οριζόντιες κινήσεις, ώστε να προσεγγίζουν όσο γίνεται περισσότερο τους πραγματικούς σεισμούς.

Οι μαθητές θα μπορούν να τοποθετούν κατασκευές πάνω στην επιφάνεια φτιαγμένες από καλαμάκια, χαρτί και άλλα υλικά χειροτεχνίας, με διαφορετικά σχήματα και συνδέσμους, με σκοπό την μελέτη της ανθεκτικότητάς τους στους σεισμούς.

Επιπλέον, στην επίπεδη επιφάνεια θα τοποθετηθεί και ένα microbit που, με τους αισθητήρες που διαθέτει, θα καταγράφει την ένταση των δονήσεων. Τις μετρήσεις που κάνει, τις στέλνει ασύρματα σε ένα άλλο microbit, το οποίο λαμβάνει και τις μετατρέπει σε κινήσεις ενός κινητήρα servo. Στον κινητήρα αυτόν έχει στερεωθεί έναν μαρκαδόρος, ο οποίος σχηματίζει την κυματομορφή των δονήσεων πάνω σε ένα ρολό χαρτί. Το ρολό χαρτί ξετυλίγεται από έναν κινητήρα συνεχούς περιστροφής με αποτέλεσμα ο σεισμός να αποτυπώνεται σε χαρτί, όπως στους σεισμογράφους. Τέλος, το microbit θα γράφει στην οθόνη του το μέγεθος του σεισμού.

Η κατασκευή αυτή θα χρησιμοποιηθεί στο πλαίσιο Περιβαλλοντικού Προγράμματος και Εργαστηρίου Δεξιοτήτων μικρότερων τάξεων με θέμα τους σεισμούς. Οι μικροί μαθητές θα έχουν την ευκαιρία να κατανοήσουν καλύτερα τους σεισμούς και πως η μηχανική και τα υλικά των κτιρίων επηρεάζουν την αντοχή τους.

Εκτός από τα ηλεκτρονικά εξαρτήματα, όλα τα υπόλοιπα υλικά που θα χρησιμοποιηθούν για το έργο αυτό θα είναι ανακυκλώσιμα και εύκολο να  βρεθούν από τους μαθητές, με βάση τις αρχές της κυκλικής οικονομίας.

Γ. ΑΞΙΟΛΟΓΗΣΗ - ΔΙΑΧΥΣΗ
•	Παρουσίαση σε μαθητές και γονείς του 1ου Δημοτικού Σχολείου Πολίχνης.
•	Ανάρτηση στην ιστοσελίδα του σχολείου.
•	Συμμετοχή σε Πρόγραμμα Περιβαλλοντικής Εκπαίδευσης με θέμα τους σεισμούς.
•	Αξιοποίηση σε δράσεις στο πλαίσιο των Εργαστηρίων Δεξιοτήτων.
•	Συμμετοχή στο Μαθητικό Συνέδριο Πληροφορικής (http://www.math-syn-pli.gr)
