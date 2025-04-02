<div align="center">
  <h2>Voting App</h2>
  <p>The Voting App is a microservices-based web application that allows users to participate in real-time polls.  
  This component enables voting through a webpage and allows users to choose between a <strong>cat</strong> and a <strong>dog</strong>.</p>
</div>

<div align="center">
  <p>The diagram below provides an overview of the various components involved.</p>
  <img src="https://github.com/user-attachments/assets/4ec02b5b-2fef-4db5-bea8-a6969966a3b7" alt="Voting App Architecture" width="600"/>
</div>

<div>
<p><strong>•</strong> A front-end web app in <strong>Python</strong> that lets users vote between two options.</p>
<p><strong>•</strong> A <strong>Redis</strong> database for collecting new votes.</p>
<p><strong>•</strong> A <strong>.NET worker</strong> that processes votes and stores them in a database.</p>
<p><strong>•</strong> A <strong>PostgreSQL</strong> database backed by a <strong>Docker volume</strong> for persistent storage.</p>
<p><strong>•</strong> A <strong>Node.js</strong> web app that displays real-time voting results.</p>
</div>
