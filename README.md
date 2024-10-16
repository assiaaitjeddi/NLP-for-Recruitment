#  NLP Recrutement 


##  Table des matières
<ol>
  <li><a href="#description">Description</a></li>
  <li><a href="#fonctionnalités">Fonctionnalités</a></li>
  <li><a href="#technologies-utilisées">Technologies utilisées</a></li>
  <li><a href="#installation">Installation</a></li>
  <li><a href="#utilisation">Utilisation</a></li>
  <li><a href="#contact">Contact</a></li>
</ol>

---

###  <a id="description"></a> Description
<p><strong>NLP Recrutement</strong> est une application innovante qui utilise le traitement du langage naturel (NLP) pour faciliter le processus de recrutement. Elle permet aux recruteurs de créer des offres d'emploi et aux candidats de soumettre leur CV. L'application calcule la similarité entre les CVs et les offres d'emploi, optimisant ainsi le processus de sélection.</p>

---

### 🔥 <a id="fonctionnalités"></a> Fonctionnalités
<ul>
  <li><strong>Création d'offres d'emploi :</strong> Les recruteurs peuvent créer des offres avec des détails comme la description, le salaire et les compétences requises.</li>
  <li><strong>Soumission de CV :</strong> Les candidats peuvent télécharger leur CV pour postuler aux offres.</li>
  <li><strong>Calcul de similarité :</strong>
    <ul>
      <li><strong>Méthode :</strong> Utilise le modèle BERT pour encoder le texte des CVs et des offres d'emploi, puis calcule la similarité cosinus.</li>
      <li><strong>Outil :</strong> sklearn pour la similarité cosinus.</li>
    </ul>
  </li>
  <li><strong>Tests pour les candidats :</strong>
    <ul>
      <li><strong>Méthode :</strong> Génération de questions techniques en utilisant le modèle Llama pour formuler des questions basées sur les CVs et les descriptions de poste.</li>
      <li><strong>Outil :</strong> API Groq pour générer des questions et des réponses.</li>
    </ul>
  </li>
</ul>

---

### ⚙️ <a id="technologies-utilisées"></a> Technologies utilisées
<ul>
  <li><strong>Frontend :</strong> React, pour l'interface utilisateur.</li>
  <li><strong>Backend :</strong> Flask, pour la gestion des API et des services côté serveur.</li>
  <li><strong>Base de données :</strong> MongoDB.</li>
  <li><strong>NLP :</strong> Utilisation de modèles NLP pour l'analyse des CVs et des offres.</li>
  <li><strong>Encodage de texte :</strong> BERT pour encoder les CVs et les offres d'emploi.</li>
  <li><strong>Extraction d'informations :</strong> API Groq avec le modèle Llama pour parser les CVs et générer des questions.</li>
  <li><strong>Évaluation des réponses :</strong> Calcul de la similarité cosinus pour évaluer les réponses des candidats par rapport aux réponses modèles.</li>
</ul>

---

### 📦 <a id="installation"></a> Installation
<p>Clonez le dépôt :</p>

```bash
git clone https://github.com/hlal-ikram/Nlp-recrutement.git
