# Guidelines for Web Design

## Typography

### Font Size

- Use 15-25px for body text
- If using larger font sizes for headers, etc., you can reduce the font weight so it doesn't take up too much visual real estate on the page

### Spacing

- Use line spacing of 120-150%
- 45-90 characters per line

### Font Families

- Sans-serif is best for most things
  - Open Sans
  - Lato
  - Raleway
  - Monsterrat
  - PT Sans
- Serif is for storytelling or long reading
  - Cardo
  - Merriweather
  - PT Serif
- Choose a font that reflects the look and feel you want for the website
- Decide on serif or sans-serif
- Use only one typeface (unless you're more experienced)

## Color

- Use only one base color (anything other than black, white, shade of gray) then you can use something like http://0to255.com to get lighter & darker shades of that color to use as accents, hover states, etc.
- Can use the main or a complementary 2nd color for things like a call-to-action button or anythign else that needs attention drawn to it
- Use a color to draw attention; a color that stands out will draw attention to things on the page
- Never use black in a design (even in fonts) - it almost never appears in the real world
- How to choose a color:
  - <span style="color:red; font-weight:bold">Red</span>: power, passion, strength, excitement
    - Brighter tones are more energetic
    - Darker shades show more power & elegance
  - <span style="color:orange; font-weight:bold">Orange</span>: draws attention without being as overpowering as red, cheerfulness, creativity, friendliness, confidence, courage
  - <span style="color:yellow; font-weight:bold">Yellow</span>: energetic, feelings of happiness & liveliness, curiousity, intelligence, brightness
  - <span style="color:green; font-weight:bold">Green</span>: harmony, nature, life, health, associated with money, balancing & harmonizing effect
  - <span style="color:blue; font-weight:bold">Blue</span>: patience, peace, trustworthiness, stability, professionalism, trust, honor
  - <span style="color:purple; font-weight:bold">Purple</span>: power, nobility, wealth, wisdom, luxury, mystery
  - <span style="color:pink; font-weight:bold">Pink</span>: romance, passivity, care, peace, affection
  - <span style="color:brown; font-weight:bold">Brown</span>: relaxation, confidence, earthiness, nature, durability, comfort, reliability

## Images

- You can put tet directly on an image but only really works if image is dark and text is white
- Can usually darken an image with black or also color gradients
- Put text in a box with a different color background and give it something less than 100% opacity so the background image shows through
- Blur an image so the text shows up more easily, or use an out-of-focus area that's already in the image
- Can use the "floor fade" technique to have the image darken at the bottom and then light text can go over it:

  ```css
  .darken {
    background-image: linear-gradient(rgba(0, 0, 0, 0.5) rgba(0, 0, 0, 0.5)),
      url(IMAGEHERE);
  }
  ```

## Icons

- Use to show features of a website or steps a user should follow to achieve some goal
- Use for actions & links
- 2 rules:
  - Icons should be instantly recognizable
  - Label icons as to avoid confusion
- Icons should not take center stage in design; they should play a supporting role and not be overbearing
- Use icon fonts and not static images (icon fonts are vector graphics and will scale)

## Spacing & Layout

- Use a lot of white space in the correct places
- You want space between different sections of the site, between headings and content, etc.
- Put whitespace between elements, groups of elements, website's sections
- Don't overexaggerate whitespace though
- Define hierarchy:
  - Define where you want your audience to look first
  - Establish a flow that corresponds to the content's message
  - Use whitespace to build that flow
