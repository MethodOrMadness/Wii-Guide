---
title: "cIOS (προσαρμοσμένο IOS)"
---

{% include toc title="Table of Contents" %}

Αυτός ο οδηγός θα σας δείξει πως να εγκαταστήσετε τα cIOS (προσαρμοσμένα IOS). Αυτό απαιτείται αν θέλετε να φορτώνετε παιχνίδια με ένα USB Loader. Κάποια προγράμματα Homebrew ίσως λειτουργούν καλύτερα αν έχετε cIOS.

![d2x cIOS Installer](/images/cios/cIOS.png)

Αν έχετε Wii mini, αντ' αυτού εγκαταστήστε [αυτό το cIOS](cios-mini). Η προσπάθεια εγκατάστασης οποιουδήποτε άλλου cIOS σε ένα Wii mini δεν θα λειτουργήσει.
{: .notice--info}

#### Τι χρειάζεστε

* Ένα Wii με σύνδεση στο διαδίκτυο
* Μία κάρτα SD ή μέσο αποθήκευσης USB
* [Το d2x cIOS Installer](/assets/files/d2x-cIOS-Installer-Wii.zip)

Ensure that if you are using an SD card, the lock switch is in the unlocked position, otherwise you will not be able to select the correct options in the installer
{: .notice--warning}

#### Οδηγίες

##### Μέρος I - Λήψη

1. Εξάγετε το d2x cIOS Installer και τοποθετήστε το στον φάκελο `apps` στο αποθηκευτικό σας μέσο.
1. Εισάγετε το αποθηκευτικό σας μέσο στο Wii και εκκινήστε το d2x cIOS Installer από το Κανάλι Homebrew.

##### Μέρος II - Εγκατάσταση

1. Πατήστε continue, και θέστε τις επιλογές στα παρακάτω:
```
Select cIOS: v10 beta52 d2x-v10-beta52
Select cIOS base: 57
Select cIOS slot: 249
Select cIOS version: 65535
```
![Install cIOS 249](/images/cios/Install249.png)
1. Μόλις τα ορίσετε σωστά, πατήστε δύο φορές Α για εγκατάσταση.
1. Όταν ολοκληρωθεί η εγκατάσταση, πατήστε Α για να επιστρέψετε και θέστε τις επιλογές στα παρακάτω:
```
Select cIOS: v10 beta52 d2x-v10-beta52
Select cIOS base: 56
Select cIOS slot: 250
Select cIOS version: 65535
```
![Install cIOS 250](/images/cios/Install250.png)
1. Μόλις τα ορίσετε σωστά, πατήστε δύο φορές Α για εγκατάσταση.
1. When done installing, press A to return, and set the options to the following: ![Install cIOS 251](/images/cios/Install251.png)
```
Select cIOS: v10 beta52 d2x-v10-beta52
Select cIOS base: 38
Select cIOS slot: 251
Select cIOS version: 65535
```
1. Όταν τελιώσετε, πατήστε ξανά A δυο φορές και βγείτε όταν τελιώσετε.

Although the majority of games should work straight away, some may require using a specific cIOS to function, or to utilize certain features within the game. To change the cIOS used for a specific game, follow these instructions:
{: .notice--warning}

<button class="tablinks btn btn--large btn--primary" id="defaultOpen" onclick="openTab(event, 'usbloadergx')">USB Loader GX</button>
<button class="tablinks btn btn--large btn--info" onclick="openTab(event, 'wiiflow')">WiiFlow</button>

<div id="usbloadergx" class="blanktabcontent">
  <p spaces-before="0">
    !!crwdP_23_Pdwrc!!Select the game that isn't working. !!crwdP_24_Pdwrc!!Click Settings. !!crwdP_25_Pdwrc!!Select <code>Game Load</code>. !!crwdP_26_Pdwrc!!Scroll down to <code>Game IOS</code>. !!crwdP_27_Pdwrc!!Enter the IOS slot to use.
  </p>
  
  <ul>
    <li>
      Try using 250 or 251, if 249 doesn't work. !!crwdP_28_Pdwrc!!Press ok and try to load the game
    </li>
  </ul>
</div>

<div id="wiiflow" class="blanktabcontent">
  <p spaces-before="0">
    !!crwdP_29_Pdwrc!!Select the game that isn't working. !!crwdP_30_Pdwrc!!Click the gear icon. !!crwdP_31_Pdwrc!!Go to cIOS and use the arrows to select the IOS slot to use.
  </p>
  
  <ul>
    <li>
      Try using 250 or 251, if 249 doesn't work. !!crwdP_32_Pdwrc!!Press Save and try to load the game.
    </li>
  </ul>
</div>
##### Επιλογές μετά την ολοκλήρωση

[Continue to the Homebrew Browser](hbb)<br> The Homebrew Browser is a good place to get homebrew on your Wii. This is optional to install.
{: .notice--info}

[Συνεχίστε στην περιήγηση ιστοσελίδας](site-navigation)<br> Έχουμε πολλούς άλλους οδηγούς που μπορεί να σας αρέσουν.
{: .notice--info}

Τώρα μπορείτε να χρησιμοποιήσετε προγράμματα όπως το[USB Loader GX](usbloadergx)και[το WiiFlow](wiiflow).
{: .notice--info}

<script>
    let tabcontent = document.getElementsByClassName("blanktabcontent");
    let tablinks = document.getElementsByClassName("tablinks");!!crwd_CB_10_BC_dwrc!!</script>

