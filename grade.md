# Grade
HTML Code Quality: 4/5
CSS Code Quality: 3.5/5
Responsive Design: 3.5/5
Assignment Requirements: 5/5

Total: 16/20

## Comments
I encourage you to re-use/stick more closely to the code we developed within the in-classes and assignments. You re-did code that you already had in ways that were less cleanly organized and written, causing some issues. An example of this are the banners. You re-wrote it with new class names and CSS code, which was extra work that was unnecessary and uses class naming and organization that is inconsistent and unnecessarily repetitive.

Take some time to review class naming. It is often inconsistent and unclear. Please review my previous tutorial files and watch the video below for some help with that:

https://www.youtube.com/watch?v=SLjHSVwXYq4

### HTML
Search for `prof comment` in individual files for specific comments.

### CSS
Search for `prof comment` in individual files for specific comments.

- The blog content is an example of where its better to use descendent selectors over classes. You put a class on every single heading and `p` tag, which was a lot of work. Instead you could have applied those styles without needing the classes with a selector like `.article p`. This is both simpler, and safer, because it protects you if you forget to add a class somewhere.
  - You've used the class `.card-content__text` on all of your `p` within the blog content. That class is part of the card design, so feels incorrectly used here. You should create a separate class.

### Responsive Design
- About image is too large, consider using the Split-Content Section pattern here for better responsive use of space
- The content within the blog is too wide and the font is too large. It makes the content feel a bit overwhelming and challenging to read.
  - Avoid increasing body copy (aka large paragraphs of text) above the default `1rem` font size.
  - Use a narrower `container--text` so that the content has a more readable line-length.

### Assignment Requirements
All requirements met!