# HTML-CSS-layout---swimming


/*  Polices */

@font-face {
    font-family: 'aaarghnormal';
    src: url('Polices/Aaargh-webfont.eot');
    src: url('Polices/Aaargh-webfont.eot?#iefix') format('embedded-opentype'),
         url('Polices/Aaargh-webfont.woff2') format('woff2'),
         url('Polices/Aaargh-webfont.woff') format('woff'),
         url('Polices/Aaargh-webfont.ttf') format('truetype'),
         url('Polices/Aaargh-webfont.svg#aaarghnormal') format('svg');
    font-weight: normal;
    font-style: normal;
}







/* Background */


.header
{
    height:0%;
}
 
.content
{
    height:85%
}
 
.footer
{
    height: 5%;
}

body content
{
    margin: 0;
    padding: 0;
    line-height: 1.7em;
    font-family: Verdana, Arial, Helvetica, sans-serif;
    background: #F2F2F2;
    font-size: 110%;
}

body header
{
  font-family: 'Lato', Arial, sans-serif;
  font-size: 20px;
  background-color: #6b6b6b;
  margin: -10px;  
}

p 
{
    font-family: sans-serif;
    font-style: normal; 
    font-size: 20px;
    line-height: 1.8em;
}







/*Header*/


#conteneur_principal
{   
    display: flex;
    width: 100%;
    justify-content: space-between;
}

#placement
{
    color: white;
    text-align: left;
    margin: 20px;
    margin-top: -20px;
    margin-bottom: 0px;
}

h1
{
    color: white;
    box-sizing: border-box;
    display: block;
    float: none;
    position: static;
    z-index: auto;
    font-family: "Lato", Arial, sans-serif;
    font-size: 48px;
    font-weight: 500;
    line-height: 57.6px;
    margin-bottom: 8px;
    margin-top: 0px;
    text-align: left;
    text-transform: uppercase;
    margin: 20px;
}

h2 
{
    color: #109DB9;
    text-align: center;
    font-family: 'aaarghnormal';
}

h3
{
    color: #06C;
    font-family: 'aaarghnormal'; 
}

.image_bordure_principal
{ 
    background-color: rgb(71, 72, 73);
    background-image: url("Images/image_noir.png");
    height: 60px;
    line-height: 30px;
}

.image_bordure_secondaire
{
    background-color: rgb(71, 72, 73);
    background-image: url("Images/image_noir.png");
    height: 20px;
    line-height: 30px;
    margin-left: 494.7px;
    width: 1088.3px;
    margin-top: 20px;
}

.image_bordure_haut
{ 
    background-color: rgb(71, 72, 73);
    background-image: url("Images/image_noir.png");
    height: 20px;
    line-height: 30px;
    margin-left: 601.55px;
    margin-top: 20px;
    width: 1100px;
}

.image_noir_haut
{
    background-image: url("Images/image_noir.png");
    height: 30px;
    margin-bottom: 0px;
    margin: 0px;
}

.image_noir_bas
{ 
    background-image: url("Images/image_noir.png");
    height: 20px;
    line-height: 20px;
    margin: -10px;
}




/* Navigation */


a.parallelogramme
{
    color: white;
}

a.parallelogramme:hover
{
    color: white;
    padding: 14px 50px;
    transform: skew(-20deg,0);
    display: list-item;
    line-height: 44.8px;
    position: static;
    margin: auto;
    background: #474849;
    oppacity: 0.5;
    font-family: "Lato", Arial, sans-serif;
    font-size: 1.4rem;
    font-weight: 100;
    margin-top: -100px;
}

.parallelogramme
{
    display: flex;
    color: white;
    padding: 14px 50px;
    transform: skew(-20deg,0);
    line-height: 44.8px;
    position: static;
    margin: auto;
    background: #6b6b6b;
    oppacity: 0;
    font-family: "Lato", Arial, sans-serif;
    font-size: 1.4rem;
    font-weight: 100;
    margin-top: -100px;
}

a.espace_liens
{
    color: darkslategrey;
}

a.espace_liens:link {
    color: darkslategrey;
    text-decoration: none;
}

a.espace_liens:visited: 
{
    color: darkslategrey;
    text-decoration: none;
}

a.espace_liens:active {
    color: darkslategrey;
    text-decoration: none;
}

a.espace_liens:hover {
    color: #06C;
    text-decoration: none;
}


nav li
{
    margin: 10px;
    font-family: 'Lato', Arial, sans-serif;
    color:white ;
}

nav ul
{
    list-style-type: none;
    display: flex;
    justify-content: space-around;
    background-color: transparent;
    color: white;
}

nav a
{
    font-size: 1.3em;
    color: black;
    padding-bottom: 2px;
    text-decoration: none;
}

nav a 
{
    font-family: carbontyperegular, serif;
    font-weight: normal;
    text-transform: uppercase;
}

nav li.parallelogramme
{ 
    margin-bottom: 0px;
}




/* Bannière */


#banniere_image
{
    height: 300px;
    background: url('Images/palette_couleurs.jpg') ; 
    box-shadow: 0px 0px 0px black;
    margin-bottom: 0px;
    box-sizing: border-box;
    display: block;
    float: none;
    line-height: 30px;
    position: static;
    z-index: auto;
    background-attachment: scroll;
    background-clip: border-box;
    background-color: rgba(0, 0, 0, 0);
    background-origin: padding-box;
    background-position-x: 0%;
    background-position-y: 0%;
    background-repeat: repeat;
    background-size: auto;
    color: rgb(33, 37, 41);
    font-family: "Lato", Arial, sans-serif;
    font-size: 20px;
    font-weight: 400;
    min-height: 527.667px;
    text-align: left;
    margin: -10px;
}






/* aside + section + article */


.titre_2
{
    margin: 100px;
    font-size: 2.6rem;
    color: #06C;
    font-family: Arial;
}

#premier_bloc
{
    margin: auto;
    margin-top: 100px;
}

#deuxieme_bloc
{
    margin: auto;
}

#lien_contact
{
    color: #007bff;
    text-decoration: none;
}

#lien_contact:visited
{
    color: #007bff;
    text-decoration: none;
}

#lien_contact:hover
{
    color: #0066CC;
    text-decoration: none;
}

#troisieme_bloc
{
    margin: 100px;
}


#bloc_1
{
    text-align: left;
}

#droite
{
    text-align: right;
}

.More_Details
{
    text-align: right;
    text-decoration: none;
    color: #06C;
}

.More_Details:visited
{
    text-align: right;
    text-decoration: none;
    color: #06C;
} 

.More_Details:hover
{
    text-align: right;
    text-decoration: none;
    color: darkslategrey;
} 

#liste
{
    
}

#bloc_2
{
    text-align: left;
}

.readmore
{
    background-color: #399;
    color: rgb(255, 255, 255);
    display: inline-block;
    font-family: "Lato", Arial, sans-serif;
    font-size: 19.2px;
    font-weight: 400;
    line-height: 28.8px;
    padding-bottom: 10px;
    padding-left: 35px;
    padding-right: 35px;
    padding-top: 10px;
    text-decoration-line: none;
}

.readmore:hover
{
    background-color: #298e7f;
}

.center
{
    margin-top: 40px;
    text-align: center;
}

#bloc_3
{
    text-align: left;
}

.readmore_2
{
    background-color: #99C;
    color: rgb(255, 255, 255);
    display: inline-block;
    font-family: "Lato", Arial, sans-serif;
    font-size: 19.2px;
    font-weight: 400;
    line-height: 28.8px;
    padding-bottom: 10px;
    padding-left: 35px;
    padding-right: 35px;
    padding-top: 10px;
    text-decoration-line: none;
}

.readmore_2:hover
{
    background-color: #8287bf;
}


#premier_bloc #deuxieme_bloc #troisieme_bloc
{
    text-align: center;
    justify-content: space-between;
}

#bloc_1 #bloc_2 #bloc_3
{
    justify-content: space-between;
}

.titre_gauche
{
    text-align: left;
}

#conteneur_1
{
    display: flex;
    width: 100%;
    justify-content: space-between;
    text-align: center;
}

#conteneur_2
{
    display: flex;
    justify-content: space-around;
}

.paragraphe
{
    color: darkslategrey;
}

.aside_gauche
{
    background-color: rgb(242, 242, 242);
    color: rgb(33, 37, 41);
    font-size: 20px;
    margin-left: 5x;
    padding-bottom: 50px;
    padding-left: 50px;
    padding-right: 50px;
    padding-top: 120px;
    text-align: left;
}

.aside_centre
{
    background-color: rgb(242, 242, 242);
    color: rgb(33, 37, 41);
    font-family: "Lato", Arial, sans-serif;
    font-size: 20px;
    text-align: left;
    padding-bottom: 30px;
    padding-left: 45px;
    padding-right: 50px;
    padding-top: 30px;
    margin-top: 270px;
}

.aside_droite
{
    background-color: rgb(242, 242, 242);
    color: rgb(33, 37, 41);
    font-family: "Lato", Arial, sans-serif;
    font-size: 20px;
    text-align: left;
    padding-bottom: 30px;
    padding-left: 45px;
    padding-right: 50px;
    padding-top: 30px;
    margin-top: 270px;
}




/* footer */

.avis_translate
{
    float: center;
}

#avis_1
{
    text-align: center;
    justify-content: space-between;
}

#diapo_avis_1:button
{
    appearance: button;
    background-attachment: scroll;
    background-clip: border-box;
    background-image: none;
    background-origin: padding-box;
    background-repeat: repeat;
    background-size: auto;
    border-bottom-style: none;
    border-image-repeat: stretch;
    border-image-slice: 100%;
    border-image-source: none;
    border-image-width: 1;
    border-left-style: none;
    border-right-style: none;
    border-top-style: none;
    box-sizing: border-box;
    cursor: pointer;
    display: block;
    font-family: "Lato", Arial, sans-serif;
    font-weight: 400;
    height: 20px;
    list-style-image: none;
    list-style-position: outside;
    list-style-type: none;
    outline-style: none;
    overflow-x: visible;
    overflow-y: visible;
    padding-bottom: 5px;
    padding-left: 5px;
    padding-right: 5px;
    padding-top: 5px;
    text-align: center;
    text-transform: none;
    width: 15px;
}

#couleur_avis
{
    color: darkslategrey;
    text-align: center;
}

#conteneur_3
{
    display: flex;
    width: 100%;
    justify-content: space-between;
    text-align: center;
}

#premier_lien
{
    margin-top: 45px;
    text-align: left;
}

#deuxieme_lien
{
    margin-top: 45px;
    text-align: left;
}

#troisieme_lien
{
    margin-top: 45px;
    text-align: left;
}

#quatrieme_lien
{
    margin-top: 45px;
    text-align: left;
}

.espace_liens
{
    margin: 10px;
}

#mise_en_forme
{   
    text-align: left;
}

#nom
{ 
    text-align: center;
    margin: 100px;
}
