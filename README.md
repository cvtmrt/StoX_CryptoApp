# StoX Market Application

StoX Market is a dynamic Android application designed to provide users with a seamless cryptocurrency trading experience. The app includes features such as buying, selling, and tracking cryptocurrency assets. It offers real-time data, detailed asset information, and an intuitive user interface for both beginners and experienced traders.

Key Features

Real-Time Data: Display current cryptocurrency prices and percentage changes. Asset Management: Manage your portfolio with detailed balance and transaction history views. Trading Options: Easy-to-use Buy and Sell screens for quick transactions. Interactive Design: Features such as animations, a recycler view for listing assets, and bottom navigation for streamlined app navigation. Modern UI/UX: Optimized layouts for different activities such as Wallet, History, and Coin Details. Buy/Sell Functionality: Simplified workflows for purchasing or selling cryptocurrencies. Bottom Navigation Bar: Easy navigation between the dashboard, wallet, and history sections. Transaction History: Access a history of your transactions for transparency and tracking. Detailed Coin View: Get detailed information on individual cryptocurrencies, including price changes, market cap, and trading volume. Home Dashboard: Displays a list of available cryptocurrencies with their current prices and changes.

Activities

MainActivity: Displays the cryptocurrency dashboard using a RecyclerView.
CoinDetailsActivity: Provides detailed insights about selected cryptocurrencies and allows users to buy or sell directly.
BuyActivity: Enables users to purchase cryptocurrencies by specifying the amount.
SellActivity: Facilitates selling of owned cryptocurrencies based on user input.
WalletActivity: Displays the user's portfolio, wallet balance, and owned assets.
HistoryActivity: Provides a summary of past transactions.

Technologies Used

Kotlin: Programming language for Android development.
Room Database: Local data storage for user assets and transaction history.
Retrofit: Fetches real-time cryptocurrency data from APIs.
Lottie Animations: Adds visual appeal to UI elements.
RecyclerView: Efficiently displays lists of cryptocurrencies and assets.
Material Design: Modern UI components for a consistent look and feel.

How to Run the Project

Clone this repository to your local system.
Open the project in Android Studio.
Ensure you have the required SDKs and dependencies installed.
Build and run the project on an emulator or physical device.
