
## Success criteria

**100** - the maximum amount of points you can get for implementing this task

!Points - **0-10** means that if none of the criteria are met, the student gets **0** points, otherwise if everything is implemented correctly - **10** points; for the partial implementation of the feature the number of points are set at mentor's discretion.

Points can be cut down in case of mistakes (described in the technical requirements)

## Technical Requirements

1. General:
    - The name of the HTML file should be *index.html*;
    - Create separate folders for images, fonts, and styles. You will be penalized if all files are placed on the same level as 'index.html' file - **minus 10 points**;
    - The markup width should be 1600px. Hence the layout will be tested on 1600px screen width or wider. The markup should be centered. If you are going to implement the task on the device with screen width lower then 1600px, the scrollbar will appear, and it is Ok (you can use zoom out)(**points - 0-10**);

2. Semantic layout:
	 - HTML5 semantic tags should be used.For example header, nav, section, article, footer, form + fields, figure(**points - 0-10**);
	 - Class names should be reasonable and correct, avoid names such as .right-column, .third-form, .left, .big. use more meaningful ones - .heading, .form-container, .wrapper, .menu-column. You are also welcome to use pseudo-classes (:first-child, last-child, etc.)(**points - 0-10**);
	 - Using id for styles will be considered as a mistake, **minus 5 points**

3. The logo should be implemented correctly. Don't forget to use *h1* tag on the page(**points - 0-5**);

4. Navigation should be implemented with a *nav* tag. Clickable parts of the menu should be *links*(**points - 0-5**);

5. Pay your attention to the fact that the background should be a graphic pattern, not just plain white(**points - 0-5**);

6. Fonts. You can find all the font for free (the links will be provided). The fonts should be imported properly. Don't forget about the font-weight, it also should be correct(**points - 0-10**);

7. Requirements for the blocks and columns:
	 - Consider the case with more text than in the markup - just add more text to the column and check if the position of the column or layout does not change (limitation by overflow)(**points - 0-10**)
	 - You should consider the case when one more column is added to menu section. This column should appear under the first one or in the center of the next line or hidden by overflow property. It should not break the layout by being positioned as a third visible element outside of parent's borders(**points - 0-5**);
	 - If you are going to use inline-block property, make sure that there is no free space between the elements(**points - 0-5**);

8. Images in *fine ingredients* section should be square or rectangle-shaped and should be styled with CSS (border, border-radius)(**points - 0-10**);

9. The form should be implemented with a *form* tag and with proper tags inside of it. Add basic browser validation for Email input field. Name, Email and Date fields should be required. Please ignore typo on one of template's input fields, you should fix it in your application(**points - 0-10**);

10. The footer should be placed at the bottom of the page, meaning that if all the content but the footer is deleted from the page, the footer will still be placed at the bottom(**points - 0-5**);

11.You should implement CSS style effects for the hover events(which effect to use is up to you - for example, the color of the navigation button can change on hover)(**points - 0-5**);

The header can be fixed on the gradient background when scrolling, but no additional points are added for this feature.

You may use any grid markup you want (e.g.: Flex or Grid). Font-awesome can be used for icons.

Pre-processors and post-processors are not necessary. In case if you decide to use these tools, the final file should still be in *.css* format. **Use of libraries such as Bootstrap is not allow**. The whole layout should be implemented by you. Fine for non-compliance - **40 points**.
