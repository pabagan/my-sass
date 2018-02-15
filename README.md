# Sass

The [sass](http://sass-lang.com/) files are ordered using [SMACSS](https://smacss.com/) principles. Here is a self [summary for SMACSS](https://github.com/pabagan/Knowledgebase/tree/master/SMACSS).

Also now working on components with (http://getbem.com/)[BEM].

Here is the scaffolding of sass:
```bash
/
├── base
│   ├── _colors.scss
│   ├── _fonts.scss
│   ├── _normalize-extended.scss
│   ├── _normalize.scss
│   └── _vertical-rythm.scss
├── layout
│   ├── _flex.scss
│   ├── _grid-height.scss
│   ├── _grid-width-flex.scss
│   ├── _grid-width.scss
│   ├── _margins.scss
│   └── _paddings.scss
├── components
│   ├── _bubble-content.scss
│   ├── _footer.scss
│   ├── _masked-image.scss
│   ├── _masked-text-image-BORRAR.scss
│   └── OLD_NO_BEM # a bunch of old components in which I am working to BEM everywhere
├── states
│   ├── _alignment-children.scss
│   ├── _alignment.scss
│   ├── _display.scss
│   ├── _position.scss
│   ├── _scroll.scss
│   ├── _transition.scss
│   ├── _typo.scss
│   ├── _visibility.scss
│   └── _z-index.scss
├── inc
│   ├── functions
│   ├── mixins
│   └── vendor
├── _config.scss
├── _exploratory.scss
└── style.scss
```
