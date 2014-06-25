# Lucid's Shopify Theme Settings.html Generator Theme&trade;

Are you still writing the `settings.html` file for your Shopify themes by hand?

Are you tired of maintaining *hugely complex* and *verbose* files, full of tables and other weird markup?

Are you getting copious amounts of merge conflicts generated by co-workers adding new settings?

Are you constantly thinking **"There must be a better way?!"**

### Well there is!!!

With Lucid's fantastical, new *and* improved "Shopify Theme Settings.html Generator Theme&trade;" you can get Shopify to generate all of your theme settings for you!

## How does it work?

1. Create a development store on Shopify.

2. Upload **Lucid's Shopify Theme Settings.html Generator Theme&trade;** to your development store.

3. Start generating theme `settings.html` files right away!

### How do I create a new theme setting?

Each theme setting is actually a product in your development store. Just add your settings name as the title of your product.

### What type of theme settings can I use?

We have a *massive* amount of theme settings for you to use. Just select the type of setting you want from the products type drop-down.<sup>1</sup>

Valid types are:

* Blog
* Checkbox
* Collection
* Color
* File
* Font
* Gif
* Jpeg
* Linklist
* Page
* Radio
* Select
* Slide
* Social
* Text
* Textarea

### My setting has multiple options?

Don't worry, we've got you covered! Just create a variant for each of the settings options. The theme generator will use the title of the variant and if you don't need it, just leave it as `Default Title`.

### What if I'm making multiple themes, do I need a new dev store?

Not at all! We use collections for grouping together settings for a theme. Add your settings to any collection like you would a normal product.<sup>2</sup> You can have as many collections as you need.

### How do I group my settings so as to create order and not overwhelm my users?

What a conscious theme developer you are. Create a vendor for your settings and they will all be grouped together under that title.

### Wait, won't all these settings be ordered alphabetically?

Yes, by default. But this can be easily changed!

You can order each setting within a group by prepending a number followed by a pipe:

    1|My magnificent theme setting
    
Your settings will now be ordered inside their group according to your numbers. Don't worry the generator knows to remove the prepended number from the generated settings.

**You can even order your settings groups!**

1. Create a navigation link-list named the same as your settings collection.

2. Create a link-list item for each of your vendor groups. It does not matter where they link too.

3. Reorder your groups within the link-list like a professional!

### Where do I find my generated settings file?

On the store front, of course! The stores index page lists each of your settings collections. Navigate into the desired collection and there is a text area all ready with your themes settings pre-generated.

The only thing left to do is to copy and paste this into your theme's `settings.html`.

### Will it cut through this old shoe?

Yes!<sup>3</sup>

#### Disclaimer:

The "Shopify Theme Settings.html Generator Theme&trade;" is only intended to be used by theme developers and is not a real store front theme.

<sup>1</sup> You may have to add these types to the type drop-down first.

<sup>2</sup> You will actually need to do this even if you only have one theme, otherwise it won't work.

<sup>3</sup> It won't actually cut through an old shoe.
