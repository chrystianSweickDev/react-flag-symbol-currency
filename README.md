# react-flag-symbol-currency

Country flag and currency symbol by currency code (iso 4217)

## Installation

Use the npm package manager to install react-flag-symbol-currency.

```bash
npm i --save  react-flag-symbol-currency
```

## Usage

```javascript
import React from 'react';
import CurrencyFlag ,{CurrencySymbol, CurrencyFlagSymbol} from 'react-flag-symbol-currency'

function Home(props) {
 

    return (
        <div>
            <CurrencyFlag currency='USD' width='40px' /> //accept img properties 
            <CurrencySymbol currency='USD' />
            <CurrencyFlagSymbol currency='USD'/>
        </div>
    );
}


```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## License
[MIT](https://choosealicense.com/licenses/mit/)
