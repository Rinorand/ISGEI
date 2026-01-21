[index.html](https://github.com/user-attachments/files/24765418/index.html)
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="developpeur" content="page ISGEI">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ISGEI - Site Complet</title>
  <style>
    body {
      margin:0;
      font-family:"Times New Roman", serif;
      background-color:#111;
      color:white;
      scroll-behavior: smooth;
    }

    /* ===== MENU FIXE ===== */
    .menu{
      position:fixed;
      top:0;
      width:100%;
      background-color:#222;
      z-index:100;
    }
    .menu ul{
      list-style:none;
      display:flex;
      justify-content:center;
      padding:10px 0;
      margin:0;
    }
    .menu li{
      margin:0 30px;
    }
    .menu a{
      text-decoration:none;
      color:white;
      font-weight:bold;
      font-size:20px;
      transition:all 0.3s ease;
    }
    .menu a:hover{
      color:#ffd700;
      transform:scale(1.2);
    }

    /* ===== HEADER ===== */
    .header {
      display: flex;
      align-items: center;
      background: linear-gradient(90deg, #222, #333);
      padding:150px 40px 60px 40px;
      gap: 20px;
      margin-top:50px;
    }
    .header img.left {
      width: 150px;
      height:auto;
      border-radius:10px;
      border:2px solid #ffd700;
    }
    .header-text{
      display:flex;
      flex-direction:column;
    }
    .header-text h2{
      margin:0;
      font-size:36px;
      color:#ffd700;
    }
    .header-text p{
      margin:5px 0 0 0;
      font-size:16px;
      line-height:1.5;
      max-width:700px;
      color:#ccc;
    }
    .header-text strong{
      color:white;
    }

    /* ===== SECTIONS ===== */
    section{
      padding:100px 20px 60px 20px;
      text-align:center;
    }
    h1{
      font-size:50px;
      margin-bottom:20px;
      text-shadow:2px 2px 10px rgba(0,0,0,0.7);
    }
    p{
      font-size:18px;
      color:#ccc;
      max-width:800px;
      margin:auto;
    }

    /* ===== BOUTON ===== */
    .btn{
      display:inline-block;
      padding:12px 25px;
      margin:20px 0;
      background-color:#4a90e2;
      color:white;
      font-size:18px;
      font-weight:bold;
      text-decoration:none;
      border-radius:8px;
      transition:background-color 0.3s, transform 0.3s;
    }
    .btn:hover{
      background-color:#50c8ff;
      transform:scale(1.1);
    }

    /* ===== CARTES ===== */
    .cards{
      display:flex;
      justify-content:center;
      flex-wrap:wrap;
      gap:30px;
      padding:40px 20px 0 20px;
    }
    .card{
      background-color:#222;
      border-radius:10px;
      overflow:hidden;
      width:250px;
      transition:transform 0.3s, box-shadow 0.3s;
    }
    .card img{
      width:100%;
      height:150px;
      object-fit:cover;
    }
    .card h3{
      margin:10px;
      font-size:20px;
    }
    .card p{
      margin:0 10px 10px;
      font-size:14px;
      color:#ccc;
    }
    .card:hover{
      transform:scale(1.05);
      box-shadow:0 10px 20px rgba(255,215,0,0.5);
    }

    /* ===== FORMULAIRE CONTACT ===== */
    .form-contact{
      padding:40px 20px;
      max-width:600px;
      margin:auto;
      text-align:left;
    }
    .form-contact input, .form-contact textarea{
      width:100%;
      padding:12px;
      margin:10px 0;
      border-radius:6px;
      border:none;
    }
    .form-contact button{
      background-color:#4a90e2;
      color:white;
      padding:12px 20px;
      font-size:18px;
      font-weight:bold;
      border:none;
      border-radius:8px;
      cursor:pointer;
      transition:0.3s;
    }
    .form-contact button:hover{
      background-color:#50c8ff;
    }

    /* ===== FOOTER ===== */
    footer{
      text-align:center;
      padding:20px;
      background-color:#222;
    }

    /* ===== RESPONSIVE ===== */
    @media(max-width:800px){
      .menu ul{flex-direction:column;}
      .menu li{margin:10px 0;}
      .cards{flex-direction:column;align-items:center;}
      .header{flex-direction:column;text-align:center;padding:100px 20px;}
    }
  </style>
</head>
<body>

<!-- MENU FIXE -->
<nav class="menu">
  <ul>
    <li><a href="#accueil">Accueil</a></li>
    <li><a href="#filiere">Filières</a></li>
    <li><a href="#partage">Partage</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<!-- HEADER -->
<header class="header">
  <img src="https://lh3.googleusercontent.com/p/AF1QipNcvYSnS3ZHAPeOSbTZNhHCOEneNzgiE9neFSQZ=s680-w680-h510-rw" alt="Photo ISGEI" class="left">
  <div class="header-text">
    <h2>ISGEI</h2>
    <p>
      <strong>L’Institut Supérieur de Génie Électronique et Informatique (ISGEI)</strong> est un établissement d’enseignement supérieur spécialisé dans les domaines de l’électronique, de l’informatique et des télécommunications. Il propose des formations en <strong>réseaux informatiques</strong>, <strong>big data</strong>, <strong>télécommunications</strong>, <strong>navigation aérienne</strong> et <strong>développement web</strong>.
    </p>
  </div>
</header>

<!-- SECTION PUBLICITÉ INSTITUT AVEC STYLE INTERFACE -->
<section id="pub-institut" class="pub-institut">

  <!-- CÔTÉ GAUCHE : Madagascar -->
  <div class="pub-left">
    <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAQQAAACtCAMAAABhsvGqAAAALVBMVEX////5QjoAhD3/PzoAhj2lZjv9zMv5MCXL2swAfCn+LCXm08ugWyfI28wAfimpTgZWAAABOElEQVR4nO3Qx40YARAEsZuWt/mHK6hy2McCZAj8+HjE12/3Is8cSJAgQYIECRIkSJAgQYIECRIkSJAgQYIECRIkSJAgQYIECf9JOAmRcBIi4SREwkmIhJMQCSchEk5CJJyESDgJkXASIuEkRMJJiISTEAknIRJOQiSchEg4CZFwEiLhJETCSYiEkxAJJyESTkIknIRIOAmRcBIi4STkqYSfn17koYRfv7+8yEMJf/5+fpGHEr7/2ItImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIRImIT8AyQivZ3TnPujAAAAAElFTkSuQmCC" alt="Madagascar">
  </div>

  <!-- TEXTE AU MILIEU -->
  <div class="pub-text">
    <h2>Découvrez ISGEI !</h2>
    <p>
      <strong>ISGEI – L’Institut Supérieur de Génie Électronique et Informatique</strong> forme les étudiants aux métiers du futur dans les domaines du <strong>réseaux</strong>, <strong>Big Data</strong>, <strong>télécommunications</strong>, <strong>navigation aérienne</strong> et <strong>développement web</strong>. Nos étudiants réalisent des projets innovants et participent à des ateliers pratiques pour relever les défis technologiques de demain.
    </p>
  </div>

  <!-- CÔTÉ DROIT : Ordinateur / style hacker -->
  <div class="pub-right">
    <img src="data:image/jpeg;base64,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" alt="Ordinateur">
  </div>

</section>

<style>
/* ===== SECTION PUBLICITÉ ===== */
.pub-institut {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: linear-gradient(135deg,#0d0d0d,#1a1a1a);
  padding:80px 40px;
  border-radius:15px;
  max-width:1200px;
  margin:50px auto;
  box-shadow:0 10px 30px rgba(0,0,0,0.6);
  color:white;
  gap:20px;
  flex-wrap: wrap;
  transition:all 0.3s ease;
}

/* CÔTÉ GAUCHE & DROIT */
.pub-left img, .pub-right img {
  max-width:200px;
  height:auto;
  border-radius:10px;
  transition: transform 0.5s;
}
.pub-left img:hover {
  transform: rotate(-5deg) scale(1.05);
}
.pub-right img:hover {
  transform: rotate(5deg) scale(1.05);
}

/* TEXTE AU MILIEU */
.pub-text {
  flex:2;
  text-align:center;
  min-width:300px;
}
.pub-text h2 {
  font-size:48px;
  margin-bottom:20px;
  font-family:'Georgia', serif;
  text-shadow: 2px 2px 12px rgba(0,0,0,0.7);
}
.pub-text p {
  font-size:18px;
  line-height:1.8;
  max-width:700px;
  margin:auto;
  color:#ddd;
}

/* RESPONSIVE */
@media(max-width:900px){
  .pub-institut {
    flex-direction:column;
    text-align:center;
    padding:60px 20px;
  }
  .pub-left, .pub-right, .pub-text {
    flex:unset;
    margin:20px 0;
  }
}
</style>

<section id="accueil">
  
  <p>Découvrez les projets, actualités et réalisations des étudiants de l’ISGEI dans les domaines du réseaux informatiques, Big Data, télécommunications et développement web. Cette plateforme met en avant leurs compétences, leurs travaux pratiques et leurs expériences, permettant de suivre l’évolution des étudiants et leurs contributions innovantes.</p>

<!-- BOUTON -->
<button id="openSite" class="btn">Visitez le site officiel</button>

<!-- MODALE IFRAME -->
<div id="modal" style="display:none; position:fixed; top:0; left:0; width:100%; height:100%; background:rgba(0,0,0,0.8); justify-content:center; align-items:center;">
  <div style="position:relative; width:90%; max-width:600px;">
    <button id="closeModal" style="position:absolute; top:-15px; right:-15px; background:#ffd700; border:none; border-radius:50%; width:30px; height:30px; cursor:pointer;">X</button>
    <iframe src="https://www.facebook.com/plugins/post.php?href=https%3A%2F%2Fwww.facebook.com%2Fisgei%2Fposts%2Fpfbid031kd17u9Lp2gnsmNtQXJiw3nUAmhuaFzwei1umzjpMP32ymqjLSfr7NwrkPgpgViGl&show_text=true&width=500" 
      width="100%" height="600" style="border:none; border-radius:10px;" allowfullscreen></iframe>
  </div>
</div>

<script>
  const openBtn = document.getElementById('openSite');
  const modal = document.getElementById('modal');
  const closeBtn = document.getElementById('closeModal');

  openBtn.onclick = () => { modal.style.display = 'flex'; }
  closeBtn.onclick = () => { modal.style.display = 'none'; }
</script>

<!-- SECTION DISSERTATION AVEC SPOTLIGHT -->
<section id="avantages-filieres" class="avantages-filieres">

  <!-- SPOTLIGHT -->
  <div class="spotlight"></div>

  <!-- HEADER -->
  <div class="section-header">
    <h2>Les Avantages de l'ISGEI</h2>
    <p>Découvrez la richesse des filières et ce qui rend notre institut unique.</p>
  </div>

  <!-- TEXTE LONG / DISSERTATION -->
  <div class="dissertation">
    <p>
      L’Institut Supérieur de Génie Électronique et Informatique (ISGEI) se distingue par sa capacité à former des étudiants compétents et polyvalents dans des domaines technologiques variés, répondant aux besoins actuels et futurs des entreprises et de la société. L’un des principaux atouts de l’ISGEI réside dans la diversité de ses filières spécialisées, permettant à chaque étudiant de développer des compétences ciblées et de participer à des projets innovants.
    </p>

    <h3>Réseaux Informatiques</h3>
    <p>
      Cette filière offre aux étudiants les connaissances nécessaires pour concevoir, configurer et gérer des infrastructures réseau fiables et performantes. Les étudiants apprennent à mettre en place des réseaux d’entreprise, à sécuriser les communications et à assurer la continuité des services.
    </p>

    <h3>Big Data</h3>
    <p>
      Les étudiants apprennent à traiter de grandes quantités de données pour identifier des tendances, prévoir des comportements et proposer des solutions optimisées pour la prise de décision. Cette filière prépare aux besoins des entreprises modernes qui dépendent de l’information et de l’intelligence artificielle.
    </p>

    <h3>Télécommunications</h3>
    <p>
      Les étudiants maîtrisent les infrastructures de communication modernes, y compris les antennes sectorielles, la fibre optique et les réseaux sans fil. Ils développent des compétences en planification et en optimisation des réseaux pour garantir des communications fiables et efficaces.
    </p>

    <h3>Développement Web</h3>
    <p>
      Cette filière met l’accent sur la création de sites interactifs et d’applications web modernes. Les étudiants acquièrent des compétences pratiques en HTML, CSS, JavaScript et bases de données, leur permettant de concevoir des plateformes ergonomiques et collaboratives.
    </p>

    <h3>Navigation Aérienne</h3>
    <p>
      Les étudiants découvrent la gestion des systèmes de communication et de navigation aérienne, en combinant des connaissances techniques et pratiques sur les radars, les systèmes aéronautiques et la coordination des infrastructures pour la sécurité et l’efficacité du trafic aérien.
    </p>

    <p>
      Grâce à la diversité et à la qualité de ses filières, l’ISGEI offre un environnement propice à l’apprentissage et à l’innovation. Les étudiants bénéficient d’une formation complète, pratique et orientée vers les besoins du marché, ce qui leur permet de se démarquer dans leurs domaines respectifs.
    </p>
  </div>

</section>

<style>
/* ===== SECTION AVANTAGES FILIERES ===== */
.avantages-filieres {
  position: relative;
  background: #111;
  color: #ccc;
  padding: 80px 20px;
  border-radius: 15px;
  max-width: 1100px;
  margin: 50px auto;
  box-shadow: 0 10px 30px rgba(0,0,0,0.6);
  font-family: 'Arial', sans-serif;
  overflow: hidden;
}

/* SPOTLIGHT */
.spotlight {
  position: absolute;
  top: 0;
  left: 0;
  width: 200px;
  height: 200px;
  background: radial-gradient(circle, rgba(255,255,255,0.25) 0%, rgba(255,255,255,0) 80%);
  border-radius: 50%;
  pointer-events: none;
  transform: translate(-100%, -100%);
  transition: transform 0.05s;
  z-index: 1;
}

/* HEADER */
.section-header h2 {
  font-size: 48px;
  margin-bottom: 15px;
  font-family: 'Georgia', serif;
  text-shadow: 2px 2px 12px rgba(0,0,0,0.7);
  position: relative;
  z-index: 2;
  text-align: center;
}
.section-header p {
  font-size: 18px;
  max-width: 800px;
  margin: auto;
  line-height: 1.6;
  margin-bottom: 50px;
  position: relative;
  z-index: 2;
  text-align: center;
}

/* TEXTE DISSERTATION */
.dissertation p, .dissertation h3 {
  position: relative;
  z-index: 2;
  text-align: justify;
}
.dissertation h3 {
  color: #4a90e2;
  margin-top: 30px;
  margin-bottom: 15px;
  transition: 0.3s;
}

/* HOVER TITRES FILIERES */
.dissertation h3:hover {
  color: #50c8ff;
  transform: translateX(5px);
}

/* RESPONSIVE */
@media(max-width:900px){
  .section-header h2 {
    font-size: 36px;
  }
  .dissertation h3 {
    font-size: 20px;
  }
  .dissertation p {
    font-size: 16px;
  }
}
</style>

<script>
// FAIRE SUIVRE LA SOURIS POUR SPOTLIGHT
const spotlight = document.querySelector('.spotlight');
const section = document.querySelector('.avantages-filieres');

section.addEventListener('mousemove', (e) => {
  const rect = section.getBoundingClientRect();
  const x = e.clientX - rect.left - spotlight.offsetWidth / 2;
  const y = e.clientY - rect.top - spotlight.offsetHeight / 2;
  spotlight.style.transform = `translate(${x}px, ${y}px)`;
});
</script>




<!-- FILIÈRES -->
<section id="filiere">
  <h1>Filières</h1>
  <p>Découvrez les spécialités proposées à l’ISGEI pour votre avenir professionnel.</p>
  <div class="cards">
    <div class="card"><img src="https://media.istockphoto.com/id/1459941554/fr/photo/concept-de-r%C3%A9seau-de-communication-mondial-transformation-num%C3%A9rique.jpg?s=612x612&w=0&k=20&c=WD6peTkclebyT0QmZqoq1o0p3q5LHODx3d6ozMF_7-s=" alt="Réseaux"><h3>Réseaux</h3><p>Gestion des réseaux, sécurité et infrastructure informatique.</p></div>
    <div class="card"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRlFxon0wdKd2_hv_-eMSOmo3K11PeKarYPPQ&s" alt="Big Data"><h3>Big Data</h3><p>Analyse et traitement de grandes bases de données.</p></div>
    <div class="card"><img src="https://i.la-croix.com/1400x933/smart/category/tag/t%C3%A9l%C3%A9communications/t%C3%A9l%C3%A9communications_561970_1625090400000.jpg" alt="Télécom"><h3>Télécommunications</h3><p>Systèmes de communication et technologies mobiles.</p></div>
    <div class="card"><img src="https://blog.lesjeudis.com/wp-content/uploads/2024/05/developpeur-informatique.png" alt="Dev Web"><h3>Développement Web</h3><p>Création de sites et applications interactives.</p></div>
       <div class="card"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQgud2O0NrVYnA0NoettDFVp4T5tf2LWbtofg&s" alt="Projet 4"><h3>Multimédia</h3><p>Les étudiants apprennent à créer des contenus numériques, vidéos et animations interactives, en utilisant des outils professionnels pour produire des projets originaux pour le web et les médias.</p></div>
    <div class="card"><img src="https://www.wonderfulpcb.com/wp-content/uploads/2025/03/Role-of-Electronic-Devices-Circuits-in-Modern-Technology.png" alt="Projet 3"><h3> Électronique</h3><p>Cette filière forme à concevoir et maintenir des systèmes électroniques, des circuits aux composants intégrés, préparant aux métiers d’ingénieur électronique ou technicien en systèmes embarqué</p></div>

    <div class="card"><img src="https://www.nessma.tv/uploads/news/3094707fa374282893d3cca1684897a010.jpg" alt="Navigation"><h3>Navigation Aérienne</h3><p>Projets liés à l’aviation et navigation aérienne.</p></div>
  </div>
</section>

<!-- PARTAGE -->
<section id="partage">
  <h1>Partage</h1>
  <p>Découvrez les projets et réalisations des étudiants ISGEI.</p>
  <div class="cards">
    <div class="card"><img src="data:image/jpeg;base64,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" alt="Projet 1"><h3>Projet Réseau</h3><p>L’installation des équipements réseaux pour une entreprise consiste à déployer des antennes sectorielles pour couvrir chaque zone, des RRU proches des antennes pour transmettre le signal radio, et des antennes FH pour relier les sites au réseau central. La fibre optique assure la connexion à haut débit entre les équipements, tandis que les racks et le câblage structuré organisent les switchs, routeurs et serveurs pour une maintenance facile. L’ensemble est complété par des accessoires et protections (panneaux de brassage, UPS, ventilation) afin d’assurer un réseau fiable, performant et sécurisé pour l’entreprise.</p></div>
    <div class="card"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQdlNVdv1NJHzIzLRnz5A6BTBSQ0TI63uBgFg&s" alt="Projet 2"><h3>Big Data Analyse</h3><p>L’étude de grandes bases de données, ou Big Data, permet d’analyser et d’extraire des informations pertinentes pour optimiser la prise de décision au sein d’une entreprise ou d’un projet. Grâce à des outils d’analyse performants, les étudiants peuvent traiter de massives quantités de données, identifier des tendances, prévoir des comportements et proposer des stratégies efficaces basées sur les résultats.</p></div>
    <div class="card"><img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBxMTEhUTExIVFRUVFRUVFhUXFxYWFRUXFRUYFxUXGBYYHSggGBolGxUWITEhJSkrLi4uFyAzODMsNygtLisBCgoKDg0OGxAQGyslICUtLS0tLS03Ky0tLS0tLS0tLS0tLS0vLS0tLS0tLS8vLS0tMC0tLS0tLS0tLy8tLS0tLf/AABEIAL8BBwMBIgACEQEDEQH/xAAcAAACAwEBAQEAAAAAAAAAAAAEBQADBgIBBwj/xABEEAACAQIEBAMEBgcFCAMAAAABAhEAAwQSITEFIkFRBhNhMnGBkQcUI0KhwRdSU5Ox0vBDYnKS0RUWJDM0goPhZHOy/8QAGgEAAgMBAQAAAAAAAAAAAAAAAwQAAQIFBv/EADIRAAICAQEFBgcAAQUBAAAAAAABAhEDIQQSEzFBIlFSkaHwYXGBscHR4RQyQqLS8YL/2gAMAwEAAhEDEQA/AE+HetHwm4BBYwP41lLLxvTGzizSmSNjsJUfTMB4lIAAACgQBR3E/EA8pSpgtIPpXzKzjY60Td4hKROxpdwklV6Bag3dajniN9iJDGe3SkOIv37WYjMo+8V2I9RsRr1oLE45o3Ne4TF2nV1v37ibBYGYEdZ0MbCm8OON6aMWz5JqNvVd1X6AV7jDky2S6P1XUEaCANIj4RrQS3sOWY3bbjN7ItQAnxYnN06Cmd5s0Il+w4EKvmLkOiGNSIMBt26il93CFjcVMOWdNzaYuqydJAmYiPhTcYvvv39RGU8fdu/LTT6170FuPW1mAtXGy5ZJuDUNJ5eUHpl12mda4/2HedFdFV1YTy3ElfRgTKmr8RgrYC5na25Uki4pUaKdidxmUjqfTQ0txeEySwdDBAlSZ5swnbT2T8x3oyXeYc3SUJea/wDAPHYN7erqy6kSw0kEqRI03Vh/2mhFtT7vTWm1zGYqyxlmBMzmAuAhS06sDIBd9j94968wfFUXOLlhXZyZYnKysY9mBywRMepmjRirAyyZErpP5P8Af7YlYET/AKTvp199dW7DHatPabh1z9rbaACGMqT1II0q8cPtqJQyPnRlifNMWe3JOpRafxRj3tEGK8ZCK0V3hgJkmhsVgDpB29Ky8bQSO1QfUVeURrXimmOIVisZaA8ojcGstUEU1JFqir0ND2yR/X9d6JUVpApl612arSrYrQswa6KCuimF0UHeWssPjYEwrk1Y4qusDaPKlSpVFkqVKlQhKlSpUISpUqVCG3FyibV2luerUeua4nRTGaX6ItXgZBIHv/relCXKsNypGNOy94epxG0EOYfCqeG8Ps3BNy8EkgCAWEno3b5ikl99KeeEMZkW5/xS2JK6MgYP8eho+J9pWhPPGUcbcG79/B/YAvcKUuFt4iy8mAJKnqTIYabdTXD8PxKaW85WSB5bMdgrGAPRx+NMLsvdInBXtYyjlY8kwGj4k5jrOvYfBYQeZeHk3pXdMM4ItandszZ9tdtjRYxQvPLNLtO9Otfz7C/EcVuo85yWyeW2cBmiTmUlhI1/Gg73E1Ylrli08kk5QbbSZPtLrv7/AOFN8Xhwpjzb1pWUs3moWZnLMCSBpqBE9xVADKPKBsX0yvzODybwAzjkPUKNyfdRqdgHPHVqP3XrX5FdnF2QzMz3kYhggQhltz0OfVhPbfsK7vm2S58+zdAzkLctZSSJMBhGpjQjq22oq6bF2AcHlLK5U27kDQElspIHKAeXcgDtqJ/s62oGYXA2U5iwKrnhoCgqDHsmSe+mxo2OLYGSi5dU/wD5frq/X1O+H8G81GCWwWyhiwYQM06AA6bGuuF+GcazFbSMxG4WWAnaeg+Nb3wN4GkLfxDMqHUWhmRmgxzkwQPQfMV9EFxLShUVUXTQD/Qb++pOUU6itTSjNN7z7L9958y4Z9HWOYDzTZtf4mLN8lBH40afowuRzYq0DHRWI9dTE1ssRxA9+/fcGkmN45E88D8mED8aiWSRhxxLoZ3FfRnfEZL9ht5kskR8DNZ/inhDFWZz2WKj76DOn+ZdvjFaq94mE+1vE6668rbHvFTCeLHBEE9JgnqpU/ioNE4c+pVR7jALgQegqp8EBtpX0m9awuME5Vs3SBDoIU8ubnQAA7MJGu2prK8S4U9pyjjXcEaqw6Mp6gxUro0Ck3HWzPixVgs0yXC1dbwtTdF3n1Ej4agcRYrWnCUuxuFrDiFx51ZlXtVS9uKdNhtaHxVmKG4nRhlTFQWrPJNXWU1o82hFUkElOhKy1zROJXWhqoImSpUqVRCVKlSoQ1BarEahWau1akGPpBSPVmfUUGrV0z7VaZGjUYRMOV58td2OKfVeTBstxrp5kZQ+w0jWQfj0rJ4g6VrPo/vsqXgL2FtyySuIWS2o1U5hEflVqVamJY97Rli4K68XHs4Fw0ZkUi06ny5KMWgq43IJJmeg0rwODKs7PZvImcqi2by5LbBwhGdrjeYczqpGmpPw9vYQvdI+rYC9LexacW2P2eaM0iW++TLakidNBeFYIebfX6tiM1ve1hbgb6vzHVnztn9kA7QVO3QsJC+XFaaGWPvQ2YXL1seXGa6mYkyxgHaI/GknEb6s4bNZugLcGdlFtFJzRnXLqZgjaTp1MtOJuDCPcxdtfLzhbyl2zBmGbKDosDLPcUhugeaGTFo2XNLsvlQdeRl9psw07c0etPSlehzYbOlr8/d1fqUYRQ2QBFY5HOjw2g3MEwR0Gk1v/Bnh4XYe6t0WrTkrbuMrBnVmiQZGUDTpqKxmDxoukBrGHYsvbIeWdIUaMZ0A3IFfY8NhVsWltLOVFIjqTMkk+pnT1rUnuxpGJJvJ2lVfH+/gMvX4/Lv/AAild26DMtGsdtdTvA7Vzi8Xvrt2/wBaxPiPjLLIViMwIOpHwqseOzc23ogTxD4lJlUOnWPwIrOXWLgMXbmBPxmD8JpVi8SSar+uvpzHQQNdgelGlOtEXw2ghXMxPp+VEWsSQ0Hv+c0tW7XYuSZNYTKlE0+HxmUjXt+f5GtBhcSL6eW0aCUPUNkGiiQCWKga96wlq7PWnPDb5BH9dDW+YrkQzZIJBEEEgjsRuKtRRVnEbRBt3dIuDYb5lC5iRGk5geu9U260tTk5YuEqLGURS7GJTOKDxKVmUTGPI7EN5IpZjDTzFLSTGJQZI7OzTsWB4NXnFaULdFUlqFdHUSTO7zzVNek15WQiJUqVKhCVKlSoQfudK9U1U50rpTSNHSRYrV7Oo99VKajnUVVEZqcHwu068xj1misPi1wK5bVu3iWusDkZczLlAIywJrIXbpjc/M1rvo+tuyXCtmxcIddbrZWXbVeU0pmTxwc5O13cvUNBqUt1Kn3llzhd14uNwzDujQ2VLwtMAUkhjmBzTLGQdyOmleAwRTzGfD4pLebKluxiFC2mFzJBdrh8w5nRSNNSdunON4czXSG4daeXnKmKKuSUnXmHORDTl2IHShuG4MeZfX6vi5t/2OFuy2H5jq7lmDnlE7QVOg6GxZrjzXp/2YvOOvv9BmIx4RsxucQsp5YTPeTPmcs7ABpy5MpEADfX1oO9j/MugriRfhLwz3LMNbkMQFtBhnJ0OYrCmCdBp5j8pZbTtxNV8rzBbujzLmcXHUXMublTQIOUbA9ZI2KCC6jfXLyhM5z3rbC4rBjlUW82ZwxABOw1nqB0cUt4UljSDPAFotjLEFORbjtAOYBVPtGBrJWCCY01r6hirjdAOkwRroenwrIeAON3LzXTduhmFpQeWCIYxmMQZnp39BWkdhIOdJ01lYOjbA+0dN56009Xqc/Ne8A47Ecs+moj0r5xx7EFmInrW58Q3sqEsYgbzAM18xv4nPcJ6UZaRMRXNgty1XGSrr71SHrDSsIm2jq3ZmiVwlc4VtaZoRFEhBMXy5JRYHbtRTPBj+vgapC0Zhrf9fA1e7QCU7H/ACHDyZzqy5TrABAzAx8ImNtJ1qmy1MOGYYNZvAyItlwP7ygESZ666RS60KkebOftkeTCgaFxVEgVVeSa20IRdSEOKak+Lp9jLFJMXapaaOzs0kJb4oVqOxCUG4oDO1jehxXle15WQpKlSpUISpUqVCDd20rpTQ7tpXatStaHQvUtU16x1FUo1WW1zMo7mstUQsvnSm3h7jViwrLdwq3yWBBYgZYjuD/RphZ8J+YkhyD67VfwzwpdQODYTEZoiGCkbTvt86SybTs8oOMn6166fcPHBlUrS/ImfiOEZ5OBAWdlvXFaI125ZLSdttI0q7B8Sw6l831hEJ+zt2bhVk1OrXGPPIIkaaz8L8HwxbxcWsE5CHK2W6rc6K2YB51nPb0GmijqJownDhcGZcLfKyYZf8VuJZmCiJYTAHMDpGhk8VVr0/3X+WLSUr6eX8PX4vZFyVxHEEUWspl1d2Ysx1YvGTKwGUDue8ktxlfMDri7rQl5c95ftkzhgAgSQQZEnpoREABbe4Oc/wD02LW2LbNqq5iwBMhoClIgyJPbeq8Jw+2xuyl4IHCqZQZAVdgLmeAGhQdxIDU5g3Hqr9GYla50av6NMRrdXPMWfYy+zzNoDOoJIkxpIrZ3sUiK91zbCIsschBVYYk6jTVjtNYz6PeEC3fa+Xi0yMlpibbZgRmJIViVYZDoY2PXSj/pCf7JLRuZEdmZnyM8+WoKiFM7yd+npTy1ZzciTlSow/iPxBcxbk+zbHsW+w6Fu7Uis3INNxgMPnZRiNMoIYrGpY8pB6hcvxJqtuG2gdHzfHepKTLpJULr12arDU0ODQbCuvq69qpsymuSAsO1MLVyurdgdqJs2RO1EhOjGTDvHdgUfgt4/rZqtw+FWNq68kKZojmhT/HlvGj4Wh8m8wzaWmBMxuoHMOo12ilFo0et5Vwj8+VnKqF1OZRBOmw2Gum9LsLzEKupPw6SZnaKqPViO2xeiCQaquPVl0FTB309QQRIIPUEEH41wuHd1LKJhlUiRMuYWFmTJ0re9oc6ONuVUK8ZcpJinp5xWwUMNGokFSGBEkSCN9QR8KT4/DFQpMc651ggyMzL02MqRG+lBmzqbMkhNiaX3Kd4rhz+V50DJ/iGaCxUMVmQpZWWe4pLcFAkdnC01oVVZhbBd0QGC7qgJ2BZgoJ+dVmoDWBgP4vgVtMuRmZXUsMwAYZbty0ZAPe0SPQ1zw7CC55ssQUs3LogAg5IJB100qnF4y5dbPcdnaAJYyYHT+PzNd4LH3bWby3KZhlaPvL2PprVmKlu11C+N8JWxEMWOd7bSAOdFRmKxuv2gr2gcVjLlzL5js+Rcq5iTlHYT7h8hUqMuCaj2uZ07V0rVUxr0Gg0P3qWo1E4JvtU/wAX5UCpq2w8Op7GsyjaZafI+ycGabe4PpFD4i6CxVcJcuHlBysBpmExLDpSDA+Ihbt6soH40TguK2rzSovPDJnNtmEAETsROnavL/404ScmtPfyO1xYyiop6+/mc8U4a7gLbw2KskQAXuTGjEZbdskmVVvcB8weLW0Q2lW1jbZZwseZL3edDAGaVbKVhojRdDPLPrBLP5tjFTJytauXeZB5gBYXHbKd9I0ANC4zEoGTNbx0sUBXOyh2Hl5gAWza5CZzaGO2nbwqSik/f/JnFyq5t+/sXNh8waLHFTGXmDS05GDA7gKVZYGUmOsMBVeBwCu1xFsY4hA3nKwDEuufy2ZYgsoZDET7UAyJFxt5lHlpaxpvsit9pduEBSpLMq23BmSCA2aMoB6g3cKt34Ib6yp8m5n+0bmYPcIAMwnsmQ28NrzSWNnTWt/LX++XxMZO6hjwfAXrF57QtOLYblORvtCxVGYMTBC21uEx6+6tL4p4e1yIV2yMNgSQcw0IA9OtZbh+MT61D2sZIv2xAu6LmZ4UgEqFhk7yM8ROux8S8StqGUC71BHmETo2uh11IPTr3NP4s2ST1j78xHLhjFrU+X8W4NiQ7v8AV7oQc2bKcoHcnafTfWqeHcAv3NVAUDqT/CK0uK47hiwUtjFtyTcS5eZxcB2VVBhROsz0ir38R4cLGHBA/VI1FZc5t9pBZY47vZYkHAnXdya8v4Mr601scULxIHT8v/dDY7FDMQdxp8RRHdCyXa1EhuuDEVdZxLg+z+Nes0ma9U0Pfa6DUcSa5jXD44xtXF7HnqKDR/WuWaiRyb2lAp4NzVMb4jEHyreo1L+8QEr3A4gowbeJ0OxBBBHyJq3iaqLYQLBs5eaTz+aoJkdCMtA2rgpmNUcPO3J2H4vFl2zQBooAEwAqhVGu+gFXYDiptIwVAWZrbhyW5TbYMvKNDrRXBLNq5YxRZJe3bzq0nTfSPhTviPCbC2biLbh7Nm1d82TLlyQwPppVOuQtbi7MTxbEm4QQgRVXKqiSAMzMdSSTzMx+NLOJ43MttcgXy0KSCxzAszyZOhzO23f0ppimA6TQPimwiX2VBlWEIEzGZFY6+81iSoZ2eW89RdiOKk2PJyLsFL65ii3GuhImPbcmfQCklytJwexayXbtxPMyG2oSSB9o0EmOwFK/EODWziLttfZVoHu3H8aFJaWdPDJbzivfIVGua7NcUIbJXs15UJqEPZqV5UqEL2r0V4xphwvhwuhiWy6hV0mWIJ110HL+NZSvQYnOMNWLxXSDmE96J4aoJ1rYYHhltgpJ0KhjygkE3PLjfXXWaDPI06SDxgmrbBcHw1HTmAIofF2xZZFsecmdoYW9yI6T1mKfWRbQ5TA5spI98aDSaQcWxOIbENasEtkuZMyrs2bLJ3j/AN1zsKyTk+748hvLKEIrv+HMlq2WDjELjSQ7BCJaQVYBOoJJD7CNTrVKJnZrijE3bYgLchWI1EsrsNNc+oiIBPWCOOYHGW3UpdxN0EPzZXRlNl7iNopMDldgZkhj60BbwWN0AF07ArnzZfZIzrJyDVfaAHfYw+oNKnJeehz+LGXaSflqML1oCQbOKBCky90AtCtO5AZQOg119YJfDcO3mlhYukKjQjXfaJuOhzMTGbKTsANCfvCnOM4VfawbflMU+qLcDxzG+ZJ59ySJHurDrwrFP5iZGY2iA4LryaO27NEe2fefXUqShzmvP+gYZ+Kn2GtffT0Njxi/JuJYwku2ZWuZkFwhw2YG4eYqPZiYEEaQIa8eQEAtZiSpkPMhlLAaGAvKRM1h8F4dvIzBxbKhbmuYNqofZfaE+WYkCdK1GGwbXMFhz51pV8jKQ7KIy5gPlBHcSBTEMilqpKvr+wWRbtLd1+n6F1/BpB+wsgwNDdmAANZ6n09PWhTetqSuVR6iIrjE8AUo1z6zYJUKSo32Gg1mZMbdKtXw7YUKwv5510IHr0oDre/1N/R/ljj3nH/Sl9V+AWzirSNmZS+mijaYYamfUH+tVdzOzE6ySSempM1sFwNsDQCaEu2lFPK9057jc+Zljh7nY14MNd7H51pmURXOlJzzNdB3Hs8WubECYO7/AEaLw/DrhI99Nswo3hYDOoHUgfOpDNNvkXPZsaWrZVxPzbrZToqhVI0km2oUliAJ2J/qaouYMnroNtI+cdaOxOIXO+v3m/iapfFL3FFWWYo9kwhXCuK3cOjInlkNObMkk+kztXWI8QX3siy7DKIBIADMF9kE9QKBS8p6iqrppjG2+ZyNsxY4yqINfvEEERoZ1AI+IO9B8Zx9y++e5BaAJChdBoNhRbihryCrkgeJqPQAwfELlgkpHMACGAZTBkaHqDS3F3WdmdjLMSSe5NMMQBS69QJHSxVdg7VxXbVxQhslHcGxCpdDM2XkuqH1Plu9p1R+XXlZgdNREjagalQpq1QbxrELcv3HT2WaQYjMYAZo6ZmBb/ur2galQiVKghrTRtVmGxNxAQhIzCDTy1gwarPDlpZbQjoPZt4R2mZTIpkOOYkZQrxlBAiNAenzq84NR0qy1hF2IqnmjzL4DqrFP1y7mDZmzAyDvr3ijsJ4kxNvOQ3PcOZnIGaTudo6VbjrCopI6ClX15ukD8a3FrLGt20CmuFPe3mn39Q/EeJMXcjPiHaBl3A0mSDAEySZneTO9GW7GOlmi6DcyBj7BbKQqSdDMxr1MzJmkbYl20LEjt00mNPifnRLcQusZN1yYj2m2me/fX30ZwfRL4+9Bbfj1b+HT9je5g8e6+UzXCpg5WuiOYkAwW2JBFLDwi4S4IBZCQRMksFLaQDOg0mJn30PcvMd2Y+8k1RFaSydWvL+md7H0T8/4OE4Q1uf+IsrodVeZgMdNpnKP83oYc8MuTh3tZlueVcbm1IZX5gR6SG09fWsiq034CxVmMHyyMrkdOzRGpG/ei41JPtOweaUGtFRbxBFWSYEN0BPSPzpZbxFsdj79Okf6fKnXEsMNVJmSTuDoQCNvfSUYGDsdp+YaPxy/KtzjK+ZMc41yD7HET0aPdUvY9v1qS3rgzcoNVm4arfpUTc1scNjW/Wqhr7HZj86Ag9aOsqIoTpm3NpFZxDdSaacLcBbjvOVUbXfmZGVB/mK0tFvMwA6kfiaKxb5VFoE9C/tDmgcrKQNVIbvvRIukBk7LcMhZZmmOE4fmEk0PwxQFMmmuCurG+1bTYnldchW8o0U54Hw/wCsEjNEClONuBnJFaTwWFDEs0aUWItndQ3upmMextuyE7GKotNnMVb4tgX2KmQTQPCr4Da9aFKWtDOPGnBSLOI4fKJpNcNPeL31ywDNIGoMxrCtCs1zXRryhjJzUr2vKhCVKlSoQeWuIgdZq+1i8+igmldnAO2wrS+HsGVBBAzVlYcbYWe15YxuKE+LxJXQqQaDXiTDpWu4nwcXSJ0PpS9fCy9S1BySwwdMNi/yMkU+Rnnvvc0n4V4uEaYitpgfCagyrGfWirvACpL5l9xreHPhkuywefZtpWtWYK7hmXcVLazWzx3B7TqpbEqpjVVQu89Qqgyeg+IpXheGWiym3591Q2pFrKGGZFgSdyzHTU7DrII80E618n9+QusWTdt15r8Ce5hyu4qgrW/4zw9PLzrhGKqASbl3IAIBIjMD1ga9VPvT3Li+ULi2sIoK6Kee8JuOvsuNWG8mdI9Ip51pS+37ZUcbpuT+/wCUhHYwbESBRmDxGRSsTrI9CRFa/iPltLLdDtLcq22G7sc2aT0M99de9KXwWGXzJTEMEIljksgGLhyS06kBSBBY5TA6UZZVup0/fzoBuOUmtPfys7wwL4RZ9pTcCuTusDkPuMQSfShL9snYTHb+6NP4054dirL4O6qYYTbYDmZmjzVIzgMdNUOnrS+/4lKgL5KLAgZfTSiucq0iSMI27l9zN3uGFTmbvMUAUhp9Z/Gm2O4mzzygUAooNO9QzkqJlmNIgfnP51dask6DroB3rq3bom3I27R861FIDKYw4TgUE5oZilyBmjIRadgTAM7bSpBApQUnU600wV97cusEiV1EiLiXEP4MaDyUR0CUikSKstk96mWu0FURsdeG+GLfds7FUto1xyNWheg9at8R4D6s6i25KXLa3EJ0OVuhjrpVPAOJeQ5YrnVlZHWYzK24npXXiDif1hw2XKqqqIu+VV2E9aKhJqfF+BmcYSTrTBeCITYy3CRdRnYkQVyTmgddqBxIpg/HVizks5fJDLqxOZWnMD75oTqx171Ld96C3i+EVMjIxKXFzLm0YQYIMe6ueEYBbzOrMVIts6wJkqJg9qnFMb5hUBciouVVmYEydeutdcH4gtlmY285KlfaKwGEHahurC9rc+IpNOjwRfKnOfN8rz8sDLknae8a0ouxJgQOg7U0PG/ssnljP5fleZP3JmI7+tUq6m57+m6Jahr2vDWAx5UqVKhDYYFxFN8N0IrAi83c1tuDqMu9XuWYeTcH+Eg6minsTEUDZuKp36Ux/wBooBv0pPLsw9h2u0U3MYbQJYgKKVNxJL15MpUEGQH0V/T3Uv8AEnGAeVYGus9qG4X4qt20KtYFw9JigQ2aUbcBp7WnpJ6D3jDRd8765hrRtqFU2rYcDzFfMpUk5m0j3NrFJuG3RCWrWIxNy1bZi4tgIoQshDDPAtyS3M5iQo6zQreKLoabVuzaEyALak7RqxGu5Pv9NKXvxC6zOxuNmugi4ZjMD90x93+7toNNBTOPZpV2vx+vi+vUQz7RByuP5/f4G/EOLWPYWwXCyPtLh+6YX/lNB5REjTaIAggDi6rc8xMPaUgFVUqrpzbsysJZuxkAdB0oGK88ommuCnzt/ViSyNcqX0Q4XxNiDtcK6k8vKASWPT1Ztf8AQQG+IdhBYwTJ2GYnq0e0fUya8w+G9Jjf5x+dabgPg+9fysw8q0YPmNoGBn2Afa2/EUxHHGCukgcptvmTwzhD9UxT6wWsqDGkrnZoPcSvzpBjcPqYHbWvq2OwFu3YWxZSEG3VrjbknqSfh8KwvFeHsurKRrRIaoBvVIyLWq9S3RWIXWuba0OUQ29odWrdEC1UtrV6iokBlIO4RhFuZkYwDB3jVQ5GuU9QOnXpuFt3DlSVYQVJBEg6jQ6imWBuFesA7/Jhrr6+7vR+KwPnsGVgpIMjIgGgkEZAJGupjlAkkittGUzMslcAUwxWBdILCA0wZUg5TBggmR67HcUGyVlo1Z6hqXDXIqMallVqA4igXo+/QVwUOQ1jKTXldxXsVkKUsKrNXsKqass0iuvDXRrw1k0c1KlSoQtrScJuGBM/Cs0K1XCroyijQ1YptcnGNoPznsaKTOdNBQ7YkdqttYqtvGhKO0TovHC0OrgHvNK/EWFti2PKt7HVgNAKKxONEd6K4VetuCps3L2hlLaltNpMbCscNXoMxzyqxBhuBEgNcv2bQMHmY5tRIhQNf67UThuG4YkfaXr2gJW1aIP3dJae7fh302OC4O7MAmEwdqB7TZb7CAQFK2iWB1nbpTrA+GwpNy9euG44hyuWwDoJ5zFw+yI2G+mpqNJc2bUm+hhV8NvdyrYw5DRbLS+vMHYchYxy5Z6yhIABgOOGfR+8/wDEXFtj9VPtLjb7KBK/EVuLSpbUImVREQCz5vUgZVJ94NBYy5oR06Bjpp2tLC/xq4uXJFSkinh/C8JhSMiFrgHtOVzT+sFGZkI7qFmKIucT6xrpzBGkkbgl9diKSXsUdAM0aaCFGuhgADSTQyXO+YbDf/Es6+4UTh9WBcxzjsYTqJ39pjB27dKx3GHnqTruZk09BBHU6ruf7s0n4paOWfQ0SKoHeplLw1rxBXbiogrEg16Fq12DXAqE1kwEW7sUbYxYA+XuMA6ncTt06dDrSnNXoetKRVGst45XEOocbnNzA5dVzay0E7G4Br7OsHm9waw4lCUOoBmEzEgyzMIgAwEt5ydNT95RwvUz2+PanDPl5h66jfp1BDfid/fWq7jO/ToTcQ4LctsRkdlALBshByAxnZN0Eke1G470re32rd4TFSIgMskldCsj9ZRAJ1+8j7++iX4bYvtLJLElmKkB2bLHMwGbKN8q2ht75w/iETR8tvrQVwV9Rxfg21nAF6BBLF1AY9gllSXPxArO+IPCr20VipUuxVUOlxux8v2oO1DaT5BoToxoFdRV31cgwe+tH43BhbYYVW6wjmkxK4qlhRBEmnNnhqZNdyKzVm3NR5maNeGr8ZaysRVBrAVOzmpUqVRZ+l7n0VcGUgNYILGFBxF8Fj2E3NTRNn6M+Fr7Nkj/AM94/wAXrW38IjsrMJKezqRvBMwdRKjQ6aChX4HYJBNsSI6t02kTrSSnJdRhwi9GjPn6O+GEx5Rnt596flnr1fAHC9QLexCn7a7oSYAPPvJFaHD8HtIRkUjcRJIOad5J7n517iOEWXMskmS27DVtyYOuw3q+JPvZjg4/CvIzZ+jnhbf2RMdr97p7n9RTjAeHMLaVUtoAFEKCcxHXc6/jRKcDsCYQ65p53+/7X3utdWOD2UbOqQ28yxO89T3qcSfezSxwXRHFzgdltw599y4R8i0Vyvh/DjQJ+X8KaVKnEl3snDh3IVP4fsH7rfC5cA+QaKqbwthT/Znr99+u/WnVSpxZ97K4OPwoRnwnhTvbbp99+mo+9Xi+EMINrZ/eXO5P63qfnT2pV8bJ4mVwcfhXkI18J4UbI3T779BHftVV3wXgmBBtEyI/5lwfwatDUqcbJ4mTg4/CvIyP6NeG/sG/fXv56n6NeG/sG/fXv5611SpxZ+Jl8KHhRkf0bcN/YN++vfz1P0a8N/YN++vfz1rqlVxJ97JwoeFGR/Rrw39g3769/PU/Rrw39g3769/PWuqVOLPvZOFDwoy9n6PuHr7Nlh/5bv8ANVreCMEf7Jv3lz+atHUq+Nk8T8yuBi8K8kZz/cfBfsm/eXQdTO+bvV48JYT9mT/iuXG//TGnlSpxsnifmTgY/CvIUL4cw42Vh6C5cA+QaKn+7WGA5UKeqMyN/nUhvxpvUquJPvZfBxr/AGoy+M+j/h93KGw/sAgQ9xSZMksVaXM6yxJqu59HPDmXKbDR/wDbe/nrWVKviz8TL4UO5GJ/RRwrf6s37+//AD1efo74YoE2SOgm9d+Wr1r6qvWFeMwBykMPQjY1XEn3sjxxfNIxF36MeDMZazqf/kXtzEf2nqPnXA+izgv7H1/6i92n9p2rZjhlofdPXTM0a76T6V43CrR3UnfdnnXfWdP9darfl3mt1GRT6JuDnUYcnUjS/fOo0I/5leVuLNkKIHUzuTr8fdUqbz7yUj//2Q==" alt="Projet 3"><h3>Application Web</h3><p> Le développement d’un site interactif pour étudiants permet de créer une plateforme pratique et conviviale pour partager des informations, projets et ressources pédagogiques. Grâce à ce type de site, les étudiants peuvent accéder facilement aux contenus, collaborer entre eux et expérimenter les bonnes pratiques du développement web moderne, tout en appliquant leurs compétences en HTML, CSS, JavaScript et bases de données.</p></div>
    <div class="card"><img src="https://www.wonderfulpcb.com/wp-content/uploads/2025/03/Role-of-Electronic-Devices-Circuits-in-Modern-Technology.png" alt="Projet 3"><h3> Électronique</h3><p>La filière Électronique forme les étudiants à concevoir, analyser et maintenir des systèmes électroniques variés. Ils apprennent à travailler sur des circuits, composants et systèmes intégrés, appliqués à la communication, l’informatique et l’industrie. Cette filière prépare aux métiers d’ingénieur électronique, technicien en instrumentation ou développeur de systèmes embarqués.</p></div>
    <div class="card"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQgud2O0NrVYnA0NoettDFVp4T5tf2LWbtofg&s" alt="Projet 4"><h3>Multimédia</h3><p>La filière Multimédia permet aux étudiants de créer des contenus numériques, vidéos, animations et projets interactifs. Ils développent leur créativité et leurs compétences techniques en utilisant des outils professionnels, ce qui leur permet de produire des projets originaux pour le web, les médias et l’industrie du divertissement.</p></div>
</div>

</section>

<!-- SECTION CONTACT / BARRE D'INFORMATIONS -->
<section id="contact" class="contact-section">

  <div class="contact-container">

    <!-- NUMÉRO SERVICE CLIENT -->
    <div class="contact-item">
      <h3>Service Client</h3>
      <p>📞 034 206 5000</p>
      <p>📱 WhatsApp: +034 206 5000</p>
    </div>

    <!-- RÉSEAUX SOCIAUX -->
    <div class="contact-item">
      <h3>Réseaux Sociaux</h3>
      <p>📘 Facebook: <strong>ISGEI</strong></p>
    </div>

    <!-- ADRESSE -->
    <div class="contact-item">
      <h3>Adresse</h3>
      <p>🏠 Ambanidia, en face de FJKM Faliarivo</p>
    </div>

    <!-- SITE WEB -->
    <div class="contact-item">
      <h3>Site Web</h3>
      <p>🌐 <a href="https://ISGEI.mg" target="_blank">ISGEI.mg</a></p>
    </div>

    <!-- SPONSORS -->
    <div class="contact-item sponsors">
      <h3>Sponsors Officiels</h3>
      <p class="yas"> YAS Madagascar</p>
      <p class="asecna">ASECNA</p>
      <p class="tvm"> TVM</p>
    </div>

    <!-- AUTORISATIONS -->
    <div class="contact-item">
      <h3>Autorisations</h3>
      <p>📜 Agrément Num: 1282/2002</p>
      <p>📜 Autorisation Num: 4715/2005</p>
    </div>

  </div>
</section>

<style>
/* ===== SECTION CONTACT ===== */
.contact-section {
  background: linear-gradient(135deg, #0d0d0d, #1a1a1a);
  color: #f0f0f0;
  padding: 50px 20px;
  border-radius: 15px;
  max-width: 1200px;
  margin: 50px auto;
  box-shadow: 0 10px 30px rgba(0,0,0,0.6);
  font-family: 'Arial', sans-serif;
  transition: all 0.3s;
}

/* CONTAINER FLEX */
.contact-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  gap: 30px;
}

/* CHAQUE ITEM */
.contact-item {
  background: #1a1a1a;
  border-radius: 15px;
  padding: 20px;
  flex: 1 1 250px;
  min-width: 220px;
  text-align: center;
  transition: transform 0.3s, box-shadow 0.3s, filter 0.3s;
  cursor: pointer;
}

/* EFFET HOVER SUR TOUTES LES CARTES */
.contact-item:hover {
  transform: translateY(-5px);
  box-shadow: 0 15px 30px rgba(255,255,255,0.3);
  filter: brightness(1.2);
}

/* TITRES */
.contact-item h3 {
  font-size: 20px;
  margin-bottom: 10px;
  color: #4a90e2;
  text-shadow: 1px 1px 5px rgba(0,0,0,0.5);
  transition: 0.3s;
}

/* TEXTES */
.contact-item p, .contact-item a {
  font-size: 16px;
  color: #ccc;
  margin: 5px 0;
  text-decoration: none;
  transition: 0.3s;
}

/* LIEN SITE */
.contact-item a:hover {
  color: #50c8ff;
  text-decoration: underline;
}

/* SPONSORS COULEURS */
.sponsors p.yas { color: #FFD700; }       /* Jaune */
.sponsors p.asecna { color: #00C851; }    /* Vert */
.sponsors p.tvm { color: #FF4444; }       /* Rouge */

/* HOVER SPONSORS SUR GLOWS */
.contact-section:hover .sponsors p.yas { text-shadow: 0 0 15px #FFD700; }
.contact-section:hover .sponsors p.asecna { text-shadow: 0 0 15px #00C851; }
.contact-section:hover .sponsors p.tvm { text-shadow: 0 0 15px #FF4444; }

/* RESPONSIVE */
@media(max-width:900px){
  .contact-container {
    flex-direction: column;
    align-items: center;
  }
}
</style>
