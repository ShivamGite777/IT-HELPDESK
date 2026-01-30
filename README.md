# ABC Tech IT Helpdesk System

A comprehensive frontend web interface for an internal company IT Helpdesk Ticketing System. This system provides role-based dashboards for Employees, IT Technicians, and Administrators to manage and track IT support tickets.

## Features

### Login System
- Role-based authentication (Employee, Technician, Admin)
- Clean, professional login interface
- Form validation

### Employee Portal
- Personal dashboard with ticket statistics
- Create new support tickets with AI-powered classification
- View ticket history and status
- Track ticket progress in real-time

### Technician Dashboard
- View assigned tickets organized by status
- Start work on tickets
- Mark tickets as resolved
- Add resolution notes
- Performance metrics

### Admin Dashboard
- Complete system overview
- Ticket analytics and trends
- Technician workload management
- SLA monitoring
- Recent activity tracking
- Performance metrics

## Technology Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom styling with CSS variables
- **Bootstrap 5.3** - Responsive layout and components
- **JavaScript (ES6)** - Form validation and interactions
- **LocalStorage** - Session management

## Project Structure

```
IT-HELPDESK/
├── index.html                    # Login page
├── employee-dashboard.html       # Employee dashboard
├── create-ticket.html           # Create new ticket form
├── ticket-status.html           # Ticket history and status
├── technician-dashboard.html    # Technician workspace
├── admin-dashboard.html         # Admin panel
├── styles.css                   # Global styles
└── README.md                    # Documentation
```

## Pages Overview

### 1. Login Page (index.html)
- Company email input
- Password field
- Role selection dropdown
- Form validation
- Redirects to appropriate dashboard based on role

### 2. Employee Dashboard (employee-dashboard.html)
- Welcome banner with user name
- Statistics cards (Total, Open, Resolved tickets)
- Table of submitted tickets with status badges
- Quick access to create new ticket

### 3. Create Ticket Page (create-ticket.html)
- Ticket title field
- Department selection
- Detailed problem description
- Contact information (optional)
- Location field (optional)
- AI classification notification
- Success modal on submission

### 4. Ticket Status/History Page (ticket-status.html)
- Detailed view of all tickets
- Activity timeline for each ticket
- Status filtering
- Search functionality
- Resolution notes for closed tickets

### 5. Technician Dashboard (technician-dashboard.html)
- Personal statistics
- Tabbed interface (Open, In Progress, Resolved)
- Ticket cards with action buttons
- Start work and resolve functionality
- Resolution notes textarea

### 6. Admin Dashboard (admin-dashboard.html)
- System-wide statistics
- Ticket trends visualization placeholders
- Category distribution charts
- Technician workload table
- All tickets overview with filters
- Recent activity feed
- Performance metrics

## Design Features

### Color Scheme
- Primary: Deep Blue (#2c5282)
- Secondary: Gray (#4a5568)
- Accent: Bright Blue (#3182ce)
- Success: Green (#38a169)
- Warning: Orange (#dd6b20)
- Danger: Red (#e53e3e)

### UI Components
- Bootstrap cards for content organization
- Color-coded badges for status and priority
- Responsive tables
- Professional navigation bar
- Statistics cards with icons
- Progress bars and charts
- Modal dialogs

### Responsive Design
- Mobile-friendly layout
- Tablet optimization
- Desktop-first approach
- Flexible grid system
- Collapsible navigation on small screens

## How to Use

### Getting Started
1. Open `index.html` in a web browser
2. Enter any email address
3. Enter any password
4. Select a role:
   - **Employee**: Access employee dashboard and ticket creation
   - **Technician**: Access technician workspace
   - **Admin**: Access admin panel with full system overview

### Navigation
- Use the top navigation bar to switch between sections
- Click "Logout" to return to login page
- All navigation is client-side (no backend required)

### Creating Tickets (Employee)
1. Navigate to "New Ticket" from the dashboard
2. Fill in ticket title and description
3. Select your department
4. Submit the form
5. System will auto-generate a ticket ID

### Managing Tickets (Technician)
1. View assigned tickets in different tabs
2. Click "Start Work" to begin working on a ticket
3. Add resolution notes
4. Click "Mark as Resolved" when complete

### System Monitoring (Admin)
1. View overall system statistics
2. Monitor technician workload
3. Track SLA breaches
4. Filter and search all tickets
5. Reassign tickets as needed

## Key Features

### AI-Powered Classification
The system indicates automatic ticket classification and prioritization based on the description provided by employees.

### Status Tracking
Tickets progress through states:
- **Open**: Newly created, awaiting assignment
- **In Progress**: Being actively worked on
- **Resolved**: Solution implemented
- **Closed**: Confirmed and archived

### Priority Levels
- **Critical**: Immediate attention required
- **High**: Urgent, affects productivity
- **Medium**: Standard priority
- **Low**: Can be scheduled

### Form Validation
- Required field checking
- Email format validation
- Real-time feedback
- Bootstrap validation styling

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Notes

- This is a frontend-only implementation
- No backend server or database required
- Data is stored in browser localStorage
- All interactions are simulated
- Perfect for demonstrations and prototypes

## Future Enhancements (Not Implemented)

- Backend API integration
- Database persistence
- Real-time notifications
- File attachment support
- Email notifications
- Advanced analytics with charts
- User management
- Authentication system
- Search and filtering
- Export functionality

## License

This project is created for educational and demonstration purposes.