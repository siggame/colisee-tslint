# siggame/colisee-tslint

The official tslint config for ACM SIG-Game's Colisee

[![Dependencies](https://img.shields.io/david/siggame/colisee-tslint.svg)](https://github.com/siggame/colisee-tslint)
[![NPM Version](https://img.shields.io/npm/@siggame/colisee-tslint.svg?style=flat-square)](https://www.npmjs.com/package/@siggame/colisee-tslint)
[![NPM Total Downloads](https://img.shields.io/npm/dt/@siggame/colisee-tslint.svg?style=flat-square)](https://www.npmjs.com/package/@siggame/colisee-tslint)

## Table Of Contents
- [Description](#description)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)
- [Contributing](#contributing)

## Description

A long description of the project.

## Getting Started
```
npm install --save-dev tslint @siggame/colisee-tslint
```

Add the following `tslint.json`
```json
{
    "extends": "@siggame/colisee-tslint/tslint.json"
}
```

Add the following to your `package.json` scripts:
```json
    "lint": "tslint --format verbose --project ./tsconfig.json",
    "lint-fix": "tslint --fix --format verbose --project ./tsconfig.json"
```

## Usage

Running the linter
```
npm run lint
```

Running the linter fixer
```
npm run lint-fix
```

## Contributors
- [Russley Shaw](https://github.com/russleyshaw)
- [user404d](https://github.com/user404d)
- [Hannah Reinbolt](https://github.com/LoneGalaxy)
- [Matthew Qualls](https://github.com/MatthewQualls)

## License

View our [LICENSE.md](https://github.com/siggame/colisee/blob/master/LICENSE.md)

## Contributing

View our [CONTRIBUTING.md](https://github.com/siggame/colisee/blob/master/CONTRIBUTING.md)