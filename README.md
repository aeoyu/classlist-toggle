# CPNT 262 Assignment 1 - classList Toggle

---

**Author :** Filora

**Repo Link :** https://github.com/aeoyu/cpnt262-a1

**Pages Link :** https://aeoyu.github.io/cpnt262-a1/

---

## Code Review

**Issues :**

- My nav bar text kept wrapping around when I minimize to tackle this problem i've added

```
display: inline-block;
```

to **.navlinks li {}** then added

```
white-space: nowrap;
```

to **.navLinks {}**

- I wanted to disable scrolling on HTML body completely the option I've found online to help with the issue:

```
  scroll="no" style="overflow: hidden;
```

- Because I disabled scrolling the footer had troubles staying within the viewsite, so i solved this issue by making a sticky footer:

```
footer { position: absolute; width: 100%; bottom: 0;
}
.sun-moon { display: flex; width: 100%; height: 50px; position: relative; margin-top: 18rem;
}
```

- The video inspiration I've got from didn't fully cover the page width so i've increased the width percentage to 100%

- I wanted to create a night and day toggle, but I put it in the footer, so was too lazy to move it else where to try to figure out how to get it to work, so instead I just used opacity property to change the color of the toggle.

## Attribution / Links

- [Responsive Navigation Bar Tutorial](https://www.youtube.com/watch?v=gXkqy0b4M5g&t=645s)

**Icons**

- svg created from Figma
