1. 11
2. 113
3. 24
4. 277 is not a number that can be donated when using rgba color scheme, the maximum value is 255 that can donate any color value.
5. em and rem are relative units, they are both scalable whereas px is not. This means that using em in place of px will scale the size of the font according to the next nested child in the tree. Thus children inherit size by scaling in relation to the parent font size. While em is relative to the font size of its direct (or nearest) parent, rem is only relative to the root font-size. So, if you are trying to achieve consistent spacing without extra markup, rem can be used to define the padding and margins.