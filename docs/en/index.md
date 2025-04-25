# HydroTrack

HydroTrack is a comprehensive water and hydration tracking application designed to help users maintain proper hydration levels, track their daily liquid intake, and manage caffeine consumption.

## Features

### Core Functionality

- **Water Intake Tracking**: Log water and other beverages with customizable amounts
- **Personalized Goals**: Set custom goals or get personalized recommendations based on your profile
- **Drink Templates**: Track various beverage types including water, coffee, tea, juice, and soda
- **Quick Add**: Quickly add frequently consumed drinks with preset volumes
- **Caffeine Monitoring**: Track caffeine intake with daily limits
- **Senior Mode**: Simplified interface option for elderly users

### Reminders

- **Scheduled Reminders**: Set reminders at specific times (morning, noon, afternoon)
- **Interval Reminders**: Alternative reminder system based on time intervals
- **Smart Notifications**: Helps users stay on track with their hydration goals

### Statistics & Analytics

- **Daily/Weekly/Monthly Stats**: View hydration trends over time
- **Progress Visualization**: Visual representation of daily goal progress
- **Drink History**: Complete log of all recorded drinks with filtering options

### Personalization

- **Unit Preferences**: Choose between metric (ml) and imperial (oz) units
- **Appearance Settings**: Light mode, dark mode, or system default
- **Custom Drink Templates**: Create and manage custom beverage types
- **Volume Presets**: Customize common volumes for quick entry

### Onboarding

- **Guided Setup**: Step-by-step introduction to the app's features
- **Personalized Recommendations**: Initial water intake goals based on user profile

## Data Models

### User Settings

- Daily water goal (ml)
- Caffeine limit per day (mg)
- Reminder preferences
- Personal metrics (gender, weight, activity level)
- Display preferences (units, appearance)
- And more customization options

### Drink Templates

- Predefined and custom beverage types
- Name, icon, and color customization
- Caffeine content per ml

### Drinks

- Recorded beverage consumption
- Amount consumed
- Timestamp
- Associated drink template

## User Interface

### Main Tabs

1. **Home**: Main dashboard showing daily progress
2. **Stats**: Detailed statistics and visualizations
3. **Add Drink**: Quick access to add new drink entries
4. **Reminders**: Configure and manage hydration reminders
5. **Settings**: App configuration and preferences

### Special Modes

- **Senior Mode**: Simplified interface with larger elements for elderly users

## Technical Implementation

- Built with SwiftUI for iOS
- Uses SwiftData for persistent storage
- Implements MVVM architecture
- Supports localization
- Weather integration for hydration recommendations

## Getting Started

1. Complete the onboarding process
2. Set your personal hydration goals
3. Configure reminders to stay on track
4. Start logging your drinks!

## Privacy & Data

- All data is stored locally on your device
- No personal information is transmitted to external servers
