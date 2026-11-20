# Lab 4: Divs, Attributes and a Small Fix

**Name:** Vishal babu  
**Roll No:** 2410303557  
**Student ID:** BCS2024333 
**Course:** B.Tech CSE (3rd Year) - HTML & CSS Development Lab (BCS554)

## Aim
Group parts of a page with div elements, add a data attribute, and fix a broken page.

## Tasks
1. `layout.html` - div blocks with classes header, main, footer.
2. `attributes.html` - div id=profile with a paragraph having data-topic="hobbies".
3. `attendance-fixed.html` - corrected broken page.

## Files
- `index.html`
- `style.css`
- `layout.html`
- `attributes.html`
- `attendance-fixed.html`

## Output
**attendance-fixed.html**

![attendance-fixed.html](images/attendance-fixed.png)

**attributes.html**

![attributes.html](images/attributes.png)

**layout.html**

![layout.html](images/layout.png)


## Errors fixed in `attendance-fixed.html`
1. `<h1>` was never closed -> added `</h1>`.
2. `<p>Asha: 92%<p>` had an opening `<p>` where a closing `</p>` was needed -> fixed to `</p>`.
(Also added `lang` and `charset`/viewport meta for good practice.)
