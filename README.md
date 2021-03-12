# nrf52-ble
Collect ADC data through uart ble app 

modify the main.c in sdk_v16\examples\ble_peripheral\ble_app_uart add these nrf_driver files: 

D:\sdk_v16\integration\nrfx\legacy\nrf_drv_ppi.c
D:\sdk_v16\integration\nrfx\legacy\nrf_drv_saadc.h
D:\sdk_v16\integration\nrfx\legacy\nrf_drv_timer.h
D:\sdk_v16\modules\nrfx\drivers\src\nrfx_saadc.c

Make sure in sdk_config.h #define SAADC_ENABLED 1

![image](https://user-images.githubusercontent.com/51981087/110908578-9cb2ab80-8341-11eb-979b-8d95005f699c.png)



To sprintf the float value, check this


![image](https://user-images.githubusercontent.com/51981087/110908835-f5824400-8341-11eb-8870-05fb17cd6975.png)

                           
                            
