# nanoleaf_build_notes

First, you'll want to figure out your layout to know what pieces you want to print for the covers since they have holes on 1, 2 or 3 sides.  The holes are where the leafs sit against eachother and wire passes through.  Also figure out if you want all white leafs or to print the sides of the leaf black or some other color.  We went with black on the sides and white faces for our leaf covers and white for the bases to help the light reflect.  We went with black on the sides of the leaf so the light didn't leak out.  That way, the leaf light is more defined on the wall. The leafs use 12 LEDs each.  At ten leafs, we were drawing around 1.7A at 5V.  We used a 3A 5V adapter to power it.  The Wemos D1 mini device has wifi and runs software with a web server so you can connect to it and change colors and light patterns.

This was our first build - https://www.thingiverse.com/make:738464

You can check out the other makes for inspiration - https://www.thingiverse.com/thing:3354082/makes

Stuff to print

Use the following files for your leaf fronts.  Quantities will depend on your layout as noted above.  You will slice these with a filament change to print the face white and then the rest black.<br>
Top_PLA_1_hole.stl<br>
Top_PLA_2_hole.stl<br>
Top_PLA_3_hole.stl<br>
https://www.thingiverse.com/thing:3354082/files

Next, you want to print the leaf bases and wiring box.  I used these files... I redesigned the original leaf for easier wiring and designed this new box:
https://www.thingiverse.com/thing:4058966. There is also the orignal version of the box on the main nano leaf replica page above with the wiring instructions.  That is an option too.

https://www.thingiverse.com/thing:4044306<br>
Print this alignment tool (you'll use it when mounting your leafs on the backboard).  I designed it while building our sets to help line up the leaf backs on the mounting board.  This helps ensure you have room to install your covers and no gaps remain between the leafs once installed.<br>

https://www.thingiverse.com/thing:4054698<br>
I designed this tool to score the ends of the wire jumpers at a given length so you can easily remove the ends of the wire jacket with the proper length for tinning and soldering.  There's a short video in there on how to use it.  Works awesome for any LED strip wiring needing soldering.<br>

Think that does it for items to print.

Bill of Materials<br>
Quantities in question will be determined by your specifc build requirements.<br>
Filament - I used PLA.  Has held up nicely.  The LEDs don't get hot so no worries on heat.<br>
(1) Roll White 1.75mm PLA<br>
(1) Roll Black 1.75mm PLA<br>
(1) Roll Silver 1.75mm PLA(you don't have to print the electronics box in silver but I found it blended in better and a roll of silver came with my printer)<br>
(?) 60 LED/meter LED Strip - IP30 non-waterproof(no rubberized cover) WS2812B addressable lights.  12 LEDs per leaf.<br>
(?) ft 22AWG 3 pin LED connection wire - https://www.amazon.com/BTF-LIGHTING-Electrical-Extension-Connection-Changing/dp/B07SKGTCWQ/<br>(?) 1/2" #6 wood screws<br>
1/2" plywood - size depends on layout<br>
(2) saw tooth picture hangers<br>
(1) Wemos D1 mini (like this - https://www.amazon.com/ACEIRMC-ESP8266-ESP-12F-Internet-Development/dp/B08FQYZX37/). Aliexpress is the cheapest if you have time to wait for the shipments. :)<br>
(1) DC power jack - https://www.aliexpress.com/item/32997902659.html?spm=a2g0s.9042311.0.0.3a744c4dW4lHVg<br>
(1) DC power adapter (5v @ 3A) - https://www.aliexpress.com/item/32911055744.html<br>
(1) utility razor (these are like (100) for $7 at Home Depot or Amazon last I checked) - links in the tool build link above<br>
(2) 10mm M3 screws<br>

I also used foil tape to tape down my wires crossing leafs else they case shadows when the leaf covers were on.

I thing I used 10mm M3 screws and nuts to connect the electronic box to the leaf.  I started with a metric hardware set like this: <br>https://www.amazon.com/dp/B08RS9467Q/. Then I started just ordering hardware from aliexpress by the ten count and it's not bad pricewise.

https://www.aliexpress.com/item/10000150053486.html

You can also buy nylock nuts and washers this same way.  I replenish my hardware drawers when needed.  Having all these small orders show up over time works out well to keep your builder supply stocked.  You can buy heat shrink in all different sizes on there too.  For like $15, you could get six different sizes and be stocked for a long time.

Tool suggestions...<br>
https://github.com/jurassic73/split89#my-tools<br>
https://github.com/jurassic73/split89#tool-suggestions

Programming the Wemos D1 mini... there's notes on the Thingiverse Nanoleaf Replica page and you use the Arduino IDE but I can help if you want to cut down on the time to program it.
