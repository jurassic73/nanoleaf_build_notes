# nanoleaf_build_notes

Figure out your layout to know what pieces you want to print for the covers since they have holes on 1, 2 or 3 sides.  The holes are where the leaves sit against eachother and wire passes through.  Also figure out if you want all white leafs or to print the sides of the leaf black or some other color.  We went with black and white for our leaf covers and white for the bases to help the light reflect.  We went with black on the sides so the light didn't leak out that way. The leafs use 12 LEDs each.  At ten leafs, we were drawing around 1.7A at 5V.  We used a 3A 5V adapter to power it.

This was our first build - https://www.thingiverse.com/make:738464

You can check out the other makes for inspiration - https://www.thingiverse.com/thing:3354082/makes

Stuff to print

Use the following files for your leaf fronts.  Quantities will depend on your layout.  You will slice these with a filament change to print the face white and then the rest black.
Top_PLA_1_hole.stl
Top_PLA_2_hole.stl
Top_PLA_3_hole.stl
https://www.thingiverse.com/thing:3354082/files

Next, you want to print the leaf bases and wiring box.  I used these files... I redesigned the original leaf for easier wiring and designed this new box:
https://www.thingiverse.com/thing:4058966

Also print this alignment tool (you'll use it when mounting your leaves on the backboard).  I designed it while building our sets to help line up the leaf backs on the mounting board(the nano leaf designer also added my file to his link above).  This helps ensure you have room to install your covers and no gaps between the leafs once installed.
https://www.thingiverse.com/thing:4044306

I designed this tool to score the ends of the wire jumpers at a given length so you can easily remove the ends of the wire jacket with the proper length for soldering.  There's a short video in there on how to use it.  Works awesome for any LED strip wiring needing soldering.
https://www.thingiverse.com/thing:4054698

Think that does it for items to print.

Bill of Materials
Filament - I used PLA.  Has held up nicely.  The LEDs don't get hot so no worries on heat.

(1) Roll White 1.75mm PLA
(1) Roll Black 1.75mm PLA
(1) Roll Silver 1.75mm PLA(you don't have to print the electronics box in silver but I found it blended in better and a roll of silver came with my printer)
(?) 1/2" #6 wood screws
1/2 plywood
(2) saw tooth picture hangers
(1) Wemos D1 mini (like this - https://www.amazon.com/ACEIRMC-ESP8266-ESP-12F-Internet-Development/dp/B08FQYZX37/). Aliexpress is the cheapest if you have time to wait for the shipments. :)
(1) DC power jack - https://www.aliexpress.com/item/32997902659.html?spm=a2g0s.9042311.0.0.3a744c4dW4lHVg
(1) DC power adapter (5v @ 3A) - https://www.aliexpress.com/item/32911055744.html
(1) utility razor (these are like (100) for $7 at Home Depot or Amazon last I checked) - links in the tool build link above
(2) 10mm M3 screws
(?) 60 LED/meter LED Strip - IP30 non-waterproof(no rubberized cover) WS2812B addressable lights.  12 LEDs per leaf.

I thing I used 10mm M3 screws and nuts to connect the electronic box to the leaf.  I started with a metric hardware set like this: https://www.amazon.com/dp/B08RS9467Q/. Then I started just ordering hardware from aliexpress by the ten count and it's not bad pricewise.

https://www.aliexpress.com/item/10000150053486.html

You can also buy nylock nuts and washers this same way.  I replenish my hardware drawers when needed.  Having all these small orders show up over time works out well to keep your builder supply stocked.  You can buy heat shrink in all different sizes on there too.  For like $15, you could get six different sizes and be stocked for a long time.

Tool suggestions...
https://github.com/jurassic73/split89#my-tools
https://github.com/jurassic73/split89#tool-suggestions
