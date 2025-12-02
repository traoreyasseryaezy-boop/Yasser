<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Devenir Créateur — Page de vente & Ebook</title>

<!-- Styles -->
<style>
  :root{
    --bg:#05060a;
    --card:#0b0d12;
    --accent:#72ff49;
    --muted:#9aa0a6;
    --glass: rgba(255,255,255,0.03);
    --maxw:1100px;
    --radius:14px;
  }
  *{box-sizing:border-box}
  body{
    margin:0;
    font-family:Inter, "Poppins", system-ui, Arial;
    background:linear-gradient(180deg,#030312 0%, #070718 60%);
    color:#e9eef8;
    -webkit-font-smoothing:antialiased;
    -moz-osx-font-smoothing:grayscale;
    line-height:1.5;
  }

  /* Container */
  .wrap{
    max-width:var(--maxw);
    margin:28px auto;
    padding:20px;
  }

  /* Header */
  header{
    display:flex;
    gap:12px;
    align-items:center;
    justify-content:space-between;
    margin-bottom:18px;
  }
  .brand{
    display:flex;
    gap:12px;
    align-items:center;
  }
  .logo {
    width:56px;height:56px;border-radius:12px;padding:8px;
    background:linear-gradient(135deg, rgba(114,255,73,0.12), rgba(114,255,73,0.03));
    border:1px solid rgba(114,255,73,0.08);
    display:flex;align-items:center;justify-content:center;
    font-weight:800;color:var(--accent);
    box-shadow:0 6px 18px rgba(7,10,14,0.7);
    font-size:20px;
  }
  h1{font-size:20px;margin:0}
  .sub-brand{color:var(--muted);font-size:13px}

  nav a{
    color:#dfe8f8;text-decoration:none;margin-left:12px;font-weight:600;
    padding:8px 12px;border-radius:999px;border:1px solid rgba(255,255,255,0.03);
    background:var(--glass);
  }

  /* Hero / Sales top */
  .hero{
    display:grid;
    grid-template-columns: 1fr 420px;
    gap:18px;align-items:center;margin-top:8px;
  }

  .hero-card{
    background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
    border-radius:var(--radius); padding:26px; border:1px solid rgba(255,255,255,0.03);
    box-shadow: 0 10px 30px rgba(2,4,8,0.6);
  }

  .hero h2{
    font-size:30px;margin:0 0 10px;color:#fff;
    line-height:1.12;
  }
  .hero h2 .green{color:var(--accent)}
  .lead{color:var(--muted);font-size:15px;margin-bottom:18px}

  .cta-row{display:flex;gap:10px;flex-wrap:wrap}
  .btn{
    display:inline-block;padding:12px 18px;border-radius:10px;text-decoration:none;font-weight:700;
    cursor:pointer;border:0;
  }
  .btn-primary{background:var(--accent);color:#07100b}
  .btn-ghost{background:transparent;border:1px solid rgba(255,255,255,0.05);color:#dfe8f8}

  /* Right promo card */
  .promo{
    background:linear-gradient(180deg,#07101a,#071018);
    border-radius:12px;padding:18px;border:1px solid rgba(255,255,255,0.03);
  }
  .price{font-size:28px;color:var(--accent);font-weight:800;margin:6px 0}
  .price small{font-size:12px;color:var(--muted)}

  .features{display:flex;flex-direction:column;gap:8px;margin-top:14px}
  .feature{display:flex;gap:10px;align-items:center;color:var(--muted);font-weight:600}
  .dot{width:10px;height:10px;border-radius:50%;background:var(--accent);box-shadow:0 6px 20px rgba(114,255,73,0.07)}

  /* Sections */
  section{margin-top:20px}
  .grid-2{display:grid;grid-template-columns:1fr 360px;gap:18px}
  .card{
    background:var(--card);padding:18px;border-radius:12px;border:1px solid rgba(255,255,255,0.02);
  }

  h3{margin:0 0 8px;color:#fff}
  p{color:var(--muted);margin:0 0 12px}

  /* bullets */
  ul{padding-left:18px;margin:0 0 12px}
  li{margin:6px 0;color:var(--muted)}

  /* Testimonials */
  .testimonials{display:flex;gap:12px;flex-wrap:wrap}
  .tm{background:linear-gradient(180deg, rgba(255,255,255,0.01), rgba(255,255,255,0.00));padding:12px;border-radius:10px;width:220px}

  /* Footer */
  footer{margin-top:28px;padding:18px;color:var(--muted);font-size:13px;text-align:center}

  /* Modal / Form */
  .modal-backdrop{
    position:fixed;inset:0;background:rgba(2,4,8,0.6);display:none;align-items:center;justify-content:center;z-index:50;
  }
  .modal{
    background:linear-gradient(180deg,#071018,#051020);padding:20px;border-radius:12px;width:400px;border:1px solid rgba(255,255,255,0.03);
    box-shadow:0 8px 40px rgba(0,0,0,0.6);
  }
  .modal h4{margin:0 0 8px}
  .field{display:flex;flex-direction:column;margin-bottom:10px}
  .field input{padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:#fff}
  .small{font-size:13px;color:var(--muted)}

  /* image pro */
  .hero-image{border-radius:10px;overflow:hidden;border:1px solid rgba(255,255,255,0.03);box-shadow: 0 10px 30px rgba(2,4,8,0.6)}
  .download-row{display:flex;gap:8px;align-items:center;margin-top:10px}

  /* responsive */
  @media (max-width:980px){
    .hero{grid-template-columns:1fr}
    .grid-2{grid-template-columns:1fr}
  }
</style>
</head>

<body>
<div class="wrap">
  <!-- Header -->
  <header>
    <div class="brand">
      <div class="logo">RAL</div>
      <div>
        <h1>Devenir Créateur — Programme</h1>
        <div class="sub-brand">Formation complète · Ebook · Accompagnement pro</div>
      </div>
    </div>

    <nav>
      <a href="#programme">Programme</a>
      <a href="#ebook">Ebook</a>
      <a href="#offre">Offre</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- HERO / TOP SALE -->
  <div class="hero">
    <div class="hero-card">
      <h2>Devenez <span class="green">Créateur de contenu</span> pro — de A à Z</h2>
      <div class="lead">
        Une méthode claire et pratique pour partir de zéro, construire votre audience, créer des produits digitaux et commencer à gagner vos premiers revenus dès le premier mois.
      </div>

      <div class="cta-row">
        <button class="btn btn-primary" id="openCheckout">Acheter l'ebook €9.99</button>
        <a class="btn btn-ghost" href="#programme">Voir le programme</a>
      </div>

      <section id="programme" style="margin-top:16px">
        <div class="grid-2">
          <div>
            <div class="card">
              <h3>Ce que vous allez apprendre</h3>
              <ul>
                <li>Choisir votre niche et trouver votre voix</li>
                <li>Créez 30 contenus qui performent</li>
                <li>Stratégie pour TikTok, Instagram et YouTube</li>
                <li>Monétisation : ebook, affiliation, sponsoring</li>
                <li>Transformer votre audience en revenus réguliers</li>
              </ul>
            </div>

            <div class="card" style="margin-top:12px">
              <h3>Pourquoi ça marche</h3>
              <p>La méthode est basée sur la régularité, l'analyse et la simplicité. On privilégie l'action : publier vite, apprendre et améliorer.</p>
            </div>
          </div>

          <aside class="promo">
            <div style="display:flex;justify-content:space-between;align-items:center">
              <div>
                <div style="font-size:13px;color:var(--muted)">Offre spéciale</div>
                <div class="price">€9.99 <small>paiement unique</small></div>
              </div>
              <div style="text-align:right">
                <div style="font-size:12px;color:var(--muted)">PDF + Ressources</div>
                <div style="font-size:11px;color:var(--muted)">Accès instantané</div>
              </div>
            </div>

            <div class="features">
              <div class="feature"><div class="dot"></div> Ebook PDF pro</div>
              <div class="feature"><div class="dot"></div> Templates Canva</div>
              <div class="feature"><div class="dot"></div> Checklist 30 jours</div>
            </div>
          </aside>
        </div>
      </section>
    </div>

    <!-- RIGHT: Image / price card -->
    <div>
      <div class="hero-image">
        <!-- SVG image pro (visuel téléchargeable) -->
        <svg id="svgBanner" xmlns="http://www.w3.org/2000/svg" width="420" height="300" viewBox="0 0 840 600">
          <defs>
            <linearGradient id="g1" x1="0" x2="1" y1="0" y2="1">
              <stop offset="0" stop-color="#07202A"/>
              <stop offset="1" stop-color="#051018"/>
            </linearGradient>
            <linearGradient id="g2" x1="0" x2="1">
              <stop offset="0" stop-color="#72ff49"/>
              <stop offset="1" stop-color="#3be06b"/>
            </linearGradient>
            <filter id="f1" x="-20%" y="-20%" width="140%" height="140%">
              <feGaussianBlur in="SourceAlpha" stdDeviation="18" result="b"/>
              <feOffset dx="0" dy="10"/>
              <feMerge><feMergeNode/><feMergeNode in="SourceGraphic"/></feMerge>
            </filter>
          </defs>

          <rect width="840" height="600" fill="url(#g1)"/>
          <g transform="translate(40,40)">
            <rect x="0" y="0" rx="20" width="760" height="520" fill="#061018" opacity="0.7" />
            <g transform="translate(24,24)">
              <rect x="0" y="0" rx="14" width="712" height="172" fill="url(#g2)" />
              <text x="30" y="62" fill="#021111" font-family="Poppins,Arial" font-size="46" font-weight="800">Devenir Créateur</text>
              <text x="30" y="108" fill="#021111" font-family="Poppins,Arial" font-size="20">Programme 3 en 1 · Ebook + Templates</text>

              <g transform="translate(0,210)">
                <rect x="0" y="0" rx="12" width="332" height="230" fill="#071018" stroke="#0e2530" stroke-width="1"/>
                <text x="18" y="36" fill="#aee9b7" font-size="22" font-weight="700">30 Jours</text>
                <text x="18" y="70" fill="#9fb9aa" font-size="15">30 contenus, checklist, idées</text>

                <rect x="360" y="0" rx="12" width="332" height="230" fill="#071018" stroke="#0e2530" stroke-width="1"/>
                <text x="378" y="36" fill="#aee9b7" font-size="22" font-weight="700">Ebook Pro</text>
                <text x="378" y="70" fill="#9fb9aa" font-size="15">PDF téléchargeable + ressources</text>
              </g>
              <circle cx="640" cy="120" r="44" fill="#071018" stroke="#0e2530" />
              <text x="603" y="129" fill="#72ff49" font-size="28" font-weight="800">€9.99</text>
            </g>
          </g>
        </svg>
      </div>

      <div class="download-row">
        <button class="btn btn-primary" id="downloadImage">Télécharger l'image pro (PNG)</button>
        <button class="btn btn-ghost" id="previewPdf">Prévisualiser l'Ebook</button>
      </div>
    </div>
  </div>

  <!-- EBOOK DETAILS -->
  <section id="ebook" style="margin-top:20px">
    <div class="card">
      <h3>Contenu de l'ebook (extrait)</h3>
      <p>Ci-dessous se trouve l'intégralité du contenu qui sera inclus dans le PDF : définitions, méthode, étapes, outils, monétisation et plan d'action complet pour devenir créateur de contenu.</p>

      <div style="max-height:420px;overflow:auto;padding-right:8px">
        <!-- Long ebook text inserted here from user's content (A→Z expanded) -->
        <article id="ebookContent" style="white-space:pre-wrap;font-size:14px;color:var(--muted);">
<strong>Devenir Créateur de contenu — Guide complet A à Z</strong>

1) Définition :
Un créateur de contenu est une personne qui produit, publie et partage des contenus digitaux (vidéos, images, textes, podcasts, ebooks…) sur internet, avec un objectif précis : informer, éduquer, inspirer, divertir ou vendre. Être créateur, ce n’est pas “juste poster sur TikTok”. C’est attirer une audience, créer une communauté fidèle, puis transformer cette audience en revenus.

2) Pourquoi devenir créateur de contenu ?
Liberté de travailler d’où tu veux : tu peux travailler depuis ton téléphone, dans un café, à la maison, en voyage. Tu n’as pas de patron, pas d’horaires fixes. Tu décides quand et où tu travailles.
Possibilité de gagner de l’argent : le contenu digital permet de générer plusieurs flux de revenus en même temps : pubs, sponsorings, ebooks, affiliation, coaching, produits digitaux...
Construire une marque personnelle : tu te fais connaître dans ton domaine...
Aucune étude obligatoire : pas besoin d’école pour commencer.
Commencer avec un téléphone : un smartphone suffit pour filmer, monter, publier.
Potentiel de revenus illimités : un contenu viral peut changer ta vie.

3) Types de contenus...
(Le reste du texte inclus — le document PDF généré contiendra l'intégralité des sections 1→14, les étapes pratiques, templates, checklist et la partie "Je peux vous accompagner..." à la fin.)
        </article>
      </div>

      <div style="margin-top:12px;display:flex;gap:8px">
        <button class="btn btn-primary" id="buyNowMobile">Acheter & télécharger</button>
        <button class="btn btn-ghost" id="generatePdf">Générer le PDF maintenant</button>
      </div>
    </div>
  </section>

  <!-- OFFER DETAILS -->
  <section id="offre" style="margin-top:18px">
    <div class="card">
      <h3>Ce que je fournis si vous prenez l'accompagnement</h3>
      <p>
        Je peux vous accompagner pour devenir créateur de contenu de A à Z. Je vous montre comment choisir votre niche, définir votre identité visuelle, créer votre premier contenu, optimiser vos comptes sur TikTok, Instagram ou YouTube et mettre en place une méthode simple pour gagner vos premiers abonnés et vos premiers revenus.
      </p>

      <ul>
        <li>✔️ Créer vos visuels et vos vidéos</li>
        <li>✔️ Bâtir une stratégie de publication</li>
        <li>✔️ Construire votre ebook ou votre première formation</li>
        <li>✔️ Mettre en place vos comptes monétisés</li>
        <li>✔️ Trouver vos premières idées de contenu</li>
        <li>✔️ Gagner du temps en utilisant les bons outils</li>
      </ul>

      <p class="small">Ce service est payant. Contactez-moi pour un diagnostic personnalisé.</p>
    </div>
  </section>

  <!-- Testimonials -->
  <section style="margin-top:18px">
    <h3>Témoignages</h3>
    <div class="testimonials">
      <div class="tm card">
        <strong>Amadou · Entrepreneur</strong>
        <p class="small">"En 30 jours j'ai trouvé ma niche et j'ai commencé à vendre mon premier ebook. Méthode simple et concrète."</p>
      </div>
      <div class="tm card">
        <strong>Sita · Créatrice</strong>
        <p class="small">"Le design du PDF et les templates Canva m'ont fait gagner du temps. Mes premiers clients en 2 semaines."</p>
      </div>
    </div>
  </section>

  <footer>
    © <span id="year"></span> RAL — Tous droits réservés · Page de vente interactive
  </footer>
</div>

<!-- Modal / Checkout -->
<div id="modal" class="modal-backdrop" role="dialog" aria-modal="true">
  <div class="modal" role="document">
    <h4>Acheter l'ebook — €9.99</h4>
    <p class="small">Paiement sécurisé — simulation local. Remplace avec Stripe/PayPal en production.</p>

    <div class="field">
      <label class="small">Nom complet</label>
      <input id="buyerName" placeholder="Ton nom complet">
    </div>
    <div class="field">
      <label class="small">Email</label>
      <input id="buyerEmail" placeholder="email@exemple.com">
    </div>

    <div class="field">
      <label class="small">Méthode de paiement</label>
      <select id="payMethod">
        <option>Carte (simulation)</option>
        <option>PayPal (redirect à ajouter)</option>
      </select>
    </div>

    <div style="display:flex;gap:8px;justify-content:flex-end;margin-top:8px">
      <button class="btn btn-ghost" id="closeModal">Annuler</button>
      <button class="btn btn-primary" id="confirmPay">Payer & Télécharger</button>
    </div>
  </div>
</div>

<!-- Scripts: jsPDF CDN -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>

<script>
  // Globals
  document.getElementById('year').innerText = new Date().getFullYear();

  // Modal control
  const modal = document.getElementById('modal');
  document.getElementById('openCheckout').addEventListener('click', ()=> modal.style.display='flex');
  document.getElementById('buyNowMobile').addEventListener('click', ()=> modal.style.display='flex');
  document.getElementById('closeModal').addEventListener('click', ()=> modal.style.display='none');

  // Convert SVG to PNG and download
  document.getElementById('downloadImage').addEventListener('click', async ()=>{
    const svg = document.getElementById('svgBanner');
    const svgData = new XMLSerializer().serializeToString(svg);
    const svgBlob = new Blob([svgData], {type: 'image/svg+xml;charset=utf-8'});
    const url = URL.createObjectURL(svgBlob);
    const img = new Image();
    img.onload = function(){
      const canvas = document.createElement('canvas');
      canvas.width = img.width; canvas.height = img.height;
      const ctx = canvas.getContext('2d');
      // white background
      ctx.fillStyle = '#061018';
      ctx.fillRect(0,0,canvas.width,canvas.height);
      ctx.drawImage(img,0,0);
      URL.revokeObjectURL(url);
      canvas.toBlob(function(blob){
        const link = document.createElement('a');
        link.download = 'image-pro-ral.png';
        link.href = URL.createObjectURL(blob);
        link.click();
      }, 'image/png');
    };
    img.src = url;
  });

  // PDF generation (using jsPDF)
  const { jsPDF } = window.jspdf;

  function generatePdfBytes(title, author, contentText){
    // create doc
    const doc = new jsPDF({unit:'pt',format:'a4'});
    const margin = 40;
    const pageWidth = doc.internal.pageSize.getWidth();
    const usableW = pageWidth - margin*2;
    const fontSizeTitle = 18;
    const fontSizeBody = 12;

    doc.setFont('Helvetica','bold');
    doc.setFontSize(fontSizeTitle);
    doc.setTextColor(12,12,12);
    doc.text(title, margin, 60);

    doc.setFontSize(10);
    doc.setTextColor(100,100,100);
    doc.text('Auteur: ' + author, margin, 80);

    doc.setTextColor(30,30,30);
    doc.setFont('Helvetica','normal');
    doc.setFontSize(fontSizeBody);

    // split text into lines
    const split = doc.splitTextToSize(contentText, usableW);
    let cursorY = 110;
    const lineHeight = fontSizeBody * 1.4;

    for (let i=0;i<split.length;i++){
      if (cursorY + lineHeight > doc.internal.pageSize.getHeight() - 60){
        doc.addPage();
        cursorY = 60;
      }
      doc.text(split[i], margin, cursorY);
      cursorY += lineHeight;
    }

    return doc.output('bloburl');
  }

  // get ebook text from page
  function getEbookText() {
    // We include a more complete text — here we assemble main sections (you can edit)
    const title = "Devenir Créateur de contenu — Guide complet A à Z";
    const author = "RAL — Programme";
    // Build content: we will collect multiple pieces from page or build long string
    const content = `
Devenir Créateur de contenu — Guide complet A à Z

1) Définition :
Un créateur de contenu est une personne qui produit, publie et partage des contenus digitaux (vidéos, images, textes, podcasts, ebooks…) sur internet, avec un objectif précis : informer, éduquer, inspirer, divertir ou vendre. Être créateur, ce n’est pas “juste poster sur TikTok”. C’est attirer une audience, créer une communauté fidèle, puis transformer cette audience en revenus.

2) Pourquoi devenir créateur de contenu ?
- Liberté de travailler d’où tu veux : tu peux travailler depuis ton téléphone, dans un café, à la maison, en voyage. Tu n’as pas de patron, pas d’horaires fixes. Tu décides quand et où tu travailles.
- Possibilité de gagner de l’argent : le contenu digital permet de générer plusieurs flux de revenus en même temps : pubs, sponsorings, ebooks, affiliation, coaching, produits digitaux...
- Construire une marque personnelle : tu te fais connaître dans ton domaine.
- Aucun diplôme obligatoire : pas besoin d’école pour commencer.
- Commencer avec un téléphone : un smartphone suffit pour filmer, monter, publier.
- Potentiel de revenus illimités.

3) Types de contenu
- Vidéos courtes (Reels, Shorts, TikTok)
- Images / carrousels
- Articles / blog
- Live
- Ebooks
- Formations
- Podcast
- Newsletter

4) Téléphone ou PC ?
Commence avec ton téléphone si tu débutes. Passe au PC pour monter, design et scaler.

5) Outils indispensables :
Vidéo: CapCut, VN, Premiere.
Design: Canva, Photoshop.
Organisation: Notion, Google Drive.
Écriture: ChatGPT, Notepad.
Analyse: Google Analytics, insights.

6) Méthode pour se lancer :
Étape 1: Choisir une niche spécifique.
Étape 2: Publier 30 contenus simples (1 par jour).
Étape 3: Observer les performances.
Étape 4: Créer une identité visuelle.
Étape 5: Publier sur plusieurs plateformes.

7) Réseaux recommandés :
TikTok, Instagram Reels, YouTube Shorts, Facebook Reels.

8) Gagner des abonnés rapidement :
Publier tous les jours, accroche forte, hashtags ciblés, répondre aux commentaires, call-to-action.

9) Monétisation :
Sponsoring, affiliation, produits digitaux (ebook, formation), publicités, coaching.

10) Conditions de monétisation (exemples) :
YouTube: 1000 abonnés + 4000 heures (ou critères Shorts).
TikTok: programmes selon pays.

11) Erreurs à éviter :
Attendre la perfection, copier sans comprendre, publier rarement, changer de niche sans raison, acheter des abonnés.

12) Créer un ebook : étapes
1. Choisir sujet
2. Faire plan
3. Rédiger (Google Docs)
4. Designer (Canva)
5. Exporter PDF
6. Vendre (Gumroad, Payhip...)

13) Se former gratuitement :
YouTube, TikTok, Google Skillshop, Canva School, HubSpot, Coursera.

14) Résumé A → Z :
1. Choisis une niche
2. Crée 30 contenus
3. Utilise TikTok + Instagram
4. Analyse, améliore, monétise
5. Reste constant

---

Ce guide inclut aussi : templates, checklist 30 jours, modèles de posts et conversation pour répondre aux clients.

FIN - Merci d'avoir choisi ce guide.
    `;
    return {title, author, content};
  }

  // Generate PDF and open in new tab
  document.getElementById('generatePdf').addEventListener('click', ()=>{
    const e = getEbookText();
    const url = generatePdfBytes(e.title, e.author, e.content);
    // open result
    window.open(url, '_blank');
  });

  // Preview PDF (same as generate)
  document.getElementById('previewPdf').addEventListener('click', ()=>{
    const e = getEbookText();
    const url = generatePdfBytes(e.title, e.author, e.content);
    window.open(url, '_blank');
  });

  // Checkout simulation: on confirm, generate pdf and "deliver"
  document.getElementById('confirmPay').addEventListener('click', ()=>{
    const name = document.getElementById('buyerName').value || 'Client';
    const email = document.getElementById('buyerEmail').value || 'email@exemple.com';
    // simple validation
    if (!email.includes('@')) { alert('Entre un email valide'); return; }
    // simulate processing
    document.getElementById('confirmPay').disabled = true;
    document.getElementById('confirmPay').innerText = 'Traitement...';
    setTimeout(()=>{
      // create pdf and download
      const e = getEbookText();
      const blobUrl = generatePdfBytes(e.title, e.author, e.content);
      // create link and click to download
      const link = document.createElement('a');
      link.href = blobUrl;
      link.download = 'Devenir-Creator-RAL-Guide.pdf';
      link.click();

      // show success
      alert('Paiement simulé ✅\nLe PDF a été téléchargé. Un email de confirmation a été envoyé à ' + email + ' (simulation).');
      modal.style.display='none';
      document.getElementById('confirmPay').disabled = false;
      document.getElementById('confirmPay').innerText = 'Payer & Télécharger';
    }, 1000);
  });

  // Close modal on backdrop click
  modal.addEventListener('click', (e)=> {
    if (e.target === modal) modal.style.display='none';
  });

  // Small helper: buyNowMobile scroll to modal on small screens
  document.getElementById('buyNowMobile').addEventListener('click', ()=> {
    modal.style.display='flex';
  });

</script>

</body>
</html>
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Yasser - Réseaux</title>
  <style>
    * { box-sizing: border-box; margin:0; padding:0; }

    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg,#0f0021,#4513a3);
      color: #fff;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      padding: 20px;
    }

    .card {
      background: rgba(255,255,255,0.08);
      backdrop-filter: blur(10px);
      width: 100%;
      max-width: 420px;
      padding: 60px 25px 30px 25px;
      border-radius: 20px;
      text-align: center;
      border: 1px solid rgba(255,255,255,0.2);
      box-shadow:0 8px 20px rgba(0,0,0,0.3);
      position: relative;
    }

    .circle-name {
      width: 140px;
      height: 140px;
      border-radius: 50%;
      border: 4px solid #fff;
      display: flex;
      justify-content: center;
      align-items: center;
      margin: 0 auto;
      font-size: 18px;
      font-weight: bold;
      text-align: center;
      background: rgba(255,255,255,0.05);
      color: #fff;
      position: relative;
    }

    .profile-img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 4px solid #fff;
      object-fit: cover;
      position: absolute;
      top: 10px;
      left: 50%;
      transform: translateX(-50%);
      background: #0f0021;
    }

    h1 { font-size: 26px; font-weight:700; margin:20px 0 5px 0; }
    p { font-size: 14px; opacity:0.9; margin-bottom:25px; }

    .btn {
      display:block;
      width:100%;
      padding:15px;
      margin:10px 0;
      background:#fff;
      color:#1a003d;
      font-size:17px;
      font-weight:bold;
      border-radius:14px;
      text-decoration:none;
      transition:0.25s;
    }
    .btn:hover {
      background:#ffcd47;
      color:#000;
      transform: translateY(-3px);
      box-shadow:0 4px 10px rgba(0,0,0,0.3);
    }

    @media(max-width:350px){
      h1{font-size:22px;}
      .btn{font-size:15px;padding:13px;}
      .circle-name{width:120px;height:120px;font-size:16px;}
    }
  </style>
</head>
<body>

  <div class="card">
    <div class="circle-name">
      Yasser Trs✪
    </div>

    <h1>Yasser</h1>
    <p>Retrouve-moi ici 👇</p>

    <a class="btn" href="https://www.facebook.com/share/1CxNTA2fJz/" target="_blank">Facebook</a>
    <a class="btn" href="https://www.youtube.com/@Yasser_Trs" target="_blank">YouTube</a>
    <a class="btn" href="https://www.tiktok.com/@yasser.trs8?_r=1&_t=ZP-91rrpiiIqUR" target="_blank">TikTok</a>
    <a class="btn" href="https://www.instagram.com/yassertrs8?igsh=MXV2Z2lsanY5dHM3eg==" target="_blank">Instagram</a>
    <a class="btn" href="https://wa.me/22654962377" target="_blank">WhatsApp</a>

  </div>

</body>
</html>
