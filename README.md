# Gogaledu Academy Muzaffarnagar - Seat Booking System Requirements

# Project Overview
Develop a seat booking system for Gogaledu Academy Muzaffarnagar that allows students to register, login, view batch schedules, and reserve seats interactively.

# Functional Requirements

1. Landing Page
* **Title Display**: "WELCOME TO GOGALEDU ACADEMY MUZAFFARNAGAR"
* **Call-to-Action Heading**: "Register for Book your seat"
* **Primary Action**: Registration button leading to registration form
  
2. User Registration & Authentication
* **Registration Form**: Capture student details (fields to be defined)
* **Auto-Login**: Upon successful registration, automatically log the user in
* **Session Management**: Maintain user session for subsequent interactions
  
3. Batch Schedule Display (Post-Login)
Weekday Batches (Monday to Friday)
* **Batch 1**: 8:00 AM to 9:30 AM
* **Batch 2**: 10:00 AM to 11:30 AM
* **Batch 3**: 12:00 PM to 1:30 PM
* **Batch 4**: 3:00 PM to 4:30 PM

Weekend Batches (Saturday & Sunday)
* **Morning Batch**: 7:30 AM to 9:30 AM
* **Evening Batch**: 7:30 PM to 9:30 PM

4. Seat Reservation Interface
* **Seat Visualization**: Display available and reserved seats graphically
* **Interactive Selection**: Click-to-reserve functionality
* **Status Indicators**: Clear visual distinction between available/reserved seats
* **Confirmation**: "Seat reserved successfully" popup message

  
# Technical Specifications

# Architecture & Stack ✅
* **Frontend**: React.js
* **Backend**: Node.js with Express.js
* **Database**: MongoDB
* **Authentication**: JWT tokens
* **Mobile Responsive**: Required for seamless mobile experience
  
# User Management ✅

* **Registration Fields**:
   * Name (required)
   * Phone (required)
   * Email (required)
   * Password (required)
   * Confirm Password (required)
* **Authentication**: JWT token-based authentication
* **Password Requirements**: *Please specify password validation rules (min length, special chars, etc.)*
  
# Seat Management
1. How many seats per batch? (Total capacity per classroom)
2. Seat numbering/labeling convention? (A1, A2, etc.)
3. Can users cancel/modify reservations?
4. Time restrictions for booking (how far in advance)?

# Business Logic
1. Payment integration required for seat booking?
2. Waitlist functionality for fully booked batches?
3. Admin panel needed for managing batches/seats?
4. Notification system (SMS/Email confirmations)?

# Data Structure Considerations
1. Multi-tenant if expanding to other academy locations?
2. Batch capacity management and overbooking rules?
3. Historical booking data retention requirements?

# UI/UX Requirements
1. Seat layout visualization preference (theater-style, classroom grid)?
2. Color scheme and branding guidelines?
3. Accessibility requirements?
4. Offline functionality needed?

# Success Metrics ✅
* Seamless registration to seat booking flow
* Real-time seat availability updates
* Intuitive seat selection interface
* Mobile-friendly responsive design

# Implementation Priority ✅
1. **Phase 1**: Registration + Auto-login + Basic batch display
2. **Phase 2**: Interactive seat selection + Reservation system
3. **Phase 3**: Enhanced features (notifications, admin panel)
   

**Recommended Defaults**
* 50 seats per batch (modifiable later)
* Simple numbering: 1, 2, 3... 30
* Allow booking cancellation up to 2 hours before batch
* Classroom grid layout (5 rows × 6 seats)
* Clean, professional blue/white color scheme

