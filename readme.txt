=== Tailor Page Builder ===
Contributors: andrew.worsfold
Donate link: http://gettailor.com/donate/
Tags: page, layout, builder, frontend, content, page builder, drag and drop builder, home page builder, landing page builder, layout builder, frontend builder, frontend editor, responsive, visual composer, beaver builder
Stable tag: 1.4.2
Requires at least: 4.3
Tested up to: 4.6
License: GPLv3 or later
License URI: http://www.gnu.org/licenses/gpl.html

Build beautiful layouts for your content faster and easier than ever before using your favourite theme!

== Description ==

[Tailor](http://gettailor.com/) is a free frontend page builder for WordPress that features a simple and intuitive drag and drop interface.  To get started:

- [Read the user documentation](support.gettailor.com/hc/en-us/categories/202586427).
- [View instructional videos on YouTube](https://www.youtube.com/channel/UCiFGt6qqPwN1ruuEnjlVOqA).
- [Give it a try in a sandbox](https://addendio.com/try-plugin/?slug=tailor).

= Easy to use =

- Add elements and create columns instantly in a single drag and drop movement.
- Copy elements anywhere on the page by dragging and holding the Shift key.
- Move content independently and have it adopt the style of its parent elements!
- Save one or more elements as templates, then drag and drop them onto any page.
- Change the appearance of any element using a set of carefully selected options.
- Undo and redo actions using the History panel (or keyboard shortcuts).
- Control global layout settings in the Customizer.
- Control page specific layout settings and add custom CSS and JavaScript.
- Preview your layouts on different device sizes and manage responsive behavior.

Because Tailor works with any theme, choosing one that you like is now the hardest part of creating a website.

= Easy to extend =

Tailor is open source and built based on WordPress' coding standards and best practices.  The plugin features:

- A comprehensive set of [actions](https://github.com/andrew-worsfold/tailor/blob/master/actions.md) and [filters](https://github.com/andrew-worsfold/tailor/blob/master/filters.md).
- An API for adding, changing or removing elements.
- An API for adding, changing or removing settings and controls.
- A [REST API](https://github.com/andrew-worsfold/tailor/blob/master/api.md) to manage elements, templates and models.

For more information:

- [Read the developer documentation](support.gettailor.com/hc/en-us/categories/202586427).
- Check out the free [Portfolio](https://wordpress.org/plugins/tailor-portfolio/) and [WooCommerce](https://wordpress.org/plugins/tailor-woocommerce/) extensions.
- Get involved in the [GitHub project](https://github.com/andrew-worsfold/tailor).

If you like the plugin, please consider [rating it](https://wordpress.org/support/view/plugin-reviews/tailor?rate=5#postform) or providing your feedback and suggestions through [Facebook](https://www.facebook.com/tailorwp/), [Twitter](https://twitter.com/tailorwp) or the [Community Forum](support.gettailor.com/hc/en-us/community/topics).

== Installation ==

Install Tailor via the plugin directory, or by uploading the files manually to your server.

= From your WordPress dashboard =

1. Visit 'Plugins > Add New’.

2. Search for ‘Tailor’.

3. Activate Tailor from your Plugins page.

= From WordPress.org =

1. Download Tailor.

2. Upload the ‘tailor’ directory to your '/wp-content/plugins/' directory, using your favorite method (ftp, sftp, scp, etc..)

3. Activate Tailor from your Plugins page.

= Once Activated =

Visit 'Settings > Tailor' to configure:

1. Allowable post types and user roles.

2. Element and feature settings.

3. Icon kits.

== Screenshots ==

1. **Adding elements** - Drag an element from the sidebar into the desired position on the page to add it.  Hold the Shift button while dragging an existing element to copy it.

2. **Editing elements** - Click and hold the Shift button to edit an element (or select it and click on the Edit button).

3. **Editing parent/ancestor elements** - Select a parent/ancestor element from the hierarchy dropdown menu and click on the Edit button to edit it.

4. **Adding columns** - Drag an element to the left or right of an existing element to create a row/column structure.  Drag it to the left or right of an existing column to add another column to that row.

5. **Adding templates** - Drag a saved template into the desired position on the page to add it.  The available dropzones will depend on the element(s) in the template.

6. **Custom CSS/JS** - Add custom CSS or JavaScript to the page from within Tailor using the editors provided on the Settings panel.

7. **Layout changes** - Make changes to the layout of the page from within the Settings panel.  To make site-wide changes, use the custom Tailor settings in the Customizer (page-level settings override those in the Customizer).

8. **Device preview** - Preview your page on desktop and mobile device sizes in exactly the same way that you do in the Customizer.

9. **Revision history** - View and restore history revision snapshots in a single click on the History panel.

== Frequently Asked Questions ==

= Can I use my existing WordPress theme? =

Yes! Tailor works out-of-the-box with nearly every WordPress theme.

= How do I get started? =

Navigate to the page that you would like to Tailor and simply select the "Tailor this Page" (or other allowable post type) option from the WordPress Admin Bar.

= Can I move Tailored pages to another WordPress site? =

Yes.  Tailored pages can be migrated like any other type of page using the [duplicator](https://wordpress.org/plugins/duplicator/) plugin.

= Can I include Tailor as part of my theme bundle? =

Yes, however, users should be directed to the WordPress plugin repository to install the latest version of the plugin.  Consider using a tool like [TGM Plugin Activation](http://tgmpluginactivation.com/) to guide users through the installation process.

== Changelog ==

= 1.4.2 =
* Improved: spacing above Posts pagination.
* Improved: initial position of Edit modal window.
* Fixed: Posts pagination not working on Front page.
* Fixed: Issue with custom element registration.

= 1.4.1 =
* Improved: style control (used for margin and padding settings by default).
* Added: special character button to editor tools.
* Added: post revision support for page settings.

= 1.4.0 =
* Added: REST API endpoints for elements, models and templates. Please refer to the associated upgrade notice.
* Added: parallax background images for sections.
* Added: background-attachment:fixed option ("fake parallax") for all elements with background images.
* Changed: post revisions are used to restore an earlier Tailor layouts or recover the original content.
* Changed: a dismissible notice is displayed on the Edit page of a Tailored post to advise of the effect of modifying content in the WordPress Editor.
* Changed: users that can modify options or edit the current post type can Tailor pages if they don't have a restricted role type.
* Changed: default Card background color to transparent.
* Improved: the Map element displays a notice when a Google Maps API key has not been added.
* Improved: order and grouping of settings on the Settings page.
* Improved: the handling of Customizer, custom and dynamic element CSS.
* Improved: posts in the Trash cannot be Tailored.
* Fixed: save button label indicates that the page will be published when Tailoring a draft post.
* Fixed: canvas errors are presented when the Jetpack Publicize module is active.
* Developer: added new PHP class for managing element models.
* Developer: added, changed and removed various [actions](https://github.com/andrew-worsfold/tailor/blob/master/actions.md) and [filters](https://github.com/andrew-worsfold/tailor/blob/master/filters.md) for consistency and to accommodate new REST API.
* Developer: code refactoring and general improvements.

= 1.3.7 =
* Improved: style for empty placeholder content.
* Improved: hover outline color for improved contrast on themes with grey backgrounds.
* Improved: various sidebar and canvas style tweaks.
* Fixed: section reordering.

= 1.3.6 =
* Added: additional actions for adding/modifying/removing custom CSS rules associated with existing elements.
* Fixed: minor color inconsistency between sidebar and preview screen during loading.

= 1.3.5 =
* Added: Jetpack Testimonials element.
* Added: actions for modifying default element settings and controls. [Learn more about this change](https://medium.com/p/c9efb5cb3016).
* Fixed: not displaying singular post type labels in the "Tailor this.." link.

= 1.3.4 =
* Added: Jetpack Portfolio element. [Learn more about this change](https://medium.com/p/f8a1ff571f21).
* Added: class for managing theme and plugin compatibility.
* Added: initialization hooks for the sidebar and canvas.
* Fixed: column width Customizer setting not working.
* Fixed: undefined variable warning in attachment partial template.

= 1.3.3 =
* Added: error message if the page canvas is not properly initialized.
* Fixed: clicking links within the canvas causes the page to be redirected.

= 1.3.2 =
* Fixed: debug error message is displayed when no admin setting description is provided.

= 1.3.1 =
* Added: descriptions to some admin settings.
* Added: minor improvements to RTL compatibility for sidebar and canvas.
* Changed: users with permission to manage options can Tailor pages.
* Fixed: inactive elements have hover effects and trigger notifications.
* Removed: separate RTL stylesheet for sidebar (now included within main stylesheet).

= 1.3.0 =
* Added: image link control to Gallery element.
* Added: title attribute to history snapshots.
* Added: compatibility for NextGen gallery plugin.
* Added: compatibility for Thesis theme framework.
* Changed: button block style to be a style option instead of alignment option.
* Changed: Open Sans to system fonts.
* Improved: vertical spacing for various elements, including rows and columns.
* Improved: RTL compatibility for modals, notifications and carousels.
* Fixed: responsive settings for rows and grids are not being applied appropriately.
* Fixed: history snapshots are created when previewing changes to an element.
* Fixed: page title is not updated correctly.
* Developer: Cleaned up SCSS project.

= 1.2.8 =
* Added: check to ensure post archives and the posts page cannot be Tailored.

= 1.2.7 =
* Added: RTL support.

= 1.2.6 =
* Added: device-specific visibility setting to rows, columns, grids and grid items under General settings tab.
* Fixed: image and gallery controls are breaking when adding small images (credit: dtbaker).
* Improved: background image/color settings.

= 1.2.5 =
* Added: compatibility for the Yoast SEO plugin.

= 1.2.4 =
* Added: resource links to the admin settings page.
* Added: Google Maps API key setting.
* Improved: CSS to ensure pseudo-elements use double colon notation.

= 1.2.3 =
* Fixed: element drag-drop ghost images are disappearing when dragging on Chrome.

= 1.2.2 =
* Improved: display of the 'Tailor this ..' Admin Bar link.

= 1.2.1 =
* Removed: 'Tailor this ..' Admin Bar link from archive pages (credit: BinaryMoon).

= 1.2.0 =
* Changed: container behaviour so that they do not collapse when only one child element remains (excludes row/column layouts). [Learn more about this change](http://www.andrewworsfold.com/2016/06/26/working-with-containers/).
* Fixed: custom CSS is not appearing within template previews.
* Fixed: tabs break after a tab is renamed.

= 1.1.3 =
* Improved: device preview and media query settings to be in line with the WordPress Customizer (i.e., Desktop, Tablet and Mobile sizes).  [Learn more about this change](http://www.andrewworsfold.com/2016/06/25/device-previews/).

= 1.1.2 =
* Added: growl notification and UI styles to help instruct new users to drag elements and templates onto the page.

= 1.1.1 =
* Added: additional filters for developers to disable panels and elements.

= 1.1 =
* Added: admin options for hiding the CSS and JavaScript editors.
* Added: admin option for hiding the Attributes panel (contained within the Edit modal window).
* Improved: scripts and styles to only load on Tailored pages.
* Removed: dynamic text domain function.

= 1.0.1 =
* Added: fallback functions for PHP 5.4.x.

= 1.0.0 =
* Initial release.

== Upgrade Notice ==

= 1.4.0 =

This is a major version change which introduced new classes, actions and filters in order to accommodate a robust REST API.  Please review all direct function calls and hooks in your code.