# Vertiq All-In-One Motor/ESC Modules

Vertiq makes high performance propulsion systems for commercial and defense UAS. The core design consists of a lightweight, tightly integrated motor and ESC with an embedded position sensor. With closed loop velocity control for the fastest response times available, class leading efficiency, no startup and reverse jitter allowing low speed control and smooth reversibility, and a built in “stow” controller for smoothly placing idle propellers in a preferred direction, Vertiq’s modules experience significant advantages over other ESCs.

![Vertiq Module Lineup](../../assets/peripherals/esc_vertiq/vertiq_esc_lineup.jpg)

All Vertiq modules support traditional [PWM input, DShot, OneShot, and Multishot communication protocols](https://iqmotion.readthedocs.io/en/latest/manual/manual_hobby.html). Vertiq’s larger modules also support [DroneCAN control](https://iqmotion.readthedocs.io/en/latest/manual/manual_dronecan.html).

## Where to Buy

Purchasing information can be found on the [Vertiq website](https://www.vertiq.co/).


## Hardware Setup
### Wiring

Connecting your Vertiq module to a PWM output from your flight controller or DroneCAN bus will vary depending on your model. Please see the product data sheets for wiring information. All Vertiq datasheets can be found at [vertiq.co](https://www.vertiq.co/). 

## Firmware Setup

The best tool to configure your Vertiq module is Vertiq’s IQ Control Center application. You can find instructions for installation [here](https://iqmotion.readthedocs.io/en/latest/tutorials/testing_with_control_center.html).

To get started with traditional PWM input or DShot with your flight controller, please see [PWM and DSHOT Control with a Flight Controller](https://iqmotion.readthedocs.io/en/latest/tutorials/pwm_control_flight_controller.html).

To get started with DroneCAN with your flight controller, please see [DroneCAN Integration with a PX4 Flight Controller](https://iqmotion.readthedocs.io/en/latest/tutorials/dronecan_px4_flight_controller.html).

## Flight Controller Setup

### Enable DroneCAN

If you are controlling your vehicle through DroneCAN, please refer to the instructions [here](https://iqmotion.readthedocs.io/en/latest/tutorials/dronecan_px4_flight_controller.html#flight-controller-configuration) to properly set up your flight controller. These instructions walk you through setting the correct parameters for enabling the flight controller’s DroneCAN drivers, setting the correct configuration parameters for communication with Vertiq modules on the DroneCAN bus, ESC configuration, and testing that your flight controller can properly control your modules over DroneCAN.

### PX4 Configuration

Vertiq provides in depth instructions for integrating your module with a flight controller through PWM and DSHOT found [here](https://iqmotion.readthedocs.io/en/latest/tutorials/pwm_control_flight_controller.html).

## Further Information

* To learn more about Vertiq modules, please visit our [website](https://www.vertiq.co/)
* For more information about configuring your Vertiq module, please refer to our [Read-The-Docs](https://iqmotion.readthedocs.io/en/latest/index.html)
