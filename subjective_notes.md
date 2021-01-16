# General Information

This file serves to publicly note some subjective thoughts which currently do not have a better place to live.


# Possible Issues for other Projects:

This section collects *observations* that I perceive as classical *issues* for a software project, i.e. things that could be improved.

## Owlready

- There should be an official issue tracker
- The code should be automatically checked by some continuous integration service
    - Potential problems waste of energy and ressources through cloud services.
    - Potential solution: configure CI such that only selected branches are tracked, like in [`.drone.yml` in yamlpyowl](https://github.com/cknoll/yamlpyowl/blob/main/.drone.yml).
- Change the extension handling in `setup.py`. Reason: The usage of `cython` in `setup.py` is [not recommended by the cython documentation](https://docs.cython.org/en/latest/src/userguide/source_files_and_compilation.html#distributing-cython-modules).
- Disable the "owlready2_optimized"-warning in `driver.py`. The user should be warned during installation but not on every use of the library. Also the doc says: "its use is entirely optional", thus a warning every time seems inappropriate.
- Change the representation of `owlready2.Thing` and its subclasses. Currently this reads like `repr(owl2.Thing)` → `<<property object at 0x7fe8a3417040> 'Thing'>`. However "object property" IMHO has a different meaning in the context of OWL, see e.g. [owl2-primer](https://www.w3.org/TR/owl2-primer/).
- Check if newer versions of Reasoners are available. At least Pellet seems to be outdated.
- Call JAVA-Reasoners directly instead of using `subprocess`. This might be relevant: <https://www.py4j.org/index.html>
- Update docs <https://owlready2.readthedocs.io/> to current version.
    - Ideally, docs should be built automatically when a new version is released.
    - Also, docs should be available for past versions too.
