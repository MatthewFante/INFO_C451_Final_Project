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
    - Test app initialization and default route.
    - Test navigation to different screens (e.g., profile page, pets list).
- [x] Error Handling
    - Test error scenarios (e.g., network failure, authentication failure).
    - Validate that appropriate error messages are displayed to the user.

## Guest User Tests
- [x] Browse Adoptable Pets
    - Test if guest users can view the list of adoptable pets.
    - Test if guest users can filter the list based on various criteria (e.g., species, breed).
- [x] View Animal Profiles
    - Test if guest users can access individual pet profiles.
    - Test if pet profiles display correct information (e.g., photos, descriptions).
- [x] Register User Account
    - Test user registration process with valid and invalid inputs.
    - Validate error handling for duplicate emails, invalid passwords, etc.

## Prospective Pet Parent Tests
- [x] Save Favorite Pets
    - Test if users can add pets to a "favorites" list.
    - Test if the favorites list persists across sessions.
- [x] Request a Meet-and-Greet
    - Test if users can request a meet-and-greet with a pet.
    - Validate error handling for invalid requests or when a pet is unavailable.
- [x] Track Request Status
    - Test if users can view the status of meet-and-greet requests.
    - Test different request statuses (e.g., pending, approved, declined).
- [x] Update User Profile
    - Test if users can update their personal information.
    - Validate that changes are reflected correctly in the database.
- [x] Update Contact Information
    - Test if users can change their contact information (e.g., phone, email).
    - Test validation of contact information (e.g., correct email format).

## Animal Shelter Staff Tests
- [x] Create Animal Profiles
    - Test if staff can create new animal profiles.
    - Test mandatory fields and error handling for invalid data.
- [x] Manage Animal Profiles
    - Test if staff can update existing animal profiles.
    - Test if changes are reflected in the user interface.
- [x] Mark Availability
    - Test if staff can change the availability status of a pet.
    - Test how the change affects the pet's visibility to users.
- [x] Manage Meet-and-Greet Requests
    - Test if staff can approve or decline meet-and-greet requests.
    - Test if users are notified of request status changes.
- [x] View Upcoming Meet-and-Greets
    - Test if staff can view scheduled meet-and-greets.
    - Validate the accuracy of the meet-and-greet schedule.
- [x] Update Shelter Information
    - Test if staff can update shelter details (e.g., contact info, hours).
    - Validate that changes are correctly stored in the database.

## System Administrator Tests
- [x] Review and Approve New Staff Accounts
    - Test if admins can approve or deny new shelter staff accounts.
    - Test error handling for invalid approval attempts.
- [x] Manage User Accounts
    - Test if admins can reset passwords or address user concerns.
    - Validate correct error handling and successful account management.
- [x] Remove Inappropriate Content
    - Test if admins can identify and remove inappropriate content.
    - Test validation to ensure only admins have this access.

## Authentication System Tests
- [x] User Registration
    - Test user registration with various inputs (valid/invalid emails, passwords).
    - Test edge cases like re-registration with the same email.
- [x] User Login
    - Test user authentication with correct and incorrect credentials.
    - Validate error handling and session management.
- [x] Password Reset
    - Test password reset process with valid and invalid emails.
    - Validate that password reset emails are sent and processed correctly.
- [x] Validate Login
    - Test session token validity and expiration.
    - Test that users are redirected to the login page upon session expiration.

## Database System Tests
- [x] Store User Data
    - Test if user information is correctly stored in the database.
    - Validate database schema constraints (e.g., unique keys, required fields).
- [x] Store Animal Data
    - Test if animal profiles are stored correctly.
    - Test database constraints and relationships among data.
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
