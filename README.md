# Sole-Stride-Footwear-WEDE5020-POE-Part

# Student Information: ST10516045 


Table of contents
Contents
1. Research and planning	2
1.1 Website Proposal 1 chosen	2
1.	Organisation Overview	2
•	Introduction	2
•	Brief History of the Organisation	2
•	Mission statement	3
•	Vison Statement	3
•	Target Audience	3
2.	Website Goals and Objectives	3
Website Goals	3
Website Objectives	3
Key Performance Indicators & Goals	3
3.	Current Website Analysis	4
•	Strengths:	4
•	Weaknesses:	4
•	Improvements:	4
4.	Proposed Website Pages	4
The website will have 6 simple pages:	4
5.	Design and User Experience (UX)	4
Fonts	5
User Experience Steps	5
6.	Technical Requirements	5
7.	Project Timeline	5
8.	Estimated Budget	5
Bibliography	7
Conclusion	7

# Organization Overview
//Organization Overview 
1. Organization Overview 
Introduction
Sole & Stride footwear is a shoe brand that makes high-quality, durable, and stylish shoes at affordable prices. The brand offers shoes for sports, daily wear, and formal events. The official website will be built using HTML, CSS, and JavaScript in Visual Studio Code.

# History of the organization
// History of the organization
Brief History of the Organization
Shoe designer Marcus Vance started Sole & Stride Footwear in 2025 to give customers comfortable, modern, and strong shoes. It began as a small shop selling sneakers and leather boots. The business grew quickly because customers loved the products. (Education., 2022)

//Website Objectives and Goals 
2.	Website Goals and Objectives

Website Goals

The main goal is to create a clean, professionals’ website for Sole & Stride Footwear so customers can view shoes, check details, and contact the business online.

Website Objectives

•	Help people learn about the Sole & Stride Footwear brand online.
•	Display the full connection of shoes. 
•	Provide clear shoe size guides, material details, and prices.
•	Make it easy for customers send messages through simple forms.
•	Make the website easy to use computers, tablets, and phones. 

//Key features and functionality
Key Performance Indicators & Goals 

•	Monthly Website Visitors: Reach 1,000 visitors per month in the first year.
•	Product Inquiries: Increase customer questions by 30% over six months.
•	Page Loading Speed: Keep loading time under 3 seconds so users do not leave. (Nielsen, 2020)
•	Mobile Compatibility: Ensure the site works perfectly on all mobile devices and laptops. (Garrett, 2011)
•	Website Availability: Keep the website online 99% of the time. 


// Website pages 
4.	Proposed Website Pages 
The website will have 6 simple pages:
•	Home Page: Display a welcome banner, popular shoes, a brief introduction, and main investigation links.
•	About Us Page: Shares the brand story, mission, materials used, and focus on sustainability.
•	Products Page: Displays all shoes under three groups with prices and sizes.
•	Services Pages: Explains extra services like fitting advice, shoe care guides, bulk orders, and product warranties.
•	Enquiry Page: Contains simple forms where customers can ask about shoe sizes or stock availability.
•	Contact Us Page: Shows shop addresses, phone numbers, email addresses, business hours, and a map.

7.	Project Timeline

Timeframe	Key Tasks

Week 1 (Early August)	
Planning & Design: Define page layout, map site structure, and collect product photos.

Weeks 2–4 (Mid–Late August)	
Core Development: Write HTML layout, style pages with CSS, and add interactive JavaScript form features.

Weeks 5–6 (Early September)	
Testing & Launch: Deploy the site, test screen responsiveness across mobile devices, and fix any styling issues.

Weeks 7–8 (Mid–Late September)	
Review & Submission: Gather user feedback, optimize page speed, and complete final project submission.


# SiteMap
SITEMAP
                           Home
                       (index.html)
                            │
      ┌───────────────┬───────────────┬───────────────┐
      │               │               │               │
   About Us        Products        Services        Enquiry
 (about.html)   (products.html) (services.html) (enquiry.html)
      │               │               │
      └───────────────┴───────────────┘
                      │
                  Contact Us
                (contact.html)




  # References 

  Bibliography
AI, O., 2026. Gemini. [Online] 
Available at: https://gemini.google.com/app/719e0b2a3da3b0c9?hl=en_GB
[Accessed 29 August 2026].
Education., T. I. I. o., 2022. The Independent Institute of Education (IIE), 2022. . In: Web Development (WEDE5020) Manual.. Johannesburg: s.n.
Frain, B., 2020. Responsive Web Design with HTML5 and CSS3. 3rd ed. Birmingham: Packt Publishing.. [Online] 
[Accessed 29 August 2026].
Garrett, J., 2011. The Elements of User Experience: User-Centered Design for the Web and Beyond. 2nd ed. Berkeley: New Riders.. [Online] 
[Accessed 29 August 2026].
Lidwell, W. H. K. a. B. J., 2010. Universal Principles of Design. 2nd ed. Beverly: Rockport Publishers.. [Online] 
[Accessed 29 August 2026].
Nielsen, J., 2020. Usability Engineering. San Diego: Academic Press.. [Online] 
[Accessed 29 August 2026].
Norman, D., 2013. The Design of Everyday Things. Revised ed. New York: Basic Books.. [Online] 
[Accessed 29 August 2026].





# Sole-Stride-Footwear-WEDE5020-POE-Part-2

# CSS CODE FOR THE WEBSITE

/* The base styles */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333333;
    max-width: 900px;
    margin: 0 auto;
    padding: 20px;
}

/* Ensure all images scale fluidly and stay visible */
img {
    max-width: 100%;
    height: auto;
    display: block;
    object-fit: cover;
}

/* Specific styling for collection grid images in the website */
.collection-grid article img {
    width: 100%;
    height: 220px;
    border-top-left-radius: 8px;
    border-top-right-radius: 8px;
    background-color: #f1f5f9; /* Fallback gray box while image loads */
}

/* Header logo display rules */
.logo-container img {
    margin: 0 auto 10px;
    max-width: 200px;
}

/* The header and navigation section */
header h1 {
    color: #1a252f;
    margin-bottom: 10px;
}

nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    gap: 15px;
}

nav a {
    text-decoration: none;
    color: #2c3e50;
    font-weight: bold;
}

nav a:hover {
    color: #e67e22;
}

/* Headings section */
h2 {
    color: #2c3e50;
    border-bottom: 2px solid #e67e22;
    padding-bottom: 5px;
    margin-top: 25px;
}

h3 {
    color: #34495e;
    margin-top: 15px;
    margin-bottom: 5px;
}

/* The footer Line */
footer {
    text-align: center;
    font-size: 0.9em;
    color: #7f8c8d;
    margin-top: 20px;
}



# Reference
Bibliography 
https://gemini.google.com/app/2517d0dd894e3c08?hl=en_GB
















































