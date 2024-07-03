# rn-assignment6-11015103
rn-assignment6-11015103

ID: 11146109

React Native ShoppingApp App README
Design Choices

App Structure:
The app features a straightforward e-commerce interface with two main screens: Home and Cart. On the Home screen, products are displayed in a grid layout using FlatList, allowing users to easily add items to their cart. The Cart screen shows all selected items with options to remove them and proceed to checkout.

UI/UX:

Home Screen: Products are presented in a grid format showing images, categories, names, and prices. Users can add items to their cart by clicking an "Add to Cart" button.
Cart Screen: Displays added items with details such as images, names, and prices. Users can remove items and view the total estimated price.
Navigation: Simple navigation buttons facilitate easy movement between the Home and Cart screens (e.g., "View Cart" on Home, back button on Cart).
Data Management with AsyncStorage:

Data Storage: Cart items are locally stored using AsyncStorage, ensuring persistence even if the app is closed and reopened.
Implementation: Functions like addToCart and removeFromCart update the cart array in AsyncStorage. On app load (via useEffect hook), cart data is fetched using getItem and displayed on both screens.
Technologies Used:
React Native for building cross-platform mobile apps, AsyncStorage for local data persistence, FlatList for efficient grid display, TouchableOpacity for interactive components, and StyleSheet for styling with JavaScript objects.

Future Enhancements:

Authentication: Implement user authentication for personalized carts and orders.
Backend Integration: Connect to a backend server to enable real-time updates and synchronization.
UI Enhancements: Improve user interface with animations, transitions, and enriched product details.


