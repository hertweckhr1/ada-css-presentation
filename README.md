# ADA CSS Presentation #

[Slides](https://docs.google.com/presentation/d/1w_2pnKUH0avPC6nstE283m_RFvHMIpkgtAWfmJueddk/edit?usp=sharing)

## Step 0: Clone this Repo (bit.ly/ada-css) ##

```bash
git clone https://github.com/kaidamasaki/ada-css-presentation.git
```

## Step 1: Walk Through ##

### Top Level Spec ###
* `header` should be at the top span width of the entire body; it
  should be as tall as its content.
* `#popular-stories` should be 300px wide and on the right; it should
    be as tall as its content.
* `main` should sit next to `#popular-stories` on the left and fill
    the remaining horizontal space; it should be as tall as its
    content.
* `footer` should be at the bottom and span the width of the entire
  body; it should be as tall as its content.
* `#popular-stories` and `main` should have a 1px wide black border
  around them a 20px space between them.

As I mentioned in the presentation the first thing I like to do when I
start styling a new webpage is position the top level elements.

### Nav Skip Spec ###
* `#nav-skip` link should be positioned off of the page _and_ removed
  from the normal page flow.
* `#nav-skip` should appear in the upper left corner when focused (say
  by using the tab key)

This is an accessibility thing, blind users don't want to _have_ to
listen to your entire navigation and popular stories all the time, but
putting them at the front makes them easy to access on the first
visit.

## Step 2: Activity ##

Using the following "mockups" (screenshots) start implementing as much
as possible of the layout.

["Mockup" of index.html](index-mockup.png)

["Mockup" of article.html](article-mockup.png)

### Annex: CSS Properties Used ###

These are all of the CSS properties I used when creating the example
solution.

```
align-items
background
border
border-bottom
border-color
border-radius
border-top
bottom
color
content
display
flex-direction
flex-shrink
float
font-family
font-size
font-style
font-weight
grid-column
grid-row
grid-template-columns
grid-template-rows
height
left
margin
margin-bottom
margin-left
margin-right
margin-top
max-width
order
overflow
padding
padding-bottom
position
quotes
right
src
text-align
text-decoration
top
transition
white-space
width
z-index
```
