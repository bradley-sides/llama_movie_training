# LLaMa Movie Training using LoRA (Low-Rank Adapatation)

## Overview
**Goal:** Given a director and a genre, produce a movie description

**Dataset:** IMDB Top 1000 Movies (Link)

**Model Used:** LLaMa 3B V2, Trained with LoRA

**CoLab Link:** LoRA Model Training

**GPU Requirements:** Trained on A100 GPU


## Dataset Information
Relevant Columns:  Title, Genre, Description, Runtime, Score

Example Entry:

	Title: The Godfather
 
	Director: Francis Ford Coppola
 
  Description: An organized crime dynasty's aging patriarch transfers control of his clandestine empire to his reluctant son.
  

## Best Results:
Prompt Format: Create a Detailed Description for the following movie from director XYZ, belonging to the genre ABC.

1 - {Stanley Kubrick, Crime}: A man is hired to kill a man who has the ability to predict the future.

2 - {Wes Anderson, Western}: A young man, who is a cowboy, is sent to the town of Laredo to bring back a fugitive.

3 - {Alfred Hitchcock, Drama}: A young woman, who is a widow, is being stalked by a man who has been released from prison


## Why is this promising?

**Let’s look at this response: {Hitchcock, Drama}: A young woman, who is a widow, is being stalked by a man who has been released from prison.**

- This plot has two descriptive characters and a somewhat complex plot idea
  
- Hitchcock famously incorporated complex female characters into his films

- He was fascinated with theme of obsession
  
  - In “Psycho” the protagonist (Norman Bates) is deeply troubled and is obsessed with Marion Crane
    
  - In “Vertigo” a police officer is hired to follow the wife of someone he knows
    
- Finally, this movie is not similar to any of his produced films
  
