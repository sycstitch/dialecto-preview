# Dialecto - Translation App Preview

![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-20.x-green?style=for-the-badge&logo=node.js&logoColor=white)
![Gemini AI](https://img.shields.io/badge/Gemini%20AI-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)
![CI/CD](https://img.shields.io/badge/CI%2FCD-Passing-brightgreen?style=for-the-badge)
![Firebase](https://img.shields.io/badge/Firebase-Deployed-orange?style=for-the-badge&logo=firebase&logoColor=white)

> *This is a preview repository showcasing the functionality and technical implementation of my dialect-aware translation application. The full codebase remains private due to security considerations during development.*

**Dialecto** is a unique take on translation technology, designed to be linguistically aware of dialects and cultural context. Unlike traditional translators, it accurately handles regional expressions, slang, and cultural nuances - particularly excelling with **AAVE** (African American Vernacular English) and **Dominican Spanish** variations.


## 🚀 Technical Highlights

- **Custom CI/CD Pipeline**: Achieved 100% deployment success rate with automated preview generation
- **Cultural Dialect Recognition**: Advanced handling of AAVE, Dominican Spanish, and regional expressions
- **Cross-Platform Responsive Design**: Seamless experience across desktop and mobile devices  
- **Firebase Integration**: Real-time deployment with preview URLs for stakeholder review
- **Docker Containerization**: Consistent development and deployment environments


## 🎬 Demo

### Desktop Experience
| Live Demo                                         | Smart Recommendations                                          |
| :-----------------------------------------------: | :------------------------------------------------------------: |
| ![computer demo](media/demos/computer-demo-1.gif) | ![computer (recommendations)](media/demos/computer-demo-2.jpg) |

### Mobile Experience
| Live Demo                                                            | Smart Recommendations                                                                                             |
| :------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------: |
| [📱 YouTube Demo](https://youtube.com/shorts/9YXpPo1dNyo?feature=share) | <img src="media/demos/recommendations-phone-1.jpg" alt="phone recommendations" width="25%" height="auto"> |


## ⚡ Dialect Translation Accuracy vs Google Translate

My app significantly outperforms Google Translate when handling cultural dialects and slang. Here's a direct comparison:

### AAVE (African American Vernacular English) Examples

<table>
  <tr>
    <td style="width: 50%; vertical-align: top; padding: 15px;">
      <img src="media/comparisons/translation-aave-1.jpg" alt="Dialecto AAVE translation" style="width: 50%; height: auto; display: block; margin: 0 auto;">
      <p style="text-align: center;"><strong>✅ Dialecto:</strong> "em" → "them" ("ellos")</p>
    </td>
    <td style="width: 50%; vertical-align: top; padding: 15px;">
      <img src="media/comparisons/google-translate-aave-1.png" alt="Google Translate AAVE failure" style="width: 90%; height: auto; display: block; margin: 0 auto;">
      <p style="text-align: center;"><strong>❌ Google Translate:</strong> "em" → cannot translate (misses cultural context)</p>
    </td>
  </tr>
  <tr>
    <td style="width: 50%; vertical-align: top; padding: 15px;">
      <img src="media/comparisons/translation-aave-3.jpg" alt="Dialecto AAVE translation" style="width: 50%; height: auto; display: block; margin: 0 auto;">
      <p style="text-align: center;"><strong>✅ Dialecto:</strong> "Ion wanna..." → "I don't want to keep the water running"</p>
    </td>
    <td style="width: 50%; vertical-align: top; padding: 15px;">
      <img src="media/comparisons/google-translate-aave-3.png" alt="Google Translate AAVE failure" style="width: 90%; height: auto; display: block; margin: 0 auto;">
      <p style="text-align: center;"><strong>❌ Google Translate:</strong> "Ion wanna..." → "I want the water to keep running" (opposite meaning!)</p>
    </td>
  </tr>
  <tr>
    <td style="width: 50%; vertical-align: top; padding: 15px;">
      <img src="media/comparisons/translation-aave-4.jpg" alt="Dialecto AAVE translation" style="width: 50%; height: auto; display: block; margin: 0 auto;">
      <p style="text-align: center;"><strong>✅ Dialecto:</strong> "not (even) gon hold you" → "I'm not going to lie to you..."</p>
    </td>
    <td style="width: 50%; vertical-align: top; padding: 15px;">
      <img src="media/comparisons/google-translate-aave-4.png" alt="Google Translate AAVE failure" style="width: 90%; height: auto; display: block; margin: 0 auto;">
      <p style="text-align: center;"><strong>❌ Google Translate:</strong> "not (even) gon hold you" → "I'm not going to hold you" (literal translation)</p>
    </td>
  </tr>
  <tr>
    <td style="width: 50%; vertical-align: top; padding: 15px;">
      <img src="media/comparisons/translation-aave-2.jpg" alt="Dialecto AAVE translation" style="width: 50%; height: auto; display: block; margin: 0 auto;">
      <p style="text-align: center;"><strong>✅ Dialecto:</strong> "bust that corner" → "turn on the corner"</p>
    </td>
    <td style="width: 50%; vertical-align: top; padding: 15px;">
      <img src="media/comparisons/google-translate-aave-2.png" alt="Google Translate AAVE failure" style="width: 90%; height: auto; display: block; margin: 0 auto;">
      <p style="text-align: center;"><strong>❌ Google Translate:</strong> "bust that corner" → Overly formal translation, misses casual tone</p>
    </td>
  </tr>
</table>

### 🎯 Key Competitive Advantages
- **Google Translate**: Provides literal word-for-word translations that lose cultural meaning
- **Dialecto**: Recognizes dialectal patterns and provides culturally aware translations
- **Real Example**: My app recognized "Qué lo que?" as a common Dominican Spanish greeting → Google returned "what what?"


## 📁 Project Structure

```
.
├── .firebaserc
├── .git/
├── .github/
│   └── workflows/
│       ├── firebase-hosting-merge.yml
│       └── firebase-hosting-pull-request.yml
├── documentation/
│   ├── roadmap.md
│   ├── skills-used.md
│   ├── troubleshooting.md
│   └── versions.md
├── docker-compose.yml
├── Dockerfile
├── entrypoint.sh
├── firebase.json
├── firebase-debug.log
├── firestore-debug.log
├── node_modules/
├── package.json
├── package-lock.json
├── public/
│   ├── config.js             # Auto-generated, ignored
│   ├── index.html
│   └── main.js
├── src/
│   ├── config.local.js       # My real keys (ignored)
│   └── config.local.js.example
└── README.md
```


## 🔄 CI/CD Pipeline

This project uses **GitHub Actions** for automated testing, building, and deployment with separate workflows for pull requests and production releases.

### ✨ Key Features
- **Pull Request Validation**: Every PR triggers automated builds with live preview deployments
- **Production Deployment**: Successful merges automatically deploy to the main Firebase hosting environment
- **Consistent Success Rate**: Maintained 100% successful deployment rate across all features and refactors

<details>
<summary>📸 View Pipeline Screenshots</summary>

<br>

**Workflow Overview**
<p align="center">
  <img src="media/ci-cd/1-Deploy-Firebase-Hosting-PR.png" alt="GitHub Actions workflow runs showing consistent successful builds" width="70%">
  <br>
  <em>All PR workflow runs demonstrating reliable CI/CD pipeline performance</em>
</p>

**Live Preview Generation**
<p align="center">
  <img src="media/ci-cd/1.2-deploy_preview.png" alt="Successful deployment with preview link" width="70%">
  <br>
  <em>Automated preview deployments provide immediate access to live testing environments</em>
</p>

</details>

### 🔧 Technical Implementation
- **Build Process**: `npm ci` → `npm run build` → Firebase deployment
- **Preview URLs**: Each PR generates a unique preview URL for stakeholder review
- **Deployment Target**: Firebase Hosting with custom domain support

> 💡 See my [personal workflow](https://github.com/sycstitch/guides/blob/main/dev/personal-workflow.md) that I follow for this project.


## 🚧 Areas for Future Development

This project is continuously evolving, and I have many exciting improvements planned:

### 🎯 Language and Translation Accuracy

* **Enhanced Contextual Understanding** — Improving the model's ability to understand nuances and slang, like ensuring "dame banda" is consistently translated as "give me space" rather than literal "give me band"

* **Robust Typo Detection** — Making the system more forgiving of minor typos (e.g., "dam**a** banda" should suggest "dam**e** banda")

* **Model Optimization** — Exploring alternative AI models with superior language capabilities while balancing cost-effectiveness

* **Broader Dialect Support** — Integrating more normalized dialectal data for various regional expressions

### 👤 User Experience and Personalization

* **Culturally Relevant Explanations** — Implementing multi-select dropdown for users to specify known languages, enabling culturally tailored concept explanations

### 🎨 User Interface Refinements

* **Responsive Layouts** — Ensuring background color consistently fills entire screen on all display sizes

* **Optimized Button Placement** — Adjusting authentication button layouts for various screen dimensions

### ⚙️ Core Functionality and Data Management

* **Persistent User Data** — Completing "Sign in with Google" integration for cross-session translation history

* **Intelligent History Management** — Auto-pruning less frequently accessed translations to optimize storage

### 🔒 Security Enhancements

* **Secure API Key Management** — Implementing robust protocols for secure storage and usage of all API keys
