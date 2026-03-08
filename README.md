Huntd Testing Repository

This repository contains all testing documentation, artifacts, and reports for the Huntd project — a comprehensive job search and application tracking platform for web and mobile (Android/iOS). It is organized to support end-to-end testing, from test planning to reporting, covering both web and mobile applications.

Repository Structure

The repository is organized for easy access to all Huntd testing artifacts and includes the following folders and files:
RTM
Link to the Requirements Traceability Matrix, connecting project requirements and features to their corresponding test cases.
Test Reports
Summary reports of executed test cases, including statistics on passed and failed tests, completed test runs, and overall project quality metrics.
Test Plans
Detailed test plans for both web and mobile applications, including testing objectives, strategy, environment setup, and coverage scope.
Jira Bug Examples
Text documents with examples of bugs found during testing, including descriptions, reproduction steps, priority, and status.
Jira Story Examples
Text documents with examples of Jira stories used to track testing tasks and assign responsibilities among team members.
Permission Testing Table
Table verifying functionality for different user roles: logged-out users, candidates, and recruiters.
Test Cases
Web Version — test cases for the web application (desktop and mobile browsers).
Mobile Version — test cases for the mobile application (Android or iOS).
Each test case includes preconditions, test steps, expected results, and actual results.

Key Modules Tested

Main Page
Candidate-facing landing page with registration forms, mobile app banners, and recruiter information.
Candidates List & Profiles
Candidate cards, filtering, profile details, and chat initiation functionality.
Sign Up / Sign In
Candidate and recruiter registration flows with OAuth integrations (Google, LinkedIn, GitHub), profile activation, and permission testing.
Chats
Messaging between recruiters and candidates, including contact sharing and offer/rejection features.
Profile Management
Multi-profile support, social network connections, profile activation/deactivation, and password management.
Web3 Companies & Job Vacancies
Browsing and filtering companies and jobs, posting jobs (for authorized users), subscription forms, and one-click applications.
Mobile App (MVP)
Testing of implemented features such as chat, profile management, and IAM features.
