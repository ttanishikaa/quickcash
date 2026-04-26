# quickcash
A group project, and a mobile application that connects people in local communities for quick job postings and opportunities. Built for Android, this app makes it easy to post jobs, find work, and manage transactions all in one place. 

## Overview

QuickCash is a Local Job Marketplace that bridges the gap between people who need tasks done and those looking for work in their area. Whether it's yard work, tutoring, deliveries, or handyman services, users can quickly post jobs or browse available opportunities nearby.

## Features

### Core Functionality
- **User Authentication**
  - Secure registration and login system
  - Profile management
  
- **Job Posting & Discovery**
  - Create and publish job listings with details and pricing
  - Browse available jobs in your locality
  - Search and filter jobs by category, location, or price

- **Real-time Notifications**
  - Push notifications for new job matches
  - Alerts for job applications and updates
  - Message notifications

- **Transaction History**
  - Complete record of posted and completed jobs
  - Payment history and receipts
  - Activity tracking

- **Payment Integration**
  - Secure PayPal integration for transactions
  - Easy payment processing for completed jobs

## Technologies Used

- **Android SDK** - Native Android development
- **Java** - Primary programming language
- **Firebase** - Authentication and real-time database 
- **PayPal SDK** - Payment processing
- **Google Maps API** - Location services 

### Prerequisites
- Android Studio (latest version)
- Android SDK (API level XX or higher)
- JDK 8 or higher

### Setup Instructions

1. Clone the repository
```bash
git clone https://github.com/yourusername/quickcash.git
```

2. Open the project in Android Studio

3. Configure API keys
   - Add your PayPal API credentials in `app/src/main/res/values/secrets.xml`
   - Add Firebase configuration file `google-services.json` (if using Firebase)

4. Sync Gradle files

5. Build and run the application on an emulator or physical device

## Usage

1. **Register/Login**: Create an account or sign in with existing credentials
2. **Browse Jobs**: View available jobs in your area
3. **Post a Job**: Create a new job listing with description, price, and location
4. **Accept Jobs**: Apply for jobs that match your skills
5. **Complete & Pay**: Mark jobs as complete and process payments through PayPal
6. **View History**: Check your past jobs and transactions
7. **Rate/ Review**: Rate and review job postings on the application.

## API Documentation

**Firebase**: For login and registration
**Google maps**: For showing job postings in the local area. Geocoder integration for searching locations on maps.

## Future Enhancements

- [ ] In-app messaging between job posters and workers
- [ ] Job categories expansion
- [ ] Real-time job tracking
- [ ] Multi-language support
- [ ] iOS version


- PayPal SDK documentation
- Android developer community
- [Any other resources or libraries you used]
