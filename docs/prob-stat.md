# Θεωρία Πιθανοτήτων και Στατιστική

## Σεπτ. 2022 Ομάδα Β

### Θέμα 2ο

**Λύση**

(α) 
$$ P(\bar{B}\_{\text{day}}) = 1 - P(B) = 1 - 0.01 = 0.99 $$
$$ P(\bar{B}\_{\text{month}}) = 0.99^{30} \approx 0.7397 $$
$$ P(B\_{\text{month}}) = 1 - P(\bar{B}\_{\text{month}}) = 1 - 0.7397 = 0.2603 $$

β)
$$ P(X = 3) = (1 - p)^x p = (1 - 0.26)^3 \cdot 0.26 = 0.1053 $$

γ)
$$ P(\bar{B} \cup B\_{\text{minimum}}) = 
(1 - 0.26)^3 \cdot 0.26 \cdot (1 - 0.26)^2 = 0.015 $$

δ)
$$ P(X = k) = \binom{n}{k} p^k (1 - p)^{n-k} $$
$$
P(X = 2) = \binom{10}{2} \cdot 0.26^2 \cdot (1 - 0.26)^8
= 45 \cdot \frac{169}{2500} \cdot 0.08791 \approx 0.2735
$$

## Σεπτ. 2022, Ομάδα Α

### Θέμα 1ο

Ένας ηλεκτρικός πίνακας περιέχει 25 ασφάλειες από τις οποίες οι 5 είναι
καμμένες. Αφαιρούμε τυχαία μία ασφάλεια και στη συνέχεια μια άλλη. Να
υπολογιστούν οι πιανότητες:

(α) Τουλάχιστον μία από τις δύο ασφάλειες να ήταν καμμένη.

(β) Ακριβώς μια από τις δύο ασφάλειες ήταν καμμένη.

[2 μονάδες]

### Θέμα 2ο

$$ P(x \geq 1) = 1 - P(x = 0) $$

## Ιούν. 2023, Ομάδα Α

## Σεπτ. 2023, Ομάδα Α

### Θέμα 1ο

### Θέμα 2ο

Ο χρόνος ping είναι ο χρόνος που κάνει ένα μικρό πακέτο πληροφορίας να πάει από
έναν εξυπηρετητή σε έναν άλλον και να ξαναγυρίσει. Εδώ θεωρούμε ως τυχαία
μεταβλητή $X$ το χρόνο ping που μετριέται κάθε λεπτό της ώρας, ping/min και
θεωρούμε πως ακολουθεί εκθετική κατανομή. Το δίκτυο θεωρείται υπερφορτωμένο όταν
ο χρόνος ping (για κάποιο λεπτό της ώρας) ξεπεράσει τα 20ms. Γνωρίζουμε πως ο
χρόνος ping σε ένα (οποιοδήποτε) λεπτό της ώρας ξεπερνά τα 10ms με πιθανότητα
0.2, δηλαδή $P(X > 10) = 0.20$.

(α) Ποια είναι η πιθανότητα υπερφόρτωσης του δικτύου σε ένα (οποιοδήποτε) λεπτό
της ώρας (σε ακρίβεια δευτέρου δεκαδικού);

(β) Ποια είναι η περίοδος εμφάνισης της υπερφόρτωσης του δικτύου, δηλαδή ο
αναμενόμενος αριθμός λεπτών της ώρας μεταξύ δύο διαδοχικών υπερφορτώσεων;

(γ) Αν παρατηρήσουμε από τώρα τον χρόνο ping ανά λεπτό της ώρας, να υπολογίσετε
την πιθανότητα ότι η τρίτη υπερφόρτωση θα συμβεί σε δέκα ακριβώς λεπτά;

[2 μονάδες]
