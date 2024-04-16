# Balance Sheet Webpage

This project is a simple webpage that displays a balance sheet for a fictional company, AcmeWidgetCorp. The balance sheet includes data for the years 2021 to 2024 and is divided into three sections: Assets, Liabilities, and Equity.

## HTML Structure

The HTML file, `BalanceSheet.html`, is structured as follows:

- The `head` section includes meta tags for character encoding, description, and viewport settings. It also links to the external CSS file, `styles.css`, and sets the title of the webpage.

- The `body` contains a `main` element, which includes a `section` for the balance sheet.

- The balance sheet section includes a `h1` heading and three `table` elements for the Assets, Liabilities, and Equity sections of the balance sheet. Each table includes a `caption`, `thead` for the header row, and `tbody` for the data rows.

- The `tr` elements with the class `data` represent the data rows, and those with the class `total` represent the total rows.

## CSS Styling

The CSS file, `styles.css`, provides the styling for the webpage. Here are some key points:

- The `html` selector sets the `box-sizing` property to `border-box`, which includes padding and border in the element's total width and height.

- The `body` selector sets the font family and color for the webpage.

- The `span[class~='sr-only']` selector hides elements that are only for screen readers.

- The `table` selector sets the table to take up 100% of the width of its parent element and removes any borders.

- The `tr[class='total']` and `tr[class='data']` selectors style the total and data rows of the tables, respectively.

- The `tr.data td` and `tr.data th` selectors style the data cells and headers in the data rows.

Please note that the CSS file uses a combination of element, class, and attribute selectors to target specific elements for styling.

## Viewing the Webpage

To view the webpage, open the `BalanceSheet.html` file in a web browser. The CSS file should be in the same directory as the HTML file for the styles to be applied.

## Contributing

Contributions are welcome. Please open an issue to discuss your ideas before making changes.

## License

This project is licensed under the terms of the MIT license.