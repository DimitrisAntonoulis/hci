# ΙΟΝΙΟ ΠΑΝΕΠΙΣΤΗΜΙΟ, ΤΜΗΜΑ ΠΛΗΡΟΦΟΡΙΚΗΣ 
## ΜΑΘΗΜΑ
### Επικοινωνία ανθρώπου υπολογιστή (HCI) 
Επιβλέπων καθηγητής: Χωριανόπουλος Κωνσταντίνος 

## Στοιχεία φοιτήτριας 
### Γιώτα Πετσάβα
### ΑΜ: Π2014068

### Προσωπικό αποθετήριο https://github.com/p14pets/hci 

## Εισαγωγή
Έγιναν 6 ασκήσεις σε linux terminal και 4 παραδοτέα συμμετοχικού εκπαιδευτικού υλικού. Οι 4 ασκήσεις terminal έγιναν σε wsl2 (Ubuntu 18.04) στα windows 10, ενώ οι επιπλέον 2 ασκήσεις έγιναν στο virtual box με ubuntu 18.04(LTS). Περιγράφεται ο τρόπος εκπόνησης της κάθε άσκησης και παραθέτοντε τα urls με τα recorded sessions του asciinema, καθώς και πηγές αντλησης πληροφοριών για την εκπόνηση της κάθε άσκησης.
## Συμμετοχικό εκπαιδευτικό υλικό
#### Προσωπικό αποθετήριο https://github.com/p14pets/gr
#### url σελίδας βιβλίου https://p14pets-gr.netlify.app/

### Παραδοτέο 1.Α
Προσθήκη 2 νέων εικόνων με λεζάντα.

#### Atari https://p14pets-gr.netlify.app/gallery/atari/
#### Oculus rift https://p14pets-gr.netlify.app/gallery/oculus-rift/

### Παραδοτέο 1.Γ.2
Προσθήκη νέας βιογραφίας

#### Ivan Sutherland https://p14pets-gr.netlify.app/biography/sutherland/

##### Πηγές
https://en.wikipedia.org/wiki/Ivan_Sutherland


### Επιπλέον παραδοτέο 1.Γ.1
Νέα μελέτη περίπτωσης

#### Twitter https://p14pets-gr.netlify.app/case-study/twitter/

##### Πηγές
https://en.wikipedia.org/wiki/Twitter

### Επιπλέον παραδοτέο 1.B
Νέο διαδραστικό παράδειγμα

#### Image map https://p14pets-gr.netlify.app/remix/imagemap/
##### Αποθετήριο χάρτη https://github.com/p14pets/Image-map

##### Πηγές
###### shp περιφέρειες Ελλάδας https://geodata.gov.gr/en/dataset/periphereies-elladas/resource/7c80a2c1-93b7-4814-9fc4-245e775acaa6

## Άσκηση 1. Σet-up the main dependencies and demonstrate your base system. change your command prompt with your student ID, list your dot files, display your shell configuration file and display system information (hardware+software)

#### url asciinema https://asciinema.org/a/yCnqSUKWRPNje3GVvlULUYAuc

Για να αλλάξω το command prompt με τον αμ μου χρησιμοποίησα το αρχείο .bashrc και τον nano editor

```
sudo nano .bashrc
```

Για να δείξω τα dotfiles έγραψα την εντολή

```
ls -a
```

Για να δείξω τις πληροφορίες του συστήματός μου χρησιμοποίησα το neofetch. Το εγκατέστησα με την εντολή

```
sudo apt-get install neofetch
```

και το έτρεξα με την εντολή 

```
neofetch
```

## Άσκηση 2. Get familiar with basic commands, reading documentation and editing files. Browse and view files on your system

#### url asciinema  https://asciinema.org/a/KZ22oOO0qMmsjZ34UFScnctN0

Για αυτη την εργασία χρησιμοποίησα το ranger. Μπορείς να πλοηγηθείς στο filesystem και να δεις directory και αρχεία πολύ εύκολα. Μπορείς ακόμα και να τα επεξεργαστείς με όποιον editor θες. Για να εγκαταστήσω το ranger χρησιμοποίησα την εντολή


```
sudo apt install ranger
```

Αφού είδα το manual με την εντολή

```
man ranger
```

Έτρεξα το ranger με την εντολή

```
ranger
```

## Άσκηση 3. Βecome productive with a todo list. Create a list of todos, edit, delete, and check some of them.

#### url asciinema  https://asciinema.org/a/h0EwpoOX1KCMoPveWbzyA2QbH

Για την άσκηση αυτή χρησιμοποίησα το taskwarrior https://taskwarrior.org/docs/start.html. Πληροφορίες σχετικά με την εγκατάσταση βρήκα στο https://www.linode.com/docs/applications/project-management/setting-up-taskwarrior-on-ubuntu-16-10/.

Η εγκατάσταση έγινε με την εντολή

```
sudo apt-get install taskwarrior
```

προσθέτεις tasks και με προθεσμία με την εντολή 

```
task add <your task> due:tomorrow
```

σβήνεις tasks με την εντολή

```
task <index> delete
```

επεξεργάζεσαι task με τον editor με την εντολή

```
task <index> edit
```

και τελειώνεις τα task που εχουν γίνει με την εντολή

```
task <index> done
```

Επίσης το taskwarrior υποστηριζει visualizations με τις εντολές 

```
burndown
```

και

```
calendar
```

Για να δεις όλα τα tasks απλά πληκτρολογείς

```
task
```

## Άσκηση 4. Plan your time with a calendar. Add, edit, search for an appointment.
#### url asciinema  https://asciinema.org/a/OO0DtR1dPoH0VGgJFonKYPXqE

Για την άσκηση αυτή χρησιμοποίησα το calcurse https://calcurse.org/. Η εγκατάσταση γίνε πολύ εύκολα με

```
sudo apt-get install calcurse
```

τρέχει με την εντολή

```
calcurse
```

Είναι πάρα πολύ εύκολο στη χρήση. Έυκολη αναζήτηση appoinmets απο το calendar, επιλογή ωρας έναρξης και ώρας λήξης, ή ολοήμερο event. Μπορείς να προσθέσεις και tasks σε todo list

## Επιπλέον άσκηση 5. Οrganise the terminal window into multiple areas. Use one window to search-edit local files or browse the web and another window for performance monitoring.
#### url asciinema  https://asciinema.org/a/qNSB43kNQIMbDiFSBameTBAOB
Εγκατέστησα το tmux και το htop για performance monitoring

```
sudo apt-get install tmux
sudo apt-get install htop
```

έτρεξα το tmux και δημιουργησα νέο παράθυρο όπου ξεκίνησα το performance monitoring

```
tmux
ctrl b % //ανοίγει το νέο παράθυρο
htop 
ctrl b ; //εναλλαγή active παραθύρου
```

Πίσω στο αρχικό παράθυρο έτρεξα το ranger γαι να περιηγηθώ στο file system.

```
ranger
```

### Πηγές

https://www.youtube.com/watch?v=BHhA_ZKjyxo

https://superuser.com/questions/777269/how-to-close-a-tmux-session

Το tmux τερματίζει πατώντας ctrl b :, γράφωντας kill-session

## Επιπλέον άσκηση 6. Surf the web.  Create a new elvi
#### url asciinema  https://asciinema.org/a/14D3J1XDWdr4rWBV5S5evuHhX

Εγκατέστησα το surfraw

```
sudo apt-get install surfraw
```
εκανα copy το youtube elvi στον φάκελο .config/surfraw/elvi με ονομασία stackoverflow και επεξεργάστηκα το νέο αυτό αρχείο ώστε να μπορώ να κάνω πλέον search στο stackoverflow. To stackoverflow χρησιμοποιεί το εξίς query στο url: https://stackoverflow.com/search?q=

```
sr -elvi //δείχνει πλέον το νέο local elvi
sr stackoverflow java //ανοίγει τον browser με το αποτέλεσμα
```

![surfraw result](result.jpg)

### Πηγές
https://www.youtube.com/watch?v=FvimaTL_kJU

https://manpages.debian.org/testing/surfraw/surfraw.1.en.html



## Συμπεράσματα
Κάνοντας τις παραπάνω ασκήσεις έμαθα να χρησιμοποιώ το λειτουργικό linux και τις βασικές εντολές του linux terminal, όπως η εξερεύνηση των αρχείων, εγκατάσταση εργαλείων, διάβασμα των manuals και χρήση editors, κυρίως του nano. Είναι πολύ σημαντική η δυνατότητα χρήσης συστήματος linux σε περιβάλλον windows, καθώς δεν υπάρχει πια η ανάγκη εγκατάστασης virtual box όπως το vmware και άλλα. Με το wsl2 είναι πιο εύκολο πλέον.

