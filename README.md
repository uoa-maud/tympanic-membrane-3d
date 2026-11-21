# Tympanic membrane 3D

Interactive 3D model of the ear canal, tympanic membrane and middle ear for teaching in the University of Auckland Master of Audiology (MAud) programme.

**Live site:** https://uoa-maud.github.io/tympanic-membrane-3d/

## What it shows

- **Tympanic membrane:** pars tensa and pars flaccida, malleolar folds, lateral process, handle of malleus, umbo, cone of light, fibrocartilaginous annulus, notch of Rivinus. You can colour the quadrants and pars flaccida, and pull apart the three layers (epidermis, lamina propria with radial and circular fibres, mucosa).
- **Ear canal:** cartilaginous part (with hairs and wax), bony part, isthmus, anterior recess.
- **Middle ear:** mucosa-lined cavity with vessels, promontory, oval and round windows, jugular dome, aditus, Eustachian tube; malleus, incus and stapes, ligaments, chorda tympani, facial nerve, tensor tympani and stapedius.
- **Ossicle landmarks (optional):** switch on “Ossicle landmarks” to label the head, neck, anterior and lateral processes and handle of the malleus; the body, short, long and lenticular processes of the incus; the head, crura and footplate of the stapes; the tensor tympani and stapedius tendons, cochleariform process, pyramidal eminence and the superior malleal and posterior incudal ligaments. These smaller labels hide when they would overlap another label and come back as you zoom in.
- **Views:** overview (cut away, including the lateral attic wall so the malleus head and incus body show), otoscope (clock face, anterior/posterior markers), and looking at the drum from the middle ear. You can switch between right and left ears.
- **Conditions:**
  - small central, subtotal, marginal posterosuperior and attic perforations, each with an approximate % of the pars tensa missing
  - generalised retraction
  - posterosuperior retraction pocket graded by Sadé (I–IV)
  - attic retraction pocket graded by Tos (I–IV, including scutum erosion)
  - acute otitis media (bulging, red drum with pus filling the middle ear) and otitis media with effusion (amber fluid with a fluid level and air bubbles)
  - attic cholesteatoma (keratin sac in the attic, scutum erosion) and congenital cholesteatoma (white mass behind an intact drum)
  - tympanosclerosis, grommet (ventilation tube), otosclerosis with Schwartze’s sign, glomus tympanicum and glomus jugulare (pulsating, “rising sun”)

Tap any structure for a short teaching note with clinical and audiology points.

## Notes

- A single static `index.html` using three.js 0.160 from jsDelivr. No build step.
- The geometry is a hand-built approximation from standard anatomical descriptions, not a scan. Dimensions are approximately to scale in millimetres. The drum layers are drawn far thicker than they really are (about 0.05–0.1 mm) so they can be seen.
