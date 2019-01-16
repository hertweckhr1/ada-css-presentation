# ADA CSS Presentation #

[Slides](https://docs.google.com/presentation/d/1w_2pnKUH0avPC6nstE283m_RFvHMIpkgtAWfmJueddk/edit?usp=sharing)

["Mockup" of index.html](index-mockup.png)

["Mockup" of article.html](article-mockup.png)

## Step 0: Clone this Repo (bit.ly/ada-css) ##

```bash
git clone https://github.com/kaidamasaki/ada-css-presentation.git
```

## Step 1: Top Level (together) ##

### Spec ###
* `header` should be at the top span width of the entire body.
* `#popular-stories` should be 300px wide and on the right; it should
    be as tall as its content.
* `main` should sit next to `#popular-stories` on the left and fill
    the remaining horizontal space; it should be as tall as its content.
* `footer` should be at the bottom and span the width of the entire body.

As I mentioned in the presentation the first thing I like to do when I
start styling a new webpage is position the top level elements.

## Step 2: Hide the "Skip to Content" link (together) ##

This is an accessibility thing, blind users don't want to _have_ to
listen to your entire navigation and popular stories all the time, but
putting them at the front makes them easy to access on the first
visit.

### Spec ###
* `.nav-skip` link should be positioned off of the page _and_ removed
  from the normal page flow.
