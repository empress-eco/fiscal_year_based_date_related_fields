<a href="https://grow.empress.eco/">Explore the Docs</a>
·
<a href="https://github.com/empress-eco/fiscal_year_based_date_related_fields/issues">Report Bug</a>
·
<a href="https://github.com/empress-eco/fiscal_year_based_date_related_fields/issues">Request Feature</a>

## About The Project

### 📖 Project Overview
The Empress Fiscal Year Based Date Field Validator is an indispensable tool for Empress users who manually input historical data. This plugin ensures that date-related fields align with the start and end dates of your default fiscal year, protecting you from mistakenly inputting data into incorrect periods.

### 🌟 Key Features
- Guarantees accuracy in data entry 
- Simplifies the process of historical data input
- Supports Date, Datetime, and Date Range fields

### 👥 Target Audience
This project is ideal for Empress users, data entry clerks, and finance professionals who manage historical data.

### 🛠 Built With
This project is a plugin for Empress and utilizes the Framework.

## Technical Stack and Setup Instructions

### Prerequisites
Ensure you have the following versions or higher:
- Empress >= v13.0.0
- Empress >= v13.0.0

### Installation
Follow these simplified steps to install the plugin:

1. Navigate to the bench directory:
```sh
cd ~/Empress-bench
```
2. Clone the plugin from Github:
```sh
bench get-app https://github.com/empress-eco/fiscal_year_based_date_related_fields.git
```
3. Build the plugin:
```sh
bench build --apps Empress_fiscal_year_based_date_related_fields
```
4. Install the plugin on your desired site (replace [sitename] with your site's name):
```sh
bench --site [sitename] install-app Empress_fiscal_year_based_date_related_fields
```

## Usage
To align date-related fields with the default Fiscal Year, navigate to Customization > Customize Form. Enter the form type/name (e.g., 'Journal Entry'), scroll down to the form fields area and edit the desired date-related fields. Add **Fiscal Year** in the **options** property of those fields to enable the plugin.

## Contribution Guidelines
We warmly welcome and appreciate contributions! Here's how you can contribute:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License and Acknowledgements

### License
This project is under the MIT License. Your contributions are also licensed under the MIT License.

### Acknowledgements
We extend our profound gratitude to the Empress Community for their foundational work, innovation, and ongoing support that power this project. Your dedication is instrumental in enhancing our functionalities and driving our success. Thank you!