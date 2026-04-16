VOXO – Farm Fresh to You
VOXO is a comprehensive, mobile-first web application designed to bridge the gap between local farmers and consumers. It provides a direct marketplace for fresh produce with integrated voice-assisted features, order management, and a seamless WhatsApp-based checkout system.

🌟 Key Features
Multi-Role Access: Dedicated interfaces for Consumers (to shop), Farmers (to manage listings), and Logistics/Delivery partners.

Voice-Enabled Shopping: Integrated voice search and command system allowing users to search for products or add items to their cart using voice prompts.

AI-Powered Product Comparison: A built-in "AI Compare" feature that helps users analyze different produce options based on price, quality, and freshness.

Offline Support: Native offline capabilities that save data locally when a connection is lost, ensuring uninterrupted access.

WhatsApp Checkout: Streamlined ordering process that generates a formatted order summary and opens it directly in WhatsApp to message the seller.

Real-time Analytics: A dashboard for sellers to track total sales, pending orders, and active listings.

🛠️ Tech Stack
Frontend: HTML5, CSS3 (using CSS Variables for theming).

Logic: Vanilla JavaScript for state management and UI interactions.

APIs: Web Speech API for voice recognition and synthesis.

Styling: Custom responsive grid system optimized for mobile devices.

🚀 Getting Started
Since VOXO is built as a standalone web application, you can run it directly in any modern web browser.

Clone the repository:

Bash
git clone https://github.com/your-username/voxo.git
Open voxo_updated.html in your preferred browser.

📱 User Roles
Consumer: Browse the marketplace, use voice search to find vegetables or fruits, compare prices, and manage a digital cart.

Farmer: Upload product images, set prices, and view sales analytics through a dedicated dashboard.

Logistics: View and manage delivery tasks within the ecosystem.

📦 Project Structure
Plaintext
├── voxo_updated.html  # Main application file containing HTML, CSS, and JS
The application uses a "Single Page Application" (SPA) approach, toggling between different "screens" (e.g., #s-login, #s-home, #s-cart) by manipulating the DOM.

🔒 Security & Performance
Local Storage: User data and cart information are persisted using localStorage for quick recovery.

Responsive Design: Optimized for mobile with a maximum width of 480px for the main content area to ensure a native app-like feel.
