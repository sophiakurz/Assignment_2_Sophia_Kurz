# Assignment 2: Exploration and Analysis of Misogynistic Insults vs Neutral Insults

For this assignement, I decided to examine if there was a difference in scoring for insults that are generally deemed to be misogynistic and targeted towards self-identifying women (I chose the terms: 'bitch', 'whore', 'slutty', 'skank', and 'tramp') and insults that are generally deemed to be primarily targeted towards self-identifying men (I chose the terms: 'dickhead', 'bastard', 'jackass', 'asshole','prick').

My hypothesis was a little difficult to solidify. On the one hand, Wikipedia is primarily used by men, so misogyny isn't neccesarily something that they have an inherent sensitivity towards. This might be a reason for traditionally female-targeted insults to be scored lower than male-targeted.

But, on the other hand, fragile masculinity might explain why men, who are perhaps being called traditionally female-targeted insults would score higher, because it might imply that they are percieved as women, and therefore, recieve a higher toxicity score.

What was interesting is that, when exploring the whole CSV file, I struggled to determine a true threshhold for the labels. By this, I mean that sometimes, one comment that scored higher than another wasn't deemed offensive in any regard, compared to one that scored lower and was deemed offensive. EXAMPLE:

![Screen Shot 2022-03-11 at 1 40 03 AM](https://user-images.githubusercontent.com/99197894/157823581-4ebddbbc-4ea8-4f68-b3c9-d4a97a1dd38d.png)

I finally settled on a hypothesis that female-targeted insults would score higher than male-targeted insults, mostly due to the notion of fragile masculinity and partly to do with my hypothesis that women are also more likely to report offensive comments than men are, er go comments including language that are specifically derogatory towards their gender identity.

The results of my test are shown here:

Female-targeted Derrogatory Terms Toxicity Test:

![Screen Shot 2022-03-13 at 1 13 32 AM](https://user-images.githubusercontent.com/99197894/158040629-d4d8d6a4-5163-493e-bfab-e157f04ce044.png)

Male-targeted Derrogatory Terms Toxicity Test: 

![Screen Shot 2022-03-13 at 1 18 47 AM](https://user-images.githubusercontent.com/99197894/158040739-182cba95-8341-4865-86bd-c25b648cfc19.png)

So, as you can see my hypothesis was incorrect and, on average, male-targeted derogatory terms scored a higher toxicity score than feamle-targeted derogatory terms. The average toxicity score for male-targeted derrogatory terms was 0.870836418 and for female-targeted derrogatory terms was 0.75098827. The theories I have for why my results are like this is because, as previously mentioned, misogyny isn't neccesarily something that men have an inherent sensitivity towards, so they just don't care enough to report it when they see it. Also, Wikipedia is primarily edited by men, which also implies that men care enough to report/comment on articles. Having a sensitivity towards male-targeted derrogatory terms could explain why they recieve a higher toxicity score. The fact that Wikipedia is primarily edited by men is, inherently, a bias to how these terms are scored in terms of toxicity. The comments themselves might be random, but the people reporting them, are not.
