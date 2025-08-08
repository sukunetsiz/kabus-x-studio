# v1.4 Release Notes

## What's New:

### Security & Privacy Enhancements:
* Implemented anti-phishing CAPTCHA for enhanced user protection
* Added bepsvpt/secure-headers package for improved security headers
* Restricted GIF and WebP file uploads to prevent potential vulnerabilities
* Implemented queue-based order processing for better system reliability
* Enhanced product review anonymity by censoring usernames

### Major System Overhauls:
* **Framework Upgrade**: Updated to Laravel 12 for latest features and security patches
* **Admin Interface**: Complete migration to new admin layout with comprehensive order management
* **Vendor Interface**: Full migration to new vendor layout with enhanced functionality
* **Auto Delivery System**: Finished implementation for digital products with automated processing

### New Features & Functionality:
* Added vendor trust system for improved marketplace reliability
* Implemented search filter component
* Added order completion timer functionality
* Created "About Us" and "Bug Bounty" pages
* Added donation page for community support
* Integrated report/message vendor buttons for better communication
* Added order and dispute statistics to admin panel
* Enhanced delivery options - digital products now restricted to single free delivery option

### User Interface Improvements:
* Recreated navbar design with cleaner structure
* Redesigned footer and removed left-right navigation bars
* Created dedicated components.css for consistent styling
* Updated logo design and branding
* Improved profile picture logic and default images
* Enhanced overall UI with detailed refinements

### Technical Improvements:
* Added ImageService and QrCodeService for better media handling
* Updated multiple core libraries:
  - endroid/qr-code for QR code generation
  - Intervention/image-laravel for image processing
  - mobicms/captcha for CAPTCHA functionality
* Recreated database seeders for improved data management
* Renamed model to AutomatedDelivery for better code clarity
* Removed bulk options from digital products for streamlined experience
* Prevented mixed orders and user-to-user messaging for security
* Fixed various bugs and improved system stability

### Auto Confirmation Updates:
* Implemented variable auto-confirmation times based on product types
* Enhanced order processing workflow for different delivery methods

### Documentation:
* Updated README.md with latest installation and usage information
