# Sheltr🐾 
### Midterm Project Submission for INFO-C451: System Implementation (Spring 2024)
### by Matthew Fante

### Unit Tests:
_No unit tests have been designed for this app yet... Check back later!_

# Sheltr🐾
### Midterm Project Submission for INFO-C451: System Implementation (Spring 2024)
### by Matthew Fante
### Unit Tests:
_No unit tests have been designed for this app yet... Check back later!_

## General Tests
- [x] Initialization and Navigation
    - [x] Test app initialization and default route.
    - [x] Test navigation to different screens (e.g., profile page, pets list).
- [x] Error Handling
    - [x] Test error scenarios (e.g., network failure, authentication failure).
    - [x] Validate that appropriate error messages are displayed to the user.

## Guest User Tests
- [x] Browse Adoptable Pets
    - [x] Test if guest users can view the list of adoptable pets.
    - [x] Test if guest users can filter the list based on various criteria (e.g., species, breed).
- [x] View Animal Profiles
    - [x] Test if guest users can access individual pet profiles.
    - [x] Test if pet profiles display correct information (e.g., photos, descriptions).
- [x] Register User Account
    - [x] Test user registration process with valid and invalid inputs.
    - [x] Validate error handling for duplicate emails, invalid passwords, etc.

## Prospective Pet Parent Tests
- [x] Save Favorite Pets
    - [x] Test if users can add pets to a "favorites" list.
    - [x] Test if the favorites list persists across sessions.
- [x] Request a Meet-and-Greet
    - [x] Test if users can request a meet-and-greet with a pet.
    - [x] Validate error handling for invalid requests or when a pet is unavailable.
- [x] Track Request Status
    - [x] Test if users can view the status of meet-and-greet requests.
    - [x] Test different request statuses (e.g., pending, approved, declined).
- [x] Update User Profile
    - [x] Test if users can update their personal information.
    - [x] Validate that changes are reflected correctly in the database.
- [x] Update Contact Information
    - [x] Test if users can change their contact information (e.g., phone, email).
    - [x] Test validation of contact information (e.g., correct email format).

## Animal Shelter Staff Tests
- [x] Create Animal Profiles
    - [x] Test if staff can create new animal profiles.
    - [x] Test mandatory fields and error handling for invalid data.
- [x] Manage Animal Profiles
    - [x] Test if staff can update existing animal profiles.
    - [x] Test if changes are reflected in the user interface.
- [x] Mark Availability
    - [x] Test if staff can change the availability status of a pet.
    - [x] Test how the change affects the pet's visibility to users.
- [x] Manage Meet-and-Greet Requests
    - [x] Test if staff can approve or decline meet-and-greet requests.
    - [x] Test if users are notified of request status changes.
- [x] View Upcoming Meet-and-Greets
    - [x] Test if staff can view scheduled meet-and-greets.
    - [x] Validate the accuracy of the meet-and-greet schedule.
- [x] Update Shelter Information
    - [x] Test if staff can update shelter details (e.g., contact info, hours).
    - [x] Validate that changes are correctly stored in the database.

## System Administrator Tests
- [x] Review and Approve New Staff Accounts
    - [x] Test if admins can approve or deny new shelter staff accounts.
    - [x] Test error handling for invalid approval attempts.
- [x] Manage User Accounts
    - [x] Test if admins can reset passwords or address user concerns.
    - [x] Validate correct error handling and successful account management.
- [x] Remove Inappropriate Content
    - [x] Test if admins can identify and remove inappropriate content.
    - [x] Test validation to ensure only admins have this access.

## Authentication System Tests
- [x] User Registration
    - [x] Test user registration with various inputs (valid/invalid emails, passwords).
    - [x] Test edge cases like re-registration with the same email.
- [x] User Login
    - [x] Test user authentication with correct and incorrect credentials.
    - [x] Validate error handling and session management.
- [x] Password Reset
    - [x] Test password reset process with valid and invalid emails.
    - [x] Validate that password reset emails are sent and processed correctly.
- [x] Validate Login
    - [x] Test session token validity and expiration.
    - [x] Test that users are redirected to the login page upon session expiration.

## Database System Tests
- [x] Store User Data
    - [x] Test if user information is correctly stored in the database.
    - [x] Validate database schema constraints (e.g., unique keys, required fields).
- [x] Store Animal Data
    - [x] Test if animal profiles are stored correctly.
    - [x] Test database constraints and relationships among data.
- [x] Store Meet-and-Greet Requests
    - Test if meet-and-greet requests are stored with correct data.
    - Validate integrity and relationships in the database.
- [x] Store Shelter Data
    - Test if shelter information is correctly stored and retrieved.
    - Validate accuracy and integrity of stored data.

## File (Image) Storage System Tests
- [x] Store Animal Photos
    - Test image upload with various image types and sizes.
    - Validate error handling for failed uploads and invalid images.
- [x] Serve Images
    - Test if stored images are served quickly and accurately.
    - Validate image caching and error handling for missing images.
