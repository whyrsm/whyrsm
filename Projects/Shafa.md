# BelajarShafa

A comprehensive mentoring management system (Sistem Manajemen Mentoring) designed for Indonesian organizations to run structured mentoring programs with class management, learning management system (LMS), attendance tracking, and progress monitoring.

## Business Context

### The Problem

Educational and professional organizations in Indonesia face challenges in:
- Managing mentoring programs at scale with multiple mentors and mentees
- Tracking attendance and participation across distributed sessions
- Delivering structured learning content alongside live mentoring
- Monitoring mentee progress and development over time
- Facilitating communication between mentors and mentees

### The Solution

BelajarShafa provides an integrated platform that enables organizations to:
- Create and manage multiple mentoring classes with co-mentoring support
- Schedule sessions with self check-in attendance system
- Deliver courses with videos, documents, quizzes, and progress tracking
- Track mentee development with private mentor notes
- Foster community through a global discussion forum

### Target Users

| Role | Description | Primary Device |
|------|-------------|----------------|
| **Super Admin** | System administrator with full platform access | Desktop |
| **Manager** | Organization owner who creates classes, manages courses, and views analytics | Desktop |
| **Mentor** | Instructor who conducts sessions, tracks attendance, and monitors mentee progress | Mobile/Desktop |
| **Mentee** | Participant who attends sessions, completes courses, and engages in discussions | Mobile |

## Product Features

### Core Modules

**Authentication & Registration**
- Email/password registration with email verification
- Separate flows for Mentee (direct) and Mentor (requires Manager approval)
- JWT-based authentication with role-based access control (RBAC)
- Password recovery and security features

**Organization Management**
- Multi-organization support per Manager
- Organization dashboard with KPIs and analytics
- Member management (invite mentors, view mentees)
- Customizable settings (timezone, logo, email templates)

**Class Management**
- Multi-mentor classes with lead mentor designation
- Unique invitation codes for mentee enrollment
- Session scheduling with online/offline support
- Self check-in attendance with time window validation
- Manual attendance override for mentors
- Private mentee development notes (visible only to class mentors)

**Learning Management System (LMS)**
- Course creation with topics and sequenced materials
- Material types: YouTube videos, documents (PDF/PPT/DOC), articles, external links
- Quiz system with multiple choice, scoring, and attempt limits
- Course assignment to classes (mandatory/optional with deadlines)
- Progress tracking per user with completion certificates
- Mentor dashboard to monitor mentee progress

**Global Forum**
- Reddit-style discussion threads with upvote/downvote
- Tag-based categorization and search
- Nested comments (up to 3 levels)
- Moderation tools (pin, close, delete, ban)
- User reputation and badges
- Bookmarks and thread following

**User Profile**
- Customizable profile with avatar, bio, skills
- Privacy settings (public, organization-only, class-only, private)
- Notification preferences (email, in-app, digest frequency)

### User Journeys

**Mentee Journey**
1. Register → Verify email → Complete profile
2. Join class via invitation code
3. View upcoming sessions → Self check-in during session
4. Access assigned courses → Complete materials and quizzes
5. Participate in forum discussions
6. Download completion certificates

**Mentor Journey**
1. Register → Await Manager approval → Complete profile
2. Create/join class → Invite co-mentors
3. Schedule sessions → Monitor real-time check-ins
4. Assign courses to class → Track mentee progress
5. Add private development notes for mentees
6. Export attendance and progress reports

**Manager Journey**
1. Create organization → Configure settings
2. Invite and approve mentors
3. Create classes → Assign mentors
4. Build courses with topics and materials
5. Assign courses to multiple classes
6. View analytics dashboard → Export reports