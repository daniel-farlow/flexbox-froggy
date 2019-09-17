# Flexbox Froggy

- **Goal:** Always move the frog(s) to the similarly colored lilypad(s).
- [Contents](#contents): Jump here to go ahead and get started by looking at your desired level. 
- [Flexbox properties and values](#flexbox-properties-and-values): Jump here to review some of the commonly used properties and values available when using the flexible box model in CSS.

- **Note:** This "README" file is really a companion to the [levels](#contents) in [flexbox froggy](http://flexboxfroggy.com/), a website dedicated to helping newcomers to the flexible box model in CSS. As loosely stated on the website:

    > Flexbox Froggy is a game where you help Froggy and friends reach their lilypads by writing CSS code using flexbox!

    Certain properties and values of flexbox have been included below that may be useful to reference throughout completing the exercises if needed. Good luck!

[](#flexbox-properties-and-values)   
## Flexbox Properties and Values

<details><summary> <code>justify-content</code></summary>

The `justify-content` property aligns flex items along the main axis (horizontal by default) and takes the following values:

- `flex-start`: Items align to the start (left by default) of the container.
- `flex-end`: Items align to the end of the container (right by default).
- `center`: Items align at the center of the container.
- `space-between`: Items display with equal spacing between them.
- `space-around`: Items display with equal spacing around them.

Note: `justify-content: flex-start` could right-align items if `flex-direction: row-reverse` has been used previously for the same flex container.

</details>

<details><summary> <code>align-items</code></summary>

The `align-items` property aligns items along the cross axis (vertical axis by default) and takes the following values:

- `flex-start`: Items align to the start of the container (top by default).
- `flex-end`: Items align to the end of the container (bottom by default).
- `center`: Items align to the center of the container (vertical center by default).
- `baseline`: Items display at the baseline of the container.
- `stretch`: Items are stretched to fit the container.

</details>

<details><summary> <code>flex-direction</code></summary>

Defines the direction of the main axis (horizontal by default) or, more simply, the direction in which items are placed in the container.

- `row`: Items are placed the same as the text direction (left to right by default).
- `row-reverse`: Items are placed opposite to the text direction (i.e., right to left).
- `column`: Items are placed top to bottom (left to right by default).
- `column-reverse`: Items are placed bottom to top.

</details>

<details><summary> <code>order</code></summary>

Specifies the order of the flex item. 

- `<integer> (..., -1, 0, 1, ...)` (0 by default)

Sometimes simply reversing the row or column order of a container is not enough. In these cases, we can apply the `order` property to individual items. By default, items have a value of 0, but we can use this property to also set it to a positive or negative integer value (..., -2, -1, 0, 1, 2, ...).

</details>

<details><summary> <code>align-self</code></summary>

Aligns an individual or specific flex item (singular) along the cross axis, overriding whatever `align-items` value may exist for this item. Hence, the `align-self` property takes all the same values (and singular effects) that `align-items` does:

- `flex-start`: Specific item aligns to the start of the container (top by default).
- `flex-end`: Specific item aligns to the end of the container (bottom by default).
- `center`: Specific item aligns to the center of the container (vertical center by default).
- `baseline`: Specific item displays at the baseline of the container.
- `stretch`: Specific item is stretched to fit the container.

</details>

<details><summary> <code>flex-wrap</code></summary>

Specifies whether flex items are forced on a single line or can be wrapped on multiple lines.

- `nowrap`: Every item is fit to a single line.
- `wrap`: Items wrap around to additional lines.
- `wrap-reverse`: Items wrap around to additional lines in reverse.

</details>

<details><summary> <code>flex-flow</code></summary>

The two properties `flex-direction` and `flex-wrap` are used so often together that the shorthand property `flex-flow` was created to combine them. This shorthand property accepts the value of one of the two properties separated by a space. For example, you can use `flex-flow: row wrap` to set rows and wrap them. Also, for the previous exercise, instead of using `flex-direction: column` and `flex-wrap: wrap` together, we could have simply used `flex-flow` by itself in the following manner: `flex-flow: column wrap`.

More concisely, we see that `flex-flow` is just a shorthand property for `flex-direction` and `flex-wrap`:

- `flex-flow: <flex-direction> <flex-wrap>`

</details>

<details><summary> <code>align-content</code></summary>

The `align-content` property can be used to set how multiple lines are spaced apart from each other (relevant when there is extra space between items along the cross-axis). This property takes the following values:

- `flex-start`: Lines are packed at the top of the container.
- `flex-end`: Lines are packed at the bottom of the container.
- `center`: Lines are packed at the vertical center of the container.
- `space-between`: Lines display with equal spacing between them.
- `space-around`: Lines display with equal spacing around them.
- `stretch`: Lines are stretched to fit the container.

Note that `align-content` determines the spacing between lines while `align-items` determines how the items as a whole are aligned within the container. When there is only one line, `align-content` has no effect.

</details>

[](#contents)
## Contents
 
- [Level 1](#level-1)    
- [Level 2](#level-2)    
- [Level 3](#level-3)    
- [Level 4](#level-4)    
- [Level 5](#level-5)    
- [Level 6](#level-6)    
- [Level 7](#level-7)    
- [Level 8](#level-8)    
- [Level 9](#level-9)    
- [Level 10](#level-10)    
- [Level 11](#level-11)    
- [Level 12](#level-12)    
- [Level 13](#level-13)    
- [Level 14](#level-14)    
- [Level 15](#level-15)    
- [Level 16](#level-16)    
- [Level 17](#level-17)    
- [Level 18](#level-18)    
- [Level 19](#level-19)    
- [Level 20](#level-20)    
- [Level 21](#level-21)    
- [Level 22](#level-22)    
- [Level 23](#level-23)    
- [Level 24](#level-24)

## Level 1

<details><summary> Click here for more explicit directions (i.e., hints)</summary>

The following are possible approaches:
- `justify-content: flex-end`: This will move the frog to the end of the container to the right. 
- `flex-direction: row-reverse`: This will change the default starting position of the row from left to right.

</details>

<img src="https://user-images.githubusercontent.com/52146855/64952375-2cab8e00-d84e-11e9-9580-d3710b97ddf9.png" width="300" height="300" />

(See the [flexbox properties and values](#flexbox-properties-and-values) for reference.)

```css
/* given code */
#pond {
    display: flex;
                                            /* your work here */
    /* only use blank line above */
}
```

<details><summary> Solution</summary>

```css
#pond {
    display: flex;              /* image 1 */
    justify-content: flex-end;  /* image 2 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64952375-2cab8e00-d84e-11e9-9580-d3710b97ddf9.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64953831-e821f180-d851-11e9-8209-1b91030c55ba.png" width="150" height="150" />

</details>

## Level 2

<details><summary> Click here for more explicit directions (i.e., hints)</summary>

Recall that `justify-content` will center content along the main axis which is horizontal by default.

</details>

<img src="https://user-images.githubusercontent.com/52146855/64954712-6e3f3780-d854-11e9-88a7-74e0d5ca8a7d.png" width="300" height="300" />

(See the [flexbox properties and values](#flexbox-properties-and-values) for reference.)

```css
/* given code */
#pond {
    display: flex;
                                            /* your work here */
    /* only use blank line above */
}
```

<details><summary> Solution</summary>

```css
#pond {
    display: flex;            /* image 1 */
    justify-content: center;  /* image 2 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64954712-6e3f3780-d854-11e9-88a7-74e0d5ca8a7d.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64954745-8020da80-d854-11e9-8090-97d06abc3976.png" width="150" height="150" />

</details>

## Level 3

<details><summary> Click here for more explicit directions (i.e., hints)</summary>

Recall that `justify-content: space-between` will produce equal spacing *between* items (this essentially means the elements on the outside extremes, or far left and far right, get pushed to the ends of the container) whereas `justify-content: space-around` produces equal spacing *around* the elements (including a sort of "wrapping" effect where side padding is taken into account between the item on the far left and the item on the far right).

</details>

<img src="https://user-images.githubusercontent.com/52146855/64960536-705bc300-d861-11e9-9640-0ac5b54fdae0.png" width="300" height="300" />

(See the [flexbox properties and values](#flexbox-properties-and-values) for reference.)

```css
/* given code */
#pond {
    display: flex;
                                            /* your work here */
    /* only use blank line above */
}
```

<details><summary> Solution</summary>

```css
#pond {
    display: flex;                  /* image 1 */
    justify-content: space-around;  /* image 2 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64960536-705bc300-d861-11e9-9640-0ac5b54fdae0.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64960990-81590400-d862-11e9-91dd-d0a6b14274fe.png" width="150" height="150" />

</details>

## Level 4

<details><summary> Click here for more explicit directions (i.e., hints)</summary>

Recall that `justify-content: space-between` will produce equal spacing *between* items (this essentially means the elements on the outside extremes, or far left and far right, get pushed to the ends of the container) whereas `justify-content: space-around` produces equal spacing *around* the elements (including a sort of "wrapping" effect where side padding is taken into account between the item on the far left and the item on the far right).

</details>

<img src="https://user-images.githubusercontent.com/52146855/64966965-c20a4a80-d86d-11e9-8bea-ea52de510e48.png" width="300" height="300" />

(See the [flexbox properties and values](#flexbox-properties-and-values) for reference.)

```css
/* given code */
#pond {
    display: flex;
                                            /* your work here */
    /* only use blank line above */
}
```

<details><summary> Solution</summary>

```css
#pond {
    display: flex;                      /* image 1 */
    justify-content: space-between;     /* image 2 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64966965-c20a4a80-d86d-11e9-8bea-ea52de510e48.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64983752-3acdce80-d88f-11e9-94e5-40966e14624a.png" width="150" height="150" />

</details>

## Level 5

<details><summary> Click here for more explicit directions (i.e., hints)</summary>

What does `align-items: flex-end` seek to accomplish?

</details>

<img src="https://user-images.githubusercontent.com/52146855/64967010-cf273980-d86d-11e9-9c04-50a295f68341.png" width="300" height="300" />

(See the [flexbox properties and values](#flexbox-properties-and-values) for reference.)

```css
/* given code */
#pond {
    display: flex;
                                            /* your work here */
    /* only use blank line above */
}
```

<details><summary> Solution</summary>

```css
#pond {
    display: flex;              /* image 1 */
    align-items: flex-end;      /* image 2 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64967010-cf273980-d86d-11e9-9c04-50a295f68341.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64983934-a748cd80-d88f-11e9-8ee4-62b28855dba1.png" width="150" height="150" />

</details>

## Level 6

<details><summary> Click here for more explicit directions (i.e., hints)</summary>

Is it possible to accomplish the desired effect using `justify-content` and `align-items`?

</details>

<img src="https://user-images.githubusercontent.com/52146855/64967031-db12fb80-d86d-11e9-99ec-0467435acbdb.png" width="300" height="300" />

(See the [flexbox properties and values](#flexbox-properties-and-values) for reference.)

```css
/* given code */
#pond {
    display: flex;
                                            /* your work here */
                                            /* your work here */
    /* only use blank lines above */
}
```

<details><summary> Solution</summary>

```css
#pond {
    display: flex;              /* image 1 */
    justify-content: center;    /* image 2 */
    align-items: center;        /* image 3 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64967031-db12fb80-d86d-11e9-99ec-0467435acbdb.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64984060-fdb60c00-d88f-11e9-8286-99e484a8a424.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64984061-fdb60c00-d88f-11e9-86dc-61007ce90b96.png" width="150" height="150" />

</details>

## Level 7

<details><summary> Click here for more explicit directions (i.e., hints)</summary>

Is it possible to accomplish the desired effect using `justify-content` and `align-items`?

</details>

<img src="https://user-images.githubusercontent.com/52146855/64967054-e5cd9080-d86d-11e9-967e-4ab9f2b08e66.png" width="300" height="300" />

(See the [flexbox properties and values](#flexbox-properties-and-values) for reference.)

```css
/* given code */
#pond {
    display: flex;
                                            /* your work here */
                                            /* your work here */
    /* only use blank lines above */
}
```

<details><summary> Solution</summary>

```css
#pond {
    display: flex;                  /* image 1 */
    justify-content: space-around;  /* image 2 */
    align-items: flex-end;          /* image 3 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64967054-e5cd9080-d86d-11e9-967e-4ab9f2b08e66.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64984410-d0b62900-d890-11e9-9abb-760d51c4fb9e.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64984411-d0b62900-d890-11e9-8773-d2f9afea9a23.png" width="150" height="150" />

</details>

## Level 8

<details><summary> Click here for more explicit directions (i.e., hints)</summary>

Can you use `flex-direction`? What does `flex-direction: row-reverse` try to accomplish?

</details>

<img src="https://user-images.githubusercontent.com/52146855/64967090-f1b95280-d86d-11e9-9697-cfb81ae5f9f5.png" width="300" height="300" />

(See the [flexbox properties and values](#flexbox-properties-and-values) for reference.)

```css
/* given code */
#pond {
    display: flex;
                                            /* your work here */
    /* only use blank line above */
}
```

<details><summary> Solution</summary>

```css
#pond {
    display: flex;                  /* image 1 */
    flex-direction: row-reverse;    /* image 2 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64967090-f1b95280-d86d-11e9-9697-cfb81ae5f9f5.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64984722-6356c800-d891-11e9-835c-9a76bb9fba91.png" width="150" height="150" />

</details>

## Level 9

<details><summary> Click here for more explicit directions (i.e., hints)</summary>

Can you use `flex-direction`? What does `flex-direction: column` try to accomplish?

</details>

<img src="https://user-images.githubusercontent.com/52146855/64967131-00a00500-d86e-11e9-985f-b1c87db71e41.png" width="300" height="300" />

(See the [flexbox properties and values](#flexbox-properties-and-values) for reference.)

```css
/* given code */
#pond {
    display: flex;
                                            /* your work here */
    /* only use blank line above */
}
```

<details><summary> Solution</summary>

```css
#pond {
    display: flex;              /* image 1 */
    flex-direction: column;     /* image 2 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64967131-00a00500-d86e-11e9-985f-b1c87db71e41.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64984862-add84480-d891-11e9-9da0-aba5d0470cd3.png" width="150" height="150" />

</details>

## Level 10

<details><summary> Click here for more explicit directions (i.e., hints)</summary>

Is it possible to accomplish the desired effect using `flex-direction` and `justify-content`? Notice that when you set the direction to a reversed row or column, start and end are also reversed.

</details>

<img src="https://user-images.githubusercontent.com/52146855/64967170-0bf33080-d86e-11e9-9302-815fe74e6162.png" width="300" height="300" />

(See the [flexbox properties and values](#flexbox-properties-and-values) for reference.)

```css
/* given code */
#pond {
    display: flex;
                                            /* your work here */
                                            /* your work here */
    /* only use blank lines above */
}
```

<details><summary> Solution</summary>

```css
#pond {
    display: flex;                  /* image 1 */
    flex-direction: row-reverse;    /* image 2 */
    justify-content: flex-end;      /* image 3 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64967170-0bf33080-d86e-11e9-9302-815fe74e6162.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64985164-4969b500-d892-11e9-984a-d91141385bda.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64985165-4969b500-d892-11e9-9635-75d33653cb0e.png" width="150" height="150" />

</details>

## Level 11

<details><summary> Click here for more explicit directions (i.e., hints)</summary>

Can you accomplish the desired effect using `flex-direction` and `justify-content`? Notice that when the flex direction is a column, the main and cross axes switch; that is, `justify-content` changes to the vertical axis and `align-items` to the horizontal axis.

</details>

<img src="https://user-images.githubusercontent.com/52146855/64967194-17def280-d86e-11e9-824d-0c0f0f6bba8e.png" width="300" height="300" />

(See the [flexbox properties and values](#flexbox-properties-and-values) for reference.)

```css
/* given code */
#pond {
    display: flex;
                                            /* your work here */
                                            /* your work here */
    /* only use blank lines above */
}
```

<details><summary> Solution</summary>

```css
#pond {
    display: flex;              /* image 1 */
    flex-direction: column;     /* image 2 */
    justify-content: flex-end;  /* image 3 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64967194-17def280-d86e-11e9-824d-0c0f0f6bba8e.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64985359-b0876980-d892-11e9-8699-b67f8457c93f.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64985361-b0876980-d892-11e9-85f2-eb3962ae60bf.png" width="150" height="150" />

</details>

## Level 12

<details><summary> Click here for more explicit directions (i.e., hints)</summary>

Can you use `flex-direction` and `justify-content` to accomplish the desired effect?

</details>

<img src="https://user-images.githubusercontent.com/52146855/64967223-22998780-d86e-11e9-9903-aec9a5e33d04.png" width="300" height="300" />

(See the [flexbox properties and values](#flexbox-properties-and-values) for reference.)

```css
/* given code */
#pond {
    display: flex;
                                            /* your work here */
                                            /* your work here */
    /* only use blank lines above */
}
```

<details><summary> Solution</summary>

```css
#pond {
    display: flex;                      /* image 1 */
    flex-direction: column-reverse;     /* image 2 */
    justify-content: space-between;     /* image 3 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64967223-22998780-d86e-11e9-9903-aec9a5e33d04.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64985886-e7aa4a80-d893-11e9-81aa-ceca77e4202b.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64985887-e7aa4a80-d893-11e9-9dcc-86d9dbf68ef9.png" width="150" height="150" />

</details>

## Level 13

<details><summary> Click here for more explicit directions (i.e., hints)</summary>

Can you use a combination of `flex-direction`, `justify-content`, and `align-items` to accomplish the desired effect?

</details>

<img src="https://user-images.githubusercontent.com/52146855/64967254-2decb300-d86e-11e9-9fb2-befdbf5b2bc0.png" width="300" height="300" />

(See the [flexbox properties and values](#flexbox-properties-and-values) for reference.)

```css
/* given code */
#pond {
    display: flex;
                                            /* your work here */
                                            /* your work here */
                                            /* your work here */
    /* only use blank lines above */
}
```

<details><summary> Solution</summary>

```css
#pond {
    display: flex;                  /* image 1 */
    flex-direction: row-reverse;    /* image 2 */
    justify-content: center;        /* image 3 */
    align-items: flex-end;          /* image 4 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64967254-2decb300-d86e-11e9-9fb2-befdbf5b2bc0.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64986150-699a7380-d894-11e9-80e4-8df58550f6ba.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64986151-699a7380-d894-11e9-90f1-b0f7a7623755.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64986153-699a7380-d894-11e9-8df7-f926ec20ec41.png" width="150" height="150" />

</details>

## Level 14

<details><summary> Click here for more explicit directions (i.e., hints)</summary>

Can you use the `order` property to accomplish the desired effect? Sometimes simply reversing the row or column order of a container is not enough. In these cases, we can apply the `order` property to individual items. By default, items have a value of 0, but we can use this property to also set it to a positive or negative integer value (..., -2, -1, 0, 1, 2, ...).

</details>

<img src="https://user-images.githubusercontent.com/52146855/64967287-380eb180-d86e-11e9-923c-de882ffb78c1.png" width="300" height="300" />

(See the [flexbox properties and values](#flexbox-properties-and-values) for reference.)

```css
/* given code */
#pond {
    display: flex;
}

.yellow {
                                            /* your work here */
    /* only use blank line above */
}
```

<details><summary> Solution</summary>

```css
#pond {
    display: flex;  /* image 1 */
}

.yellow {
    order: 1;       /* image 2 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64967287-380eb180-d86e-11e9-923c-de882ffb78c1.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64986350-d0b82800-d894-11e9-95b6-9d0322537ff7.png" width="150" height="150" />

</details>

## Level 15

<details><summary> Click here for more explicit directions (i.e., hints)</summary>

Can you use the `order` property to accomplish the desired effect (remember that items have a default `order` value of 0)?

</details>

<img src="https://user-images.githubusercontent.com/52146855/64967310-42c94680-d86e-11e9-9d71-4d1cb995c51d.png" width="300" height="300" />

(See the [flexbox properties and values](#flexbox-properties-and-values) for reference.)

```css
/* given code */
#pond {
    display: flex;
}

.red {
                                            /* your work here */
    /* only use blank line above */
}
```

<details><summary> Solution</summary>

```css
#pond {
    display: flex;  /* image 1 */
}

.red {
    order: -1;      /* image 2 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64967310-42c94680-d86e-11e9-9d71-4d1cb995c51d.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64986609-6a7fd500-d895-11e9-8517-243d0d22e460.png" width="150" height="150" />

</details>

## Level 16

<details><summary> Click here for more explicit directions (i.e., hints)</summary>

Can you use `align-self` to accomplish the desired effect?

</details>

<img src="https://user-images.githubusercontent.com/52146855/64967327-4e1c7200-d86e-11e9-9183-88259af3e006.png" width="300" height="300" />

(See the [flexbox properties and values](#flexbox-properties-and-values) for reference.)

```css
/* given code */
#pond {
    display: flex;
    align-items: flex-start; 
}

.yellow {
                                            /* your work here */
    /* only use blank line above */
}
```

<details><summary> Solution</summary>

```css
#pond {
    display: flex;
    align-items: flex-start;    /* image 1 */
}

.yellow {
    align-self: flex-end;       /* image 2 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64967327-4e1c7200-d86e-11e9-9183-88259af3e006.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64986821-dbbf8800-d895-11e9-8494-b05eae4f958e.png" width="150" height="150" />

</details>

## Level 17

<details><summary> Click here for more explicit directions (i.e., hints)</summary>

Can you use `order` and `align-self` to accomplish the desired effect?

</details>

<img src="https://user-images.githubusercontent.com/52146855/64967359-596f9d80-d86e-11e9-95f6-8de5db2a3946.png" width="300" height="300" />

(See the [flexbox properties and values](#flexbox-properties-and-values) for reference.)

```css
/* given code */
#pond {
    display: flex;
    align-items: flex-start; 
}

.yellow {
                                            /* your work here */
                                            /* your work here */
    /* only use blank lines above */
}
```

<details><summary> Solution</summary>

```css
#pond {
    display: flex;
    align-items: flex-start;    /* image 1 */
}

.yellow {
    order: 1;                   /* image 2 */
    align-self: flex-end;       /* image 3 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64967359-596f9d80-d86e-11e9-95f6-8de5db2a3946.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64987882-2c37e500-d898-11e9-9394-9580924c603a.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64987883-2c37e500-d898-11e9-8446-92a01a0d45e5.png" width="150" height="150" />

</details>

## Level 18

<details><summary> Click here for more explicit directions (i.e., hints)</summary>

Can you use `flex-wrap` to accomplish the desired effect?

</details>

<img src="https://user-images.githubusercontent.com/52146855/64967387-67252300-d86e-11e9-9757-8b5b9a7fe270.png" width="300" height="300" />

(See the [flexbox properties and values](#flexbox-properties-and-values) for reference.)

```css
/* given code */
#pond {
    display: flex;
                                            /* your work here */
    /* only use blank line above */
}
```

<details><summary> Solution</summary>

```css
#pond {
    display: flex;      /* image 1 */
    flex-wrap: wrap;    /* image 2 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64967387-67252300-d86e-11e9-9757-8b5b9a7fe270.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64988033-8cc72200-d898-11e9-86b5-1d973fb3b7e8.png" width="150" height="150" />

</details>

## Level 19

<details><summary> Click here for more explicit directions (i.e., hints)</summary>

Can you use `flex-direction` and `flex-wrap` to accomplish the desired effect? What about being even more concise and using `flex-flow`?

</details>

<img src="https://user-images.githubusercontent.com/52146855/64967436-7d32e380-d86e-11e9-9bff-6cff57baae26.png" width="300" height="300" />

(See the [flexbox properties and values](#flexbox-properties-and-values) for reference.)

```css
/* given code */
#pond {
    display: flex;
                                            /* your work here */
                                            /* your work here */
    /* only use blank lines above */
}
```

<details><summary> Solution</summary>

```css
#pond {
    display: flex;              /* image 1 */
    flex-direction: column;     /* image 2 */
    flex-wrap: wrap;            /* image 3 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64967436-7d32e380-d86e-11e9-9bff-6cff57baae26.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64988197-e92a4180-d898-11e9-9856-3afbe21ffcd8.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64988198-e9c2d800-d898-11e9-8fb4-6ab15608eb7e.png" width="150" height="150" />

Note that we can accomplish the above using `flex-flow`, namely `flex-flow: column wrap`.

</details>

## Level 20

<details><summary> Click here for more explicit directions (i.e., hints)</summary>

Can you use the `flex-flow` shorthand property by itself instead of both `flex-direction` and `flex-wrap` to accomplish the desired effect?

</details>

<img src="https://user-images.githubusercontent.com/52146855/64967437-7d32e380-d86e-11e9-9ad9-f5cc923b6064.png" width="300" height="300" />

(See the [flexbox properties and values](#flexbox-properties-and-values) for reference.)

```css
/* given code */
#pond {
    display: flex;
                                            /* your work here */
    /* only use blank line above */
}
```

<details><summary> Solution</summary>

```css
#pond {
    display: flex;              /* image 1 */
    flex-flow: column wrap;     /* image 2 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64967437-7d32e380-d86e-11e9-9ad9-f5cc923b6064.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64988381-5938c780-d899-11e9-98d6-081cbe10dea8.png" width="150" height="150" />

</details>

## Level 21

<details><summary> Click here for more explicit directions (i.e., hints)</summary>

Can you use `align-content` to accomplish the desired effect?

</details>

<img src="https://user-images.githubusercontent.com/52146855/64968501-4cec4480-d870-11e9-9cbb-91db368da517.png" width="300" height="300" />

(See the [flexbox properties and values](#flexbox-properties-and-values) for reference.)

```css
/* given code */
#pond {
    display: flex;
    flex-wrap: wrap;
                                            /* your work here */
    /* only use blank line above */
}
```

<details><summary> Solution</summary>

```css
#pond {
    display: flex;
    flex-wrap: wrap;            /* image 1 */
    align-content: flex-start;  /* image 2 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64968501-4cec4480-d870-11e9-9cbb-91db368da517.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64988561-b765aa80-d899-11e9-8933-3f9695bdda26.png" width="150" height="150" />

</details>

## Level 22

<details><summary> Click here for more explicit directions (i.e., hints)</summary>

Can you use `align-content` to accomplish the desired effect?

</details>

<img src="https://user-images.githubusercontent.com/52146855/64967439-7dcb7a00-d86e-11e9-9a7f-e87d9f926426.png" width="300" height="300" />

(See the [flexbox properties and values](#flexbox-properties-and-values) for reference.)

```css
/* given code */
#pond {
    display: flex;
    flex-wrap: wrap;
                                            /* your work here */
    /* only use blank line above */
}
```

<details><summary> Solution</summary>

```css
/* given code */
#pond {
    display: flex;
    flex-wrap: wrap;        /* image 1 */
align-content: flex-end;    /* image 2 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64967439-7dcb7a00-d86e-11e9-9a7f-e87d9f926426.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64988714-17f4e780-d89a-11e9-9c0b-fec8720946e9.png" width="150" height="150" />

</details>

## Level 23

<details><summary> Click here for more explicit directions (i.e., hints)</summary>

Can you use `flex-direction` and `align-content` to accomplish the desired effect?

</details>

<img src="https://user-images.githubusercontent.com/52146855/64967440-7dcb7a00-d86e-11e9-8cb7-b1f3e71e56fc.png" width="300" height="300" />

(See the [flexbox properties and values](#flexbox-properties-and-values) for reference.)

```css
/* given code */
#pond {
    display: flex;
    flex-wrap: wrap;
                                            /* your work here */
                                            /* your work here */
    /* only use blank lines above */
}
```

<details><summary> Solution</summary>

```css
#pond {
    display: flex;
    flex-wrap: wrap;                    /* image 1 */
    flex-direction: column-reverse;     /* image 2 */
    align-content: center;              /* image 3 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64967440-7dcb7a00-d86e-11e9-8cb7-b1f3e71e56fc.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64988957-8df94e80-d89a-11e9-8d7c-6d41ca59eec6.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64988958-8df94e80-d89a-11e9-867e-1f2a5cd3e0f3.png" width="150" height="150" />

</details>

## Level 24

<details><summary> Click here for more explicit directions (i.e., hints)</summary>

<details><summary> Hint 1 (somewhat vague)</summary>

Can you use some combination of `flex-direction`, `flex-wrap`, `justify-content`, and `align-content` to accomplish the desired effect (recall that `flex-direction` and `flex-wrap` can be combined into one property with `flex-flow`)? 

</details>

<details><summary> Hint 2 (terribly specific, basically the answer)</summary>

Would `flex-direction: column-reverse` be helpful? What about `flex-wrap: wrap-reverse`? Now it's mostly a matter of having our axes sorted correctly. Would `justify-content: center` help us get the yellow frogs centered vertically? If so, would `align-content: space-between` then help us place the yellow frogs on their lily pads?

</details>

</details>

<img src="https://user-images.githubusercontent.com/52146855/64967441-7dcb7a00-d86e-11e9-9890-b2fdec6d3e5e.png" width="300" height="300" />

(See the [flexbox properties and values](#flexbox-properties-and-values) for reference.)

```css
/* given code */
#pond {
    display: flex;
                                            /* your work here */
                                            /* your work here */
                                            /* your work here */
                                            /* your work here */
    /* only use blank lines above */
}
```

<details><summary> Solution</summary>

```css
#pond {
    display: flex;                      /* image 1 */
    flex-direction: column-reverse;     /* image 2 */
    flex-wrap: wrap-reverse;            /* image 3 */
    justify-content: center;            /* image 4 */
    align-content: space-between;       /* image 5 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64967441-7dcb7a00-d86e-11e9-9890-b2fdec6d3e5e.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64997778-bf304980-d8af-11e9-8e36-72ebddd06a94.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64997779-bf304980-d8af-11e9-82bf-3f61418e5ced.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64997780-bf304980-d8af-11e9-8572-471993369b90.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64997782-bf304980-d8af-11e9-915a-75f485595459.png" width="150" height="150" />

Note: Each decision in the solution was reached via the following "thought process": 

- `flex-direction: column-reverse`: The lilypads are arranged vertically. This first suggests that the frogs need to be aligned vertically (i.e., we should probably have something like `flex-direction: column`). Additionally, the red lilypad is at the bottom while the red frog is at the top. This suggests that we should reverse the ordering of the column (i.e., `flex-direction: column-reverse`).
- `flex-wrap: wrap-reverse`: We now want to right-align the frogs and have proper vertical spacing. We almost get this with `flex-wrap: wrap`, but the red and green frogs need to be on the right instead of the left. The solution is to reverse the wrap (i.e., `flex-wrap: wrap-reverse`). 
- `justify-content: center:` The yellow frogs need to be centered vertically and then moved to the left. *Normally* we would use `align-content: center` to center flex items vertically, but recall that we swapped the axes by using `flex-direction: column-reverse`. Thus, the solution is to actually use `justify-content: center` since now the vertical axis is the main axis.
- `align-content: space-between`: We now need the yellow frogs to be pushed all the way to left. More specifically, we need to have equal space between the yellow frogs and the other frogs. This leads us to use `align-content: space-between`.

Final note: since `flex-flow` incorporates both `flex-direction` as well as `flex-wrap`, we can actually refactor our code to be slightly more concise: 

```css
#pond {
    display: flex;                              /* image 1 */
    flex-flow: column-reverse wrap-reverse;     /* images 2 and 3 *
    justify-content: center;                    /* image 4 */
    align-content: space-between;               /* image 5 */
}
```

</details>