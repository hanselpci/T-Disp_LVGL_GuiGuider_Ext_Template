# ESP32 TTGO-TDisplay LVGL Gui Guider Template

Hello world base project for TTGO-TDisplay board using LVGL and GuiGuider.
lvgl and lvgl_esp32_drivers is in external path.

Example Hello World

- [TTGO TDisplay Github](https://github.com/Xinyuan-LilyGO/TTGO-T-Display)
- [Product page](http://www.lilygo.cn/prod_view.aspx?TypeId=50033)
- [LVGL Core](https://github.com/lvgl/lvgl)
- [LVGL Drivers](https://github.com/lvgl/lvgl_esp32_drivers)
- [LVGL Example Repo](https://github.com/lvgl/lv_port_esp32)

## Usage

Clone and checkout submodules.

```
git clone  https://github.com/szhansel/T-Disp_LVGL_GuiGuider_Ext_Template.git
git clone https://github.com/lvgl/lvgl.git
git clone https://github.com/lvgl/lvgl_esp32_drivers.git
```
Set environment variable IDF_EXTRA_COMPONENT_DIRS to the parent location of lvgl and lvgl_esp32_drivers.
Please use '/' instead of '\' for Windows system in environment variable IDF_EXTRA_COMPONENT_DIRS.

Build and flash
```
idf.py build
idf.py -p PORT [-b BAUD] flash
```