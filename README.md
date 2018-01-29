# mtg-mana-cost

Wrapper on [`micku/mana-cost`](https://github.com/micku/mana-cost) for use with Web Components.

```sh
bower install StreamsGood/mtg-mana-cost --save
```

Properties
* `cost`: Mana Cost using `{1}{U}` curly bracket syntax.
* `size`: (`small`, `medium`, `large`) The physical size of the symbols.

```html
<mtg-mana-cost cost="{1}{W/U}{W/U}" size="small"></mtg-mana-cost>
```