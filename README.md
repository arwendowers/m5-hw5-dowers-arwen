# Assignment 5 - Auditing for A11y
## Accessibility Issues
I used Lighthouse and WAVE to find these A11y issues:
* The nav text has low contrast.
* The first heading (Internet Andrea) has low contrast.
* The sub-heading (About Me) has low contrast.
* The body text has low contrast.
* The sub-heading in the form section (Reach out for a quote today!) has low contrast.
* The footer text has low contrast.
* Document does not have a main landmark.
* The sub-headings (About Me, and Reach out...) are h3, skipping from h1 to h3 and disrupting the hierarchical order of headings.
* All the form elements are missing labels.

## Fixes
I changed the following:
* The nav links' color to white, for high contrast.
* The sub-heading, body text, and form heading to a dark grey rather than a light grey for better contrast against the background.
* The footer color to the same light grey as the form, and the text to the same dark grey color, to add more contrast to the phone emoji.
* The first heading, Internet Andrea, where I added a text shadow to make the title stand out more against the busy black and white background, while keeping the original text color.
* The tags from div to semantic tags (like nav, header, main, section, button, and footer).
* The h3 headings to h2 headings, to keep the correct hierarchical order after the h1 heading at the top of the page.
* The input form elements to have ARIA labels for screen-reader accessibility.