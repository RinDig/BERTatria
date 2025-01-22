# README

### Welcome to My Hebrew NLP and Gematria Project!

Hi there! 👋 I noticed an interesting intersection between text embeddings (like the ones we get from models like BERT) and the natural number values assigned to letters in ancient Aramaic and Hebrew—what's often called **gematria**. This isn’t about claiming mystical connections or deep truths, but more about exploring **patterns**—whether they’re human-made or just statistically interesting.

This project is my little sandbox for playing around with Hebrew text, gematria calculations, and modern NLP tools. It’s a mix of traditional and modern: taking ancient numeric systems and embedding them in cutting-edge AI techniques. Maybe it’s useful, maybe it’s just fun. Let’s see what we can do!

---

### What’s Here?

1. **Text Tokenization + Gematria**  
   - I break Hebrew text into tokens and calculate their gematria (numeric value). Simple, but surprisingly cool for spotting patterns.  

2. **Text Embedding with Hebrew BERT**  
   - Using a pretrained model (like AlephBERT), I create embeddings for Hebrew words and combine these with their gematria values.  

3. **Combining Patterns**  
   - Explore connections between tokens using either **semantic embeddings** or gematria—or both!  

4. **Downstream Task Ideas**  
   - I threw in some ideas for fine-tuning or building something fun or useful with this setup (see below).  

---

### Why This Might Be Interesting

- **Patterns Are Everywhere**: Whether it’s human intention (authors assigning meaning to numbers) or purely statistical coincidence, gematria introduces another way to explore text beyond just meaning or syntax.  
- **Bridging Ancient and Modern**: Combining ancient numeric systems with modern embeddings lets us ask questions we couldn’t before.  

---

### Ideas for Fine-Tuning / Tasks

Here are some things I think could be fun (or useful) to explore next:

1. **Textual Similarity Search**  
   - Find verses or passages that are thematically related—but also happen to share numeric patterns. A combination of gematria and semantic embeddings could make this interesting.  

2. **Question Answering**  
   - Fine-tune a model to answer questions on Hebrew texts (e.g., Torah, Talmud). Could it incorporate gematria insights into the response?  

3. **Thematic Clustering**  
   - Group words or passages by gematria and see if their semantic embeddings show surprising connections. Human design or random chance? Let’s find out.  

4. **Mystical or Statistical Discovery**  
   - Are there surprising links between high-gematria words and their context? Build a tool to automatically surface “fun coincidences.”  

5. **Educational Games**  
   - For Hebrew learners: Can gematria + embeddings make a language-learning game? Something like “Guess the related word by its numeric value.”  

---

### What’s Next?

This is a starting point—think of it as a playground for Hebrew text + NLP + numbers. If any of this sparks your interest, feel free to clone, modify, or contribute! Let’s explore some patterns and see where they take us. 🚀

---

### How to Use

1. Install dependencies:
   ```bash
   pip install transformers torch hebrew-tokenizer scikit-learn
   ```

2. Run the notebook or scripts to:
   - Tokenize Hebrew text.
   - Calculate gematria values.
   - Generate embeddings and explore connections.

3. Try adding your own Hebrew text or fine-tuning on a specific task!

---

Happy exploring! 😊
