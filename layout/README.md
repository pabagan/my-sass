# Grid

## Width grid (same syntax for using flex, just load proper version at `styles.scss`).
12 column width grid with `Col__[xs,sm,md,lg]--[1-12]`.

```html
<div class="Row">
  <div class="Container">
    <p>Hi there human!</p>
  </div>
  <div class="Row__xs--12 Row__lg--6">
    <h3>Grid width content</h3>
  </div>
  <div class="Row__xs--12 Row__lg--6">
    <h3>Grid width content</h3>
  </div>
  <div class="Row__xs--12 Row__lg--6">
    <h3>Grid width content</h3>
  </div>
  <div class="Row__xs--12 Row__lg--6">
    <h3>Grid width content</h3>
  </div>
</div>
```

## Height grid
12 column height grid with `Row__[xs,sm,md,lg]--[1-12]`.

```html
<div class="Row">
  <div class="Container">
    <p>Hi there human!</p>
  </div>
  <div class="Row__xs--12 Row__lg--6">
    <h3>Grid height content</h3>
  </div>
  <div class="Row__xs--12 Row__lg--6">
    <h3>Grid height content</h3>
  </div>
  <div class="Row__xs--12 Row__lg--6">
    <h3>Grid height content</h3>
  </div>
  <div class="Row__xs--12 Row__lg--6">
    <h3>Grid height content</h3>
  </div>
</div>
```

## Flex
`TODO: test Flex layout and complete here...`
### Alignment

### 3 columns layout

## Spacing (Margins & Paddings);

### Margins

* Margins: `m[t,r,b,l]-[xs,sm,md,lg]`.
* Lateral/Vertical margins: `m[v,l]-[xs,sm,md,lg]`.
* Reset margins: `m-0`.
* Reset margin by side: `m-[t,r,b,l]-0`.

```html
<img class="c-img cm-0" src="http://placehold.it/960x960" />
```


```html
<div class="row">
  <ul class="c-l-block">
    <li><img class="mb-md" src="assets/img/logo-acc.png" /></li>
    <li><img class="mb-md" src="assets/img/logo-acc.png" /></li>
    <li><img class="mb-md" src="assets/img/logo-acc.png" /></li>
    <li><img class="mb-md" src="assets/img/logo-acc.png" /></li>
  </ul>
</div>
```

### Paddings

## Using %

* Padding: `p-[xs,sm,md,lg]`.
* Per side padding: `p[t,r,b,l]-[xs,sm,md,lg]`.
* Vertical padding: `pv-[xs,sm,md,lg]`.
* Lateral padding: `pl-[xs,sm,md,lg]`.

```html
<div class="c-p-md">
  Hi with md padding
</div>
```

## Using rem

* Vertical padding: `c-p-rem-[xs,sm,md,lg]`.
* Lateral padding: `c-p-rem-[xs,sm,md,lg]-lat`.
* Single side padding: `c-p-rem-[xs,sm,md,lg]-[top,right,bottom,left]`.

```html
<div class="c-p-rem-md">
  Hi with md padding
</div>
```

## Reset paddings

* Reset padding: `c-p-0`.
* Reset padding by side: `c-p-[vert,lat]-0`.