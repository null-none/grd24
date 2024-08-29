# grd24
A CSS grid framework using Flexbox.


### Install

```bash
npm install grd24
```

#### Usage

```html
<div class="grid">
  <div class="cell -sm-12of24">sm-12of24</div>
  <div class="cell -sm-12of24">sm-12of24</div>
</div>
```

### grid options

| size| value |
|---|---|
| `$sm` | 576px |
| `$md` | 768px |
| `$lg` | 992px |
| `$xl` | 1200px |


### `grid` modifiers

| vertical layout | description |
|---|---|
| `-top` | Pull items to top |
| `-middle` |  Pull items to middle |
| `-bottom` |  Pull items to bottom |
| `-stretch` | Stretch items |
| `-baseline` |  Pull items to baseline |

| horizontal layout | Ddscription |
|---|---|
| `-left` | Layout items to left |
| `-center` | Layout items To center |
| `-right` | Layout items to right |
| `-between` | Add spaces between items |
| `-around` | Add spaces around items |
| `-reverse` | Add reverse column items |


### `cell` modifiers

| cell width | description |
|---|---|
| `-fill` | Set item width to left |
| `-1of12` | Set item width to 8.3% |
| `-2of12` | Set item width to 16.7% |
| `-3of12` | Set item width to 25% |
| `-4of12` | Set item width to 33% |
| `-5of12` | Set item width to 41.7% |
| `-6of12` | Set item width to 50% |
| `-7of12` | Set item width to 58.3% |
| `-8of12` | Set item width to 66.7% |
| `-9of12` | Set item width to 75% |
| `-10of12` | Set item width to 83.3% |
| `-11of12` | Set item width to 91.7% |
| `-12of12` | Set item width to 100% |
