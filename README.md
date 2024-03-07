# Cryptocurrency Website 🌐💰

## Overview
The *Cryptocurrency Website* is a sleek and responsive website that provides real-time prices for popular cryptocurrencies such as Bitcoin, Ethereum, and Dogecoin. It features a clean design, market information, and a user-friendly interface.

![Cryptocurrency Website](./images/readme.png)

## Technologies Used 🚀
- **HTML**
- **CSS**
- **JavaScript**
- **jQuery**
- **CoinGecko API**

## Features 🌟
- Market navigation with links to explore various sections.
- Dynamic cryptocurrency prices fetched from CoinGecko API.
- Responsive design for both web and mobile devices.
- Call-to-action buttons for users to explore more.

## Usage 💻
1. Navigate through different sections using the top navigation links.
2. Explore real-time prices of Bitcoin, Ethereum, and Dogecoin.
3. Click on the "Explore More" button for additional information.

## Live Demo 🌐
Check out the live demo: [Cryptocurrency Website Demo](https://cryptocurrency-website-one.vercel.app)

## Installation 🛠️
1. Clone the repository: `git clone https://github.com/your-username/cryptocurrency-website.git`
2. Open the project folder in your code editor.
3. Launch the `index.html` file in a web browser.

## Customization 🎨
- Customize the logo and background images in the `images/` directory.
- Modify the navigation links and content to suit your needs.

## API Integration 📊
This website uses the CoinGecko API to fetch real-time cryptocurrency prices. You can obtain your API key and replace it in the `script.js` file.

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "https://api.coingecko.com/api/v3/simple/price?ids=bitcoin%2Cethereum%2Cdogecoin&vs_currencies=usd",
    "method": "GET",
    "headers": {
        // Add your API key here
        "Authorization": "Bearer YOUR_API_KEY"
    }
};

$.ajax(settings).done(function (response) {
    // Update cryptocurrency prices dynamically
});
```
## Contributing 🤝
Contributions are welcome! Feel free to enhance the design, add new features, or fix any issues. Open a pull request to contribute.

## License 📜
This project is licensed under the [MIT License](LICENSE.md).

## Author ✨
- Eraycan Sivri
- Contact: eraycansivri@hotmail.com

Enjoy exploring the world of cryptocurrencies!
