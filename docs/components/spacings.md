# Component: Spacings

Question| Answer
--------|--------
What?   | For setting **margins** and **paddings**.
When?   | In sections where the spacing should be equal with each other.
Why?    | If you hardcode the spacings and then decide to change a few pixels after a while, perhaps you will have to do it everywhere for consistency. This component gives you a list of predefined spacing sizes, which you can use and change to your own likings.

## Usage
Every available size is bound to a "level".
You should think in terms of levels.

The levels are defined in `/src/scss/settings/_spacings.scss`. These are the default values:

level | pixels
------|------
0   | 0
1   | 4px
2   | 8px
3   | 16px
4   | 24px
5   | 32px
6   | 48px
7   | 64px
8   | 96px
9   | 128px
10  | 256px

### Paddings
#### No padding
```html
<div class="no-padding">
    This div shouldn't have any padding anyway, but now you are sure!
</div>

<div class="padding-level-0">
    This div shouldn't have any padding anyway, but now you are sure!
</div>
```

#### All padding
```html
<div class="padding-level-3">
    All sides have padding, right?
</div>
```

#### Top/bottom padding
```html
<div class="padding-top-bottom-level-3">
    Only the top and the bottom have a padding.
</div>
```

### Margins
#### No margin
```html
<div class="no-margin">
    This div shouldn't have any margin anyway, but now you are sure!
</div>
```

#### Top margin
```html
<div class="margin-top-level-5">
    Only the top has a margin.
</div>
```

#### Bottom margin
```html
<div class="margin-bottom-level-5">
    Only the bottom has a margin.
</div>
```

#### Left margin
```html
<div class="margin-left-level-3">
    Only the left has a margin.
</div>
```

#### Right margin
```html
<div class="margin-right-level-3">
    Only the right has a margin.
</div>
```

### Combined!
```html
<div class="padding-top-bottom-level-3 margin-right-level-2">
    A top and bottom padding of 16px, and a right margin of 8px.

    <small class="margin-top-level-3">
        Unless you changed the settings of course.
    </small>
</div>
```
