# What I Learned from SideBar

### In HTML 

-> Aside tag is used for sidebars because it states that the component is present in the web page with importance and coves less space.

```html
<aside></aside>
```

-> In HTML the first thing you have to do is create the structure of your webpage.

```html
<div>
    <div>
       <p></p> 
    </div>
<!-- This is the basic Structure example -->
    <div>
        <h1></h1>
    </div>
</div>
```

->Always try to access thing by their parents avoid accessing directly.

```css
.container .sidebar .logo:hover a,
.container .sidebar .logo:hover i,
.container .sidebar .menu ul li:hover a,
li:hover i{
    property
}
```

## In CSS

In CSS there is a display property value named as ***Grid*** which divides the content of webpage as grid and you can define the value of grid that hoe much width each grid is going to take.

```css
    display: grid;
    grid-template-columns: 1fr 4fr 2fr;
    /* Here fr represents fraction */
```

