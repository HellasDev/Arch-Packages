# Πακέτα Arch

Μια λίστα συστάσεων για πακέτα Arch Linux που θεωρώ χρήσιμα. Για γενικές οδηγίες για το πώς να εγκαταστήσετε μια νέα εγκατάσταση Arch, δείτε [τον οδηγό εγκατάστασης του wiki](https://wiki.archlinux.org/title/installation_guide).

## Χρήσιμες Εντολές

- `pacstrap [root] [pkgs...]` (Εγκατάσταση πακέτων σε νέα ρίζα)
- `pacman -S [pkgs...]` (Εγκατάσταση πακέτων)
- `pacman -Syu` (Ενημέρωση όλων)
- `pacman -Q` (Λίστα εγκατεστημένων πακέτων)
- `pacman -Ql [pkg]` (Λίστα αρχείων σε ένα πακέτο)
- `pacman -Qo [file]` (Βρείτε ποιο πακέτο κατέχει ένα αρχείο)

## Σύστημα

Πακέτα για κάθε εγκατάσταση Arch.

- [`base`](https://archlinux.org/packages/core/any/base/) (Βασικές Εργαλειοθήκες)
- [`linux`](https://archlinux.org/packages/core/x86_64/linux/) (Πυρήνας)
- [`linux-firmware`](https://archlinux.org/packages/core/any/linux-firmware/) (Φirmware)
- [`grub`](https://archlinux.org/packages/core/x86_64/grub/) (Φορτωτής Εκκίνησης)
- [`networkmanager`](https://archlinux.org/packages/extra/x86_64/networkmanager/) (Δικτύωση)

## Απαραίτητα

- [`neovim`](https://archlinux.org/packages/extra/x86_64/neovim/) (Επεξεργαστής Κειμένου)
- [`git`](https://archlinux.org/packages/extra/x86_64/git/) (Έλεγχος Εκδόσεων)
- [`tmux`](https://archlinux.org/packages/community/x86_64/tmux/) (Πολυπλεξοχρονισμός Τερματικού)
- [`htop`](https://archlinux.org/packages/extra/x86_64/htop/) (Διαχειριστής Διεργασιών)
- [`python`](https://archlinux.org/packages/core/x86_64/python/) (Γλώσσα Σεναρίων)
- [`sudo`](https://archlinux.org/packages/core/x86_64/sudo/) (Εκτέλεση ως Root)
- [`zsh`](https://archlinux.org/packages/extra/x86_64/zsh/) (Κέλυφος)
- [`curl`](https://archlinux.org/packages/core/x86_64/curl/) (Κατέβασμα URL)
- [`less`](https://archlinux.org/packages/core/x86_64/less/) (Προβολή Κειμένου)
- [`openssh`](https://archlinux.org/packages/core/x86_64/openssh/) (Πελάτης SSH)
- [`rsync`](https://archlinux.org/packages/extra/x86_64/rsync/) (Αντιγραφή Αρχείων)
- [`avahi`](https://archlinux.org/packages/extra/x86_64/avahi/) (Στοίβα mDNS/DNS-SD/Bonjour)
- [`yay` (AUR)](https://aur.archlinux.org/packages/yay) (Βοηθός AUR)
- [`reflector`](https://archlinux.org/packages/community/any/reflector/) (Ενημερωτήριο Καθρέπτη Arch)

## Εργαλεία CLI

- [`trash-cli`](https://archlinux.org/packages/community/any/trash-cli/) (Βοηθός Κάδου)
- [`tree`](https://archlinux.org/packages/extra/x86_64/tree/) (Λίστα Καταλόγου)
- [`fzf`](https://archlinux.org/packages/extra/x86_64/fzf/) (Ασαφής Εύρεση)
- [`jq`](https://archlinux.org/packages/community/x86_64/jq/) (Επεξεργαστής JSON)
- [`zip`](https://archlinux.org/packages/extra/x86_64/zip/) (Αρχειοθέτης ZIP)
- [`unzip`](https://archlinux.org/packages/extra/x86_64/unzip/) (Αποσυμπιέστε ZIP)
- [`whois`](https://archlinux.org/packages/extra/x86_64/whois/) (Πελάτης Whois)
- [`wget`](https://archlinux.org/packages/extra/x86_64/wget/) (Κατέβασμα CLI)
- [`rlwrap`](https://archlinux.org/packages/community/x86_64/rlwrap/) (Περιτύλιγμα Readline)

## Development

- [`base-devel`](https://archlinux.org/groups/x86_64/base-devel/) (Βασικά Εργαλεία Κατασκευής)
- [`visual-studio-code-bin` (AUR)](https://aur.archlinux.org/packages/visual-studio-code-bin) (Επεξεργαστής/IDE)
- [`cmake`](https://archlinux.org/packages/extra/x86_64/cmake/) (Μετα-Εργαλείο Κατασκευής)
- [`ninja`](https://archlinux.org/packages/community/x86_64/ninja/) (Σύστημα Κατασκευής)
- [`clang`](https://archlinux.org/packages/extra/x86_64/clang/) (Μεταγλωττιστής C/C++/ObjC)
- [`sqlite`](https://archlinux.org/packages/core/x86_64/sqlite/) (Ενσωματωμένη Βάση Δεδομένων)
- [`nodejs`](https://archlinux.org/packages/community/x86_64/nodejs/) (Εκτελεστικό Περιβάλλον JS)
- [`npm`](https://archlinux.org/packages/community/any/npm/) (Διαχειριστής Πακέτων Node.js)
- [`yarn`](https://archlinux.org/packages/community/any/yarn/) (Εναλλακτικό για npm)
- [`jdk-openjdk`](https://archlinux.org/packages/extra/x86_64/jdk-openjdk/) (Java)
- [`gradle`](https://archlinux.org/packages/community/any/gradle/) (Εργαλείο Κατασκευής JVM)
- [`maven`](https://archlinux.org/packages/community/any/maven/) (Εργαλείο Κατασκευής JVM)
- [`ruby`](https://archlinux.org/packages/extra/x86_64/ruby/) (Γλώσσα Σεναρίων)
- [`rustup`](https://archlinux.org/packages/community/x86_64/rustup/) (Εγκαταστάτης Εργαλείων Rust)
- [`go`](https://archlinux.org/packages/community/x86_64/go/) (Μεταγλωττιστής Go)
- [`stack`](https://archlinux.org/packages/community/x86_64/stack/) (Εργαλείο Κατασκευής Haskell)
- [`dotnet-sdk`](https://archlinux.org/packages/community/x86_64/dotnet-sdk/) (.NET Core)
- [`swi-prolog`](https://archlinux.org/packages/community/x86_64/swi-prolog/) (Περιβάλλον Prolog)
- [`valgrind`](https://archlinux.org/packages/extra/x86_64/valgrind/) (Εργαλείο Εντοπισμού Μνήμης)
- [`visualvm`](https://archlinux.org/packages/extra/x86_64/visualvm/) (Προφίλ JVM)
- [`strace`](https://archlinux.org/packages/extra/x86_64/strace/) (Εντοπιστής Syscall)
- [`patchelf`](https://archlinux.org/packages/community/x86_64/patchelf/) (Εργαλείο Επεξεργασίας ELF)
- [`sccache`](https://archlinux.org/packages/community/x86_64/sccache/) (Κοινόχρηστη Κρυφή Κατασκευής)
- [`intellij-idea-community-edition`](https://archlinux.org/packages/community/x86_64/intellij-idea-community-edition/) (IDE JVM)
- [`pycharm-community-edition`](https://archlinux.org/packages/community/x86_64/pycharm-community-edition/) (IDE Python)

## Containers

- [`podman`](https://archlinux.org/packages/community/x86_64/podman/) (Εκτελεστής εμπορευματοκιβωτίων OCI)
- [`podman-compose`](https://archlinux.org/packages/community/any/podman-compose/) (Εκτελεστής αρχείου Compose)
- [`buildah`](https://archlinux.org/packages/community/x86_64/buildah/) (Δημιουργός εμπορευματοκιβωτίων OCI)
- [`kubectl`](https://archlinux.org/packages/community/x86_64/kubectl/) (Πελάτης API Kubernetes)
- [`k9s`](https://archlinux.org/packages/community/x86_64/k9s/) (ΤUI Kubernetes)
- [`helm`](https://archlinux.org/packages/community/x86_64/helm/) (Διαχειριστής πακέτων Kubernetes)
- [`k3s-bin` (AUR)](https://aur.archlinux.org/packages/k3s-bin) (Ελαφρύς διακομιστής Kubernetes)

## Διαχείριση Συστήματος

- [`ansible`](https://archlinux.org/packages/community/any/ansible/) (Αυτοματοποίηση IT, υποδομή ως κώδικας)

## Server

- [`traefik`](https://archlinux.org/packages/community/x86_64/traefik/) (Αντίστροφος διακομιστής)
- [`nginx`](https://archlinux.org/packages/extra/x86_64/nginx/) (Διακομιστής ιστοσελίδων)
- [`samba`](https://archlinux.org/packages/extra/x86_64/samba/) (Διακομιστής SMB)
- [`postgresql`](https://archlinux.org/packages/extra/x86_64/postgresql/) (Βάση Δεδομένων)
- [`shairport-sync`](https://archlinux.org/packages/community/x86_64/shairport-sync/) (Διακομιστής AirPlay)

## Επιφάνεια Εργασίας

- [`xorg-server`](https://archlinux.org/packages/extra/x86_64/xorg-server/) (Διακομιστής Οθόνης)
- [`sddm`](https://archlinux.org/packages/extra/x86_64/sddm/) (Διαχειριστής Οθόνης)
- [`plasma`](https://archlinux.org/groups/x86_64/plasma/) (Περιβάλλον επιφάνειας εργασίας, KDE)
  - Συμβουλή: Χρησιμοποιήστε Alt-Space για γρήγορη ανοιχτή εφαρμογή στο Plasma
- [`kde-applications`](https://archlinux.org/groups/x86_64/kde-applications/) (Εφαρμογές επιφάνειας, επιλέξτε ό,τι χρειάζεστε)
- [`redshift`](https://archlinux.org/packages/community/x86_64/redshift/) (Θερμά χρώματα τη νύχτα)
- [`mesa`](https://archlinux.org/packages/extra/x86_64/mesa/) (Υλοποίηση OpenGL)
- [`barrier`](https://archlinux.org/packages/community/x86_64/barrier/) (KVM)

## Deamons

- [`earlyoom`](https://archlinux.org/packages/community/x86_64/earlyoom/) (Δαίμονας OOM)
- [`cronie`](https://archlinux.org/packages/core/x86_64/cronie/) (Δαίμονας Cron)

## Διαδίκτυο

- [`firefox`](https://archlinux.org/packages/extra/x86_64/firefox/) (Περιηγητής Web)
- [`thunderbird`](https://archlinux.org/packages/extra/x86_64/thunderbird/) (Πελάτης Ηλεκτρονικού Ταχυδρομείου)
- [`discord`](https://archlinux.org/packages/community/x86_64/discord/) (Φωνή και Κείμενο Συνομιλία)
- [`signal-desktop`](https://archlinux.org/packages/community/x86_64/signal-desktop/) (Μεσίτης)
- [`mattermost-desktop-bin` (AUR)](https://aur.archlinux.org/packages/mattermost-desktop-bin) (Συνομιλία Κειμένου)
- [`zulip-desktop-bin` (AUR)](https://aur.archlinux.org/packages/zulip-desktop-bin) (Συνομιλία Κειμένου)
- [`zoom` (AUR)](https://aur.archlinux.org/packages/zoom) (Συνδιάσκεψη Βίντεο)
- [`wireshark-qt`](https://archlinux.org/packages/community/x86_64/wireshark-qt/) (Αναλυτής Κίνησης)

## Bluetooth

- [`bluez`](https://archlinux.org/packages/extra/x86_64/bluez/) (Δαίμονες Bluetooth)

## Παραγωγικότητα

- [`okular`](https://archlinux.org/packages/extra/x86_64/okular/) (Προβολέας Εγγράφων)
- [`xournalpp`](https://archlinux.org/packages/community/x86_64/xournalpp/) (Χειρόγραφες Σημειώσεις)
- [`cups`](https://archlinux.org/packages/extra/x86_64/cups/) (Σύστημα Εκτύπωσης)
- [`cups-pdf`](https://archlinux.org/packages/extra/x86_64/cups-pdf/) (Εκτύπωση PDF)
- [`texlive-most`](https://archlinux.org/groups/x86_64/texlive-most/) (LaTeX)
- [`libreoffice-fresh`](https://archlinux.org/packages/extra/x86_64/libreoffice-fresh/) (Σουίτα Γραφείου)
- [`zotero` (AUR)](https://aur.archlinux.org/packages/zotero) (Διαχειριστής Βιβλιογραφίας)

## Γραμματοσειρές

- [`ttf-liberation`](https://archlinux.org/packages/community/any/ttf-liberation/) (Αντικατάσταση Arial/Times New Roman/Courier New)
- [`ttf-jetbrains-mono`](https://archlinux.org/packages/community/any/ttf-jetbrains-mono/) (Γραμματοσειρά για προγραμματιστές)
- [`ttf-font-awesome`](https://archlinux.org/packages/community/any/ttf-font-awesome/) (Εικονογραφική γραμματοσειρά)

## Ήχος/Βίντεο

- [`pipewire`](https://archlinux.org/packages/extra/x86_64/pipewire/) (Επεξεργαστής/Δρομολογητής ήχου)
- [`pipewire-pulse`](https://archlinux.org/packages/extra/x86_64/pipewire-pulse/) (Αντικατάσταση PulseAudio)
- [`pipewire-jack`](https://archlinux.org/packages/extra/x86_64/pipewire-jack/) (Αντικατάσταση JACK)
- [`pamixer`](https://archlinux.org/packages/community/x86_64/pamixer/) (CLI αναμείκτη)
- [`helvum`](https://archlinux.org/packages/community/x86_64/helvum/) (Πίνακας σύνδεσης PipeWire)
- [`ffmpeg`](https://archlinux.org/packages/extra/x86_64/ffmpeg/) (Μετατροπέας ήχου/βίντεο)
- [`vlc`](https://archlinux.org/packages/extra/x86_64/vlc/) (Πολυμεσικός παίκτης)
- [`mixxx`](https://archlinux.org/packages/community/x86_64/mixxx/) (Διασκεδαστικός)
- [`spotify` (AUR)](https://aur.archlinux.org/packages/spotify) (Μουσική σε ροή)
- [`audacity`](https://archlinux.org/packages/community/x86_64/audacity/) (Επεξεργαστής ήχου)
- [`ardour`](https://archlinux.org/packages/community/x86_64/ardour/) (DAW)
- [`kdenlive`](https://archlinux.org/packages/extra/x86_64/kdenlive/) (Επεξεργαστής βίντεο)
- [`obs-studio`](https://archlinux.org/packages/community/x86_64/obs-studio/) (Διαδικτυακή μετάδοση και οθόνη)

## Γραφικά

- [`gimp`](https://archlinux.org/packages/extra/x86_64/gimp/) (Επεξεργαστής εικόνας)
- [`inkscape`](https://archlinux.org/packages/extra/x86_64/inkscape/) (Επεξεργαστής διανυσμάτων)

## Παιχνίδια

- [`steam`](https://archlinux.org/packages/multilib/x86_64/steam/) (Πλατφόρμα Διανομής Παιχνιδιών)
- [`multimc-bin` (AUR)](https://aur.archlinux.org/packages/multimc-bin) (Εκκινητής Minecraft)
