# Journey Around the World

In this project, you will use the knowledge you gained on color theory
and apply it to a simple web page. You will take an existing grayscale
website, select a color scheme, and apply the colors to various elements
and sections within the design.

This means you will need to consider how to select your color scheme,
adhere to proper contrast of elements, and carefully apply those colors
to the page to create an elegant design.

Remember, it’s important to use the color wheel tool to determine your
color scheme and properly pair colors together. When applying colors to
the page, make sure you select a dominant color with additional
supporting colors that provide structure to the design.

When changing the colors within your code, you can use either
hexadecimal, RGB, or HSL values.

You can view <a
href="https://content.codecademy.com/programs/ui-design/journey_around_the_world/color-theory-onplatform.jpg?_gl=1*5nazhi*_ga*NjM4NDk1MTE3OS4xNjgzODkzNzEy*_ga_3LRZM6TM9L*MTY4Mzg5NzE5NS4yLjEuMTY4Mzg5OTI3NC41OS4wLjA."
class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0"
target="_blank" rel="noopener">an example here</a> we’ve created which
uses a monochromatic color scheme.

If you get stuck during this project or would like to see an experienced
developer work through it, click “**Get Unstuck**“ to see a **project
walkthrough video**.

[HTML CSS Journey Around the World](https://www.youtube.com/watch?v=siPJf98Rp4w)

1.

Before you begin to add colors to the site, you must first choose a
color scheme to follow.

As we reviewed in the lesson, there are multiple color schemes to select
from:

-   Monochromatic,
-   Complementary
-   Analogous
-   Triadic

You’ll need to determine your scheme and select a dominant color
followed by supporting colors to accent your page design.

You can use <a href="https://color.adobe.com/"
class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0"
target="_blank" rel="noopener">Adobe Color CC</a> to help generate color
schemes if you want help with inspiration.

2.

Once you determine your color scheme, it’s important to update the color
of the text across the page to ensure the contrast is well defined.

Remember to use colors opposite of each other when setting your text
color. If you have a darker background color, use light-colored text.
And vice versa.




3.

Using your dominant color from your selected scheme, find and replace
the background color of the `.photo-hero` class.

Applying this color should help in determining the hierarchy and a focal
point for the user when they land on your page.




4.

Next, we want to apply some color contrast within the type of the hero
section of the website. Doing so will help emphasize one single word and
add a small hint of color.

You can do so by replacing the text color of the `span` nested in the
main `<h1>` tag with the accent color you’ve selected.




5.

To help the user navigate through the web page, you can add some
separation between sections by applying color backgrounds.

To do this, change the background color of the `blockquote` section to
that of the accent color you’ve selected or one of your other supporting
colors.

Keep in mind the contrast of the type when applying this background
color to ensure the text is legible.




6.

Within the `blockquote` section of your website, let’s update the
citation of the testimonial so the text color isn’t as monotonous.

Find and replace the color of the `<footer>` text within this section
with a tint of your accent color. This will ensure the text is legible
while providing some contrast between the quote color and the background
itself.




7.

Right now, our page is coming together. However, the `.photo-about`
section feels a little bland. While we don’t want to apply a background
color as to not overwhelm the user with too many colors in sections, we
can add some subtle changes to the text to help improve the overall
design.

One of the easiest ways to do this is by changing the color of the
`<h2>` tag to another color within your color scheme.

Choose a color from your palette and apply it to this element.




8.

As you’ve noticed, we developed a pattern for our section backgrounds.
Now that we’ve reached the `.photo-contact` section, it’s time to apply
another background color.

The section above it is white, so this should use one of the colors
within your color scheme. Update the background color to one of your
colors defined in the color scheme to test and determine if it flows
nicely in the design.




9.

Our contact section is taking shape now. However, we need to make sure
users understand how to use and fill out the form elements within the
page.

The `<input>` and `<textarea>` backgrounds can either be white or a
darker shade of the background color to ensure the user knows they can
select and input their information.

If you select white as the background color, you will also need to
update the color of the text to ensure it is legible as the user begins
to fill out the form.

Be sure to apply the same background color to both the `<input>` and
`<textarea>` elements to keep all form elements consistent.




10.

Now our site is looking great!

The last part of our website that needs updating is the `<footer>`.

We should provide a solid foundation for the bottom of the site, and we
can do so by updating the background color while ensuring the color of
the type appears readable.


``` css
footer {
  background-color: /*Choose a color within your color scheme */
}
```