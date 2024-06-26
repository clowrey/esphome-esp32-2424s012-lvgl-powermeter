This is based on the example found here: https://gist.github.com/clydebarrow/9d2cffd739cb844e9d6d5005fd29518d and created by https://gist.github.com/clydebarrow

The current LVGL dev code is here I believe https://github.com/clydebarrow/esphome/tree/75c5d5f19fe789053d47fa6874df0e03d5bf1015/esphome/components/lvgl

While this is still under active development it is best to reference a previous working commit like this:
```yaml
external_components:
  - source:
      type: git
      url: https://github.com/clydebarrow/esphome
      ref: fd15094c0860df23d532881df36cfd16c7da1091 #previous commit - wont be needed in the future
    components: [ lvgl ]
```

LVGL Docs: https://deploy-preview-3678--esphome.netlify.app/components/lvgl#lvgl-main

LVGL tips and tricks: https://deploy-preview-3678--esphome.netlify.app/cookbook/lvgl

Another example is here: https://gist.github.com/clydebarrow/3a3d7d48ee72c333d094e80ac43b8054

The most complete example from Clyde Barrow that I found a little later is here:
https://gist.github.com/clydebarrow/ef89e9a93bd44771483b9144ae9042a1

I am using a different LCD from his examples, the esp32-2424s012 ESP32C3 round 1.28" 240*240 IPS board with touchscreen

affiliate link to product:
[https://www.aliexpress.us/item/3256806114329043.html](https://s.click.aliexpress.com/e/_DeAb5Zz)

Disclaimer: my examples are by no means the best or right way to do things - I am still in the early stages of learning LVGL and specifically the ESPHome syntax for LVGL component

Sunton display general info https://github.com/rzeldent/platformio-espressif32-sunton 

![240x240lvgl](https://github.com/clowrey/esphome-esp32-2424s012-lvgl-powermeter/assets/6935928/72f1f324-b43b-4b48-8b11-d7b1c189d15d)


![esp32-2424s012_1 (Small)](https://github.com/clowrey/esphome-esp32-2424s012-lvgl-powermeter/assets/6935928/f7c1a190-99d1-4168-a0c7-906efd464e62)
![esp32-2424s012_2 (Small)](https://github.com/clowrey/esphome-esp32-2424s012-lvgl-powermeter/assets/6935928/6b1ba872-356d-426f-aa1e-d95ab732c966)
![esp32-2424s012_3 (Small)](https://github.com/clowrey/esphome-esp32-2424s012-lvgl-powermeter/assets/6935928/e51b7cd1-dc2e-46a3-a03a-f01a7e7d2377)



![esp32-2424s012-lvgl-2](https://github.com/clowrey/esphome-esp32-2424s012-lvgl-powermeter/assets/6935928/df1c8915-9a5c-425e-a78f-248a0b2734d7)

