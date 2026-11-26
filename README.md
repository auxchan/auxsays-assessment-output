# auxsays-assessment-output

This repository holds one machine-written data file, `provisional_assessments.yml`: the stored provisional
assessments shown on [auxsays.com](https://auxsays.com) patch pages. It contains no code.

The file is written by a scheduled job. The AUXSAYS site repository
([auxchan/auxsays.github.io](https://github.com/auxchan/auxsays.github.io)) reads it on its own schedule with no
credential, checks it with its own code, and publishes it only if every check passes. Nothing here can write to the
site repository.
