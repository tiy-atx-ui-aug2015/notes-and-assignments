# Web Accessibility

####Notes
- What is Web Accessibility?
    - Accessibility means that people with disabilities/changing abilities due to age can perceive, understand, navigate, interact, and contribute to the web
    - Accessibility includes:
        + visual
            * blindness, low vision, color blindness
        + auditory
            * deafness, hard of hearing
        + motor
            * inability to use a mouse, slow response time, limited fine motor control
        + cognitive
            * learning disabilities, inability tor emember or focus on large amounts of information, distractability
        + Non-biological: slow internet
    - We need to provide equal access and equal opportunity to people with disabilities
    - Principles of Accessibility:
        + Provide appropriate alternative text
            * screen readers cannot analyze and determine what an image represents
            * text must provide users with the content and function of your images
            * 2 ways to create alternative text
                - alt tag
                - surrounding text (ie. comment)
                * steps to creating an alt tag
                    *  determine whether image has content and function
                    *  mostly won't hav efunction unless it is a link
                    *  an empty alt tag may suffice if the content of the image is provided around the image
                    *  be accurate
                    *  be succinct
                    *  don't be redundant (don't repeat a comment)
                    *  don't use phrases such as "image of" or "graphic of" (doesn't say anything about the content in relationship to its surroundings)
            -  Image sprites should generally be avoided
        + Provide Appropriate document structure
            * People using screen readers often scroll a site by document structure
            * They can choose to jump through main content by navigating through h1 tags (h1 = most important, h6 = least important)
            * don't skip headings (h2 to h4) without including h3
            * don't use headers to achieve visual results (think abou the content)
                -  if you want to change the header visually, use font-size, bold, italics, etc.
                -  screen readers can read <em> and <strong> tags
            * use lists correctly to convey hierarchy (ol vs ul)
            * only use tables for actual data (otherwise screen readers won't read the data in the proper order)
        + Ensure users can complete and submit all forms
            * forms should be logical and easy to use (step by step)
                - labels
                - inputs
                - actions (buttons) 
                - help - assistance on how to fill out the form
                - messages - positive or negative (the username you have selected is already in use)
                - validation - ensures data submitted fulfills parameters
        + Ensure links make sense out of context
            * tab allows you to move from link to link (non empty href) and enter allows you to select it
            * most screen readers say "link" before a link
            * "click here", "click for more", "more details" are ambiguous
            * "Products" is more descriptive
            * provide additional information if the link has additional functionality: Products (opens in a new window)
        + Provide captions for audio and video
            * Synchronized - the text content should appear at approximately the same time that audio would be available
            * Equivalent - content provided in captions should be equivalent to that of the spoken word
            * Accessible - caption content should be readily accessible and available to those who need it (closed captions)
                - https://support.google.com/youtube/answer/2734796?hl=en
        + Allow users to skip to main content
            * navigation is very cumbersome to go through
            * skip to navigation link works, but can be visually unappealing
            * hidden skip to navigation link works best
                - hide visually
                - make the same color as the background
                - size the link to 0
                - hide off screen
                - can include multiple "skip" links
            * Defining h1s properly (and contextually) can help to skip to main content 
        + Do not rely on color alone to convey meaning
            * http://webaim.org/articles/visual/colorblind
            * http://colorfilter.wickline.org/
            * https://chrome.google.com/webstore/detail/accessibility-developer-t/fpkknkljclfencbdbgkenhalefipecmb/reviews?hl=en
            * http://colorsafe.co/
        + Write clearly and concisely
        + Make JS accessible
            * make sure you have a backup if JS is turned off or inaccessible
            * Navigation. Inability or difficulty navigating using a keyboard or assistive technology.
            * Hidden content. Presentation of content or functionality that is not accessible to assistive technologies.
            * User control. Lack of user control over automated content changes.
            * Confusion/Disorientation. Altering or disabling the normal functionality of the user agent (browser) or triggering events that the user may not be aware of.

- Test w/screen reader
    + https://webaccessibility.withgoogle.com/course
- ARIA
    + accessible rich internet applications
    + with interactivity on websites, there is no way of describing what is happening to a screen reader
    + enables developers to describe widgets in more detail
    + 3 attributes
        * roles
            - describe widgets not available in html 4
                + sliders, menu bars, tabs, and dialogs.
        * states
            - describe the current interaction state of an element, informing the assistive technology if it is busy, disabled, selected, or hidden
        * properties
            - describe characteristics of widgets, such as if they are draggable, have a required element, or have a popup associated with them
    + https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Web_applications_and_ARIA_FAQ
    + http://www.standardista.com/standards/wai-aria-accessible-rich-internet-applications-basics/
    + http://heydonworks.com/practical_aria_examples/

#### Reading/Video Assignments
- [Introduction to Web Accessibility](http://webaim.org/intro/)
- [Aria Roles 101](http://www.webteacher.ws/2010/10/14/aria-roles-101/)
- [Aria Basics](http://www.standardista.com/standards/wai-aria-accessible-rich-internet-applications-basics/)

#### CSS Zen Garden Research
- [Details](assignments/css-zen-garden-research.md)

#### CSS Zen Garden Inspiration
- [Details](assignments/css-zen-garden-inspiration.md)

#### Additional Resources/Reading
-[Web Accessibility Course with Google](https://webaccessibility.withgoogle.com/course)
-[Aria states and Properties](http://www.w3.org/TR/wai-aria/states_and_properties)
