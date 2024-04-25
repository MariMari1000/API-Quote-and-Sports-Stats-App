

<body>

<h1>SportsQuoteStats</h1>

<p>SportsQuoteStats is a mobile application built with Angular and Ionic framework for displaying quotes and sports player statistics.</p>

<h2>Project Overview</h2>

<p>SportsQuoteStats provides users with the ability to view random quotes and sports player statistics based on user-defined criteria. It leverages Angular for frontend development, Ionic framework for mobile UI components, and integrates with external APIs for data retrieval.</p>

<h3>Features</h3>

<ul>
<li><strong>Home Page:</strong>
<ul>
<li>Displays a random quote fetched from the <a href="https://api.quotable.io/random">Quotable API</a>.</li>
<li>Allows navigation to the Settings page for customizing player statistics filters.</li>
            </ul>
        </li>
<li><strong>Settings Page:</strong>
<ul>
<li>Enables users to input a country ID, minimum age, and maximum age to filter sports player statistics.</li>
<li>Utilizes local storage to save user preferences for persistent customization.</li>
            </ul>
        </li>
    </ul>

<h2>Project Structure</h2>

<pre>
Folder PATH listing for volume OS
Volume serial number is 94B5-1205
C:.
|   index.html
|   manifest.json
|   output.doc
|   service-worker.js
|   
+---app
|   |   app.component.ts
|   |   app.html
|   |   app.module.ts
|   |   app.scss
|   |   main.ts
|       
+---assets
|   +---icon
|   |       favicon.ico
|   |       
|   \---imgs
|           logo.png
|           
+---pages
|   +---home
|   |       home.html
|   |       home.scss
|   |       home.ts
|   |       
|   \---settings
|           settings.html
|           settings.module.ts
|           settings.scss
|           settings.ts
|           
+---providers
|   +---quotes
|   |       quotes.ts
|   |       
|   \---stats
|           stats.ts
|           
\---theme
        variables.scss
    </pre>

<h2>Installation and Setup</h2>

<p>Follow these steps to set up and run the SportsQuoteStats application locally:</p>

<h3>Prerequisites</h3>

<p>Node.js and npm installed on your machine.</p>

<h3>Clone the Repository</h3>

<pre><code>git clone &lt;repository_url&gt;
cd SportsQuoteStats
    </code></pre>

<h3>Install Dependencies</h3>

<pre><code>npm install
    </code></pre>

<h3>Run the Application</h3>

<p>Use Ionic CLI to serve the application in a development environment:</p>

<pre><code>ionic serve
    </code></pre>

<p>This command will launch the application in your default web browser.</p>

<h2>Usage</h2>

<ol>
<li><strong>Home Page:</strong>
<ul>
<li>Navigate to the home page (<code>http://localhost:8100/home</code>) to view a random quote.</li>
<li>Click on the settings icon to access the Settings page.</li>
            </ul>
        </li>
        <li><strong>Settings Page:</strong>
            <ul>
                <li>Enter a country ID, minimum age, and maximum age to filter sports player statistics.</li>
                <li>Click the "SAVE" button to save preferences and retrieve updated statistics.</li>
                <li>Click the "CANCEL" button to return to the home page.</li>
            </ul>
        </li>
    </ol>

<h2>Contributing</h2>

<p>Contributions to SportsQuoteStats are welcome! If you'd like to contribute to the project, please follow these guidelines:</p>

<ol>
<li>Fork the repository.</li>
<li>Create a new branch (<code>git checkout -b feature/your-feature</code>).</li>
<li>Commit your changes (<code>git commit -am 'Add new feature'</code>).</li>
<li>Push your changes to the branch (<code>git push origin feature/your-feature</code>).</li>
<li>Create a new Pull Request.</li>
    </ol>

<h2>License</h2>

<p>This project is licensed under the <a href="LICENSE">MIT License</a>.</p>

</body>

</html>
