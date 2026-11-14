# Engineering Portfolio — C. Bhavith Sai

A responsive static portfolio documenting engineering projects across embedded systems, robotics, mechatronics, soft robotics and biomedical signal processing.

## Live website

https://cbhavithscultural-cloud.github.io/engineering-portfolio/

## Site structure

- `index.html` — portfolio landing page and selected project cards
- `projects/sentry.html` — SENTRY embedded hardware case study
- `projects/mobile-robot.html` — ROS 2 / Gazebo simulation case study
- `projects/respiratory-monitoring.html` — offline respiratory dataset analysis case study
- `projects/emg-soft-gripper.html` — SOFA soft-gripper simulation case study
- `assets/css/style.css` — landing-page design
- `assets/css/project.css` — shared case-study styling
- `assets/js/main.js` — mobile navigation and current year

## Project scope and accuracy

The project cards and case studies distinguish implementation types:

- **SENTRY:** embedded hardware project using STM32F407 and ESP32-C3.
- **Adaptive Mobile Robot:** ROS 2 / Gazebo simulation.
- **Respiratory Monitoring:** offline analysis of the PhysioNet BIDMC dataset.
- **Adaptive EMG Soft Robotic Gripper:** SOFA simulation using a synthetic EMG signal.

The portfolio does not claim clinical validation, real-time patient monitoring, live EMG acquisition, or physical validation of simulated systems. Results and status labels should be updated only when supported by repeatable tests.

## Editing and deployment

The site is published with GitHub Pages from the `main` branch and repository root. Edit the HTML and CSS files directly; each commit triggers a Pages build and deployment.


## Career OS

A separate local-first application workspace is available at `/career/`:

- Opportunity pipeline with stages, follow-up dates, notes and role links
- Search and stage filters, CSV export and JSON backup/restore
- Keyword-overlap role-fit helper based on documented project skills
- Role-specific outreach email composer and a lightweight career guidance helper
- Browser-local storage; application notes are not sent to a server

The dashboard is a static front-end prototype. It does not yet connect to Gmail, LinkedIn or job boards, and it does not submit applications or send messages. Do not store credentials or sensitive documents in the public repository. The public site is not an authenticated private workspace.
