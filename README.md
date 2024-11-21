Job Application System

This repository contains the code for a Job Application System consisting of three main pages: a job application form, a list of job postings, and a detailed job description page. The backend is powered by MongoDB and Mongoose for database management.


Table of Contents

Overview

Technologies Used

Frontend Structure
Job Application Form
List of Jobs
Job Details Page

Backend Structure
Applicant Model
Job Model

Setup Instructions
Overview
This Job Application System allows users to view available job postings, submit applications, and view detailed job descriptions. The application features a responsive design and provides a user-friendly interface for both job seekers and employers.

Technologies Used
HTML
CSS (with Tailwind CSS framework)
JavaScript
MongoDB
Mongoose

Frontend Structure

Job Application Form
The job application form allows users to submit their applications. The form includes fields for the applicant's name, email, and resume upload. Upon submission, a success message is displayed.

List of Jobs
This page displays a grid of available job postings, each showing the job title, company name, and a brief description. Users can click a button to view more details about each job.

Job Details Page
This page provides detailed information about a specific job, including responsibilities, requirements, and what the company offers. There is also an "Apply" button for users to submit their applications

Backend Structure

Applicant Model
The Applicant model defines the structure for applicant data in the database. It includes fields for job ID, name, email, and resume.

Job Model
The Job model defines the structure for job postings in the database. It includes fields for job title, description, location, and company name.
