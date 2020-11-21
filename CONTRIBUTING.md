# Contributing to bruno-strap

:+1::tada: First off, thanks for taking the time to contribute! :tada::+1:

## I don't want to read the whole thing and I just want to ask a question!!!

Do not file an issue for a question!!!

*This section is comming later*

## What should I know before I get started?

### About `CAN_BE_EDITED` files at the beginning

Never edit versioned areas in the dist directory without a "`CAN_BE_EDITED`" file with a value of "`true`".

Here is the structure of the files:

> **Note**:
>
> File structures with `...` means it's not listed.
>
> Directories not starting with `|` after a space is a note.

```
-- bruno-strap/
 |
 |--- coc/
 |     |
 |     |--- index.md
 |
 |--- dist/
 |     |
 |     |--- 1.0/
 |     |     |
 |     |     |--- CAN_BE_EDITIED
 |     |     |--- bruno-strap.css
 |     |
 All files after here have a "CAN_BE_EDITED" file with a value of true.
 |     |--- 1.1/
 |           |
 |           |--- CAN_BE_EDITED
 |           |--- bruno-strap.css
 |           |--- bruno-strap.min.css
 |           |--- theme-red.css
 |           |--- theme-red.min.css
 |
 |--- docs/
 |     |
 |     |--- ...
```

## Issues or "first pr comment" with labels or emoji???

If you don't see your label on the list, you could start the issue with "`This issue is about `" and add some emojis at the end.

| Emoji | Meaning |
|---|---|
|:apple:|Apple device error|
|:art:|Improving design/format/structure/`.css` files ([see here](#about-can_be_edited-files-at-the-beginning)).|
|:memo:|When improving text|

Please don't use emojis that are not listed here of emojis that are not here, like `:banana:`(:banana:).
