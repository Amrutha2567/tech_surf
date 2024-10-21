# tech_surf
Problem Statement 1: Server-Driven UI — Concepts and Building Blocks
Objective: Build a website where both the content and its layouts are managed through
Contentstack.
Content Types:
Home Page:
The main landing page provides an overview of the website, its purpose, and key
highlights.
About Us:
This section provides information about the company, organization, or individual
behind the website, including its mission, vision, history, and team members.
Services/Products:
Detailed descriptions of services offered or products sold, including features and
pricing.
Blog/News:
Section for articles, updates, news, and blog posts to keep the audience informed
and engaged.
These content types will hold the data for each page, containing only the content without UI
specifications.
A. Visuals (Content Type to hold UI spec):
i. This will store the page layout/templates for each content type listed
above.
Flexible UI JSON specifications should be used to support any layout
design.
UI Builder Requirements: Three Sections
1. Left Sidebar: Contains all available components pre-created by
developers.
2. Canvas: Area where users drag and drop components to adjust the layout
and build templates. This section generates the UI specification.
3. Right Sidebar:
a. Design Tab: Provides design properties, listing all CSS styles to
modify and customize the layout and Visual blocks defined in UI
JSON.
b. Data Tab: Data tab will link the above Content Type fields to the
visuals to populate data from ContentType to Visual blocks.
The page is rendered using the UI specification and content. Any changes made in the builder
or content should reflect directly on the page.
Availability: The UI builder should be accessible as a page-level extension within Contentstack.
Example: The UI builder should be in the lines of platforms like Wix or Squarespace, allowing
for intuitive and flexible design
