# melange-testing-library

> [Melange](https://github.com/melange-re/melange) bindings for [testing-library](https://testing-library.com/) (**[dom-testing-library](https://github.com/testing-library/dom-testing-library)** and **[react-testing-library](https://github.com/testing-library/react-testing-library)**)

Initially forked from [@wyze/bs-dom-testing-library](https://github.com/wyze/bs-dom-testing-library) and [@wyze/bs-react-testing-library](https://github.com/wyze/bs-react-testing-library).

<!-- ## Documentation

[**Read the docs**](//testing-library.com/docs/bs-react-testing-library/intro) | [Edit the docs](//github.com/alexkrolick/testing-library-docs)

## Installation

```sh
$ yarn add --dev bs-react-testing-library

# or..

$ npm install --save-dev bs-react-testing-library
```

## Usage

#### Add to `bsconfig.json`

```json
{
  "bs-dev-dependencies": [
    "bs-react-testing-library"
  ]
}
```

#### With [`bs-jest`](//github.com/glennsl/bs-jest)

```ocaml
/* Component_test.re */

open Jest;
open Expect;
open ReactTestingLibrary;

test("Component renders", () =>
  <div style=ReactDOMRe.Style.make(~color="rebeccapurple", ())>
    <h1> {ReasonReact.string("Heading")} </h1>
  </div>
  |> render
  |> container
  |> expect
  |> toMatchSnapshot
);
```

## Examples

See [`src/__tests__`](src/__tests__) for some examples.

## Development

```sh
$ git clone https://github.com/wyze/bs-react-testing-library.git
$ cd bs-react-testing-library
$ yarn # or `npm install`
```

## Build

```sh
$ yarn build
```

## Test

```sh
$ yarn test
```

## Change Log

> [Full Change Log](changelog.md)

### [v0.8.0](https://github.com/wyze/bs-react-testing-library/releases/tag/v0.8.0) (2020-10-21)

* Upgrade to latest dependencies ([@wyze](https://github.com/wyze) in [#27](https://github.com/wyze/bs-react-testing-library/pull/27))
* Add sponsor button ([@wyze](https://github.com/wyze) in [c69f028](https://github.com/wyze/bs-react-testing-library/commit/c69f028))

## License

MIT © [Neil Kistner](https://neilkistner.com)

[actions-image]: https://img.shields.io/github/workflow/status/wyze/bs-react-testing-library/CI.svg?style=flat-square
[actions-url]: https://github.com/wyze/bs-react-testing-library/actions

[npm-image]: https://img.shields.io/npm/v/bs-react-testing-library.svg?style=flat-square
[npm-url]: https://npm.im/bs-react-testing-library

[codecov-image]: https://img.shields.io/codecov/c/github/wyze/bs-react-testing-library.svg?style=flat-square
[codecov-url]: https://codecov.io/github/wyze/bs-react-testing-library -->
