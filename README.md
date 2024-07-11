<p align="center">
  <img src="https://zrcdn.net/static/img/logos/paidwork/paidwork-logo-github.png" alt="Paidwork" />
</p>

<h3 align="center">
  Create, Send, Receive, Swap, Burn and Tax on Solana Blockchain
</h3>
<p align="center">
  🚀 Over 20K Worken holders!
</p>

<p align="center">
  <a href="https://github.com/paidwork/solana-sdk-unity">
    <img alt="GitHub Repository Stars Count" src="https://img.shields.io/github/stars/paidwork/solana-sdk-unity?style=social" />
  </a>
    <a href="https://x.com/paidworkco">
        <img alt="Follow Us on X" src="https://img.shields.io/twitter/follow/paidworkco?style=social" />
    </a>
</p>
<p align="center">
    <a href="http://commitizen.github.io/cz-cli/">
        <img alt="Commitizen friendly" src="https://img.shields.io/badge/commitizen-friendly-brightgreen.svg" />
    </a>
    <a href="https://github.com/paidwork/solana-sdk-js">
        <img alt="License" src="https://img.shields.io/github/license/paidwork/solana-sdk-js" />
    </a>
    <a href="https://github.com/paidwork/solana-sdk-js/pulls">
        <img alt="PRs Welcome" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" />
    </a>
</p>

<a href="https://www.paidwork.com/worken?utm_source=github.com&utm_medium=referral&utm_campaign=readme" target="_blank">Read more</a> about Worken Token.

Feel free to try out our provided Postman collection. Simply click the button below to fork the collection and start testing.<br>

[<img src="https://run.pstmn.io/button.svg" alt="Run In Postman" style="width: 128px; height: 32px;">](https://god.gw.postman.com/run-collection/32839969-fd54da1c-0e5b-43e8-9d89-8330e9bebf17?action=collection%2Ffork&source=rip_markdown&collection-url=entityId%3D32839969-fd54da1c-0e5b-43e8-9d89-8330e9bebf17%26entityType%3Dcollection%26workspaceId%3Dbeab0417-9a12-472d-8f22-3c7c478123a9)

## Configuration

To ensure flexibility and ease of integration, the Worken SDK allows for configuration through environmental variables. These variables can be set directly in your project's .env file. Below is a list of available configuration variables along with their descriptions:

`WORKEN_OPENSSL_CONF`: Specifies the path to your OpenSSL configuration file. Setting this variable is optional but recommended if you need to customize OpenSSL settings. This can be particularly useful for cryptographic key generation, where specific configurations may be necessary.

`WORKEN_POLYGONSCAN_APIKEY`: This is your API key, which you can generate at: https://polygonscan.com/myapikey. The API key is required for accessing PolygonScan's data programmatically and is essential for querying transaction history, token balances, and other blockchain-related information on the Polygon network.

