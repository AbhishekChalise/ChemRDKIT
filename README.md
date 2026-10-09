
- `:` = lone pair (concentrated cloud of negative charge)
- `-----` = the electrostatic attraction

### MW — Molecular Weight (< 500)

The molecule should be light enough to travel and 
cross membranes.

### LogP — Lipophilicity / Greasiness (≤ 5)

LogP measures how a drug distributes between water 
and octanol (a greasy alcohol used to mimic body fat).

- LogP = -2 → highly water-soluble, hates oil
- LogP = +3 → dissolves well in oil

Lipinski set ≤ 5 to balance: dissolve in blood (water) 
BUT still cross fatty membranes. Too fat-loving = 
won't dissolve in blood. Too water-loving = won't 
cross membranes.

---

## 💡 Key Insight: Why Isn't Sugar a Drug?

Sugar passes EVERY Lipinski rule — yet it's not medicine.

**Lipinski is a FILTER, not a judge.** It only checks 
if a molecule is SHAPE-compatible with being a pill 
(size, oiliness, H-bond hands). Being a drug ALSO 
requires binding a disease target and treating 
something. Sugar binds nothing disease-relevant.

**Filters let it in — function makes it medicine.**

### 🧬 Fun Facts I Discovered

- **Glycolysis:** Proteins take sugar molecules and 
  break them down — releasing energy the body uses!
- **Glycosylation:** Proteins use sugar chains as 
  ID cards, so the immune system won't attack them.

---

## ⚙️ How It Works

1. Parse SMILES string → molecule object (`Chem.MolFromSmiles`)
2. Calculate 4 descriptors: MolWt, MolLogP, NumHDonors, NumHAcceptors
3. Count Lipinski violations → verdict: PASS / BORDERLINE / FAIL

---

## 📊 Sample Output
