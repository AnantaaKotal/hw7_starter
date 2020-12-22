# CMSC 671 Fall 2020 HW7

# Your Name, Your UMBC ID

What follows is a partial example of what you should do for your topics.

---
---


## 0. Example topic: the film Double Indemnity

### 0.1 Beginning
Double Indemnity is one of the most influential films ever made.

### 0.1 End
It helped define Film Noir and will remain an important film for years to come.

### 0.1 Result
Double Indemnity is one of the most influential films ever made. Not only is it considered to be the best of the genre, but arguably the best of all time, period. It was the subject of numerous publications and was ranked on many "best of" lists in the early 40's. It was nominated for the Oscars, winning three times. The film's influence has spread through the decades, and it is one of the highest grossing films of all time in the US, has been remade, and is in the process of being a remake. It remains as compelling as ever. The film was made in 1951 and set just years after the 1929 Great Chicago Fire, in a forgotten suburb. It helped define Film Noir and will remain an important film for years to come.

### 0.1 Assessment
The paragraph is reasonable but goes off the rail in sentence seven.  It was not made in 1951 and the Chicago file is completely irrelevant.  Also, it was not a high-grossing film and has not been remade, except as an unimportant made-for-tv movie.  But the first three sentences Haim-added sentences were good, as was the beginning of the fourth added sentence.

---

### 0.2 Beginning
Double Indemnity is one of the most influential films ever made.

### 0.2 End
It is a dark and depressing film.

### 0.2 Result
Double Indemnity is one of the most influential films ever made. It shows the real side to the character of Tom Corbett. This was no ordinary man. This was a man in the business of taking on the big names, the big money, and the powerful. This was the man that started the Coronet empire and took down Tom Corbett. The film puts us right on the ground where Corbett was when he was killed, as the story unfolds. The film also exposes Tom Corbett's character to his best advantage as he explains himself, and we feel his anger, sadness and struggle. The film features some very beautiful music by John Williams. It is a dark and depressing film.

### 0.2 Assessment
None of the intervening text is relevant to the film.  Tom Corbett is neither the name of an actor or character in the film and john Williams did not do the music. This is a very bad example.

---

### 0.3 Beginning
Double Indemnity is one of the most influential films ever made.

### 0.3 End
Double Indemnity remains, however, a dark and depressing movie.

### 0.3 Result:
Double Indemnity is one of the most influential films ever made. It's a comedy that's deeply humane and yet has a sense of purpose. It's full of moral ambiguity and philosophical ambiguity, of heartbreak and redemption, of love and violence and friendship. This documentary, made decades later to celebrate the 50th anniversary of the release, uses several scenes from Double Indemnity to illustrate its case. The documentary makes a strong case that it was also a feminist film. It tells the story of Margaret Anderson, who played a brilliant woman and one of the first female private investigators in American history. Anderson gets a lot of credit for the development of the private eye, but it's really her. Double Indemnity remains, however, a dark and depressing movie.

### 0.3 Assessment
None of the generated sentences are relevant to this film, unfortunately. Adding the name of the file to the final sentence did not help keep Haim on the topic.

### 0.3 Comments
I suspect that Haim is not good at locking onto a named entity, like **Double Indemnity**, in the initial sentence and recognizing that it is likely to be a good focus for the paragraph.  Perhaps adding a mechanism to recognize and remember named entities would help. Another issue may be the data that it was trained on, which included web pages linked from Reddit.  Training it also on the text from Wikipedia might have helped on this set of examples.  It may also help to have it generate a paragraph that is not expected to be fact-based or even contain any facts, like one that opines on what it means to be a good person.

---
---

## 1. Example topic:
---
### 1.1 Beginning
The Grapes of Wrath in one of the most thoroughly discussed novel. 

### 1.1 End
The book was noted for Steinbeck's passionate depiction of the plight of the poor.

### 1.1 Result
The Grapes of Wrath in one of the most thoroughly discussed novel. In 1941, Steinbeck made an effort to get published again, writing a manuscript for a book, White Pine Bay, which was never published. Another of his early published works, The Grapes of Wrath (1939), was widely acclaimed and became both his most famous work and his first successful movie. It was praised by Gore Vidal, Philip Roth, Philip Larkin, and Richard Yates for its powerful use of the social and natural geography of northern Mississippi. It was the first of what became known as Steinbeck's "prose" works, and remains his best known. The book was noted for Steinbeck's passionate depiction of the plight of the poor.

### 1.1 Assessment
The paragraph seems reasonable at first glance. But it contains historical innacuracies. There is no evidence of Steinbeck writing an unpublished manuscript. The paragraph goes back to talking about the novel. However, in the second sentence, it shows that the context provided at the start is not fully grasped.

---


## 2. Example topic:

---
### 1.2 Beginning
Lynyrd Skynyrd is an American rock band formed in Jacksonville, Florida.

### 1.2 End
They are best known for popularizing the Southern hard rock genre during the 1970s.

### 1.2 Result
Lynyrd Skynyrd is an American rock band formed in Jacksonville, Florida. One of the most influential rock bands of the 20th century, they achieved international fame for their recordings of rock songs such as "Georgia on My Mind" and "Mr. Tambourine Man". In their early years, they sold little to no records and were primarily a showcase act for their lead singer Johnny Reb. As their popularity grew, they reached number one on the Billboard Hot 100, where they remained until 1988. The band was disbanded in 1989 and they reunited in 2012. A Lynyrd Skynyrd concert is known for its hard rock guitar solos and loud, aggressive vocals by Johnny Reb. They are best known for popularizing the Southern hard rock genre during the 1970s.

### 1.2 Assessment
The paragraph sounds like a legitimate Wikipaedia entry for Lynyrd Skynyrd. However, most if not all facts presented here are wrong. The band was primarily led by Ronnie Van Zant and unfortunately, they never reached number one on Billboard Hot 100. The paragraph is mostly inaccurate, but believable!
---


## 3. Example topic:

---
### 1.2 Beginning
Abraham Lincoln was the 16th president of the United States.

### 1.2 End
He abolished slavery in 1865.

### 1.2 Result
Abraham Lincoln was the 16th president of the United States. Founded in Springfield, Illinois, his political career began in 1835 when he came to the Illinois legislature as one of its first twenty-six new members. In 1843, he was elected mayor of the city. After the 1858 election, Lincoln formed an opposition party, which won a majority in the Illinois Legislature. He was elected to the United States Senate and served two terms (1859–1865), and from 1865–1869. At the outbreak of the Civil War in 1861, Lincoln called a convention to consider the proposal for a new government. He died the next year in office. He abolished slavery in 1865.

### 1.2 Assessment
Most of the facts presented are inaccurate. However, the paragraph does stick to talk about the colourful career of a politician. It is not the political career of Abraham Lincoln. But it could be one for a fictional 16th president of the United States.
---

## Overall Comments on your experiments with Haim
The paragraphs generated by Haim are mostly factually inaccurate. But if it were lying, it is a believable lie. The construction of the sentences are natural and sticks to the general idea introduced in the first and last sentences. Maybe a simple wikidata check could help it be more factually accurate. Most sentences generated also present a fact of some sort. Maybe generating sentences that are opinions rather than facts can help.
