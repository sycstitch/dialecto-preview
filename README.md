# dialecto-preview

## Description
This is a preview of my project called Dialecto, a unique take on a translator made to be linguistically aware of dialects. Currently, there are security risks with the app not exposed through git, but will be if app is faced to the public. Once those are wrinkled out, you'll be able to try it out for yourself! :D


## Demo
### Computer
(Recorded with Gifox but limited on time, so recommendations are shown with the screenshot)
| Live Demo                                         | Recommendations                                                |
| ------------------------------------------------- | -------------------------------------------------------------- |
| ![computer demo](media/demos/computer-demo-1.gif) | ![computer (recommendations)](media/demos/computer-demo-2.jpg) |

### Phone
| Live Demo                                             | Recommendations                                                                                                   |
| ----------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| [YouTube link](https://youtube.com/shorts/9YXpPo1dNyo?feature=share) | <img src="media/screenshots/recommendations-phone-1.jpg" alt="phone (recommendations)" width="25%" height="auto"> |

### Unique Translations
Translations are even accurate coming from English slang! Most is from AAVE, which I speak.
| ![translation 1](media/screenshots/translation-aave-1.jpg) "em"                         | ![translation 2](media/screenshots/translation-aave-2.jpg) "prolly", "bust that corner"  |
| --------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| ![translation 3](media/screenshots/translation-aave-3.jpg) **"Ion", "wanna", "runnin"** | ![translation 4](media/screenshots/translation-aave-4.jpg) **"not (even) gon hold you"** |

## CI/CD Pipeline
| Build and Preview                                          | Deploy Preview Site                                  |
| ---------------------------------------------------------- | ---------------------------------------------------- |
| ![build and preview](/media/ci-cd/1-build_and_preview.png) | ![deploy preview](/media/ci-cd/2-deploy_preview.png) |

## Areas of Improvement


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
