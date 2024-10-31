## Requirements

- **Python 3.x**
- **Selenium Library**: Install via `pip`
- **Chrome WebDriver**# ![Neon Banner](./banner.png)

# Traffic Simulator

This project simulates website traffic using Selenium to help test website analytics. Follow these steps to configure and run the script.

## Requirements

- **Python 3.x**
- **Selenium Library**: Install via `pip`
- **Chrome WebDriver** (auto-installed with `webdriver_manager`)

## Quick Start Guide

1. **Clone the Repository**:
   - Open a terminal and run:
     ```bash
     git clone https://github.com/yourusername/traffic-simulator.git
     cd traffic-simulator
     ```

2. **Install Dependencies**:
   - Run the following command to install required libraries:
     ```bash
     pip install -r requirements.txt
     ```

3. **Configure Settings**:
   - Open the `config.json` file in the root directory and set:
     - `"TARGET_URL"`: The URL of the website to simulate traffic for.
     - `"NUMBER_OF_VISITS"`: Number of visits to simulate.
     - `"VISIT_DURATION"`: Duration (in seconds) for each visit.

4. **Run the Script**:
   - Execute the script using:
     ```bash
     python simulate_traffic.py
     ```

5. **View the Simulation**:
   - The script runs in headless mode by default. You’ll see output in the terminal indicating each visit and pause.

### Configuration Example (`config.json`)

Here’s an example `config.json`:

```json
{
    "TARGET_URL": "https://yourwebsite.com",
    "NUMBER_OF_VISITS": 10,
    "VISIT_DURATION": 10
}
 (auto-installed with `webdriver_manager`)
