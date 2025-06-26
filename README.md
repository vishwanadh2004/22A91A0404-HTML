# 22A91A0404-HTML
# 22A91A0404-HTML
{
"email" : "22a91a04p4@aec.edu.in",
"name"  :  "V.BALAJI VISHWANADH",
"mobile no"  :   "8978072486",
"ROLL NO"  :  '22A91A04P4',
"ACCEESS CODE":  NFwgRT
}



<html>
<html lang="en">
<head>
    <title>Develop a React URL Shortener Web App</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
            color: #333;
        }
        h1 {
            color: #2c3e50;
        }
        h2 {
            color: #34495e;
            margin-top: 30px;
        }
        ul {
            list-style-type: disc;
            margin-left: 20px;
        }
        li {
            margin-bottom: 10px;
        }
        a {
            color: #3498db;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <h1>Develop a React URL Shortener Web App</h1>
    <p>Ensure you've followed the instructions and registered provided in the <a href="#">Campus Hiring Evaluation - Pre-Test Setup</a> document before starting.</p>
    <p>Your task is to develop a user-friendly URL Shortener application that provides core URL shortening functionality and displays analytical insights, all managed within the client-side application.</p>

    <h2>Requirements & Constraints</h2>
    <ul>
        <li><strong>Mandatory Logging Integration:</strong> Your app MUST extensively use the Logging Middleware you created in the Pre-Test Setup stage. Use of inbuilt language loggers or console logging is not allowed.</li>
        <li><strong>Application Architecture:</strong> Implement a React application.</li>
        <li><strong>Authentication:</strong> For the purpose of this evaluation, assume users accessing your APIs are pre-authorized. Your application must not require user registration or login mechanisms for API access.</li>
        <li><strong>Short Link Uniqueness:</strong> All generated short links within the application must be unique. The application must manage this uniqueness</li>
        <li><strong>Default Validity:</strong> If a user does not specify a validity period for a shortened URL, it must default to 30 minutes. Validity input from the user will always be provided as an integer representing minutes.</li>
        <li><strong>Custom Shortcodes:</strong> Users may optionally provide a custom shortcode of their choice. If a shortcode is provided, your service must attempt to use it, ensuring it is unique and valid (e.g., alphanumeric, reasonable length). If no shortcode is provided, your service must automatically generate a unique shortcode.</li>
        <li><strong>Redirection:</strong> When a user accesses a shortened URL (e.g., http://hostname:port/abcd1) from the short URL creation's result page or from the statistics page, the React application must handle the route and redirect them to the original long URL. This implies client-side routing and management of the URL mappings.</li>
    </ul>
</body>
</html>
