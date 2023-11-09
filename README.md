# Orange-E-reputation

This repository contains a Python code to scrape TrustPilot reviews for the company Orange Bank and perform sentiment analysis on the reviews using the Camembert sentiment analysis pipeline from Hugging Face. The scraped data is saved to a CSV file called `orangeScraping2.csv`, and the sentiment analysis results are saved to a CSV file called `final_orange_reputation.csv`.

**Installation**

To install the required libraries, run the following command in a terminal:

```
pip install requests beautifulsoup4 datetime pandas chardet transformers
```

**Usage**

To scrape TrustPilot reviews for Orange Bank and save the results to a CSV file, run the following command in a terminal:

```
python orange_scraping.py
```

To perform sentiment analysis on the scraped reviews and save the results to a CSV file, run the following command in a terminal:

```
python sentiment_analysis.py
```

**Example output**

The following shows an example output of the sentiment analysis results:




ID | Content | emotion_label | emotion_prob
---|--- |--- |---
1 | Après séparation, grosse galère pour clôturer le compte joint.On m'a demandé trois fois les mêmes documents. Au final, il faut que je demande la clôture, sur un seul document manuscrit, avec la demande de madame, la copie de sa pièce d'identité. Alors qu'elle l'a fait de son côté. Et pour raison privée, je n'ai plus ses coordonnées et il n'est pas question que je la recontacte. C'est totalement surréaliste ! Leurs procedures sont incroyables. Très déçu ! | très négatif | 97.0 %
2 | Super service, rien à redire. Je suis très satisfaite d'Orange Bank. | très positif | 99.0 %
3 | Service client au top, j'ai eu un problème avec ma carte bancaire et ils ont réagi très rapidement. Je recommande vivement Orange Bank. | très positif | 98.0 %
4 | Orange Bank est une très bonne banque en ligne. Les frais sont bas et le service client est réactif. Je suis très satisfait de mon compte Orange Bank. | très positif | 99.0 %
5 | Je suis déçu du service client d'Orange Bank. J'ai eu un problème avec mon compte et ils ont mis plusieurs jours à le résoudre. | négatif | 85.0 %

Here is a picture of the visualisation

![E reputation Orange]("e%20reputation.png")
