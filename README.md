# seeingwhy
A meditative study in my obsession with CMYK

## birds.html

A GPU flock of cyan, magenta and yellow birds, multiply-blended so the
colours mix like ink where they overlap. The flocking model (separation,
alignment, cohesion, field of view, colour affinity, banking, a drifting
home and the pointer as predator) is documented at the top of the file.

Tune it by editing `CONFIG` in the file, or from the URL:

    birds.html?birds=64        flock is birds x birds (default 40 desktop, 32 mobile)
    birds.html?speed=0.7       time scale
    birds.html?affinity=0.6    how strongly each colour keeps to itself (0 - 0.95)
