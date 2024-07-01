# App

GymPass-style app.

# Tech Stack
This project utilizes Node.js with Fastify and Prisma for its backend stack.

## Functional Requirements
- [ ] Users should be able to sign up
- [ ] Users should be able to sign in
- [ ] Users should be able to retrieve their profile information
- [ ] Users should be able to retrieve their check-in count
- [ ] Users should be able to retrieve their check-in history
- [ ] Users should be able to search for nearby gyms
- [ ] Users should be able to search for gyms by name
- [ ] Users should be able to check in at a gym
- [ ] Check-ins should be able to be validated
- [ ] Admins should be able to add new gyms

## Business Rules
- [ ] Users cannot sign up with a duplicate email
- [ ] Users cannot check in more than once per day
- [ ] Users can only check in if they are within 100 meters of the gym
- [ ] Check-ins can only be validated 20 minutes after being created
- [ ] Check-ins can only be validated by an admin
- [ ] Gyms can only be added by admins

## Non-Functional Requirements
- [ ] Passwords need to be encrypted
- [ ] App data should persist in a PostgreSQL database
- [ ] All data lists should be paginated with 20 items per page
- [ ] Users need to be authenticated and identified using JWT