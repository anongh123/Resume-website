<!Doctype HTML>
<head><title></title></head>
<body>
<p>
Overview:
I chose the font from Google fonts. It was kept simple throughout for a professional look and capitalised in the heading (name) and bold wherever necessary accordingly
The colour scheme was monochromatic using different shades of blue and was kept consistent throughout,  in accordance with the logo of LinkedIn which gave a very professional look, which already had its corporate connotations and was regarded as a colour of trust & reliability in website design mentioned in the web design course module 2. Such simple font and colour scheme was to adhere to the standards of resume.

Separated page into 5 broad zones: header (with name and linkedin link), navigation bar (linked to sidebar), sidebar (headings for main content), main content (with all descriptions of the resume) and footer with all my contact information. This was dont using display type grid and footer was made using display type flex

The alignment was mostly centered and the spacing was kept evenly in footer and padding used was of 20px and rest accoring to the requirements 

Key features implemented:
1) Responsive design using media queries, enabling consistency across devices with different aspect ratios of website.
2) A clickable LinkedIn button for redirection, with LinkedIn logo, for seamless experience. Got the logo css link from bootstrap icon website, which I copy pasted in the anchor tag.
3) Hover effects for dynamic interactivity and visual appeal, over the headings of navigation bar, which inverted the blue and white colours when cursor was bought over it.
4) I linked headings (in the form of a button) from navigation bar to the respective Heading on sidebar, this provided more interactivity to the website and easy navigation.

Overcoming obstacles:
1) Inconsistent grid sizes, which was resolved through better CSS structuring, using grid-template-areas and height for class sidebar and main-content, and different class for all 7 headings and content of the resume gave me more customisation power. After which I made use of grid-template-columns and grid-template-rows making 7 rows for the sidebar and main content
2) The footer overlapping issue was fixed by inserting a dummy spacer element,  I added an extra box and resized it at the end to make the footer be at that place, wasn’t able to solve the issue otherwise even after taking help of copilot
3) Sidebar and content clashes were corrected by enclosing them in independent, <div> containers, with separate sidebar classes (sidebar1, sidebar2 … sidebar7), similarly for main-conetnt. This gave me more control over the output. I kept the sidebar and respective numbered main-content side by side for better navigating.
4) I tried using fixed display for header, but for some reason the header then overlapped the navigation box, this issue was also not resolved after multiple tries and AI help, so I dropped the plan and any which ways the resume didn’t need any position feature mandatorily.
5) Similarly for cards, I didn’t find any use of cards in a resume, the only linking I wanted to do was done through anchor tag of the LinkedIn page. </p>

<a href="resume.html"> Resume </a>

</body>
</html>
