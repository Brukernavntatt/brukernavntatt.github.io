<style>
  /* 1. DEFINE VICHY PALETTE */
  :root {
    --primary-teal: #05AD98;
    --bg-outside: #BBBFBF;
    --muted-gray: #878787;
    --card-white: #FFFFFF;
    --text-dark: #1F2328;
  }

  body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: var(--bg-outside) !important;
    color: var(--text-dark) !important;
  }

  /* 2. TOP BANNER (Cayman Style) */
  .custom-header {
    background-color: var(--primary-teal);
    color: var(--card-white);
    padding: 60px 20px;
    text-align: center;
  }
  .custom-header h1 {
    margin: 0;
    font-size: 2.5em;
    color: var(--card-white) !important;
  }
  .custom-header p {
    margin-top: 8px;
    font-size: 1.1em;
    opacity: 0.95;
    color: var(--card-white) !important;
  }

  /* 3. MAIN CONTENT CARD */
  .main-content {
    max-width: 850px;
    margin: -30px auto 50px;
    background-color: var(--card-white);
    padding: 40px;
    border-radius: 8px;
    border: 1px solid var(--bg-outside);
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
  }

  /* 4. TYPOGRAPHY & ELEMENTS */
  .main-content h1, .main-content h2, .main-content h3 {
    color: var(--primary-teal) !important;
    border-bottom: 2px solid var(--bg-outside);
    padding-bottom: 6px;
  }
  .main-content a {
    color: var(--primary-teal) !important;
    font-weight: 600;
    text-decoration: none;
  }
  .main-content a:hover {
    text-decoration: underline;
  }
  
  /* Sekundærtekst og detaljer bruker #878787 */
  .subtitle, .project-meta {
    color: var(--muted-gray);
    font-size: 0.9em;
  }
  hr {
    border: 0;
    height: 1px;
    background: var(--muted-gray);
    opacity: 0.4;
  }
</style>
