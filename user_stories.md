# User Story Template

**Title:**
_As a [user role], I want [feature/goal], so that [reason]._

**Acceptance Criteria:**
1. [Criteria 1]
2. [Criteria 2]
3. [Criteria 3]

**Priority:** [High/Medium/Low]
**Story Points:** [Estimated Effort in Points]
**Notes:**
- [Additional information or edge cases]

-------------------------------------------------------------

# User Stories
# Admin User Stories
# User Story — Admin Login

**Title:**
As an admin, I want to log into the portal with my username and password, so that I can manage the platform securely.

**Acceptance Criteria:**

Admin can enter username and password.

Credentials are validated securely.

Admin is redirected to the dashboard after successful login.

**Priority:** High
**Story Points:** [Points]
**Notes:**

Show an error message for incorrect credentials.

User Story — Admin Logout

**Title:**
As an admin, I want to log out of the portal, so that I can protect system access.

**Acceptance Criteria:**

Logout option is available on all admin pages.

Session/token is invalidated on logout.

User is redirected to the login page.

**Priority:** High
**Story Points:** [Points]
**Notes:**

Include session timeout for security.

User Story — Add Doctor

**Title:**
As an admin, I want to add doctors to the portal, so that they can manage appointments.

**Acceptance Criteria:**

Admin can access a form to add doctor details.

System validates required fields.

Doctor profile is saved successfully.

**Priority:** High
**Story Points:** [Points]
**Notes:**

Avoid duplicate doctor entries.

User Story — Delete Doctor

**Title:**
As an admin, I want to delete a doctor’s profile, so that inactive or incorrect profiles are removed.

**Acceptance Criteria:**

Admin can view a list of doctors.

Delete option is available for each doctor.

System asks for confirmation before deletion.

**Priority:** Medium
**Story Points:** [Points]
**Notes:**

Consider soft delete instead of permanent removal.

User Story — Run Stored Procedure for Monthly Appointments

**Title:**
As an admin, I want to run a stored procedure in MySQL CLI to get monthly appointment counts, so that I can track usage statistics.

**Acceptance Criteria:**

Admin can run the stored procedure.

System returns appointment counts per month.

Results are readable and accurate.

**Priority:** Medium
**Story Points:** [Points]
**Notes:**

Could later be automated or shown in the dashboard.

# Doctor User Stories
# User Story — Doctor Login

**Title:**
As a doctor, I want to log into the portal, so that I can manage my appointments.

**Acceptance Criteria:**

Doctor can enter username and password.

System validates credentials.

Dashboard loads after successful login.

**Priority:** High
**Story Points:** [Points]
**Notes:**

Secure password handling required.

User Story — Doctor Logout

**Title:**
As a doctor, I want to log out of the portal, so that I can protect my data.

**Acceptance Criteria:**

Logout option is available on all pages.

Session is cleared on logout.

Doctor is redirected to login screen.

**Priority:** High
**Story Points:** [Points]
**Notes:**

Auto-logout after inactivity recommended.

User Story — View Appointment Calendar

**Title:**
As a doctor, I want to view my appointment calendar, so that I can stay organized.

**Acceptance Criteria:**

Calendar displays booked appointments.

Appointments include date, time, and patient details.

Interface is easy to navigate.

**Priority:** High
**Story Points:** [Points]
**Notes:**

Consider color coding by status.

User Story — Mark Unavailability

**Title:**
As a doctor, I want to mark my unavailability, so that patients can only book available time slots.

**Acceptance Criteria:**

Doctor can select dates/times of unavailability.

System prevents bookings during unavailable periods.

Calendar updates automatically.

**Priority:** Medium
**Story Points:** [Points]
**Notes:**

Allow recurring unavailability (optional).

User Story — Update Profile

**Title:**
As a doctor, I want to update my profile with specialization and contact information, so that patients see up-to-date details.

**Acceptance Criteria:**

Doctor can edit specialization and contact information.

Changes are validated.

Updated details appear to patients.

**Priority:** Medium
**Story Points:** [Points]
**Notes:**

Optional: upload profile image.

User Story — View Patient Details for Upcoming Appointments

**Title:**
As a doctor, I want to view patient details for upcoming appointments, so that I can be prepared.

**Acceptance Criteria:**

Doctor can view patient information.

Information includes name, age, and reason for visit.

Data loads only for authorized appointments.

**Priority:** High
**Story Points:** [Points]
**Notes:**

Follow data privacy standards.

# Patient User Stories
# User Story — View Doctors List (No Login Required)

**Title:**
As a patient, I want to view a list of doctors without logging in, so that I can explore options before registering.

**Acceptance Criteria:**

List of doctors is publicly visible.

Doctor details show specialization and availability.

No login is required.

**Priority:** High
**Story Points:** [Points]
**Notes:**

Consider filtering options.

User Story — Patient Signup

**Title:**
As a patient, I want to sign up using my email and password, so that I can book appointments.

**Acceptance Criteria:**

Patient can enter email, password, and details.

System validates fields and prevents duplicates.

Account is created successfully.

**Priority:** High
**Story Points:** [Points]
**Notes:**

Email verification optional.

User Story — Patient Login

**Title:**
As a patient, I want to log into the portal, so that I can manage my bookings.

**Acceptance Criteria:**

Login form accepts email and password.

Credentials are validated.

Patient is taken to dashboard.

**Priority:** High
**Story Points:** [Points]
**Notes:**

Encrypt passwords.

User Story — Patient Logout

**Title:**
As a patient, I want to log out of the portal, so that I can secure my account.

**Acceptance Criteria:**

Logout option is available.

Session ends on logout.

Redirects to login page.

**Priority:** High
**Story Points:** [Points]
**Notes:**

Auto logout after inactivity.

User Story — Book Appointment

**Title:**
As a patient, I want to log in and book an hour-long appointment, so that I can consult with a doctor.

**Acceptance Criteria:**

Patient can select a doctor and available slot.

Appointment is saved for one hour.

Confirmation message is displayed.

**Priority:** High
**Story Points:** [Points]
**Notes:**

Prevent double-booking.

User Story — View Upcoming Appointments

**Title:**
As a patient, I want to view my upcoming appointments, so that I can prepare accordingly.

**Acceptance Criteria:**

Patient sees a list of upcoming appointments.

Details include date, time, doctor name.

Past appointments are separated from upcoming ones.

**Priority:** Medium
**Story Points:** [Points]
**Notes:**

Option to cancel future appointments (optional).