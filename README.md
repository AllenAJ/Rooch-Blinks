# Rooch Blinks

**Turn any Bitcoin action into a shareable, metadata-rich link on Twitter**

// The CORS need to updated from server-side to make it work. 

With **Bitcoin Blinks**, we've created a feature that transforms Bitcoin-based actions (such as transactions, wallet interactions, or smart contract executions) into shareable links that are optimized for social media platforms like Twitter. These "Blinks" contain rich metadata, enabling seamless sharing and visibility of Bitcoin activities, including wallet addresses, transaction amounts, timestamps, and smart contract details. When shared on Twitter, each link displays dynamic, informative previews, allowing users to engage with Bitcoin actions directly from their timeline.

### Workflow:

![Screenshot at Nov 08 10-13-43.png](https://i.ibb.co/B4xjR0h/Screenshot-at-Nov-12-12-55-46.png)

**1. Bitcoin Action Execution:**
   - A user initiates a Bitcoin-related action (e.g., sending BTC, executing a smart contract, or interacting with a Bitcoin Layer 2 network). This action is captured via the integrated Bitcoin transaction or smart contract interface.
   
**2. Metadata Extraction:**
   - Once the action is completed, the metadata related to the Bitcoin transaction is extracted. This includes transaction IDs, sender/receiver wallet addresses, token amounts, and timestamps.
   - For smart contract interactions, additional details like the contract address, executed function, and parameters are extracted.

**3. Creation of Bitcoin Blink:**
   - The extracted metadata is then used to generate a Bitcoin Blink. This is a unique URL containing all relevant details about the Bitcoin action, encoded in a way that is easily shareable on Twitter and other platforms. 

**4. Social Media Integration:**
   - The Bitcoin Blink URL is designed to integrate smoothly with Twitter’s metadata preview capabilities, ensuring that when a user shares the link, a rich preview of the Bitcoin transaction or smart contract interaction is displayed. This includes details like the amount of Bitcoin transacted, wallet addresses, and transaction timestamps, enhancing the visibility and transparency of Bitcoin activities.

**5. Shareable Link:**
   - The Bitcoin Blink can now be shared with a single click. It’s fully optimized for social media, ensuring a smooth user experience with clear, informative visuals that help others understand the Bitcoin action and its significance.
   
This feature not only improves Bitcoin's transparency but also enhances social engagement by turning complex blockchain activities into easily shareable content. By utilizing rich metadata, users can quickly broadcast key information from their Bitcoin transactions to their followers, increasing awareness of Bitcoin's growing use cases and its integration into social platforms.
