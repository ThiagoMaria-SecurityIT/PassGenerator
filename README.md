# 🔐 PassGenerator

![Python Version](https://img.shields.io/badge/python-3.7%20%7C%203.8%20%7C%203.9%20%7C%203.10-blue)
![License](https://img.shields.io/github/license/ThiagoMaria-SecurityIT/PassGenerator)
![Code Size](https://img.shields.io/github/languages/code-size/ThiagoMaria-SecurityIT/PassGenerator)
![Security](https://img.shields.io/badge/Security-Password%20Generator-green)
![Cryptography](https://img.shields.io/badge/Cryptography-Random%20Generation-yellowgreen)
![Dependencies](https://img.shields.io/badge/dependencies-see%20requirements.txt-orange)
![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)

A secure password generator tool written in Python that creates strong, random passwords for enhanced security.    

<img width="648" height="448" alt="image01" src="https://github.com/user-attachments/assets/2f36b44a-8e78-4ff9-9394-e972d49c1815" /> 


## 📑 Index
- [Features](#-features)
- [Installation](#-installation)
- [Usage](#-usage)
- [Security Features](#-security-features)
- [AI Transparency](#-ai-transparency)
- [About the Author](#-about-the-author)
- [Contributing](#-contributing)
- [License](#-license)

## ✨ Features
- Generates cryptographically secure random passwords
- Customizable password length and character sets
- Exclude similar characters (like 'l' and '1')
- Copy password to clipboard functionality
- Simple command-line interface  

💡 **Tip**: For maximum security, generate passwords with at least 18 characters including uppercase, lowercase, numbers, and special symbols.    

## 📦 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/ThiagoMaria-SecurityIT/PassGenerator.git
   cd PassGenerator
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 🚀 Usage
Run the password generator:
```bash
python main.py
```

## 🔐 Security Features
- **Cryptographically Secure Generation**
  - Utilizes Python's `secrets` module (OS-level entropy sources)
  - Generates truly random passwords using `secrets` module
  - Guarantees at least one character from each selected character set
- **Secure Memory Handling**
  - Passwords are wiped from memory after generation
- **Controlled Clipboard Exposure**
  - Automatic clipboard clearing after 30 seconds with visual countdown
  - Detects external clipboard modifications during countdown


## 🤖 AI Transparency  
This application was developed with AI assistance to generate and refine the Python code, and is designed for Cybersecurity and InfoSec professionals at all experience levels.  

**Important Notes:**  
- Do not use this application without considering potential security implications in your work environment  
- Always consult your Cybersecurity, InfoSec or IT department before deployment  
- The AI-generated code has been thoroughly reviewed for security best practices 

## 👨‍💻 About the Author  

**Thiago Maria - From Brazil to the World 🌎**  
*Senior Security Information Professional | Passionate Programmer | AI Developer*

With a professional background in security analysis and a deep passion for programming, I created this GitHub account to share knowledge about security information, cybersecurity, Python and AI development practices. Most of my work focuses on implementing security-first approaches at companies and developer tools while maintaining usability and productivity.

**Let's Connect:**    

👇🏽 Click in the badges below:   

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/thiago-cequeira-99202239/)  
[![Hugging Face](https://img.shields.io/badge/🤗Hugging_Face-AI_projects-yellow)](https://huggingface.co/ThiSecur)  

## 🤝 Contributing
Contributions are welcome! Please:
1. Fork the repository
2. Create a new branch
3. Submit a pull request

**Ways to Contribute:**   
Want to see more upgrades? Help me keep it updated!    
[![Sponsor](https://img.shields.io/badge/Sponsor-%E2%9D%A4-red)](https://github.com/sponsors/ThiagoMaria-SecurityIT)  

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

