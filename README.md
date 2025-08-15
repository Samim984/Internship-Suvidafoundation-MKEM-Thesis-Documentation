🧠 Multi-Knowledge-Enhanced Model (MKEM) framework applied to both Single-Document Summarization (SDS) and Multi-Document Summarization (MDS)⬇

✒️Author: Samim Imtiaz

📩 samimimtiazhuawei@gmail.com 

🔗 linkedin.com/in/samim-imtiaz-611a35273

🌐 https://Samim984.github.io

✍️Abstract

In an age where the world produces more news in a single day than a human can read in a lifetime, the ability to distill vast information into concise, meaningful summaries is no longer a luxury—it is a necessity. This thesis presents the Multi-Knowledge-Enhanced Model (MKEM) framework applied to both Single-Document Summarization (SDS) and Multi-Document Summarization (MDS) tasks. We explore and evaluate three state-of-the-art abstractive summarization models—T5, PEGASUS, and BART—across diverse datasets, including CNN/DailyMail, XSum, MultiNews, and a custom-built Indian news dataset ( NewsSum ). Through a carefully designed experimental pipeline, we measure performance using ROUGE metrics, BERTScore, and inference runtime, uncovering the unique strengths and weaknesses of each model. Our findings reveal distinct trade-offs between accuracy and efficiency, while offering a roadmap for building summarization systems capable of navigating the complexity of modern information landscapes.

📚Introduction

It begins with a flood. Every morning, billions of words pour into our lives—breaking news alerts, social media threads, articles, and opinion pieces—demanding our attention. For a journalist, a researcher, or even an everyday reader, keeping up with this torrent is impossible. In this ocean of information, what we need is not more text, but less —refined, meaningful, and precise. This is where text summarization steps in. Like an experienced editor who knows exactly which words to keep and which to let go, summarization condenses a lengthy narrative into its essence. But the challenge lies in doing this intelligently , preserving both meaning and factual accuracy. In our journey, we focus on two complementary paths:● Single-Document Summarization (SDS): distilling meaning from one source at a time, as if interviewing a single witness to an event. ● Multi-Document Summarization (MDS): merging perspectives from multiple sources, like piecing together a complete picture from several eyewitness accounts.

<img width="590" height="463" alt="image" src="https://github.com/user-attachments/assets/3c3b9bd5-7d4d-4c41-ae40-5200f379728f" />

To navigate these paths, we introduced the Multi-Knowledge-Enhanced Model (MKEM) —a methodological framework designed to evaluate and compare the capabilities of three leading abstractive summarization models: T5 , PEGASUS , and BART . Each model has its own character: T5, the versatile linguist; PEGASUS, the pre-training prodigy; and BART, the robust storyteller. Our datasets form the stage on which these models perform—ranging from globally recognized corpora like CNN/DailyMail and XSum , to the MultiNews dataset for MDS, and finally our own handcrafted dataset, NewsSum , capturing the pulse of Indian front-page news.

<img width="692" height="442" alt="image" src="https://github.com/user-attachments/assets/0b6f8965-3a62-42fb-8aac-160793f8e864" />

🔍“The donut chart visualizes the distribution of 1003 Indian first-page news articles across various categories. This dataset is our own curated collection, representing diverse topics such as Politics, Business, and Sports, ensuring a comprehensive and balanced base for summarization tasks.”

📚MKEM story👇

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/17c0bcb7-f732-4297-9e6d-e6040dcec4b1" />

Continued..in the PDF
