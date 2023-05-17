# Step 1: Check the imports

The slick has to be imported before creating the slides.
Check the imports in styles.php and if its not here import this one:

wp_enqueue_script('slick-slider', get_template_directory_uri() . '/assets/libs/slick/slick/slick.min.js', ['jquery'], null, true);

Make sure that the path it's right.

# Step 2: Check the style import

Inside of the file my.scss check if there is a style for the slick if not import like this:

@import "../../assets/libs/slick/slick/slick.scss";

Make sure that the path it's right.

# Step 3: Previous sliders

To get the slider you can always check the old sliders in the previous projects to have a base of how to work with slick slider.

# Done

