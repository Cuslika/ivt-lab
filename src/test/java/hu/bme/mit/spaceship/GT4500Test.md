## GT4500 fireTorpedo() tesztek:

# 1. Teszt

FiringMode.ALL paraméterrel futtatva úgy, hogy egyik TorpedoStore sincs töltve.

Mivel egyik TorpedoStore sincs töltve, így false értéket várunk visszatérési értékként.

# 2. Teszt

FiringMode.ALL paraméterrel futtatva úgy, hogy csak az elsődleges TorpedoStore van töltve.

Mivel csak az egyik TorpedoStore van töltve, így false értéket várunk visszatérési értékként.

# 3. Teszt

FiringMode.SINGLE paraméterrel futtatva úgy, hogy csak a másodlagos TorpedoStore van töltve.

Mivel csak amásodlagos TorpedoStore vna töltve és a programban a _wasPrimaryFiredLast_ értéke alapértelmezetten false így false értéket várunk.

# 4. Teszt

FiringMode.SINGLE paraméterrel futtatva úgy, hogy egyik TorpedoStore sincs töltve.

Mivel egyik TorpedoStore sincs töltve, így false értéket várunk visszatérési értékként.

# 5. Teszt

FiringMode.SINGLE paraméterrel futtatva úgy, hogy csak az elsődleges TorpedoStore van töltve.

Mivel legalább az egyik TorpedoStore töltve van, így true értéket várunk visszatérési értéknek.