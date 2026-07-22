## 202-2026 ChemicalQDevice Translation Map
- AI: ChatGPT 5.6 Thinking Extended
- Input: 22 Publication Abstracts' Text
- Location: Manuscripts/README.md
- ChemicalQDevice_Translation_Map.ipynb
- Output: One high resolution map

[Download Image, Notebook](https://drive.google.com/drive/folders/1mWzHk5xvTX0sIslxgRYY5wRefxdgbLii)

#### Graph 1
- Publication Abstract Similarity Network
- Each pager connects to as two nearest TF-ID/cosine neighbors
- Only the strongest necessary bridges join disconnected components

#### Graph 2
- Research Theme Co-occurrence Network
- Themes use explicit README wording plus four reviewed false-positive corrections
- Edges report Ochia-normalized abstract co mentions

#### Graph 3
- Abstract-Derived Pipeline-Theme Association Network
- Light clinical research stages connect to themes only when at least two README publications support the pair
- Strength is normalized weighted keyword evidence

#### Graph 4
- Temporal Text-Similarity Precursor Network
- Arrows run from earlier publications to the closest later abstract by TF-I/cosine
- A near tied second earlier match is retained when supported
