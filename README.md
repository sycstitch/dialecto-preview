# Dialecto - Translation App Preview
![Node.js](https://img.shields.io/badge/Node.js-20.x-green?style=for-the-badge&logo=node.js&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)
[![Firebase PR Build](https://img.shields.io/github/actions/workflow/status/sycstitch/dialecto/.github/workflows/firebase-hosting-pull-request.yml?branch=main&label=Firebase%20PR%20Build&style=for-the-badge)](https://github.com/sycstitch/dialecto/actions/workflows/firebase-hosting-pull-request.yml)
[![Firebase Deploy](https://img.shields.io/github/actions/workflow/status/sycstitch/dialecto/.github/workflows/firebase-hosting-merge.yml?branch=main&label=Firebase%20Deploy&style=for-the-badge)](https://github.com/sycstitch/dialecto/actions/workflows/firebase-hosting-merge.yml)

*This is a preview repository showcasing the functionality and technical implementation of my dialect-aware translation application. The full codebase remains private due to security considerations during development.*

Dialecto is a unique take on translation technology, designed to be linguistically aware of dialects and cultural context. Unlike traditional translators, it accurately handles regional expressions, slang, and cultural nuances - particularly excelling with AAVE (African American Vernacular English) and Dominican Spanish variations.

## Technical Highlights

- **Custom CI/CD Pipeline**: Achieved 100% deployment success rate with automated preview generation
- **Cultural Dialect Recognition**: Advanced handling of AAVE, Dominican Spanish, and regional expressions
- **Cross-Platform Responsive Design**: Seamless experience across desktop and mobile devices  
- **Firebase Integration**: Real-time deployment with preview URLs for stakeholder review
- **Docker Containerization**: Consistent development and deployment environments

## Demo
### Computer
(Recorded with Gifox but limited on time, so recommendations are shown with the screenshot)
| Live Demo                                         | Recommendations                                                |
| :-----------------------------------------------: | :------------------------------------------------------------: |
| ![computer demo](media/demos/computer-demo-1.gif) | ![computer (recommendations)](media/demos/computer-demo-2.jpg) |

### Phone
| Live Demo                                                            | Recommendations                                                                                                   |
| :------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------: |
| [YouTube Link](https://youtube.com/shorts/9YXpPo1dNyo?feature=share) | <img src="media/demos/recommendations-phone-1.jpg" alt="phone (recommendations)" width="25%" height="auto"> |

### Dialect Translation Accuracy vs Google Translate
My app significantly outperforms Google Translate when handling cultural dialects and slang. Here's a direct comparison:

#### AAVE (African American Vernacular English) Examples
<table>
  <tr>
    <td style="width: 50%; vertical-align: top; padding: 10px;">
      <img src="media/comparisons/translation-aave-1.jpg" alt="Dialecto AAVE translation" style="width: 50%; height: auto; display: block; margin: 0 auto;">
      <p style="text-align: center;"><strong>Dialecto:</strong> "em" → "them" ("ellos")</p>
    </td>
    <td style="width: 50%; vertical-align: top; padding: 10px;">
      <img src="media/comparisons/google-translate-aave-1.png" alt="Google Translate AAVE failure" style="width: 90%; height: auto; display: block; margin: 0 auto;">
      <p style="text-align: center;"><strong>Google Translate:</strong> "em" → thinks "em" cannot be translated (misses cultural context)</p>
    </td>
  </tr>
  <tr>
    <td style="width: 50%; vertical-align: top; padding: 10px;">
      <img src="media/comparisons/translation-aave-3.jpg" alt="Dialecto AAVE translation" style="width: 50%; height: auto; display: block; margin: 0 auto;">
      <p style="text-align: center;"><strong>Dialecto:</strong> "Ion wanna..." → "I don't want to keep the water running" ("No quiero")</p>
    </td>
    <td style="width: 50%; vertical-align: top; padding: 10px;">
      <img src="media/comparisons/google-translate-aave-3.png" alt="Google Translate AAVE failure" style="width: 90%; height: auto; display: block; margin: 0 auto;">
      <p style="text-align: center;"><strong>Google Translate:</strong> "Ion wanna..." → "I want the water to keep running" ("Quiero que") (complete opposite meaning)</p>
    </td>
  </tr>
  <tr>
    <td style="width: 50%; vertical-align: top; padding: 10px;">
      <img src="media/comparisons/translation-aave-4.jpg" alt="Dialecto AAVE translation" style="width: 50%; height: auto; display: block; margin: 0 auto;">
      <p style="text-align: center;"><strong>Dialecto:</strong> "not (even) gon hold you" → "I'm not going to lie to you..."</p>
    </td>
    <td style="width: 50%; vertical-align: top; padding: 10px;">
      <img src="media/comparisons/google-translate-aave-4.png" alt="Google Translate AAVE failure" style="width: 90%; height: auto; display: block; margin: 0 auto;">
      <p style="text-align: center;"><strong>Google Translate:</strong> "not (even) gon hold you" → "I'm not going to hold you" (literal translation)</p>
    </td>
  </tr>
  <tr>
    <td style="width: 50%; vertical-align: top; padding: 10px;">
      <img src="media/comparisons/translation-aave-2.jpg" alt="Dialecto AAVE translation" style="width: 50%; height: auto; display: block; margin: 0 auto;">
      <p style="text-align: center;"><strong>Dialecto:</strong> "bust that corner" → "turn on the corner"</p>
    </td>
    <td style="width: 50%; vertical-align: top; padding: 10px;">
      <img src="media/comparisons/google-translate-aave-2.png" alt="Google Translate AAVE failure" style="width: 90%; height: auto; display: block; margin: 0 auto;">
      <p style="text-align: center;"><strong>Google Translate:</strong> "bust that corner" → Grammatically correct translation but inaccurate in tone - very formal </p>
    </td>
  </tr>
</table>

**Key Differences:**
- **Google Translate**: Provides literal word-for-word translations that lose cultural meaning
- **Dialecto**: Recognizes dialectal patterns and provides accurate translations, even if tone doesn't fully match
  - Ex: In the phone demo, my app recognized "Qué lo que?" as a common Dominican Spanish greeting. In Google Translate, it returned "what what?"

## Project Structure
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

## CI/CD Pipeline

This project uses GitHub Actions for automated testing, building, and deployment with separate workflows for pull requests and production releases.

### Key Features
- **Pull Request Validation**: Every PR triggers automated builds with live preview deployments
- **Production Deployment**: Successful merges automatically deploy to the main Firebase hosting environment
- **Consistent Success Rate**: Maintained 100% successful deployment rate across all features and refactors

<details>
<summary>View Pipeline Screenshots</summary>

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

### Technical Implementation
- **Build Process**: `npm ci` → `npm run build` → Firebase deployment
- **Preview URLs**: Each PR generates a unique preview URL for stakeholder review
- **Deployment Target**: Firebase Hosting with custom domain support

See my [personal workflow](https://github.com/sycstitch/guides/blob/main/dev/personal-workflow.md) I follow for my project.

## Areas for Future Development

This project is continuously evolving, and I have many exciting improvements planned. Here are some key areas I'm focusing on:

### Language and Translation Accuracy

My primary goal is to provide highly accurate and contextually relevant translations.

* **Enhanced Contextual Understanding:** I'm actively working to improve the model's ability to understand nuances and slang, like ensuring "dame banda" is consistently translated as "give me space" rather than a literal "give me band."
* **Robust Typo Detection:** The system will become more forgiving of minor typos. For instance, "dam**a** banda" should prompt a suggestion for "dam**e** banda" rather than a direct, incorrect translation.
* **Model Optimization:** I'm exploring alternative AI models with superior language capabilities, balancing translation quality with cost-effectiveness.
* **Broader Dialect Support:** Integrating more normalized dialectal data will significantly enhance the accuracy and breadth of translations for various regional expressions.

### User Experience and Personalization

Improving how users interact with and learn from the application is crucial.

* **Culturally Relevant Explanations:** To address the current English-centric explanations, I plan to implement a multi-select dropdown menu allowing users to specify their known languages. This will enable concept explanations to be tailored to their linguistic and cultural background, using more familiar analogies and examples.

### User Interface (UI) Refinements

A seamless and visually appealing interface is essential for a positive user experience.

* **Responsive Layouts:** I'll be refining the UI to ensure the background color consistently fills the entire screen on all display sizes.
* **Optimized Button Placement:** The layout for authentication buttons (e.g., "Sign in with Google") will be adjusted to better accommodate various screen dimensions, ensuring all elements are clearly visible without impacting text size.

### Core Functionality and Data Management

Enhancing core features and efficient data handling are high priorities.

* **Persistent User Data:** Completing the "Sign in with Google" integration will allow users' translation history to be saved across sessions, even if their browser cache is cleared.
* **Intelligent History Management:** I'm planning to implement a system that automatically prunes less frequently accessed translations from a user's history after a certain period, optimizing storage space.

### Security Enhancements

Ensuring the security of user data and API keys is paramount.

* **Secure API Key Management:** I will be implementing robust protocols for the secure storage and usage of all API keys to protect sensitive information.
