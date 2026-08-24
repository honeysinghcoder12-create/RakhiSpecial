# 📸 Photos Folder — How It Works

## Folder Structure

Create one subfolder per person, named exactly as you'd type their name (lowercase):

```
photos/
  honey/
    1.jpg
    2.jpg
    3.jpg
    4.jpg
  priya/
    1.jpg
    2.jpg
    3.jpg
    4.jpg
  riya/
    1.jpg
    ...
```

## Rules

- **Folder name** = first name in lowercase (e.g. `honey`, `priya`, `riya`)
- **Photo names** = `1.jpg`, `2.jpg`, `3.jpg`, `4.jpg` (exactly 4 photos)
- Supported formats: `.jpg`, `.jpeg`, `.png`, `.webp`
- If a photo is missing, that slot shows a placeholder automatically

## How it works

When someone types their name in the name gate (e.g. "Honey"),
the page automatically looks inside `photos/honey/` for photos 1–4
and fills the memory wall with them.

If the folder doesn't exist or photos are missing → placeholder shown instead.
