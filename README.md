# mtg-mana-cost

[![Greenkeeper badge](https://badges.greenkeeper.io/StreamsGood/mtg-mana-cost.svg)](https://greenkeeper.io/)
[![Build Status](https://travis-ci.org/StreamsGood/mtg-mana-cost.svg?branch=master)](https://travis-ci.org/StreamsGood/mtg-mana-cost)

```sh
bower install StreamsGood/mtg-mana-cost --save
```

Wrapper on [`micku/mana-cost`](https://github.com/micku/mana-cost) for use with Web Components.

Properties
* `cost`: Mana Cost using `{1}{U}` curly bracket syntax.
* `size`: (`small`, `medium`, `large`) The physical size of the symbols.

```html
<mtg-mana-cost cost="{1}{W/U}{W/U}" size="small"></mtg-mana-cost>
```