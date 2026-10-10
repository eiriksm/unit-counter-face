# unit-counter-face
A [Second Movement](https://github.com/joeycastillo/second-movement) watch face that counts alcohol units and estimates blood alcohol content, using [bac.c](https://github.com/eiriksm/bac.c).

## Installation

Install with composer, alongside `eiriksm/bac.c`:

```
composer require eiriksm/unit-counter-face:dev-main
```

The face depends on the Second Movement firmware headers (`movement.h`, `watch.h` and friends), so it only builds as part of the firmware.
