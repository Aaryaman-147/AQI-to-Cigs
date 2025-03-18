# AQI to Cigarette Equivalent Calculator
This simple tool calculates the number of cigarettes smoked equivalent to your exposure to the Air Quality Index over a given duration, providing insight into the health risk comparable to smoking.

## Features

- Calculates the equivalent number of cigarettes smoked based on the exposure time
- User Friendly UI
- Shows AQI classification (Good, Moderate, Unhealthy, etc.)

## AQI Categories

- **Good (0-50) 🟢**: Air quality is considered acceptable, with little to no risk to public health.
- **Satisfactory (51-100) 🟡**: Air quality is acceptable, but sensitive individuals might experience mild discomfort.
- **Moderate (101-200) 🟠**: Air quality is considered unhealthy for sensitive groups, such as children, the elderly, and people with respiratory or heart conditions.
- **Unhealthy (201-300) 🟣**: Air quality is considered unhealthy, and all individuals may experience health effects.
- **Hazardous (301 +) ⚫**: Air quality is considered hazardous, and all individuals may experience serious health effects.

## How it Works

- The tool takes the AQI value and exposure duration as inputs.
- It then converts AQI to PM2.5 concentration using the EPA formula.
- This tool estimates the cigarette equivalent of air pollution based on the assumption that 22 µg/m³ of PM2.5 exposure over 24 hours equals smoking one cigarette.
- Finally, it shows the AQI category based on the output.

## How to Use

- Enter the AQI value in the given input box.
- Input the number of hours exposed.
- Click the "Calculate" button.

## Contributing

You can fork this repository and contribute by submitting pull requests. Contributions and feedback are welcome—especially from experienced professionals.

## License

This project is open source and available under the [MIT License](https://github.com/Aaryaman-147/aqi-cigarette-calculator/blob/main/LICENSE)

## Acknowledgements

- Inspired by [Jasminedevv's Calculator](https://jasminedevv.github.io/AQI2cigarettes)
- Uses the EPA’s formula to convert AQI to PM2.5 concentration.

## Contact

For any reach questions or feedback, you can reach out to me on [Github](https://github.com/Aaryaman-147)
