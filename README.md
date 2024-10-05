# Exploration of Generative Models Through Lyric Synthesis

This project explores the use of open-source generative AI models to synthesize song lyrics. We used three models—RNN, GPT-2, and Falcon 7B—fine-tuning them on Rihanna's lyrics from a Kaggle dataset to generate new songs in her style. We evaluated the models' outputs based on structure, meter, rhyming, and musicality.

## Key Features:
- **RNN Baseline**: Limited ability to generate coherent lyrics, often lacked structure.
- **GPT-2**: Improved performance, generated lyrics with verses and choruses, but struggled with meter and rhyming.
- **Falcon 7B**: The best-performing model, producing structured lyrics with occasional rhyming and meter, though still limited by computational resources.

## Methodology:
The models were fine-tuned using Rihanna’s corpus of 143 songs. Each model used different tokenization techniques, and while larger models like Falcon 7B showed better results, they also required more computational power. We used Google Colab's free tier, which constrained the model size and training time.

## Ethical Considerations:
This project highlights issues like plagiarism, copyright infringement, and the potential disruption of creative industries. While these models can be helpful tools for songwriters, they must be used with caution to avoid unintended ethical violations.

## Future Directions:
- Improve tokenization and fine-tuning techniques.
- Expand to multiple artists and genres to generate more robust results.
- Leverage more powerful hardware or cloud-based solutions to train larger models, like Falcon 40B or Falcon 180B, to enhance the quality of generated lyrics.

---

### Google Colab Notebooks:
- [RNN Model](https://shorturl.at/gxGQX)
- [GPT-2 Model](https://shorturl.at/cuBJX)
- [Falcon 7B Model](https://shorturl.at/hiHW9)



