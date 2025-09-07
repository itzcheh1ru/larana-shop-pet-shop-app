# 🐾 Larana Shop - Pet Shop & Care App (UI Design)

A beautiful Android UI design implementation for a pet shop and care application, featuring modern Material Design principles and a comprehensive user experience.

![Android](https://img.shields.io/badge/Android-UI%20Design-green?style=for-the-badge&logo=android)
![Status](https://img.shields.io/badge/status-UI%20Complete-blue?style=for-the-badge)
![Design](https://img.shields.io/badge/design-Figma%20to%20Android-purple?style=for-the-badge)

## 📱 UI Screenshots

### Onboarding Flow
| Welcome Screen | Pet Items | Healthy Foods | Fast Delivery |
|:---:|:---:|:---:|:---:|
| ![Welcome](screenshots/01_welcome.PNG) | ![Pet Items](screenshots/02_pet_items.png) | ![Foods](screenshots/03_foods.png) | ![Delivery](screenshots/04_delivery.png) |

### Main Application
| Home Screen | Product Detail | Shopping Cart | Payment |
|:---:|:---:|:---:|:---:|
| ![Home](screenshots/05_home.png) | ![Product Detail](screenshots/06_product_detail.png) | ![Cart](screenshots/07_cart.png) | ![Payment](screenshots/08_payment.png) |

### User Management
| My Account | Notifications |
|:---:|:---:|
| ![Account](screenshots/09_account.png) | ![Notifications](screenshots/10_notifications.png) |

## �� Design Features

- **Modern UI/UX** - Clean, intuitive interface following Material Design guidelines
- **Consistent Branding** - Purple theme with professional color scheme
- **Responsive Layout** - Optimized for various Android screen sizes
- **Interactive Elements** - Smooth transitions and user-friendly navigation
- **Accessibility** - High contrast colors and readable typography

## 🛠️ Technical Implementation

- **Platform**: Android Studio
- **Language**: Java
- **Minimum SDK**: API 21 (Android 5.0)
- **Target SDK**: API 34 (Android 14)
- **UI Framework**: Android XML Layouts
- **Design System**: Material Design Components

## 🚀 Getting Started

### Prerequisites
- Android Studio Arctic Fox or later
- Android SDK 21 or higher
- Java 8 or higher

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/itzcheh1ru/PetApp.git
   cd PetApp
   ```

2. **Open in Android Studio**
   - Launch Android Studio
   - Select "Open an existing project"
   - Navigate to the PetApp folder
   - Click "OK"

3. **Sync Project**
   - Android Studio will automatically sync Gradle files
   - Wait for the sync to complete

4. **Run the App**
   - Connect an Android device or start an emulator
   - Click the "Run" button (▶️)
   - Select your target device

## �� Design System

### Color Palette
```xml
Primary Purple: #6B46C1
Dark Purple: #4A148C
Light Purple: #E1BEE7
Background Dark: #2C2C2C
Accent Red: #FF5722
Text Primary: #212121
Text Secondary: #757575
```

### Typography
- **App Title**: 28sp, Bold, White
- **Screen Title**: 24sp, Bold, Dark Purple
- **Subtitle**: 18sp, Bold, Dark Purple
- **Body Text**: 14sp, Regular, Dark Grey
- **Caption**: 12sp, Regular, Light Grey

### Components
- **Buttons**: Rounded corners (8dp), Material Design
- **Cards**: Elevated with subtle shadows
- **Icons**: 24dp, Material Design style
- **Navigation**: Bottom navigation bar with 3 tabs

## 📱 Screen Descriptions

### 1. Welcome Screen
- **Purpose**: App introduction and branding
- **Elements**: Logo, app name, tagline, CTA button
- **Background**: Dark with paw print pattern

### 2. Onboarding Screens (3 screens)
- **Pet Items**: Showcases pet accessories and supplies
- **Healthy Foods**: Features premium pet food options
- **Fast Delivery**: Highlights delivery service benefits
- **Navigation**: Page indicators and Next button

### 3. Home Screen
- **Header**: Search bar, menu icon, notification bell
- **Banner**: Super sale promotion with product image
- **Products**: "Special for You" product grid
- **Navigation**: Bottom tab bar (Home, Cart, Profile)

### 4. Product Detail Screen
- **Image**: Large product photo
- **Info**: Name, price, rating, description
- **Actions**: Buy Now and Add to Cart buttons
- **Navigation**: Back button, menu, notifications

### 5. Shopping Cart Screen
- **Header**: Screen title with menu and notifications
- **Items**: List of added products with images and prices
- **Action**: Buy Now button for checkout

### 6. Payment Screen
- **Summary**: Order totals (subtotal, delivery, total)
- **Form**: Payment details input fields
- **Action**: Buy Now button for final purchase

### 7. My Account Screen
- **Profile**: User avatar and personal information
- **Form**: Editable fields for name, address, mobile, password, email
- **Navigation**: Bottom tab bar

### 8. Notifications Screen
- **Header**: Screen title with menu and notification bell
- **List**: Notification cards with timestamps
- **Content**: Offers, purchase updates, promotions

## �� Customization

### Adding New Screens
1. Create new Activity class in `activities/` package
2. Add corresponding layout XML in `res/layout/`
3. Update `AndroidManifest.xml`
4. Add navigation logic

### Modifying Colors
1. Edit `res/values/colors.xml`
2. Update `res/values/styles.xml` if needed
3. Rebuild the project

### Adding New Products
1. Update `res/values/strings.xml`
2. Add product images to `res/drawable/`
3. Modify `ProductAdapter.java` if needed

## �� UI Checklist

- [x] Welcome screen with branding
- [x] 3 onboarding screens with navigation
- [x] Home screen with product grid
- [x] Product detail screen
- [x] Shopping cart screen
- [x] Payment screen with form
- [x] User account screen
- [x] Notifications screen
- [x] Bottom navigation bar
- [x] Consistent color scheme
- [x] Material Design components
- [x] Responsive layouts
- [x] Vector drawables
- [x] String resources
- [x] Style definitions

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Hirusha Thisayuru Ellawala**
- Email: thisayuruhirusha@gmail.com

## 📞 Support

- 📧 Email: thisayuruhirusha@gmail.com

---

<div align="center">

**⭐ If you like this UI design, give it a star! ⭐**

Made with ❤️ for pet lovers and Android developers

</div>
