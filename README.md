# Orbital Logic Synthesizer

The Orbital Logic Synthesizer is an interactive web application for designing and simplifying logic circuits with Karnaugh maps (K-maps). It provides an intuitive interface for entering boolean expressions or minterms, visualizing Karnaugh maps, obtaining simplified expressions, and viewing the corresponding gate-level schematic.

## Features
- **Dynamic Karnaugh Maps:** Generate 2-, 3-, or 4-variable K-maps with automatically grouped cells based on user inputs.
- **Expression Parsing:** Accept boolean expressions, minterm lists, or truth tables and convert them into simplified sum-of-products forms.
- **Gate Diagram Rendering:** Visualize the simplified logic as a digital circuit diagram drawn directly onto an HTML5 canvas.
- **Theme & UI:** Styled interface with responsive layout optimized for desktop and tablet viewports.

## Getting Started
1. Clone or download this repository.
2. Open `index.html` in any modern web browser.
3. Enter your desired number of variables, minterms, or boolean expressions using the controls at the top of the page.
4. Use the generated K-map and simplified outputs to design or verify your logic circuits.

No additional build steps or dependencies are required because the application is implemented entirely with static HTML, CSS, and JavaScript.

## Development Notes
- The project currently consists of a single HTML file that includes inline styles and scripts. Consider modularizing the codebase into separate CSS and JavaScript files as features grow.
- When modifying logic parsing or rendering routines, ensure that both the textual output and the gate diagram remain synchronized.
- Please document significant implementation details or project decisions in `AGENTS.md` so future agents can quickly regain context.

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests with feature enhancements, bug fixes, or documentation improvements. When contributing:
- Describe the motivation and testing steps in the pull request.
- Update the README or in-app documentation when introducing new features or workflows.
- Follow any project-wide guidance recorded in `AGENTS.md`.

## License
This project does not currently specify a license. If you plan to reuse or distribute the code, consider adding an appropriate open-source license file.
