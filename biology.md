# Biology — what the patch is actually reading

Amateur map. Numbers are published ranges, not my measurements. Sources at the bottom.

Two rooms at Högskolan Väst: teknik and idrott. They are separate. I carry this page between them.

## Two fluids, do not mix them up

| Fluid | Where | Glucose | Na |
| --- | --- | --- | --- |
| Blood plasma | vessels | 3.9–7.8 mmol/L | 135–145 mmol/L |
| Interstitial fluid | between cells, where a CGM filament sits | tracks blood, with a lag | close to plasma |
| Final sweat | skin surface | 0.01–0.20 mmol/L | 10–90 mmol/L |

A CGM reads interstitial glucose. A sweat patch reads what the gland dumped on the skin. Sweat glucose is about 100 times lower than blood and is a bad glucose meter. Do not call this a CGM. The CGM is only the shape: stick on skin, number on a phone.

## What the gland does

Eccrine gland = coil + duct.

1. Coil secretes primary sweat, nearly isotonic with plasma. Na about 135–145 mmol/L, Cl about 95–110, K about 4–5.
2. Duct reabsorbs most of the Na and Cl before it reaches the skin. Final sweat is hypotonic.
3. Na enters the duct cell through ENaC. It is pumped out by Na/K-ATPase. Cl follows through CFTR.
4. Faster flow means less time to reabsorb. Saltier sweat at higher sweat rate. This is normal, not a sensor bug.
5. Aldosterone turns up the duct pumps. Heat acclimation over days makes sweat less salty. A patch that ignores the last week of heat will misread the person.
6. Broken CFTR (cystic fibrosis) means Cl is not reabsorbed. Sweat Cl stays high. That is already a medical test. It is not this product.

K in final sweat stays low, a few mmol/L. It is not the big variable. Lactate in sweat is mostly from the gland burning its own glucose, not from blood lactate. Do not use sweat lactate as an effort meter.

## Salt or sugar — they are different jobs

Vätskeersättning needs both. Not because you sweat out sugar.

What leaves in sweat: water and NaCl. Almost no glucose. Replacing the loss is water plus salt.

Why the drink still has sugar: in the small intestine, SGLT1 carries one glucose with sodium across the gut wall. Water follows. Salt alone is a weaker pull. Sugar alone does not run that couple. That is the WHO reason for oral rehydration solution, since the reduced-osmolarity formula (2004): Na 75, glucose 75, K 20, citrate 10 mmol/L, about 245 mOsm/L.

So:

- Salt replaces the ion that left the skin.
- Sugar is the carrier in the gut, and in sport it is also fuel.
- A sports drink is a third recipe: more sugar, less sodium, made to keep blood glucose and spare glycogen, not to match sweat.

A patch that reports sweat Na does not tell you the glucose dose. Glucose dose comes from the gut job or the fuel job, not from the skin.

## What a number on the patch can mean

Useful: local sweat Na, and only if you also know local sweat rate. Loss rate is concentration times flow. A salty drop at a trickle can be less salt lost than a dilute stream.

Not useful, per the physiology reviews:

- Sweat Na is not hydration status.
- Sweat Na is not whole-body Na loss. Forehead, back, and forearm can differ several-fold.
- One patch site is one site.

The feedback loop that survives this: patch gives Na and a rate, scale gives body-mass change, human picks water plus salt. Sugar is chosen for the gut or the fuel, not by the patch.

## What to hand each room

Idrott: questions 1–3 in `questions.md`. Salt versus sugar, and whether sweat Na should change the bottle.

Teknik: questions 4–7. Rest versus exercise, paper conductivity versus a sodium electrode, what fails on skin.

I connect the answers. Neither room has to own the product.

## Sources

- Baker LB. Physiology of sweat gland function. Temperature. 2019. PMC6773238.
- Baker LB. Sweating rate and sweat sodium concentration in athletes. Sports Med. 2017.
- WHO/UNICEF reduced-osmolarity ORS: NaCl 2.6 g, glucose anhydrous 13.5 g, KCl 1.5 g, trisodium citrate dihydrate 2.9 g, per 1 L.
- SGLT1 as the gut couple behind oral rehydration: Wright et al., the Na-glucose cotransporter literature.
