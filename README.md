# Solace App
It is a jewellery based app to showcase different brands and sell it to customers. I use Google Pay and UPI for payments. This jewellery app is a solace to the soul when you wear a piece of luxurious accessories customized for you specifically.

## Project Overview
Solace is a Flutter-based mobile application that leverages modern state management with Riverpod and AR technology to provide an immersive jewelry shopping experience. The app allows users to virtually try on jewelry pieces using AR technology and make secure payments through Google Pay and UPI.

## Features To-Do List

### 1. User Authentication & Profile
- [ ] Implement user registration and login
- [ ] Create user profile management
- [ ] Add social media authentication
- [ ] Implement user preferences for jewelry styles
- [ ] Add size and measurement tracking
- [ ] Create wishlist functionality

### 2. Jewelry Catalog
- [ ] Design product database schema
- [ ] Implement product listing page
- [ ] Add advanced filtering options:
  - [ ] By brand
  - [ ] By category (rings, necklaces, etc.)
  - [ ] By price range
  - [ ] By material
  - [ ] By style
- [ ] Implement search functionality
- [ ] Add product details page
- [ ] Include product specifications
- [ ] Add product reviews and ratings

### 3. AR Try-On Experience
- [ ] Integrate AR framework (ARCore/ARKit)
- [ ] Implement face/ear detection
- [ ] Create virtual jewelry placement
- [ ] Add real-time jewelry visualization
- [ ] Implement size adjustment
- [ ] Add lighting effects
- [ ] Create screenshot and sharing feature
- [ ] Implement AR session recording

### 4. E-commerce Features
- [ ] Design shopping cart
- [ ] Implement secure checkout
- [ ] Add multiple payment methods:
  - [ ] Google Pay integration
  - [ ] UPI integration
  - [ ] Credit/Debit cards
- [ ] Create order tracking
- [ ] Implement order history
- [ ] Add delivery tracking
- [ ] Create return/refund system

### 5. Brand Showcase
- [ ] Create brand profiles
- [ ] Implement brand story sections
- [ ] Add brand collections
- [ ] Create brand-specific filters
- [ ] Implement brand search
- [ ] Add brand ratings and reviews

### 6. Customization Features
- [ ] Create jewelry customization interface
- [ ] Implement material selection
- [ ] Add size customization
- [ ] Create engraving options
- [ ] Implement design preview
- [ ] Add price calculator

### 7. Social Features
- [ ] Implement social sharing
- [ ] Create community reviews
- [ ] Add style inspiration gallery
- [ ] Implement user collections
- [ ] Create follow system for brands

## Technical Requirements
- Flutter for cross-platform development
- Riverpod for state management
- ARCore/ARKit for AR features
- Firebase services:
  - Authentication
  - Cloud Firestore
  - Storage
  - Cloud Functions
- Payment gateway integrations:
  - Google Pay
  - UPI
- Image processing libraries
- 3D model rendering

## Development Setup
1. Flutter SDK installation
2. Firebase project setup
3. AR development environment
4. Required dependencies:
   - flutter_riverpod
   - firebase_core
   - firebase_auth
   - cloud_firestore
   - firebase_storage
   - ar_flutter_plugin
   - google_pay
   - upi_payment
   - image_picker
   - camera
   - shared_preferences
   - http
   - cached_network_image