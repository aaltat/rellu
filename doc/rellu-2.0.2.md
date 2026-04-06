# Rellu 2.0.2


Rellu provides utilities to ease creating releases.
Rellu 2.0.2 is a new release with invoke 3.0 support.

All issues targeted for Rellu v2.0.2 can be found from the
[issue tracker](https://github.com/robotframework/rellu/issues?q=milestone%3Av2.0.2).

If you have `pip` installed, run:

```bash
pip install --upgrade rellu
```

to install the latest available release or use

```bash
pip install rellu==2.0.2
```

to install exactly this version. Alternatively you can download the source
distribution from [PyPI](https://pypi.python.org/pypi/rellu) and install it manually.

Rellu 2.0.2 was released on Monday April 6, 2026.


## Most important enhancements

**EXPLAIN** or remove these.

### invoke 3 support ([#35](https://github.com/robotframework/rellu/issues/35))
Support invoke 3, `from invoke import __version_info__`  import was removed,
so remove the invoke version check and trust on [requirements.txt](../requirements.txt)
definition.

## Full list of fixes and enhancements

| ID | Type | Priority | Summary |
|---|---|---|---|
| [#35](https://github.com/robotframework/rellu/issues/35) | bug | critical | invoke 3 support |

Altogether 1 issue. View on the [issue tracker](https://github.com/robotframework/rellu/issues?q=milestone%3Av2.0.2).
