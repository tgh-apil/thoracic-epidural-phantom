# APIL Normal Thoracic Spine Epidural Phantom

![thoracic spine epidural phantom](https://github.com/tgh-apil/thoracic-epidural-phantom/assets/84343976/28f1e0e3-7c0a-469f-a6b7-1dc5fc3b269d)

3D Printed thoracic epidural spine based on CT data. Our epidural spine phantom is encased in an synthetic, shelf-stable gel which has a realistic tactile feel to human muscle and is echogenic. We can augment the echogenic properties to be transparent (clear gel) or to mimic that of biological tissue (opaque) based on the learning objective. Additionally, the Thoracic Spine Epidural Phantom contains an echogenic faux-thecal sac to replicate loss-of resistance on puncture. The faux-thecal sac can be inflated with water to simulate spinal fluid.

This model was developed at the [Lynn & Arnold Irwin Advanced Perioperative Imaging Lab](https://apil.ca/), Toronto General Hospital, University Health Network.

# Purchasing Information

To purchase this phantom, please email apil@uhn.ca and a representative will be in touch with you with more details.

A purchased phantom contains the following:
1. Fully assembled Normal Thoracic Spine Phantom
2. Custom table clamp to hold phantom to table surface

# Ultrasound Images

Coming soon

# Care and Maintenance

1. Apply generous amount of ultrasound gel to surface of phantom.
2. Inflate thecal sac with water and ensure quickturn locks are closed

# Materials & Equipment
## Hardware

* 6 x M4 6mm screws
* 4 x M4 8mm screws
* 11 x M4 12mm screws
* 4 x M4 14mm screws (for use with lid)
* 4 x M4 20mm (for use with case bottom)
* 2 x Quick-turn Lock
* 8 mm ID Silicone Tubing (as low durometer as possible)
* 2 x Tube Fittings

## Printing Equipment

* Polylactic Acid (PLA)
* Bridge Nylon
* Fused Deposition Modelling 3D printer

## Casting Equipment

* Ballistics Gel
  * 50/50 mixture by weight of [20% ballistics gel from Clear Ballistics](https://www.clearballistics.com/shop/20-ballistic-gelatin-nato-block-16x6x6/) and [Gelatin #5 from Humimic Medical](https://humimic.com/product/gelatin-5-medical-gel-by-the-pound/)
  * [Gel dye from Humimic Medical](https://humimic.com/product-category/dye/) (optional)
* Graphite Powder (optional)
  * Used to replicate echogenic scatter of muscle
* Slowcooker
* Silicone Mold Release Agent
* Two-part Platinum Cure Silicone Rubber (or equivalent)
  * Available from [Smooth-On](https://www.smooth-on.com/products/mold-star-trade-31t/)
* Degas Chamber (optional)
* Heat Gun (optional)

# Assembly Instructions

## Printing

This repo includes stl files for each printed part.

In general, we use the following settings for all parts of this phantom:

|Material      |	Colour  |	Nozzle Temp (C) |	Bed Temp (C) |	Infill (%) |	Perimeters (#) |
| ------------ | ------- | --------------- | ------------ | ---------- | -------------- |
| PLA          |	White   |	210.0           |	60.0         |	10.0       |	2              |
| Bridge Nylon |	Natural |	250.0           |	80.0         |	15.0       |	3              |

## Silicone Mold Casting

![thoracic mold and insert](https://github.com/tgh-apil/thoracic-epidural-phantom/assets/84343976/61d41c00-9936-4f40-8599-097d292e11f2)
*Silicone mold (left), and insert with overhangs and tubing (right).*

1. Print all components in the directory */molds/* using the PLA printing settings outlined above.
2. Assemble outer mold parts 1 and 2 and together using:
   1. 6 x M4 6mm screws
3. Place inner mold parts 1 and 2 into the assembled outer parts and attach them using:
   1. 5 x M4 12mm screws (inner part 1)
   2. 6 x M4 12mm screws (inner part 2)
4. Spray the inside of the mold with a silicone mold release agent.
5. Mix 3700 g of silicone according to manufacturers instructions.
    - Degassing the silicone is optional but encouraged -- unless working with silicones with very short pot lives, such as Mold Star 31T.
    - Adding colourant to silicone is optional.
6. Pour all silicone into the assembled mold.
7. Allow silicone to cure according to manufacturer's instructions.
8. Carefully disassmble the mold and release the silicone.
    - NOTE: This step can be very difficult. Procede with caution and patience to avoid damaging the silicone shell.
9. Place the silicone mold into the two outer mold parts and screw the outer parts together with 4-6 M4 6mm screws. This will prevent the mold from deforming during the ballistics gel casting process.

## 3D-Printed Components

1. Print the thoracic spine (*/insert/thoracic spine insert.stl*) using the Bridge printing settings outlined above.
    - Ensure that there are **no/minimal supports in the spinal canal** where the thecal sac will pass through.
2. Print 2 insert overhangs (*/insert/insert overhang.stl*) using the PLA print settings outlined above.
3. Print all components in the directory */case/* using the PLA printing settings outlined above.
4. Carefully remove all supports from the parts when complete.

## Ballistics Gel Casting

1. **CAUTION:** Use appropriate heat-proof gloves when working with liquefied ballistic gel and/or heat gun.
2. **CAUTION:** work only in a very well ventilated area. A fumehood is highly recommended.

### Ballistics Gel Casting

#### Opaque Layer
If an opaque phantom is desired for use in ultrasound-guided epidural training, follow the steps below. If however the learning objective is to insert an epidural without the use of ultrasound, skip to the gel body section and use only clear gel.

1. Melt 95 g 20% gel, 95 g Humimic #5 gel, and 10 g of d in crockpot @ 105C - 115C (approx. 225F - 240F). This is **200 g** of gel total, i.e. **5% dye** by weight, however the percentage of dye can be adjusted to achieve a desired opacity.
2. Pour into mold, then tilt the mold in a circular motion, ensuring the dyed gel coats the entirety of the bottom of the mold. Once the gel begins to cool and is moving very slowly, set aside and allow to cool completely.

#### Gel Body

1. Melt at least 850 g 20% gel and 850 g Humimic #5 gel (a total of **1700 g**) in crockpot @ 105C - 115C (approx. 225F - 240F).
2. Thread roughly 30 cm of silicone tubing through the spine insert to replicate the thecal sac.
3. Attach the two overhang parts to the spine insert using 4 x M4 8mm screws. 
4. Use a heat gun to gently melt the top of the dyed gel (if applicable).
5. Pour in gel until it reaches the top of the mold.
6. Place the insert spine side down into the mold, ensuring the overhang components bracket the sides of the mold. Weigh down the insert to prevent air bubbles.
7. Allow gel to fully cool before removing from silicone mold.

## Phantom Assembly

1. Insert spine with gel block into printed case.
2. Thread both ends of silicone tubing through printed case.
3. Attach case bottom with 4 x M4 20mm screws.
4. Attach case lid with 4 x M4 14mm screws.
5. Attach a tube fitting to each end of the silicone tube.
6. Attach a quick-turn lock to each end of the tube fittings.
