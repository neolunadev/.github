# neoluna brand

The studio mark: a new moon on a black tile, in flat black and white. These files are the single
copy every neolunadev README links to, so a change here reaches every repo.

| File | Use |
| :- | :- |
| `neoluna-mark.svg` | The square mark: favicons, avatars, small placements |
| `neoluna-lockup-on-dark.svg` | Mark and wordmark for dark backgrounds |
| `neoluna-lockup-on-light.svg` | Mark and wordmark for light backgrounds |

## In a README

GitHub picks the lockup that matches the reader's theme:

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/neolunadev/.github/main/brand/neoluna-lockup-on-dark.svg">
  <img alt="neoluna" src="https://raw.githubusercontent.com/neolunadev/.github/main/brand/neoluna-lockup-on-light.svg" height="48">
</picture>
```

Use the files as they are: no recolouring, gradients or effects.
