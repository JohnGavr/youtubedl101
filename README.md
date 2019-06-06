## YTD101 - YoutubeDownloadBashScript

### Λόγοι δημιουργίας

Έχετε βαρεθεί να ψάχνετε για online μετατροπές youtube URL σε mp3 αρχεία; 

Χρησιμοποιείτε Linux; 

Αν και οι δύο απαντήσεις σας είναι ναι τότε αυτό το script θα σας λύσει τα χέρια από περιττές αναζητήσεις. 

### Προαπαιτούμενα

1. Linux σύστημα
2. youtube-dl command

Σε Debian/Ubuntu : ```sudo apt-get install youtube-dl```

Σε περίπτωση που υπάρχει ασυμβατότητα του youtube-dl στο σύστημα σας μπορείτε να εγκαταστήσετε το πακέτο μέσω του python-pip

``` sudo apt-get install python-pio```
``` sudo pip install youtube-dl```

Σε Arch : ```sudo pacman -S youtube-dl```

### Εκτέλεση

Μόλις κατεβάσετε το repo, ανοίξτε το τερματικό σας και μέσω της εντολής cd πηγαίνετε στο μέρος που το έχετε αποθηκεύσει.

Για την εκτέλεση του script : ./ytd.sh

Σε περίπτωση που δεν είναι εκτελέσιμο πληκτρολογήστε στο τερματικό : ```chmod +x ytd.sh```

### Πρόσθετες Πληροφορίες

1. Όλα τα mp3 αρχεία αποθηκεύονται στο PATH= /home/username/Music
2. Το mp3 αρχείο παίρνει το όνομα του youtube video.
3. Μαζί με το mp3 αποθηκεύεται και το thumbnail του video. 

