# Currency-Conversion-using-API

In this project, I utilized the Requests and Sys libraries in Python to fetch currency data from a website and perform currency conversion. The aim was to provide accurate currency conversion rates based on the specific date, allowing users to convert currencies according to their respective values at that time.

The project involved the following steps:

1. Retrieving Currency Data: I used the Requests library to send an HTTP request to a website that provides currency data. By accessing the relevant API endpoint, I fetched the necessary information, such as exchange rates for different currencies, historical currency data, and other related details.

2. Handling User Input: The Sys library was utilized to accept user input for the currency conversion. Users were prompted to provide the amount to convert, the source currency, the target currency, and the date for which the conversion should be performed.

3. Parsing and Processing Data: The fetched currency data was parsed and processed to extract the required information. The relevant exchange rates were extracted based on the provided date, and the conversion calculation was performed accordingly.

4. Performing Currency Conversion: Using the extracted exchange rates, the currency conversion was executed based on the user's input. The source currency amount was multiplied by the appropriate exchange rate to obtain the converted amount in the target currency.

5. Displaying Results: The final converted amount, along with the corresponding source and target currencies, was displayed to the user. Additionally, the specific date was also presented to indicate that the conversion was performed based on the currency values at that particular time.

By leveraging the Requests and Sys libraries, this project facilitated the retrieval of accurate currency data from a website and enabled users to perform currency conversions with historical context. The provided date ensured that the conversions were reflective of the currency values at the specified time, resulting in more precise and relevant results for users' currency conversion needs.
