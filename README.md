# Master Theorem Via Sage Math

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Kapral67/MasterMethod.Sage/HEAD?urlpath=voila%2Frender%2Findex.ipynb)

- Launches in Browser with [Binder](https://mybinder.org)
- Built using [sage](https://www.sagemath.org/)
- Fully Interactive (Launch Binder to See!)
- [Source Code](https://github.com/Kapral67/MasterMethod.Sage/blob/master/index.ipynb)
- For non-interactive examples, see the [static folder](https://github.com/Kapral67/MasterMethod.Sage/tree/master/static)

### Known Issues

- If we let C be some constant, `expr` != C * factorial(n)
- `expr` also cannot be a term containing factorial(n), it may only be factorial(n)
  - E.g.&emsp;`expr` != factorial(n)/n&emsp;`expr` = factorial(n)

