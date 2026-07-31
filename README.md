# Oscilator-AAT

Διαδραστική εφαρμογή για την Απλή Αρμονική Ταλάντωση:

- ταλαντωτής `(m, k)`
- άξονας `0, ±A`
- ομαλή κυκλική κίνηση
- προβολή
- γράφημα `x(t)` με ακέραιες περιόδους
- αρχική φάση `φ₀`
- ορισμός νέας αρχής χρόνου με «Τώρα → t=0»

## Εκτέλεση

Ανοίξτε το `index.html` ή δημοσιεύστε τον φάκελο ως στατικό site στο Netlify.

## Καταστάσεις URL για BookWriter

- `?state=spring&play=1`
- `?state=spring_axis&play=1`
- `?state=spring_circle&play=1`
- `?state=spring_projection&play=1`
- `?state=spring_graph&play=1`
- `?state=spring_phase&play=1&phi=35`
- `?preset=body_axis&showPosition=1&showClock=1&play=0`
- `?preset=body_axis&showPosition=1&showVelocity=1&showClock=1&play=0`
- `?preset=body_axis&showPosition=1&showVelocity=1&showAcceleration=1&showClock=1&play=0`

Παράμετροι:

- `play=0` για παγωμένη αρχική κατάσταση
- `phi=<μοίρες>` για αρχική φάση
- `preset=body_axis` για λιτή οριζόντια ΑΑΤ σώματος χωρίς ελατήριο
- `showPosition=1|0` εμφάνιση διανύσματος θέσης
- `showVelocity=1|0` εμφάνιση διανύσματος ταχύτητας
- `showAcceleration=1|0` εμφάνιση διανύσματος επιτάχυνσης
- `showClock=1|0` εμφάνιση χρονομέτρου
- `showForce=1|0` μελλοντική/προαιρετική εμφάνιση συνισταμένης δύναμης
- `showEnergy=1|0` εμφάνιση ενεργειακών μπαρών
- `controlsMode=guided` για περιορισμένα χειριστήρια
- `allowedControls=togglePosition,toggleVelocity,toggleAcceleration,toggleEnergy` για τα κουμπιά που επιτρέπονται
- `t=<δευτερόλεπτα>` αρχική χρονική στιγμή

© antarxo 2026
