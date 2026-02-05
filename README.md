# Chess Club Tournament Website

An all-in-one tournament management website built for the **UMass Chess Club Spring Classic Tournament**.  
This site streamlined player registration, payments, and tournament information display, replacing a previously manual workflow based on Google Forms and email validation.

**Live site:** https://websites.umass.edu/chess-rso

---

## Overview

This project was designed and implemented as a **solo project** and used in a **live tournament setting** with **70 players**. The website handled:

- Player registration tracking
- Payment calculation guidance
- Section and standings display
- Integration with SwissSys tournament software
- Clear payment instructions via the UMass Amherst payment portal

The system significantly reduced manual overhead and improved the experience for both players and organizers. A full backup is included in the xml format. See this [guide](https://wordpress.com/support/import/import-a-sites-content/) for how to import this project into your own Wordpress installation.

---

## Screenshots

### Website Navigation
![Screenshot of club website navigation bar](images/Screenshot%202026-02-05%20101629.png)

### Live-Updating Entry List
![An entry list that is updated continuously after each form response](images/Screenshot%202026-02-05%20101652.png)

### Section Information (U1900)
![Screenshot of the U1900 section information](images/Screenshot%202026-02-05%20101706.png)

### Wall Chart (Top 5 – U1900)
![The wall chart of the top 5 in the under 1900 section](images/Screenshot%202026-02-05%20101720.png)

### Registration & Payment Submission
![The submission button of the registration and payment form](images/Screenshot%202026-02-05%20101906.png)

---

## Features

- Tournament information pages by section
- Continuously updated player entry list
- Wall charts generated from SwissSys exports
- Registration form with automatic payment calculation
- Clear instructions and linking to the official UMass Amherst payment portal

---

## Tech Stack

- **WordPress** – CMS and page structure
- **Custom JavaScript** – Payment calculation logic
- **SwissSys** – Tournament pairing and standings generation
- **UMass Amherst Payment Portal** – Secure payment processing (external)

---

## Automation & Data Flow

- Registration data collected via forms
- **Manual import/export workflow**
- SwissSys exported standings and wall charts as HTML files
- Exported HTML manually integrated into the website
- Payments handled entirely outside the site via the UMass portal

> No direct payment processing or storage occurs on the website. All payment was managed through the UMass club payment portal, adhering to UMass policy.

---

## Usage & Impact

- Used live during an official tournament
- Supported **70 registered players**
- Replaced manual email-based validation from Google Forms
- Improved clarity, speed, and reliability for tournament organizers

---

## Reusability

- Designed to be reused for future UMass Chess Club tournaments
- Tournament pages, forms, and workflows can be adapted with minimal changes