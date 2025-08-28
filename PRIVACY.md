Privacy Policy for “Inventory” GPT

Last updated: 28 Aug 2025

1. Who we are

This privacy notice applies to the custom GPT named “Inventory” that you have built using OpenAI’s GPT Builder. The GPT retrieves sale‑price information from a Google Sheets document via a Google Apps Script. It is operated by the GitHub user youservemeonline‑ops
.

If you have any questions about this policy, please open an issue on this repository or contact us via GitHub.

2. What data we collect

When you interact with the Inventory GPT, it receives:

The text of your query (e.g., the product name you are asking about).

The GPT forwards that product name to a Google Apps Script endpoint hosted on Google’s servers. The endpoint looks up the item’s sale price in an “inventory” spreadsheet.

The GPT does not collect or process any personal data such as names, addresses or payment information. It does not modify your Google Sheet; it only reads sale‑price data.

3. How we use your data

We use the text of your query solely to:

Search the “inventory” Google Sheet for the product name.

Return the corresponding sale price to you.

No personal data is stored, logged or shared beyond what is necessary to fulfil your request. Query data may be processed by OpenAI and Google in accordance with their respective privacy policies (see OpenAI Privacy Policy
 and Google Privacy Policy
).

4. Data sharing

OpenAI processes your queries to generate responses.

Google hosts the Apps Script and the underlying Google Sheet.

We do not share your queries or the inventory data with any other third parties. We do not sell any data.

5. Data storage and retention

We do not store the product names you query or the sale prices returned. The data resides in your Google Sheet and is only accessed at the moment of your request.

6. Security

The Google Apps Script endpoint is hosted via HTTPS on Google’s servers. Access to the underlying Google Sheet is controlled by your Google account permissions. We recommend that you restrict editing rights on the sheet and keep your Apps Script deployment configured for “Anyone” (or “Anyone with a Google account”) only if necessary.

7. Changes to this policy

We may update this privacy notice from time to time. Updates will be posted to this GitHub repository with a new “last updated” date.

8. Contact us

If you have questions or concerns about this policy, please open an issue in this repository on GitHub: youservemeonline‑ops
