# Flexbox Froggy

[](#general-information)   
## General Information 

<details><summary> <code>justify-content</code></summary>

The `justify-content` property aligns flex items along the main axis (horizontal axis by default).

- `flex-start`: Items align to the left side of the container.
- `flex-end`: Items align to the right side of the container.
- `center`: Items align at the center of the container.
- `space-between`: Items display with equal spacing between them.
- `space-around`: Items display with equal spacing around them.

</details>

<details open><summary> <code>align-items</code></summary>

Aligns flex items along the cross axis (vertical axis by default).

- `flex-start`
- `flex-end`
- `center`
- `baseline`
- `stretch`

</details>

<details open><summary> <code>flex-direction</code></summary>

Defines the direction of the main axis (horizontal by default).

- `row`
- `row-reverse`
- `column`
- `column-reverse`

</details>

<details open><summary> <code>order</code></summary>

Specifies the order of the flex item. 

- `<integer> (..., -1, 0, 1, ...)` (0 by default)

</details>

<details open><summary> <code>align-self</code></summary>

Aligns a flex item along the cross axis, override the `align-items` value.

- `flex-start`
- `flex-end`
- `center`
- `baseline`
- `stretch`

</details>

<details open><summary> <code>flex-wrap</code></summary>

Specifies whether flex items are forced on a single line or can be wrapped on multiple lines.

- `nowrap`
- `wrap`
- `wrap-reverse`

</details>

<details open><summary> <code>flex-flow</code></summary>

Shorthand property for `flex-direction` and `flex-wrap`.

- `<flex-direction> <flex-wrap>`

</details>

<details open><summary> <code>align-content</code></summary>

Aligns a flex container's lines within the flex container when there is extra space on the cross-axis.

- `flex-start`
- `flex-end`
- `center`
- `space-between`
- `space-around`
- `stretch`

</details>



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

Move the frog to the right on top of the lilypad.

<details><summary> Click here for more explicit directions (i.e., a hint).</summary>

TBD

</details><br>

<img src="https://user-images.githubusercontent.com/52146855/64952375-2cab8e00-d84e-11e9-9580-d3710b97ddf9.png" width="300" height="300" />

(See [general information](#general-information) for reference.)

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

Notes: 

</details>

## Level 2

Help the pictured frogs get to their lilypads.

<img src="https://user-images.githubusercontent.com/52146855/64954712-6e3f3780-d854-11e9-88a7-74e0d5ca8a7d.png" width="300" height="300" />

(See [general information](#general-information) for reference.)

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

Notes: 

</details>

## Level 3

Move the frog to the right on top of the lilypad.

<img src="https://user-images.githubusercontent.com/52146855/64960536-705bc300-d861-11e9-9640-0ac5b54fdae0.png" width="300" height="300" />

(See [general information](#general-information) for reference.)

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

Notes: 

</details>

## Level 4

Move the frog to the right on top of the lilypad.

<img src="https://user-images.githubusercontent.com/52146855/64966965-c20a4a80-d86d-11e9-8bea-ea52de510e48.png" width="300" height="300" />

(See [general information](#general-information) for reference.)

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

Notes: 

</details>

## Level 5

Move the frog to the right on top of the lilypad.

<img src="https://user-images.githubusercontent.com/52146855/64967010-cf273980-d86d-11e9-9c04-50a295f68341.png" width="300" height="300" />

(See [general information](#general-information) for reference.)

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
    align-items: flex-end;     /* image 2 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64967010-cf273980-d86d-11e9-9c04-50a295f68341.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64983934-a748cd80-d88f-11e9-8ee4-62b28855dba1.png" width="150" height="150" />

Notes: 

</details>

## Level 6

Move the frog to the right on top of the lilypad.

<img src="https://user-images.githubusercontent.com/52146855/64967031-db12fb80-d86d-11e9-99ec-0467435acbdb.png" width="300" height="300" />

(See [general information](#general-information) for reference.)

```css
/* given code */
#pond {
    display: flex;
                                            /* your work here */
                                            /* your work here */
    /* only use blank line above */
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

Notes: 

</details>

## Level 7

Move the frog to the right on top of the lilypad.

<img src="https://user-images.githubusercontent.com/52146855/64967054-e5cd9080-d86d-11e9-967e-4ab9f2b08e66.png" width="300" height="300" />

(See [general information](#general-information) for reference.)

```css
/* given code */
#pond {
    display: flex;
                                            /* your work here */
                                            /* your work here */
    /* only use blank line above */
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

Notes: 

</details>

## Level 8

Move the frog to the right on top of the lilypad.

<img src="https://user-images.githubusercontent.com/52146855/64967090-f1b95280-d86d-11e9-9697-cfb81ae5f9f5.png" width="300" height="300" />

(See [general information](#general-information) for reference.)

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

Notes: 

</details>

## Level 9

Move the frog to the right on top of the lilypad.

<img src="https://user-images.githubusercontent.com/52146855/64967131-00a00500-d86e-11e9-985f-b1c87db71e41.png" width="300" height="300" />

(See [general information](#general-information) for reference.)

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

Notes: 

</details>

## Level 10

Move the frog to the right on top of the lilypad.

<img src="https://user-images.githubusercontent.com/52146855/64967170-0bf33080-d86e-11e9-9302-815fe74e6162.png" width="300" height="300" />

(See [general information](#general-information) for reference.)

```css
/* given code */
#pond {
    display: flex;
                                            /* your work here */
                                            /* your work here */
    /* only use blank line above */
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

Notes: 

</details>

## Level 11

Move the frog to the right on top of the lilypad.

<img src="https://user-images.githubusercontent.com/52146855/64967194-17def280-d86e-11e9-824d-0c0f0f6bba8e.png" width="300" height="300" />

(See [general information](#general-information) for reference.)

```css
/* given code */
#pond {
    display: flex;
                                            /* your work here */
                                            /* your work here */
    /* only use blank line above */
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

Notes: 

</details>

## Level 12

Move the frog to the right on top of the lilypad.

<img src="https://user-images.githubusercontent.com/52146855/64967223-22998780-d86e-11e9-9903-aec9a5e33d04.png" width="300" height="300" />

(See [general information](#general-information) for reference.)

```css
/* given code */
#pond {
    display: flex;
                                            /* your work here */
                                            /* your work here */
    /* only use blank line above */
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

Notes: 

</details>

## Level 13

Move the frog to the right on top of the lilypad.

<img src="https://user-images.githubusercontent.com/52146855/64967254-2decb300-d86e-11e9-9fb2-befdbf5b2bc0.png" width="300" height="300" />

(See [general information](#general-information) for reference.)

```css
/* given code */
#pond {
    display: flex;
                                            /* your work here */
                                            /* your work here */
                                            /* your work here */
    /* only use blank line above */
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

Notes: 

</details>

## Level 14

Move the frog to the right on top of the lilypad.

<img src="https://user-images.githubusercontent.com/52146855/64967287-380eb180-d86e-11e9-923c-de882ffb78c1.png" width="300" height="300" />

(See [general information](#general-information) for reference.)

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
    order: 1;        /* image 2 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64967287-380eb180-d86e-11e9-923c-de882ffb78c1.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64986350-d0b82800-d894-11e9-95b6-9d0322537ff7.png" width="150" height="150" />

Notes: 

</details>

## Level 15

Move the frog to the right on top of the lilypad.

<img src="https://user-images.githubusercontent.com/52146855/64967310-42c94680-d86e-11e9-9d71-4d1cb995c51d.png" width="300" height="300" />

(See [general information](#general-information) for reference.)

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
    order: -1;       /* image 2 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64967310-42c94680-d86e-11e9-9d71-4d1cb995c51d.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64986609-6a7fd500-d895-11e9-8517-243d0d22e460.png" width="150" height="150" />

Notes: 

</details>

## Level 16

Move the frog to the right on top of the lilypad.

<img src="https://user-images.githubusercontent.com/52146855/64967327-4e1c7200-d86e-11e9-9183-88259af3e006.png" width="300" height="300" />

(See [general information](#general-information) for reference.)

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

Notes: 

</details>

## Level 17

Move the frog to the right on top of the lilypad.

<img src="https://user-images.githubusercontent.com/52146855/64967359-596f9d80-d86e-11e9-95f6-8de5db2a3946.png" width="300" height="300" />

(See [general information](#general-information) for reference.)

```css
/* given code */
#pond {
    display: flex;
    align-items: flex-start; 
}

.yellow {
                                            /* your work here */
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
    order: 1;                   /* image 2 */
    align-self: flex-end;       /* image 3 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64967359-596f9d80-d86e-11e9-95f6-8de5db2a3946.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64987882-2c37e500-d898-11e9-9394-9580924c603a.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64987883-2c37e500-d898-11e9-8446-92a01a0d45e5.png" width="150" height="150" />

Notes: 

</details>

## Level 18

Move the frog to the right on top of the lilypad.

<img src="https://user-images.githubusercontent.com/52146855/64967387-67252300-d86e-11e9-9757-8b5b9a7fe270.png" width="300" height="300" />

(See [general information](#general-information) for reference.)

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

Notes: 

</details>

## Level 19

Move the frog to the right on top of the lilypad.

<img src="https://user-images.githubusercontent.com/52146855/64967436-7d32e380-d86e-11e9-9bff-6cff57baae26.png" width="300" height="300" />

(See [general information](#general-information) for reference.)

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
    flex-wrap: wrap;            /* image 3 */
}
```

<img src="https://user-images.githubusercontent.com/52146855/64967436-7d32e380-d86e-11e9-9bff-6cff57baae26.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64988197-e92a4180-d898-11e9-9856-3afbe21ffcd8.png" width="150" height="150" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/52146855/64988198-e9c2d800-d898-11e9-8fb4-6ab15608eb7e.png" width="150" height="150" />

Notes: 

</details>

## Level 20

Move the frog to the right on top of the lilypad.

<img src="https://user-images.githubusercontent.com/52146855/64967437-7d32e380-d86e-11e9-9ad9-f5cc923b6064.png" width="300" height="300" />

(See [general information](#general-information) for reference.)

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

Notes: 

</details>

## Level 21

Move the frog to the right on top of the lilypad.

<img src="https://user-images.githubusercontent.com/52146855/64968501-4cec4480-d870-11e9-9cbb-91db368da517.png" width="300" height="300" />

(See [general information](#general-information) for reference.)

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

Notes: 

</details>

## Level 22

Move the frog to the right on top of the lilypad.

<img src="https://user-images.githubusercontent.com/52146855/64967439-7dcb7a00-d86e-11e9-9a7f-e87d9f926426.png" width="300" height="300" />

(See [general information](#general-information) for reference.)

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

Notes: 

</details>

## Level 23

Move the frog to the right on top of the lilypad.

<img src="https://user-images.githubusercontent.com/52146855/64967440-7dcb7a00-d86e-11e9-8cb7-b1f3e71e56fc.png" width="300" height="300" />

(See [general information](#general-information) for reference.)

```css
/* given code */
#pond {
    display: flex;
    flex-wrap: wrap;
                                            /* your work here */
                                            /* your work here */
    /* only use blank line above */
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

Notes: 

</details>

## Level 24

Move the frog to the right on top of the lilypad.

<img src="https://user-images.githubusercontent.com/52146855/64967441-7dcb7a00-d86e-11e9-9890-b2fdec6d3e5e.png" width="300" height="300" />

(See [general information](#general-information) for reference.)

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