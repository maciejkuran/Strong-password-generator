# Super strong password generator –npm

Get a strong, unique, and secure password immediately.

# Installation

This library can be imported as Node.js modules or as ES modules.
`npm i super-strong-password-generator --save`
`npm i super-strong-password-generator-es --save`

\*To save as `devDependencies` use `--save-dev`

##### Node.js modules

```
Const pw = require('super-strong-password-generator');
//then just call the function
pw.caseSensitive_numbs_PW(15)
```

```
//Using @Parcel bundler
import { caseSensitive_numbs_PW) from 'super-strong-password-generator'
//then just call the function
caseSensitive_numbs_PW(15)
```

##### ES modules

```
import {caseSensitive_numbs_PW} from './node_modules/super-strong-password-generator-es/pw-generator.js';
//then just call the function
caseSensitive_numbs_PW(15)
```

## Options

The function takes one argument – the length of the password.
There are multiple options for password generation.

- `lowercase_PW` - generates lowercase random letters
- `caseSensitive_PW` - generates case sensitive random letters
- `caseSensitive_numbs_PW` - generates case sensitive letters + numbers
- `caseSensitive_SpecialCharacters_PW` - generates case sensitive letters + special characters
- `caseSensitive_Numbs_SpecialCharacters_PW` - generates case sensitive letters + numbers + special characters (recommended option due security reasons)

## Issues

Report any inconveniences or bring suggestions for improvement. Thank you in advance.
