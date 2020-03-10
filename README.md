# Cesium-React

<h1>Getting Started</h1>
<h2>You will require:</h2>
<ul>
  <li>npm install cesium resium</li>
</ul>

<hr />
<h2>Optional modules</h2>
<ul>
  <li>npm install react-helmet</li>
  <li>npm install react-router-dom</li>
</ul>

<hr />
<h1>Steps</h1>
<ol>
  <li>Run the <b>npx create-react-app</b> to get the environment setup.</li>
  <li>Open the "package.json" file.</li>
  <li>
    Replace the "scripts" section with
    <b>
    "scripts": {
      "start": "craco start",
      "build": "craco build",
      "test": "craco test",
      "eject": "react-scripts eject"
    },
    </b>
  </li>
  <li>Create a <b>"craco.config.js"</b> file in the React root directory (same as the "package.json" file).</li>
  <li>Go to <b>"App.js"</b> and add <b>import { Viewer } from 'resium';</b>.</li>
  <li>Add <b><Viewer /></b> within the return code block.</li>
  <li>Run "npm start" and it should now provide you with the Cesium map within React.</li>
</ol>
