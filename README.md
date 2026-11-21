# Tympanic membrane 3D

Interactive 3D model of the ear canal, tympanic membrane and middle ear for teaching in the University of Auckland Master of Audiology (MAud) programme.

**Live site:** https://uoa-maud.github.io/tympanic-membrane-3d/

## What it shows

- **Tympanic membrane:** pars tensa and pars flaccida, malleolar folds, lateral process, handle of malleus, umbo, cone of light, fibrocartilaginous annulus, notch of Rivinus. You can colour the quadrants and pars flaccida, and pull apart the three layers (epidermis, lamina propria with radial and circular fibres, mucosa).
- **Ear canal:** cartilaginous part (with hairs and wax), bony part, isthmus, anterior recess.
- **Middle ear:** mucosa-lined cavity with vessels, promontory, oval and round windows, jugular dome, aditus, Eustachian tube; malleus, incus and stapes, ligaments, chorda tympani, facial nerve, tensor tympani and stapedius.
- **Views:** overview (cut away), otoscope (clock face, anterior/posterior markers), and looking at the drum from the middle ear. You can switch between right and left ears.
- **Conditions:**
  - small central, subtotal, marginal posterosuperior and attic perforations, each with an approximate % of the pars tensa missing
  - generalised retraction
  - posterosuperior retraction pocket graded by Sadé (I–IV)
  - attic retraction pocket graded by Tos (I–IV, including scutum erosion)

Tap any structure for a short teaching note with clinical and audiology points.

## Notes

- A single static `index.html` using three.js 0.160 from jsDelivr. No build step.
- The geometry is a hand-built approximation from standard anatomical descriptions, not a scan. Dimensions are approximately to scale in millimetres. The drum layers are drawn far thicker than they really are (about 0.05–0.1 mm) so they can be seen.
