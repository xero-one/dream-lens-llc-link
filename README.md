# dream-lens-link
Dream Lens LLC


Description

Dream Lens is a simple yet thick single page web application built with revolutionary technologies and features. 

Stack;




Features
	Front-End
	Power Up page
o	A pseudo-page that displays every 24 hours per unique user session by safely manipulating user’s local storage.

Liquid Video Header
o	Dynamic video hero header with altering height that changes on scroll for greater UX/UI capabilities.

Burger Nav
o	An elegant burger navigation for mobile view ports to reduce clutter in header, navigates to users desired section.

Carousel
o	A simple services section with pure svg (standard vector graphics) embedded into a carousel to nicely display service capabilities which collapses based on viewport size, thus making it mobile friendly.

Strict Form
o	“The bread and butter of the Dream Lens SPWA” is a unique contact form that collects users input and submits it to back-end. This contact form validates user input before submitting data to the back end, its validation features include:
	Profanity watcher 
the form catches profanity in inputs (blocks malicious inquires)

	Input checker
The form checks for empty strings and uses browser native api to validate email submission

	Internal Search (future update)
o	Every application needs some sort of an independent internal search (without the use of Google’s crawlers). As of now once the client adds more content to the website a internal search will be needed, however for now a beautiful collapsing search bar sits in the footer of the SPWA.

Back-end
	Serverless Server
o	Dream Lens has a dedicated serverless server hosted with Firebase. The server has Node.js installed on it to communicate with any web application using JavaScript.

SMTP
o	Dream Lens serverless server has a custom SMTP module to connect to a valid gmail account using OAuth 2 and parses the data from form submissions and sends it to the designated emails.

Email Templates
o	Custom coded email templates using embedded JavaScript for better user experience on both the admin and user side. 
