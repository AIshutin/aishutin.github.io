---
published: false
---
## The winner of the hackathon
This is a brief story about my participation in Metachallenge. I developed the solution called Communicabio to improve the soft skills of the users.

### Proofs

- https://vk.com/@practicing_futures-pozhirateli-mobilnogo-trafika-ili-nyam-nyam-chto-eto

### The idea

After reading the news and the description of Metachallenge I shortly came up with the idea. It was a telegram bot that will negotiate with the users and force them to politely refuse his offers. Thus, the user would learn how to refuse bad offers. I built a working prototype in 2 days even before the official start. 

After speaking to the mentor, the core idea was changed a bit. Instead of refusing offers, the users are able to negotiate politely with the bot. Also, Communicabio is not a telegram bot, but the site instead. Cause it's less concise to show tips about mistakes in telegram rather than in our own UI.

### The techs

We used GCP to make the Communicabio serverless and auto scalable by deploying it via Cloud Run and Kubernetes. 

The frontend was made with React and Tilda.

The first phrase was randomly selected from the prescripted list. I used GPT-2 to generate replies. BERT was used to measure the score of politeness and positiveness.

## The team

I invited my friend Roma to the hackathon, but unfortunately due to his work and life problems he was unable to participate fully. 

### The presentation

I presented my product to experts from Sberbank, Softline, etc. I was a bit nervous which is unusual for me. The speech was prepared quite well unlike my responses to the questions. 

## My mistakes

I see the mistakes in the following:

- switching to React site. It was chosen to win a big money prize from VK, but we did not win. I should have switched back to Telegram Bot Platform or do not switch at all.

- teammate choice. I should have included the frontender to free my time. Thus, I would have time to improve NLP.

- English support. One of the judges advised us to make an English-speaking version of Communicabio. Thus, the amount of work hugely increased. I should have refused the advice.

### The conclusion

It was more than a month-long competition. But despite the fact that I win Metachallenge, I gained nearly nothing - only a T-shirt and bottle. The organizers promised an internship, but they did not fulfill their word.

On the other hand, it was a useful experience for me. It gave me an idea of what I did wrong. It's said, "fail fast".
