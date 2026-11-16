# Solar & UPS Calculator

A free calculator that sizes a solar and battery backup system. List your appliances, then get the battery capacity, solar panels, inverter, charge controller, DC breaker, and cable you need.

## Use it now

**[Open the calculator](https://kenweill.github.io/solar-ups-calculator/)**

https://kenweill.github.io/solar-ups-calculator/

No sign-up, no install, and no tracking. It works in any browser on a phone, tablet, or computer.

## How to use it

1. Add your appliances. Tap a quick-add button such as LED bulb, Electric fan, or Refrigerator, or add your own with its watts, quantity, and hours per day.
2. Tick **Motor** for fridges, fans, pumps, and aircon. They draw extra power when they start, and the inverter size accounts for it.
3. Set your system: battery voltage (12V, 24V, or 48V), battery type, days without sun, sun hours, panel wattage, and efficiency. The defaults suit most setups.
4. Read the results on the right (or below on a phone).

## What it calculates

- Daily energy use (kWh) from your appliance list
- Battery size in Ah for LiFePO4 or lead-acid
- Number of solar panels, based on sun hours and system losses
- Inverter size, including extra power for motor start-up
- MPPT charge controller current, DC breaker, and DC cable size
- How long a battery you already own will run your load

## Features

- Quick-add presets for common appliances
- Your list is saved in your browser, so it is still there next time
- Print-friendly
- One HTML file, no build step

## Run locally

1. Clone the repository:
   ```
   git clone https://github.com/kenweill/solar-ups-calculator.git
   ```
2. Open `index.html` in any browser.

## Disclaimer

Results are planning estimates only. Have a qualified electrician check the final design, especially DC wiring, fuses, and breakers.

## License

[MIT License](LICENSE)
