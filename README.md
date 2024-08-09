## Inspiration
AuraScan was inspired by a deep interest in blockchain technology, with a particular focus on the unique aspects of Aleo. Aleo excels in balancing transparency with privacy, and also offers remarkable scalability, programmability. These attributes motivated us to explore how to better visualize and leverage this data. Our goal with AuraScan is to provide a comprehensive visualization of blockchain data for Aleo, helping users understand and engage with this emerging blockchain ecosystem.

## What it does
AuraScan is a comprehensive blockchain explorer designed for the Aleo blockchain. It features:
1. **Standard Blockchain Data Queries**: Provides information on blocks, transactions, validators, provers, programs and domain data.
2. **Program Compilation and Deployment**: Supports the compilation, execution, and deployment of Aleo programs, simplifying the development process.
3. **Mapping Parse**: Supports the fetching of values stored in aleo's special structure mapping
4. **Multi-Wallet support**: Currently, it supports connections to Puzzle Wallet and Leo Wallet. As the mainnet launches, we will expand support to include other authoritative and trusted wallets.
5. **Data Visualization**: Uses charts and tables to present blockchain data for better user understanding.

## How we built it
1. **Technology Stack**:: Utilized React for the frontend, with Golang for the backend. Using WebSocket to realize the latest height and other real-time data push.
2. **Blockchain Integration**:
   - **Data Fetching**: Integrated Aleo blockchain APIs to retrieve and display real-time data on blocks, transactions, and other blockchain activities.
   - **Data Conversion**: Converted raw blockchain data into user-friendly formats for display on the frontend.
3. **Wallet Connection**:
   Wallet connections are essential for enabling users to perform on-chain operations directly through AuraScan. This includes tasks such as compiling, deploying, and executing Aleo programs.
4. **Data Storage and Processing**:
- **Database**: We use a MongoDB cluster to store data, ensuring high availability and scalability.
- **Data Backup**: Regular backups are performed to prevent data loss and ensure data integrity.
- **Data Snapshots and Archiving**: Periodic data snapshots and archiving are conducted to capture and record data changes over time, facilitating analysis and preserving historical data.
5. **SDK Integration**: Integrated Aleo's SDK to facilitate the compilation, execution, and deployment of programs. This feature provides developers with a streamlined process for managing their programs directly within AuraScan.

## Challenges we ran into
1. **Data Synchronization**: Ensuring real-time and accurate data synchronization was challenging due to frequent updates on the Aleo blockchain. We had to optimize our data fetching and updating mechanisms.
2. **Wallet Compatibility**: Supporting multiple wallets necessitates adapting to various wallet plugins, ensuring compatibility and security through extensive testing.
3. **Program Debugging**: Compatibility issues in program compilation and deployment have required in-depth research into Leo 2.0 updates and Aleo's program model, leading to targeted improvements.
4. **User Experience Design**: Presenting complex blockchain data in a user-friendly manner required iterative design to ensure clarity and ease of use.

## Accomplishments that we're proud of
1. **Efficiency**: In the case of a very short development cycle, with the knowledge of snarkos,sdk and other aleo source code, I completed most of the main functions of Aleo blockchain browser.
2. **Multi-Wallet Support**: Successfully implemented connectivity for multiple Aleo wallets.
3. **Program Support**: Provided simplified tools for compiling, executing, and deploying programs, streamlining development tasks.

## What we learned
1. **About Aleo**: Through developing AuraScan, we gained a deeper understanding of the Leo language, Aleo's economic model, and the Puzzle algorithm, significantly enhancing our technical expertise and application optimization.
2. **Complexity of Blockchain Data**: Handling blockchain data requires a deep understanding of underlying data structures and update mechanisms to ensure accuracy and timeliness.
3. **Diverse User Needs**: User requirements for a blockchain explorer are varied, ranging from basic data queries to complex program operations, necessitating careful consideration of user experience.
4. **Technical Integration Challenges**: Integrating various technical components (e.g., blockchain APIs, wallet interfaces, data storage) smoothly involves detailed planning and rigorous testing.

## What's next for AuraScan
1. **Feature Expansion**: Plan to add more analytical tools and reporting features to help users explore blockchain data and trends more deeply.
2. **Performance Optimization**: Continue improving data synchronization and processing mechanisms to enhance speed and stability.
3. **User Feedback**: Collect user feedback to iteratively improve the user experience and overall product functionality.
4. **Community Engagement**: Strengthen interactions with the Aleo community to gain support and insights, driving the ongoing development of AuraScan.


AuraScan aims to provide a comprehensive, efficient, and user-friendly data platform for the Aleo blockchain, with ongoing enhancements and expansions to become a vital tool in the Aleo ecosystem.
