# Ecergodox
The Ecergodox is a reconfiguration of the Redox to use upgraded parts and usb
type c connections

## Bill of materials
- [x] Swtiches
    - Type: Cherry MX Brown
    - Qty: 70
    - Link: [mechanicalkeyboards.com](https://mechanicalkeyboards.com/shop/index.php?l=product_detail&p=1036)
    - Purpose: Key switches
- [x] PCB
    - Type: Redox
    - Qty: 2 (1 for left-hand, 1 for right-hand)
    - Link: [falba.tech](https://falba.tech/product/redox-pcb-electrical-boards-set-of-2/)
    - Purpose: Circuit board to hold and wire components together
- [x] Cherry mx keycap
    - Type: DSA profile
    - Qty: 54 x 1u, 10 x 1.25u, 6 x 1.5u
    - Link [falba.tech](https://falba.tech/product/dsa-keycaps-printed-left-right-keyboards-redox/)
    - Purpose: Keycaps
- [x] Diodes
    - Type: 1N4148
    - Qty: 70
    - Link: [amazon.com](https://www.amazon.com/McIgIcM-1n4148-switching-Standard-Through/dp/B06XB1R2NK/ref=sr_1_1_sspa?crid=2MDTB9G1MR030&keywords=1N4148+diode&qid=1558984194&s=gateway&sprefix=spide%2Caps%2C258&sr=8-1-spons&psc=1&smid=ATHZ0BI0D2RLH)
    - Purpose: Acts as a "check valve" to make sure electricity only flow one
    direction. This is needed for the key matrix ([more info](http://www.jasonamyers.com/2015/building-a-keyboard-part-2/))
- [x] Resistors
    - Type: 4.7kOhm
    - Qty: 2
    - Link: [amzon.com](https://www.amazon.com/gp/product/B072BL2VX1/ref=ox_sc_act_title_1?smid=A2WWHQ25ENKVJ1&psc=1) **Note: This
    link is to a kit with many types of resistors. You only need 2 4.7kOhm resistors
    - Purpose: Something to do with flashing new firmware. They will ne soldered
    to only one pcb (one half of the keyboard)
- [x] Through hole momentary switch
    - Type: 6mm lenght x 6mm width x 4.3mm height
    - Qty: 2
    - Link: [amazon.com](https://www.amazon.com/6x6x4-3mm-Momentary-Tactile-Button-Through/dp/B00EDJYK46/ref=sr_1_6?keywords=momentary+switch+6+x+6+x+4.3&qid=1558984023&refinements=p_85%3A2470955011&rnid=2470954011&rps=1&s=gateway&sr=8-6)
    - Purpose: Factory reset button
- [x] usb-a to usb-c cable
    - Type: Male to male, 6 feet
    - Qty: 1
    - Link [amazon.com](https://www.amazon.com/AmazonBasics-Type-C-USB-Male-Cable/dp/B01GGKYN0A)
    - Purpose: Connect keyboard to computer
- [x] TRRS cable
    - Type: 3 feet (you can probably use a shorter one)
    - Qty: 1
    - Link [keeb.io](https://keeb.io/products/trrs-cable?variant=7049325936670)
    - Purpose: Connect right-hand and lef-hand side of keyboard together
- [x] TRRS connectors
    - Type: PJ-320A 4 poles 3.5 mm
    - Qty: 2
    - Link: [keeb.io](https://keeb.io/products/trrs-jacks-3-5mm-one-pair)
    - Purpose: Femal connection port to connect the spearate havles of the keyboard
- [x] Arduino Pro-micro compatible board
    - Type: 5v/16MHz, usb-micro
    - Qty: 1
    - Link: [keeb.io](https://keeb.io/products/pro-micro-5v-16mhz-arduino-compatible-atmega32u4)
    - Purpose: This is a cheap mcu with a usb-micro interface. It will 
    be on the slave half (left-hand side) of the keyboard
- [x] Arduino Pro-micro compatible board
    - Type: 5v/16Mhz, usb-c
    - Qty: 1
    - Link: [keeb.io](https://keeb.io/products/elite-c-usb-c-pro-micro-replacement-arduino-compatible-atmega32u4)
    - Purpose: This is a more expensive  mcu with a usb-c interface. It will
    be on the master half (righ-hand side) of the keyboard
- [ ] Case
    - Type: Custom built, 3D printed
    - Qty: 1
    - Link: [github.com/mattdibi](https://github.com/mattdibi/redox-keyboard/tree/master/redox/case) **Note: I went to the library and used their 3D printer to print
    for free
    - Purpose: Encase the keyboard