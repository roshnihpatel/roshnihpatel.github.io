---
layout: project
title: Fine-Tune Small Language Model for Spanish Mnemonics Generation
image: 'https://workable-dentist-613.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2F552b43c9-1fd8-4d98-ba08-a101f94ef0b4%2Fe9c265f1-ad3c-4b40-be04-3ff52cd848f4%2Fimage.png?table=block&id=9ce0d45c-e98c-452c-bbfc-ab6710ed8b82&spaceId=552b43c9-1fd8-4d98-ba08-a101f94ef0b4&width=1420&userId=&cache=v2'
tags:

This project was a solution to a personal challenge I faced while learning Spanish. I found sound associated mnemonics helpful for memorising spanish words, but creating the mnemonics was time consuming. I decided to fine-tune a Language Model to automatically generate sound association mnemonics from English words and their Spanish translations

For example, the Spanish word for "dawn" is amanecer. A sound-based mnemonic would be: "At dawn, the man is here (amanecer) to greet the sun." The phrase "man is here" phonetically resembles amanecer while the imagery is linked to the word’s meaning.

I used Parameter-Efficient Fine-Tuning (PEFT) techniques and Quantized Low-Rank Adaptation (QLoRA) to fine-tune a Small Language Model (Phi-2) to generate sound association mnemonics from English words and their Spanish translations. 

For more details, you can view the full project write-up [here](https://workable-dentist-613.notion.site/Fine-Tune-SLM-for-Spanish-Mnemonics-Generation-5726bba032d64c82898f34f4301a704f)

You can find it on Kaggle:

- <https://www.kaggle.com/code/roshnihpatel/fine-tune-slm-for-spanish-mnemonics-generation>

