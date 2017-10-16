## Opinions

It's an opinionated thing, so let's look at some of the opinions.

TODO: Is this repo JUST the reset? Or is it everything?

1. **This isn't Bootstrap** I'm not trying to build a universal set of styles for every element. This is intended to get things off of the ground.

## Edge Cases

There are edge cases frequently included in resets etc that seem like overkill to me. They target specific edge cases that are rare in the work that I do.

But man, would it suck to have to look these up later.

```
//
// Correct element displays
//

output {
  display: inline-block;
}

summary {
  display: list-item; // Add the correct display in all browsers
}

template {
  display: none; // Add the correct display in IE
}

/**
 * Add the correct margin in IE 8.
 */

figure {
  margin: 1em 40px;
}
```
