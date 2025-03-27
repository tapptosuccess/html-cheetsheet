# HTML Cheat Sheet
HTML Cheat Sheet covering the most challenging topics for beginner HTML developers.

## .htaccess (Used for server configuration)
```
RewriteEngine On
RewriteCond %{HTTPS} !=on
RewriteRule ^ https://%{HTTP_HOST}%{REQUEST_URI} [L,R=301]
```
## Structures (Basic HTML structure)
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page Title</title>
</head>
<body>
    <h1>Welcome to HTML</h1>
</body>
</html>
```
## Create iFrame
```
<iframe src="https://www.example.com" width="600" height="400"></iframe>
```
## Create Image
```
<img src="image.jpg" alt="Description of image" width="300">
```
## robots.txt (Controls search engine crawling)
```
User-agent: *
Disallow: /private-folder/
Allow: /
```
## HTML5 Page Structure
```
<header>Website Header</header>
<nav>Navigation Menu</nav>
<main>Main Content</main>
<aside>Sidebar</aside>
<footer>Footer Content</footer>
```
## Open Graph (For social media previews)
```
<meta property="og:title" content="Website Title">
<meta property="og:description" content="Brief Description">
<meta property="og:image" content="image.jpg">
<meta property="og:url" content="https://example.com">
```
## Head Tags (Essential Meta Tags)
```
<meta charset="UTF-8">
<meta name="description" content="This is an HTML cheat sheet">
<meta name="keywords" content="HTML, Beginner, Cheat Sheet">
<meta name="author" content="Your Name">
```
## Blank Page
```
<!DOCTYPE html>
<html>
<head><title>Blank Page</title></head>
<body></body>
</html>
```
## Attributes (Examples of common attributes)
```
<input type="text" name="username" placeholder="Enter your name">
<button disabled>Disabled Button</button>
```
## Create Link
```
<a href="https://www.example.com" target="_blank">Visit Example</a>
```
## Special Characters
```
&copy; → ©  
&lt; → <  
&gt; → >  
&quot; → "  
```
