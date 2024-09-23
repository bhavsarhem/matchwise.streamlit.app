<!-- # MatchWise: A Resume Matching and Scoring Web Application 
By leveraging AI and user-friendly design, this web application aims to empower job seekers and enhance the overall efficiency of the job search process.

<div align="center">
  <a href="https://github.com/mfts/papermark/stargazers"><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/mfts/papermark"></a>
  <a href="https://x.com/Psycho2049"><img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/mfts0"></a>
  <a href="https://github.com/mfts/papermark/blob/main/LICENSE"><img alt="License" src="https://img.shields.io/badge/license-AGPLv3-purple"></a>
</div>

<a href="https://github.com/bhavsarhem/matchwise.streamlit.app/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=bhavsarhem/matchwise.streamlit.app" />
</a> -->
# MatchWise: A Resume Matching and Scoring Web Application

![Hacktoberfest](https://img.shields.io/badge/Hacktoberfest-2024-blueviolet)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-1.x-brightgreen)

MatchWise is an AI-powered web application that helps users analyze and score resumes against job descriptions. It's built with Python, Streamlit, and the Google Gemini API, and it aims to assist job seekers and recruiters in gauging how well a resume matches the desired job criteria.

## 🎯 Features

- 📄 **Upload Resumes**: Supports multiple file formats for resume uploads.
- 💼 **Upload Job Descriptions**: Match resumes with specific job descriptions.
- 🔍 **Matching Score**: Generates a score indicating the resume's fit for the job.
- 🧠 **AI-Powered Analysis**: Leverages AI models via the Google Gemini API for resume parsing and matching.
- 🖥️ **Streamlit-Based**: Simple, intuitive UI for both developers and non-developers.

## 🚀 Quick Start

### Prerequisites

- Python 3.7+
- Google Gemini API Key
- Streamlit

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/bhavsarhem/matchwise.streamlit.app.git
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
   For More info [clicl here 🔗](https://python.land/virtual-environments/virtualenv)

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Add your Google Gemini API key in `.env`:

   ```bash
   GOOGLE_API_KEY = "YOUR_GOOGLE_GEMINE_API_KEY"
   ```

### Running the Application

Once all dependencies are installed, run the Streamlit application:

```bash
streamlit run app.py
```

The application will open in your browser at `http://localhost:8501/`.

## 🛠️ Contributing

We welcome contributions from the open-source community! To get started:

1. Fork the repository.
2. Create a new branch:

   ```bash
   git checkout -b feature/your-feature-name
   ```

3. Make your changes and commit them:

   ```bash
   git commit -m "Add: your feature or fix description"
   ```

4. Push to your branch:

   ```bash
   git push origin feature/your-feature-name
   ```

5. Open a Pull Request on GitHub.

### Contributions for Hacktoberfest 2024

We are proud participants in Hacktoberfest 2024! Here’s how you can contribute:

- 📊 **New Features**: Help us add new features like advanced parsing, custom matching algorithms, or new file formats.
- 🐛 **Bug Fixes**: Hunt down bugs and suggest improvements.
- 📖 **Documentation**: Improve this `README`, write tutorials, or add comments to the code.
- 🎨 **UI/UX Improvements**: Enhance the web app's design, layout, or accessibility.
- 💡 **Open to Ideas**: Feel free to propose any new features or improvements.

### Guidelines

- Please ensure your contributions align with the existing coding style.
- Always provide clear commit messages and proper PR descriptions.
- We encourage creating an issue first to discuss your ideas before submitting a PR.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 💬 Feedback

If you have any questions or feedback, feel free to reach out by opening an issue or contacting the project maintainers.

## 🙌 Acknowledgments

Thanks to all our contributors, Hacktoberfest participants, and the open-source community for making this project better!

---

### ✨ Happy Coding! ✨

---
```

### Notes:
- Make sure to update the GitHub repository link (`https://github.com/your-username/MatchWise.git`) with the actual repo URL.
- Add a `requirements.txt` file in your project for dependencies.
- The `.env` file should contain sensitive API keys securely. Don't forget to include instructions or an example `.env` file.
