# Airship TSLint React Config

The [Airship](https://teamarship.com) TSLint config file used for React projects. This package includes the [@airship/tslint-react-a11y](https://www.npmjs.com/package/@airship/tslint-react-a11y) package as well.

## Installation

We assume you have and use Prettier for code formatting.

```bash
yarn add -D @airship/tslint-react-config
```

If you do not have [TSLint]() or [TypeScript]() installed (globally or in your project) you will need to install those as well.

```bash
yarn add -D tslint typescript
```

## Usage

In `tslint.json`:

```javascript
{
  "extends": [ "@airship/tslint-react-config" ],
  "rules": {
    // override @airsihp/tslint-react-config rules here
    "react-a11y-lang": false
  }
}
```

## Contributing

Bug reports and pull requests are welcome on GitHub at [https://github.com/teamairship/tslint-react-config](https://github.com/teamairship/tslint-react-config). This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the Contributor Covenant code of conduct.

## License

This package is available as open source under the terms of the [MIT License](https://github.com/teamairship/tslint-react-config/blob/master/LICENSE).
