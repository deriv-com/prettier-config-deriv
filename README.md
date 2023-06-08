# prettier-config-deriv
This package provides Deriv's `.prettierrc` as an extensible shared config.

# installation

    npm i --save-dev prettier-config-deriv

# Usage

import your config inside `.prettierrc.js` :
```
module.exports = {
    ...require('prettier-config-deriv'),
};
```