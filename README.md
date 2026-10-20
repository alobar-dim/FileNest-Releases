# FileNest για Windows / FileNest for Windows

[![Latest release](https://img.shields.io/github/v/release/alobar-dim/FileNest-Releases?label=Latest%20release)](https://github.com/alobar-dim/FileNest-Releases/releases/latest)

[Τελευταία έκδοση / Latest release](https://github.com/alobar-dim/FileNest-Releases/releases/latest) · [Οδηγός χρήσης / User guide](https://filenest-guide.alowind.chatgpt.site)

## Ελληνικά

Εδώ διατίθενται οι εγκαταστάτες MSI, οι υπογραφές ενημέρωσης και τα manifests του FileNest. Ο πηγαίος κώδικας παραμένει ιδιωτικός. Τα αυτόματα **Source code ZIP/TAR** του GitHub περιέχουν μόνο αυτό το αποθετήριο διανομής.

Για εγκατάσταση, άνοιξε την [τελευταία δημοσιευμένη έκδοση](https://github.com/alobar-dim/FileNest-Releases/releases/latest) και διάλεξε από τα **Assets**:

- **Ελληνικός εγκαταστάτης:** το αρχείο που τελειώνει σε `_x64_el-GR.msi`.
- **Αγγλικός εγκαταστάτης:** το αρχείο που τελειώνει σε `_x64_en-US.msi`.

Τα αρχεία `.sig` και `.json` χρησιμοποιούνται για την επαλήθευση και την αυτόματη ενημέρωση· δεν είναι εγκαταστάτες. Η γλώσσα περιβάλλοντος και η γλώσσα φακέλων επιλέγονται χωριστά μέσα στην εφαρμογή.

Για ήδη εγκατεστημένο FileNest: **Ενημερώσεις → Έλεγχος ενημερώσεων → Ενημέρωση και επανεκκίνηση**. Ο καθημερινός έλεγχος και η λήψη γίνονται στο παρασκήνιο. Η εγκατάσταση περιμένει να ολοκληρωθούν οι εργασίες αρχείων και διατηρεί ρυθμίσεις και ιστορικό. Δεν απαιτείται λογαριασμός GitHub.

Η τελευταία έκδοση και ο δίαυλος αυτόματων ενημερώσεων χρησιμοποιούν την ίδια δημοσιευμένη έκδοση. Το [latest.json](https://github.com/alobar-dim/FileNest-Releases/releases/latest/download/latest.json) προορίζεται για την εφαρμογή. Οι σύνδεσμοι αυτής της σελίδας ακολουθούν την τελευταία έκδοση, ώστε να μη μένουν σε παλιότερο αριθμό.

Τα πακέτα διαθέτουν κρυπτογραφική υπογραφή ενημέρωσης FileNest. Το πιστοποιητικό **Windows Authenticode** εκκρεμεί ακόμη: τα Windows μπορεί να εμφανίσουν προειδοποίηση άγνωστου εκδότη ή να ζητήσουν έγκριση διαχειριστή. Η υπογραφή ενημέρωσης και το πιστοποιητικό εκδότη Windows είναι διαφορετικοί έλεγχοι. Οι αναφορές επαλήθευσης και οι τιμές SHA-256 συνοδεύουν κάθε έκδοση.

## English

This repository distributes FileNest MSI installers, update signatures and manifests. The application source code is private. GitHub's automatic **Source code ZIP/TAR** downloads contain only this distribution repository.

Open the [latest published release](https://github.com/alobar-dim/FileNest-Releases/releases/latest) and choose an installer from **Assets**:

- **Greek installer:** the file ending in `_x64_el-GR.msi`.
- **English installer:** the file ending in `_x64_en-US.msi`.

The `.sig` and `.json` files support update verification; they are not installers. Interface language and folder language can be selected independently in the app.

To upgrade an installed copy, open **Updates → Check for updates → Update and restart**. Daily checks and downloads run in the background. Installation waits for file operations to finish and preserves settings and history. No GitHub account is required.

The latest release and the automatic update channel use the same published version. The [latest.json endpoint](https://github.com/alobar-dim/FileNest-Releases/releases/latest/download/latest.json) is intended for the app. Links on this page follow the latest release rather than a fixed version.

Packages carry a cryptographic FileNest update signature. A **Windows Authenticode** certificate is still pending, so Windows may display an unknown-publisher warning or request administrator approval. Update verification and Windows publisher certification are separate checks. Verification reports and SHA-256 hashes accompany each release.
