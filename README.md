<style>
  /* 1. TOPP-BANNER (Mørk teal/blågrå: #2C444C) */
  .page-header {
    background-color: #2C444C !important;
    background-image: none !important; /* Fjerner Cayman sin standard-gradient */
    color: #FFFFFF !important;
  }
  .page-header h1, .project-name, .project-tagline {
    color: #FFFFFF !important;
  }

  /* 2. HOVEDBAKGRUNN FOR RESTEN AV SIDEN (Mørkeblå: #262B40) */
  body {
    background-color: #262B40 !important;
    color: #E2E8F0 !important; /* Lys grå/hvit tekst for god kontrast */
  }

  /* 3. HOVEDOMRÅDET (Innholdet ligger nå direkte på bakgrunnen) */
  .main-content {
    max-width: 850px !important;
    margin: 0 auto 40px auto !important;
    background-color: transparent !important; /* Gjennomsiktig - ingen hvit boks */
    padding: 2rem !important;
    box-shadow: none !important;              /* Ingen skygge */
    border: none !important;
    color: #E2E8F0 !important;
  }

  /* 4. OVERKRIFTER, LENKER OG ELEMENTER */
  .main-content h1, .main-content h2, .main-content h3 {
    color: #64D2FF !important; /* Lys cyan/blå tone på overskrifter som matcher fargene dine */
    border-bottom: 1px solid #3A4260 !important;
    padding-bottom: 6px;
  }
  
  .main-content a {
    color: #64D2FF !important; /* Lystoner på lenkene slik at de "popper" på mørk bakgrunn */
    font-weight: bold;
  }
  .main-content a:hover {
    text-decoration: underline;
  }

  /* Kodeblokker tilpasset mørk bakgrunn */
  .main-content code {
    background-color: #1E2233 !important;
    color: #64D2FF !important;
    border: 1px solid #3A4260 !important;
  }
  .main-content pre {
    background-color: #1E2233 !important;
    border: 1px solid #3A4260 !important;
  }

  /* Sekundærtekst (meta, datoer osv.) */
  .project-meta {
    color: #8E98B7 !important;
    font-size: 0.9em;
  }

  /* Skjuler den automatiske GitHub Pages-bunnteksten */
  .site-footer {
    display: none !important;
  }
</style>

# Velkommen til min Github
Her finner du mine prosjekter!

---

## Prosjekter

### 🖥️ [Proxmox VE & Windows Server 2025](./proxmox-lab/)
<span class="project-meta">Teknologier: Proxmox, Active Directory, DNS, DHCP</span>

Bygging og konfigurering av et virtuelt domenemiljø.
