# Text Summarization using Machine Learning

This repository contains a data science project focused on building a text summarization model. Using a dataset of 5000 text-summary pairs, the project explores techniques to clean, preprocess, and train a deep learning model for generating concise summaries of textual data.

## Project Features

- **Data Preprocessing**: Includes handling missing values, removing duplicates, and cleaning text data.
- **Modeling**: Implements an LSTM-based sequence-to-sequence model with attention mechanisms for summarization.
- **Evaluation**: Uses metrics and visualization techniques to evaluate model performance.

## Dataset

The dataset contains 5000 samples of economic headlines and their corresponding summaries. It is loaded and preprocessed to prepare it for model training. The following steps are included:

1. Reading the dataset (`economic-headline.csv`).
2. Removing duplicates and null values.
3. Cleaning text data using techniques like stopword removal and text normalization.

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - Data Manipulation: pandas, NumPy
  - NLP: NLTK, BeautifulSoup
  - Deep Learning: TensorFlow, Keras
- **Visualization**: Matplotlib

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Testing2.ipynb
   ```

## Key Components

### Data Cleaning
- Removes HTML tags using BeautifulSoup.
- Handles special characters and stopwords.

### Text Summarization Model
- **Architecture**: Sequence-to-sequence model with:
  - Bidirectional LSTM encoder.
  - Attention mechanism.
  - Dense layers for prediction.
- **Training**: Split dataset into training and validation sets.

### Evaluation
- Visualizes the performance of the summarization model.
- Generates sample summaries to compare against ground-truth data.

## Results

Input:
```bash
Ekonomi kerakyatan menjadi basis utama perekonomian Indonesia agar keadilan sosial bagi seluruh rakyat Indonesia dapat terwujud. Atas dasar itu, negara juga mewajibkan setiap perusahaan di Indonesia untuk mendukung ekonomi kerakyatan. Hal tersebut juga menjadi komitmen PT Astra International Tbk, yang secara serius membangun ekosistem ekonomi kerakyatan, dan secara nyata terbukti memberi dampak terhadap peningkatan kesejahteraan masyarakat. 
Oleh karena itu detikcom Awards 2024 memberikan anugerah Perusahaan Multi Sektoral Terkemuka Penggerak Ekonomi Rakyat untuk Astra International.  
Astra berkeinginan untuk berkontribusi dalam memperkuat ketahanan perekonomian Indonesia yang mendukung masyarakat yang inklusif dan sejahtera. 
Astra memiliki rekam jejak kontribusi publik dan sosial yang baik melalui empat pilar, yang terdiri dari kesehatan, pendidikan, lingkungan, dan kewirausahaan. Serta sembilan yayasan yang turut berkontribusi untuk pertumbuhan ekonomi Indonesia sekaligus mendukung masyarakat yang inklusif dan sejahtera. Dilaksanakan pertama kali pada tahun 2010, program Astra Semangat Astra Terpadu Untuk (SATU) Indonesia Awards, telah mengapresiasi 657 pemuda Indonesia dari masing-masing bidang, terdiri dari 92 penerima tingkat nasional dan 565 penerima tingkat provinsi. Program SATU Indonesia Awards dikolaborasikan dengan berbagai kegiatan komunitas Astra melalui 200 Kampung Berseri Astra dan 1.196 Desa Sejahtera Astra di 35 provinsi di seluruh Indonesia. Astra adalah salah satu perusahaan publik terbesar di Indonesia, yang terdiri dari 291 anak perusahaan, ventura bersama serta entitas asosiasi, didukung lebih dari 200.000 karyawan. Model bisnis perusahaan yang terdiversifikasi menciptakan sinergi dan peluang di seluruh sektor industri termasuk Otomotif, Jasa Keuangan, Alat Berat, Pertambangan, Konstruksi & Energi, Agribisnis, Infrastruktur dan Logistik, Teknologi Informasi, dan Properti. Astra mempunyai kerangka sustainability baru yang di dalamnya terdapat Astra 2030 Sustainability Aspirations untuk memandu perjalanan transisi Grup Astra dalam menjadi perusahaan yang lebih sustainable pada tahun 2030 dan seterusnya.
```

Output:
```bash
ekonomi indonesia terus berakselerasi dengan mengorbankan pertumbuhan ekonomi indonesia dan diikuti dengan mengorbankan kepentingan
```

## Future Improvements

- Experiment with larger datasets.
- Explore transformer-based architectures like BERT or GPT for improved performance.
- Fine-tune hyperparameters for better accuracy.

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests to improve the project.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/SNRxCode/MR-Data-Science-Projects/blob/main/LICENSE) file for details.

---

### Acknowledgments

- The dataset used in this project is credited to its respective sources.
- Inspiration and guidance from the data science community.

---

Feel free to explore the code and improve upon it!
