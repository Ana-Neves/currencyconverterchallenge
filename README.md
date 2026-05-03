# Currency Converter CLI 🌍💰

## 📌 Pitch & Architecture
The **Currency Converter CLI** is a lightweight, command-line interface application built in Java that provides real-time currency exchange rates. 

Designed to demonstrate core backend principles, this application integrates seamlessly with the RESTful **ExchangeRate-API**, handling HTTP requests and deserializing complex JSON responses to deliver accurate financial data. It highlights strong foundational logic, API consumption, and an interactive console-based user experience.

## 🛠️ Tech Stack
* **Language:** Java
* **Libraries:** Gson (Google JSON Library for Serialization/Deserialization)
* **External Integration:** RESTful API (ExchangeRate-API)
* **Interface:** Command Line Interface (CLI)

## 🚀 Key Features
* **Real-Time Data Consumption:** Establishes secure HTTP connections to fetch live exchange rates.
* **JSON Parsing:** Utilizes the Gson library to map JSON payloads into Java Objects dynamically.
* **Interactive CLI Menu:** Offers a robust, error-handled console menu for seamless user interaction.
* **Precision Engine:** Accurately calculates bidirectional conversions between USD (🇺🇸), BRL (🇧🇷), and EUR (🇪🇺).

## 👩‍💻 Technical Highlights
*(Como este é um projeto focado na sua lógica individual, esta seção destaca o seu domínio sobre o código)*
* **API Integration:** Engineered the HTTP client logic to request and process real-time financial data efficiently.
* **Data Serialization:** Utilized Gson to parse and extract specific currency rates from nested JSON structures, demonstrating clear data manipulation skills.
* **Clean Code Practices:** Maintained strict separation of concerns between the API consumption logic and the CLI presentation layer, ensuring maintainability.

## ⚙️ How to Run Locally

### Prerequisites
* Java Development Kit (JDK) 11 or higher
* [Gson Library](https://github.com/google/gson) (included in your build path)
* An API Key from [ExchangeRate-API](https://www.exchangerate-api.com)

### Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Ana-Neves/currency-converter.git](https://github.com/Ana-Neves/currency-converter.git)
   cd currency-converter

   Configure the API Key:

2. **Configure the API Key:**

Open the CurrencyConverter.java file.

Locate the API constant and replace YOUR-API-KEY with your generated key.

2. **Compile the application:**
(Ensure Gson is in your classpath. Example below assumes Gson is in the same directory)

Bash
javac -cp .:gson-x.x.x.jar CurrencyConverter.java

2. **Run the application:**

Bash
java -cp .:gson-x.x.x.jar CurrencyConverter


## 📝 License
This project is licensed under the MIT License.


***
