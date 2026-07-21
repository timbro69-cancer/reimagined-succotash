 **YTC Style Builder - Firebase Backend** 
 Cloud backend infrastructure for Yung Timmy's outfit builder e-commerce app. 
 Manages user authentication, product inventory, outfit recommendations, orders, and customer data. Core Features:
 - User Authentication: Email/password signup, login, and account management via Firebase Auth
 -  - Product Database: Firestore collections for shoes, apparel, accessories with metadata (name, price, palette, category, inventory)
    - - Outfit Recommendations: Color harmony matching algorithm that scores shoe-to-apparel compatibility based on HSL color analysis
      - - Complete Look Bundles: Bundle pricing, discount calculations, and bundle-to-product relationships
        - - Shopping Cart: Cart management with items, quantities, sizes, and delivery method selection - Orders: Order creation, payment processing, order history, and order status tracking
          - - User Profiles: Customer data including addresses, preferred delivery method, sizes, favorites, saved outfits - Cloud Storage: Product images, outfit preview images, user-uploaded photos
            - - Rewards System: Points tracking for purchases, referrals, reviews, and loyalty rewards
              -  - Live Shopping: Livestream event data and real-time product inventory updates - Admin Tools: Product management, inventory updates, order fulfillment, customer support Tech Stack: - Platform: Firebase (Authentication, Firestore Database, Cloud Storage, Cloud Functions)
                 - - Color Matching: HSL harmony algorithm for intelligent outfit recommendations - Payment Processing: Stripe or Square integration for transactions - Deployment: Firebase Hosting for any web admin dashboard --- Is this what you're building for the backend?
