
**Bitcoin Price Fetcher**

This Python script fetches and displays the current Bitcoin price in different currencies (USD, GBP, EUR) from the CoinDesk API.

## Files Included in this Repository:

1. **app.py**: 
   - This is the main script that fetches Bitcoin prices in various currencies using the CoinDesk API.
   - It allows users to select whether they want to see the price in USD, GBP, or EUR.
   
2. **requirements.txt**: 
   - This file lists the required Python dependencies to run the project.

3. **README.md**: 
   - This file provides an overview of the project and instructions for setting it up.

## Features

- Fetches Bitcoin prices in USD, GBP, and EUR.
- Displays the current time when the price was last updated.
- Allows the user to select the currency for which they want to see the price.

## How It Works

1. The script makes an HTTP GET request to the CoinDesk API.
2. It retrieves the current Bitcoin price in the specified currency.
3. It prints the updated time, currency code, and Bitcoin rate to the console.

## Getting Started

### Prerequisites

To run this project, you need to have Python 3.x installed on your local machine.

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Th3LostOne/Assignment-3.git
   cd Assignment-3
   ```

2. **Create and activate a virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use: venv\Scripts\activate
   ```

3. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Run the application with:
   ```bash
   python app.py
   ```

2. The script will prompt you to choose the currency in which you'd like to see the Bitcoin price:
   - Type `1` for USD.
   - Type `2` for GBP.
   - Type `3` for EUR.

3. The current Bitcoin price will be displayed along with the time it was last updated.

## Example

After running the script, you will be prompted to select a currency. For example:

```
1. Show Bitcoin Price in USD.
2. Show Bitcoin Price in GBP.
3. Show Bitcoin Price in EUR.
Please Enter Your Choice: 1
```

Output:

```
Time: Oct 25, 2022 23:01:00 UTC
Currency: USD
Rate: 21,206.8859
```

## `requirements.txt`

The `requirements.txt` file contains the following dependencies:

```
certifi==2022.9.24
charset-normalizer==2.1.1
idna==3.4
requests==2.28.1
urllib3==1.26.12
```

### To install these dependencies, run:
```bash
pip install -r requirements.txt
```

## License

This project is licensed under the MIT License.

## Acknowledgments

This project was created as part of my learning experience with APIs and Python.
```

### Explanation of Files:
1. **app.py**: This file contains the core script you wrote to interact with the CoinDesk API and display the Bitcoin price in the selected currency.
2. **requirements.txt**: This file lists all the Python packages that need to be installed for the script to work, ensuring that anyone can replicate your environment by installing the dependencies.
3. **README.md**: The documentation for the project, explaining how to run it, install dependencies, and providing examples.
