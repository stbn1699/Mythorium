---
draft: true
---

# Story block

```html
	<div class="event"> 
		<div class="event-content">
			 <h2></h2> 
			 <h3></h3> 
			 <p class="content"></p>
		</div>
	</div>
```

# Sotry wrapper

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Timeline</title>
<style>
    .timeline {
        max-width: 800px;
        margin: 50px auto;
        font-family: Arial, sans-serif;
    }
    .event {
        margin-bottom: 50px;
        position: relative;
    }
    .event::before {
        content: '';
        position: absolute;
        top: 0;
        left: -15px;
        height: 100%;
        width: 5px;
        background-color: #3d4852;
    }
    .event-content {
        padding: 15px;
        border-radius: 10px;
        background-color: rgba(0, 0, 0, 0.15);
        box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        margin-left: 25px;
        border: 2px solid #3d4852;
    }
    .event h2 {
        margin-bottom: 5px;
        margin-top: 5px;
    }
    .content {
        margin: 0;
    }
    .author{
	    margin-top: 10px;
	    margin-bottom: 0px;
	    font-style: italic;
	    text-align: end;
    }
    .author::before{
	    content: 'auteur.e.s : ';
    }
</style>
</head>
<body>
<div class="timeline">
</div>
```

# template de page de sorts

```
# Nom du Sort : [Nom du Sort]

## Origine du Nom
- **Étymologie** : Le nom **[Nom du Sort]** est dérivé du grec ancien **[Mot Grec]**, signifiant "..." (expliquer la signification et pourquoi ce mot a été choisi pour ce sort).

## Niveau de Maîtrise
- **Catégorie** : [Débutant/Intermédiaire/Avancé/Maître]
- **Difficulté** : [1 à 10] (échelle de difficulté)
- **Pré-requis** : [Description des compétences, connaissances ou niveau requis pour apprendre ce sort]

## Description des Effets
- **Effet Principal** : Décrire en détail l'effet principal du sort. Expliquer comment il se manifeste et son impact.
- **Effets Secondaires** : Décrire les effets secondaires possibles ou additionnels.
- **Durée** : [Instantané/Temporaire/Permanent]
- **Portée** : [Courte/Moyenne/Longue] et détails (ex: 10m, 50m, à vue)
- **Consommation d'Énergie** : Décrire la quantité d'énergie nécessaire pour lancer le sort.

## Geste à Produire
- **Description du Geste** : Décrire précisément les mouvements à exécuter avec la baguette ou les mains.
  
![Geste à Produire](url_de_l_image)

---

## Exemple Complété

### Nom du Sort : **Ignis Sphaira**

## Origine du Nom
- **Étymologie** : Le nom **Ignis Sphaira** vient du grec ancien **ἴγνις (ignis)** signifiant "feu", et **σφαῖρα (sphaira)** signifiant "sphère". Il décrit parfaitement le sort qui crée une sphère de feu.

## Niveau de Maîtrise
- **Catégorie** : Intermédiaire
- **Difficulté** : 6/10
- **Pré-requis** : Connaissance de base des sorts élémentaires du feu, maîtrise des gestes précis de canalisation.

## Description des Effets
- **Effet Principal** : Crée une sphère de feu de taille modérée pouvant être projetée vers une cible. Elle explose à l'impact, causant des dégâts de brûlure.
- **Effets Secondaires** : Peut provoquer un éclairage temporaire de la zone ou allumer des objets inflammables.
- **Durée** : Instantané
- **Portée** : Moyenne (jusqu'à 20 mètres)
- **Consommation d'Énergie** : Modérée, nécessite une bonne concentration et un flux arcanique stable.

## Geste à Produire
- **Description du Geste** : Effectuer un mouvement circulaire avec la baguette, puis une poussée rapide vers l'avant.

![Geste à Produire](https://exemple.com/image-geste.png)
```

# liens gpt


|     page    | lien |
| ----------- | ---- |
| les Maewens | [ici](https://chatgpt.com/g/g-E5XmqJQ4d-mythorium/c/6701db5a-9650-8003-b4c1-4e0572bfce17) |
| sorts       | [ici](https://chatgpt.com/g/g-E5XmqJQ4d-mythorium/c/6726e23c-0b68-8003-8751-cb86bc2ef568) |
| alchimie    | [ici](https://chatgpt.com/c/af5360c8-6702-4ac2-8a38-9b4183c70d44) |
