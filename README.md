HTML5 device mockups fork
====================

You can view the demo page of the fork here:
http://voodoocode.github.io/html5-device-mockups/Examples_w_iframes.html

Note: It is proven that some websites such as reddit won't allow being inserted into iframes from foreign domains,
so if some page can't be displayed, have a look into your dev tools console for an error such as:

    Refused to display 'http://www.somerestrictingpage.com/' in a frame because it set 'X-Frame-Options' to 'SAMEORIGIN'.

HTML5 device mockups
====================

You can view the demo page of all devices here: http://aarnis.com/pixelsign/demo.html

Use on...
* Your website / splash screen

For...
* Displaying photos
* Displaying screenshots of your app(s)
* Displaying reference works / illustrations
* Displaying a content rotator / slideshow
* Embedding a JavaScript app inside the device
* Embedding a YouTube video

Why?
* Looks cool
* Attracts customers
* Makes your site look professional
* Give people the idea that your app/site works on mobile
* Give the impression that your illustrations are meant for web/mobile
* Lots of screenshots in just one "device"

Features:
* Maintains the device's aspect ratio when scaled
* Perfectly aligned screen content containers
* Some devices have "home button" layer defined for possible click event bindings
* Lengthy gallery of different devices
* Multiple color schemes
* Multiple orientations
* Two separate ways for integrating the devices to your site

Integrating to your website:
----------------------------

*STEP 1)*

        Import either one of the provided CSS file to your project:

                Import "device-mockups/device-mockups.css"
                        - If you want to define the devices using CSS class names
                        - <link rel="stylesheet" type="text/css" href="device-mockups/device-mockups.css" />

                Import "device-mockups/device-mockups2.css"
                        - If you want to define the devices using HTML tag attributes
                        - <link rel="stylesheet" type="text/css" href="device-mockups/device-mockups2.css" />

*STEP 2)*

        Use the provided HTML generator to generate your devices source code:

                - Open in your browser: "Mockup Device Generator.html"

                - Select the device type

                - Select orientation
                        - Note: not all devices support multiple orientations

                - Select color
                        - Note: not all devices support multiple colors

                - Copy / paste the HTML to your projects HTML source code

*STEP 3)*

        If you want to use the CSS class name approach for defining the devices,
        simply remove the "data-..." tag attributes from the provided HTML code
        and copy the values of those tags in the CSS classes:

                <div class="device-mockup" data-device="iphone5" data-orientation="portrait" data-color="black">
                    <div class="device">
                        <div class="screen">
                            <!-- PUT CONTENTS HERE -->
                        </div>
                        <div class="button">
                            <!-- You can hook the "home button" to some JavaScript events or just remove it -->
                        </div>
                    </div>
                </div>

        Turns to:

                <div class="device-mockup iphone5 portrait black">
                    <div class="device">
                        <div class="screen">
                            <!-- PUT CONTENTS HERE -->
                        </div>
                        <div class="button">
                            <!-- You can hook the "home button" to some JavaScript events or just remove it -->
                        </div>
                    </div>
                </div>


Created by:
---

> Tomi Hiltunen
> * tomi@innovaniac.com
> * http://innovaniac.com


> Angelos Arnis
> * angelos.arnis@gmail.com
> * http://dribbble.com/pixelsign


Credits for the original graphical renderings of the devices
used in this package are found in a separate file which is
provided with this package.


Fork by:
---
> Sascha Lach
> mail@voodoocode.de
> http://voodoocode.de

Credits for the iframe resizing control panel go to http://www.reddit.com/user/lindymad

I added the device-pixel-ratio to respond to HiDPI/retina displays.
